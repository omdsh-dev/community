# Internationalization

[Chinese](README.zh-CN.md) | English

English is the default documentation language. Simplified Chinese uses a separate file with the `.zh-CN.md` suffix. Do not place full English and Chinese bodies in the same document.

## File conventions

- `README.md` → default English
- `README.zh-CN.md` → Simplified Chinese
- `template.md` → default English template
- `template.zh-CN.md` → Simplified Chinese template
- Issue forms use separate English and `-zh-CN.yml` files.

Language switch links are allowed at the top of documents. Code identifiers, role names, statuses, and product names may remain in English when translating them would reduce precision.

## Change process

1. High-impact governance, security, conduct, and access changes update both languages in the same pull request.
2. Routine documentation may merge with a clearly linked translation follow-up, but must be labeled as temporarily out of sync.
3. Reviewers check semantic parity, especially authority, deadlines, exceptions, privacy, and enforcement.
4. If versions materially disagree, pause the affected decision until reconciled. Neither version silently overrides the other during the trial.
5. Generated translation must be reviewed by a contributor who accepts responsibility for meaning and licensing.

Use [`translation-checklist.md`](translation-checklist.md) for review.
