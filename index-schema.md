# `index-<name>.json` — field reference

_Generated from `src/index-schema.ts` — index schema 2. Do not edit by hand; run `npm run sync-skills`._

**Source.** State repo `egamma/vscodesweeper-state`, branch `main`: `targets.json` (the roster — one entry per enrolled repo, `name` picks the file) and `index-<name>.json` per repo (`index-vscode.json` for microsoft/vscode).

**Envelope.** `{ schema, target, generatedAt, site: { stateRepo, stateBranch }, rows }` — `schema` is the shape version (refuse a major you don't know), `target` the `owner/repo`, `generatedAt` when the index was built, `rows` the records below.

**Rows are sparse.** A key is omitted when it would hold its default: an open issue has no `currentState`, an unassigned one no `owner`, a non-agent-ready one no `agentReadiness`. Always write `(.x // default)` or `.x == null` checks. `labels` and `areaLabels` are comma-joined strings, not arrays.

| Field | Type | Present | Meaning |
|---|---|---|---|
| `number` | number | always | The issue number. Link: `https://github.com/<repo>/issues/<number>`. |
| `title` | string | always | The issue title at review time. |
| `url` | string | only when the issue URL is not the canonical `https://github.com/<repo>/issues/<number>` | Safety valve; derive the link from `number` otherwise. |
| `reviewUrl` | string | only when the record lives off the canonical path | The review record's URL. Canonical: `https://github.com/<stateRepo>/blob/state/records/<repo>/items/<number>.md`. |
| `owner` | string | when the issue had an assignee at review time | The assignee's GitHub login (a review-time snapshot, not the live assignee). Say "assignee" to users. |
| `createdAt` | string | always (ISO 8601) | When the issue was opened — the issue's age. |
| `reviewedAt` | string | always (ISO 8601) | When the sweeper last reviewed the issue. |
| `labels` | string | when the issue had labels at review time | The issue's labels, COMMA-JOINED into one string (`"bug, terminal, help wanted"`). Split before matching: `(.labels // "") \| split(", ") \| index("terminal")`. |
| `areaLabels` | string | when the review suggested area labels | Area labels the review proposed (or found), comma-joined like `labels`. Informational — nothing applies them. |
| `itemType` | string | always | What kind of item the review judged this to be. Values: `bug`, `feature-request`, `debt`, `polish`, `upstream`, `question`, `under-discussion`. |
| `triageAction` | string | when NOT `keep-open` (the absent default; route-to-area is folded into keep-open) | What the sweeper proposes. A proposal is never applied by the sweeper itself. Values: `propose-close`, `needs-info`. |
| `proposedLabel` | string | when the verdict proposes a label (absent = `none`) | A real label of the repo the verdict proposes (`*duplicate`, `info-needed`, `bug`, …). |
| `closeReason` | string | on close proposals | Why the close is proposed. Values: `duplicate`, `implemented-on-main`, `as-designed`, `not-reproducible`, `out-of-scope`, `question`, `invalid`. |
| `canonical` | string | on duplicate close proposals | The issue this one duplicates: `"12345"` (same repo) or `"owner/repo#12345"` (cross-repo). |
| `confidence` | number | always (0–1) | The review's confidence in its verdict. |
| `proposedComment` | string | when the verdict drafted a comment | The full proposed comment (long). Print it for ONE issue when asked, never in bulk. |
| `verification` | string | on bugs the review assessed | Reproduction strength tier, best → worst. Values: `Confirmed`, `Source-confirmed`, `Traced`, `Plausible`, `Unverified`, `Inconclusive`, `not applicable`. |
| `agentReadiness` | string | when not `none` (the absent default) | `implement`: diagnosis done, bounded change, named validation — an agent can go straight to code. `plan`: goal clear, but a design/diagnosis decision is open first. A review-time snapshot: the issue may have gained a PR or a `security` label since. Values: `implement`, `plan`. |
| `autoFixable` | string | always, as the STRING `"true"`/`"false"` | Legacy boolean = `agentReadiness == "implement"`. Prefer `agentReadiness`. |
| `linkedPr` | string | on agent-ready rows an OPEN contributor PR already references | That PR's URL. Treat the issue as taken. |
| `skillPr` | string | when a sweeper-implement skill PR exists for the issue | That PR's URL. |
| `skillPrState` | string | beside `skillPr` | Its state when last seen. Values: `open`, `merged`, `closed`. |
| `fixPr` | string | historical rows only (retired fork lane) | URL of a draft fix PR from the retired fork lane. |
| `implementPr` | string | historical rows only (retired implement lane) | URL of a draft PR from the retired implement lane. |
| `lane` | string | on open keep-open rows of the two ranked types | Which ranking the row belongs to. Rows without a lane are not ranked (closed, close proposals, needs-info, other item types). Values: `bugs`, `features`. |
| `valueRaw` | number | beside `lane` | The UN-normalized value score (demand × severity/breadth, age-damped). Compare only within one assignee × lane; sort with `sort_by(-(.valueRaw // 0))`. |
| `upvotes` | number | beside `lane` | 👍 reactions at review time. |
| `comments` | number | beside `lane` | Comment count at review time. |
| `severity` | string | bugs lane | The bug's severity class. Values: `crash`, `data-loss`, `freeze`, `perf`, `correctness`, `visual`, `papercut`, `none`. |
| `signal` | string | features lane | Demand signal: `backlog-candidate` (milestoned Backlog), `active` (recent demand), `dormant`. Values: `backlog-candidate`, `active`, `dormant`. |
| `infoRequestedAt` | string | on a needs-info row whose request still stands (ISO, or `unknown`) | When the repo's needs-info label was applied. |
| `infoAnsweredAt` | string | beside `infoRequestedAt`, when the reporter answered but the label is still on | The reporter's first reply after the ask — the issue now waits on the maintainer. |
| `infoAnsweredBy` | string | beside `infoAnsweredAt` | Who answered. Values: `reporter`. |
| `infoRequestedBy` | string | on needs-info rows with a post-review request | Login that applied the label. |
| `infoCommentUsed` | string | on needs-info rows with a post-review request | Whether the proposed question was posted. Values: `verbatim`, `embedded`, `edited`, `none`, `not-proposed`. |
| `infoActedBy` | string | beside `infoCommentUsed` | Login that posted the question. |
| `currentState` | string | when CLOSED (absent = open) | Open issues carry no `currentState`. Filter open rows with `select(.currentState == null)`. Values: `closed`. |
| `closedAt` | string | closed rows (ISO) | When the issue was closed. |
| `stateReason` | string | closed rows | GitHub's close reason. Values: `completed`, `not_planned`, `duplicate`, `not_found`. |
| `closedBy` | string | closed rows | Login that closed the issue. |
| `proposedCommentUsed` | string | closed close-proposal rows | Whether the sweeper's proposed closing comment was posted. Values: `verbatim`, `embedded`, `edited`, `none`, `not-proposed`. |
| `actedBy` | string | beside `proposedCommentUsed` | Login that posted it. |
| `autoClosedAt` | string | rows the sweeper-close action closed (ISO) | An automatic close — never a maintainer action. |
| `autoLane` | string | beside `autoClosedAt` | Which auto-close lane closed it. Values: `duplicate`, `implemented`. |
| `autoObjectedAt` | string | auto-closed rows someone replied to afterwards (ISO) | A possible objection the assignee should look at. |
| `lastCommentAt` | string | open rows with a non-bot comment (ISO) | The newest human comment. |
| `lastCommentBy` | string | beside `lastCommentAt` | `reporter` for the issue author, else the login. |
| `assigneeActedAt` | string | open rows where a live assignee acted (ISO) | The assignee's latest action. |
| `previousTriageAction` | string | open rows re-reviewed after a comment | The verdict this review replaced (e.g. `needs-info` → now keep-open). |
| `previousCloseReason` | string | beside `previousTriageAction` | The replaced verdict's close reason. |
| `previousCanonical` | string | beside `previousTriageAction` | The replaced verdict's duplicate canonical. |
| `verifyVerdict` | string | close/needs-info proposals a blinded second review checked | The second review's verdict on the proposal. Values: `confirmed`, `refuted`, `unverifiable`. |
| `verifyEvidence` | string | beside `verifyVerdict` | Its one-line rationale. |
| `verifyKind` | string | beside `verifyVerdict`, where the lane classifies | Duplicate lane: canonical kind; implemented lane: `bug-fix` \| `feature`. |
| `verifyCanonical` | string | duplicate lane | The canonical the verifier found. |
| `verifyCanonicalRepo` | string | when the verifier's canonical is in another repo | That repo (`owner/name`). |
| `verifyStale` | boolean | when the row was re-reviewed after its verification | The verification no longer matches the current review. |
| `verifyUnreleased` | boolean | implemented lane | Fixed on main but in no stable release yet. |
| `disputedAgain` | boolean | refuted twice | A refuted proposal whose automatic re-review is spent — for a person. |
| `verifiedUpdatedAt` | string | when set | Issue `updatedAt` as the verifier saw it. |
| `dismissed` | boolean | when a maintainer removed the proposal | Hide by default: `select(.dismissed != true)`. |
| `dismissedIssue` | string | beside `dismissed` | The state-repo issue that recorded the dismissal. |
| `dismissedAt` | string | beside `dismissed` (ISO) | When. |
| `dismissedBy` | string | beside `dismissed` | Who. |
| `dismissedReason` | string | when a reason was given | The maintainer's one-line reason. |
| `dismissedKind` | string | when classified | Why it was dismissed. Values: `disagree`, `other-direction`, `already-handled`, `keep-open-anyway`, `other`. |
| `contentStale` | boolean | when the issue changed since its review | The verdict may be out of date. |
