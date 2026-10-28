# Craig decisions

Read this ledger before work in `craig-saves/feedback`.

- Owner: Craig. Entries below paraphrase his decisions; they are not quotations.
- Source: [CS-139](https://craigsaves.getbb.app/plugins/tasks/tasks/task/CS-139), including the current bot and PostHog Surveys amendment recorded on 2026-10-28 at 07:27:49.906 UTC.
- [Hub canonical ledger](https://github.com/craig-saves/craigsaves/blob/main/docs/craig-decisions.md) owns cross-section rules. Its publication and anchors are pending verification by the Hub coordinator before this PR merges. Links below use the planned explicit IDs; they do not prove live publication.
- Current decisions are binding within their scope. Product entries are cross-section reference. They do not authorize product work in this repository.
- Status of this backfill: decisions recorded from source receipts. Product implementation and live behavior are not verified by this documentation change.
- Task links use the route verified from installed BB source. Browser rendering of those links is not verified.

## Record each new decision

1. Record an immediate receipt on the owning task when Craig gives an instruction, preference, or decision directly, or CraigSaves bot relays one.
2. Add the dated decision to this ledger in the same relevant PR flow. Link cross-section rules to the Hub canonical entry. Keep the task receipt while publication is pending.
3. State the section, source task, requested outcome, and verified status separately. Preserve source receipts and superseded history. Mark paraphrases; quote only exact source text.
4. The coordinator obtains independent review and relevant checks at the final head, then merges without asking Craig. Children do not merge. A new head needs a new verdict. Report merged results on CS-121; Hub consolidates this rollout.

The routine merge rule preserves standing safety and verification gates. Never touch production data, secrets, DNS, or Coolify under this documentation task. Do not send test messages to real users, bypass checks or hooks, rewrite main, or force-push another owner's branch. Preserve correction-round history and explicit stop decisions. Mark a stop as superseded when a later Craig decision replaces it within a stated scope. These entries do not grant exceptions to unrelated task gates.

<a id="craig-2026-10-28-01"></a>
## 01 — Merge after review and checks

- Date: 2026-10-28. Scope: all sections, including feedback.
- Decision: do not ask Craig before routine merge and deployment. The section coordinator merges after independent review and relevant checks pass. Children never merge. Report the merged result on CS-121.
- Sources: [CS-139](https://craigsaves.getbb.app/plugins/tasks/tasks/task/CS-139), [CS-121](https://craigsaves.getbb.app/plugins/tasks/tasks/task/CS-121), standing orders 1–5.
- [Canonical decision 01](https://github.com/craig-saves/craigsaves/blob/main/docs/craig-decisions.md#craig-2026-10-28-01).
- Status: current operating rule. This ledger is not a review verdict or deployment receipt.

<a id="craig-2026-10-28-02"></a>
## 02 — Run workers on Craig's laptop

- Date: 2026-10-28. Scope: all sections, including feedback.
- Decision: new workers and independent reviewers use Craig's laptop, `host_qfx8ucfcm3`, with fresh isolated worktrees. No BB workers on the VPS. Each child owns one task and one branch.
- The four Hub script factories stay on the server. Their scripts and configuration remain unchanged: weekly chores, coordinator heartbeat, user reports, and broken jobs.
- Sources: [CS-131](https://craigsaves.getbb.app/plugins/tasks/tasks/task/CS-131), [CS-137](https://craigsaves.getbb.app/plugins/tasks/tasks/task/CS-137), [CS-136](https://craigsaves.getbb.app/plugins/tasks/tasks/task/CS-136), [CS-139](https://craigsaves.getbb.app/plugins/tasks/tasks/task/CS-139), standing order 12.
- [Canonical decision 02](https://github.com/craig-saves/craigsaves/blob/main/docs/craig-decisions.md#craig-2026-10-28-02).
- Status: current placement rule. No factory or automation change is authorized here.

<a id="craig-2026-10-28-03"></a>
## 03 — Fix the cause of data errors

- Date: 2026-10-28. Scope: all sections, including feedback.
- Decision: when Craig reports a data error, fix the parser, importer, grouping logic, or other root cause so the error cannot recur. A correction to one record is insufficient.
- Source: [CS-139](https://craigsaves.getbb.app/plugins/tasks/tasks/task/CS-139).
- [Canonical decision 03](https://github.com/craig-saves/craigsaves/blob/main/docs/craig-decisions.md#craig-2026-10-28-03).
- Status: current repair principle. No data repair or production-data action is authorized by this backfill.

<a id="craig-2026-10-28-04"></a>
## 04 — Use GitHub failure emails

- Date: 2026-10-28. Scope: all sections, including feedback.
- Decision: Craig does not use Slack. Remove existing Slack alert steps and Slack secret references from workflows. Do not add Slack alerts. GitHub failure emails are sufficient.
- Sources: [CC-123](https://craigsaves.getbb.app/plugins/tasks/tasks/task/CC-123), receipt `01M60NCFT2PY4BSPQEJR9CJYJX` at 07:07:55.587 UTC; [CS-139](https://craigsaves.getbb.app/plugins/tasks/tasks/task/CS-139).
- [Canonical decision 04](https://github.com/craig-saves/craigsaves/blob/main/docs/craig-decisions.md#craig-2026-10-28-04).
- Status: current communication preference. No alert configuration changed here.

<a id="craig-2026-10-28-05"></a>
## 05 — Build the feedback loop with PostHog Surveys

- Date: 2026-10-28. Scope: site-wide; cross-section product reference for this repository.
- Decision: build a site-wide user feedback loop with PostHog Surveys. The latest direct relay names PostHog Surveys as Craig's choice.
- Sources: [CS-138](https://craigsaves.getbb.app/plugins/tasks/tasks/task/CS-138), [CS-139](https://craigsaves.getbb.app/plugins/tasks/tasks/task/CS-139), amendment at 07:27:49.906 UTC.
- [Canonical decision 05](https://github.com/craig-saves/craigsaves/blob/main/docs/craig-decisions.md#craig-2026-10-28-05).
- History: the original CS-139 entry requested the feedback loop without naming the tool. The later choice makes that requirement specific.
- Status: requested product outcome. No survey, installation, live configuration, or product implementation in this PR.

<a id="craig-2026-10-28-06"></a>
## 06 — Make Net worth public pages available

- Date: 2026-10-28. Scope: Net worth and Hub; cross-section reference here.
- Decision: move toward public pages that need no login. Make `/net-worth` a public, indexable landing page with its own canonical URL and sign-up/sign-in actions. Anonymous visitors must not be redirected to sign in. Keep the Hub sitemap entry. A person's own account and private data remain protected by login.
- Beyond NW-4, propose other public Net worth pages or tools on CS-121, then build them in the owning section's work flow. No Hub proxy or navigation edit is authorized here.
- Sources: [NW-4](https://craigsaves.getbb.app/plugins/tasks/tasks/task/NW-4), receipt `01M60NGXQVRYNW3H1EB9ZZF8HY` dated 2026-10-28 at 07:10:20.923 UTC; [CS-121](https://craigsaves.getbb.app/plugins/tasks/tasks/task/CS-121), [CS-139](https://craigsaves.getbb.app/plugins/tasks/tasks/task/CS-139).
- [Canonical decision 06](https://github.com/craig-saves/craigsaves/blob/main/docs/craig-decisions.md#craig-2026-10-28-06).
- History: the latest decision keeps the sitemap entry and supersedes the earlier exclusion proposal.
- Status: desired outcome from NW-4. Public access, canonical tags, account protection, and completion are not verified here.

<a id="craig-2026-10-28-07"></a>
## 07 — Fully repair Places navigation and React 418 errors

- Date: 2026-10-28. Scope: Places; cross-section reference here.
- Decision: fix the navigation bug and three live React 418 hydration errors fully. Diagnosis alone is insufficient. Find the cause with a fresh approach, reproduce with production builds, add a regression test that fails before the fix, and verify that the live errors stop after the reviewed repair.
- Sources: [CS-98](https://craigsaves.getbb.app/plugins/tasks/tasks/task/CS-98), fresh repair grant `01M60ND3RRGJV7PJMM71M9VDCA` at 07:08:16.024 UTC and earlier STOP receipt at 06:25:35.433 UTC; [CS-139](https://craigsaves.getbb.app/plugins/tasks/tasks/task/CS-139).
- [Canonical decision 07](https://github.com/craig-saves/craigsaves/blob/main/docs/craig-decisions.md#craig-2026-10-28-07).
- History: initial PR66 failed. Correction round 1, PR67, failed valid-missing 404 acceptance. Correction round 2, PR69, failed production hydration. Craig's 07:08:16.024 UTC grant authorizes the fresh repair approach and supersedes the earlier STOP for that approach. The failed history remains recorded. This is not a blanket correction-budget reset.
- Related PL-4 decision: receipt `01M60RCSQHQASC38F436RS4KA2` at 08:00:31.477 UTC supersedes the former STOP and photo allowance. Allow crawling of public Places pages and public data. Disallow photo/image proxy paths and private, account, and private API paths. Reference the sitemap if one exists. No separate photo address is needed. Source: [PL-4](https://craigsaves.getbb.app/plugins/tasks/tasks/task/PL-4).
- Status: the fresh CS-98 repair is authorized; technical acceptance remains pending. After review and tests pass, the Places coordinator merges and deploys, confirms React 418 errors stop in production, then reports on CS-121. PL-4 implementation, merge, and deployment are also authorized within that decision's scope. No product PASS, completion, or production access is verified or granted by this documentation PR. Current safety, private-data, and release restrictions remain in force.

<a id="craig-2026-10-28-08"></a>
## 08 — Show Full price and group Shopping variants

- Date: 2026-10-28. Scope: Shopping; cross-section reference here.
- Decision: Amazon cards show Full price (RRP) on the price ruler, as Coles cards do. Group flavour, colour, and scent variants into one card when the product, retailer, size, and price match. CraigSaves bot owns the daily page check and records missed groups in ST-139 task comments. No new worker automation is assigned.
- Sources: [ST-138](https://craigsaves.getbb.app/plugins/tasks/tasks/task/ST-138) for Full price; [ST-139](https://craigsaves.getbb.app/plugins/tasks/tasks/task/ST-139) for grouping and the daily check, coordinator receipt `01M60QRPPHGR4T25CS5TC0PFFS` at 07:49:33.009 UTC; [CS-139](https://craigsaves.getbb.app/plugins/tasks/tasks/task/CS-139).
- [Canonical decision 08](https://github.com/craig-saves/craigsaves/blob/main/docs/craig-decisions.md#craig-2026-10-28-08).
- Status: requested outcomes from the CS-139 backfill. No Shopping implementation or daily check is created or verified here.

<a id="craig-2026-10-28-09"></a>
## 09 — Correct Cards fees, benefits, and sections

- Date: 2026-10-28. Scope: Cards; cross-section reference here.
- Decision: monthly-fee cards must not also show an annual fee. Keep sign-up bonus credits separate from ongoing credits. Remove duplicate benefits. Fail an import when credits exceed the issuer's headline. Group the white cards on `/credit-cards` into sections.
- Sources: [CC-126](https://craigsaves.getbb.app/plugins/tasks/tasks/task/CC-126) for fees, credits, benefits, and import limits; [CC-125](https://craigsaves.getbb.app/plugins/tasks/tasks/task/CC-125) for sections; [CS-139](https://craigsaves.getbb.app/plugins/tasks/tasks/task/CS-139).
- [Canonical decision 09](https://github.com/craig-saves/craigsaves/blob/main/docs/craig-decisions.md#craig-2026-10-28-09).
- Status: requested outcomes from the CS-139 backfill. No Cards behavior or import result is verified here.

<a id="craig-2026-10-28-10"></a>
## 10 — Share a prep bowl within one Cooking step

- Date: 2026-10-28. Scope: Cooking; cross-section reference here.
- Decision: ingredients added in the same step share one prep bowl.
- Sources: [COO-47](https://craigsaves.getbb.app/plugins/tasks/tasks/task/COO-47), [CS-139](https://craigsaves.getbb.app/plugins/tasks/tasks/task/CS-139).
- [Canonical decision 10](https://github.com/craig-saves/craigsaves/blob/main/docs/craig-decisions.md#craig-2026-10-28-10).
- Status: requested outcome from the CS-139 backfill. No Cooking behavior or saved-record repair is verified here.

<a id="craig-2026-10-28-11"></a>
## 11 — Route current communication through CraigSaves bot

- Date: 2026-10-28. Scope: all sections, including feedback, factories, and coordinators.
- Decision: CraigSaves bot replaces Grok Bot from 28 October 2026. CraigSaves bot is Craig's single contact and handles factory/coordinator communication. Post Craig-facing reports, questions, and decisions on CS-121. CS-121 is an inbox, not a chief-thread registry. Do not contact retired chief threads.
- Sources: [CS-139](https://craigsaves.getbb.app/plugins/tasks/tasks/task/CS-139), direct relay recorded at 07:27:49.906 UTC; [CS-121](https://craigsaves.getbb.app/plugins/tasks/tasks/task/CS-121).
- [Canonical decision 11](https://github.com/craig-saves/craigsaves/blob/main/docs/craig-decisions.md#craig-2026-10-28-11).
- History: this replaces only Grok Bot's current contact role, including the old name in standing order 18. Preserve truthful historical Grok receipts, including [CS-135](https://craigsaves.getbb.app/plugins/tasks/tasks/task/CS-135).
- Status: current routing rule. No bot, factory, schedule, or saved automation configuration is changed by this PR.
