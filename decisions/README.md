# Decision Log

[Chinese](README.zh-CN.md) | English

The log records what was decided, by whom, within which authority, why, and until when. It does not replace the underlying controller's confirmation.

Statuses: `proposal`, `ratified`, `implemented`, `paused`, `reversed`, `expired`, `superseded`.

Every record includes scope, evidence, alternatives, reasons, decision-maker or ratifier, recusals, objections, owner, deadline, rollback, and review/expiry date. Confidential decisions publish only safe de-identified metadata.

Create records from [`D-0000-template.md`](D-0000-template.md). Use monotonically increasing IDs and never silently rewrite history; supersede a record with a new one.
