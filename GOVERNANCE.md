# Community Governance — 30-Day Trial Proposal

[简体中文](GOVERNANCE.zh-CN.md) | English

oh-my-dsh is a shared collaboration layer, not the governing committee of a plugin marketplace. It coordinates common boundaries, contribution paths, upstream compatibility, public decisions, safety, and conduct while preserving project autonomy and a plural ecosystem.

This proposal applies to an asset only after that asset's controller confirms the scope in writing. Only a rule confirmed by both `omdsh-dev` and `oh-my-dsh` may be described as cross-organization governance.

## Principles

1. Project autonomy and repository-scoped authority.
2. Multiple catalogs, markets, distributions, and allowlists may coexist.
3. Public participation does not require organization membership.
4. Routine reversible work uses the lightest accountable process.
5. Root access, security, conduct, sanctions, funds, brand, and irreversible actions require explicit authority and review.
6. Decisions state scope, reasons, owner, review/expiry date, and rollback.
7. Confidential cases are minimized; public records use de-identified metadata.

## Trial responsibilities

- **Facilitator:** agenda and meeting scope.
- **Recorder:** proposals, decisions, objections, owners, and review dates.
- **Community Maintainer:** this repository and participation routes.
- **Compatibility Coordinator:** upstream breaking changes and affected projects.
- **Security/Conduct Contact:** sensitive intake and non-conflicted review.

These are temporary responsibilities, not permanent ranks. The proposer, decision-maker, and appeal reviewer must not be the same person in a sensitive case. If no independent reviewer is available, pause or seek a temporary external reviewer.

## Decisions

| Class | Examples | Trial process | Timeout default |
|---|---|---|---|
| Routine | Docs, metadata, reversible maintenance | Project maintainer review; automation where suitable | May proceed with rollback recorded |
| Project | Features and ordinary project policy | Maintainers decide in their repository | Current state if no owner |
| Cross-project | Shared schema, compatibility convention | Public proposal; normally 72 hours for objections | Remains a proposal/current state |
| High-impact | Root assets, org rules, brand, funds, sanctions, CoC, irreversible removal | Confirmed controller; recusal, response, reasons, independent review | Never passes by silence |
| Emergency | Active serious harm | Least intrusive temporary action | Review in 72 hours or expire |

The 72-hour window is a trial parameter. It starts after a complete proposal reaches the agreed channel and pauses on a substantive objection.

## Meetings and records

A meeting is non-binding unless the applicable controller delegated authority in advance; otherwise the output is a `proposal` awaiting asynchronous ratification. Public records include identifier, date, scope, alternatives, evidence, reasons, decision-maker, recusals, owner, deadline, rollback, review date, and status.

Vulnerabilities, conduct reports, personal data, secrets, and recovery details must not enter public proposals or minutes.

## Contribution and access

The lightweight path is Participant → Contributor → Triager → Repository Maintainer/Steward → Emeritus. Access is repository-scoped and based on demonstrated work. During the trial, one non-conflicted sponsor plus public contribution evidence and a 90-day review is sufficient. Offboarding removes unneeded team, publisher, token, and recovery access.

## Review and expiry

On day 30, review contributor response, upstream compatibility response, governance-blocked work, volunteer burden, bypass behavior, safety, and due process. Continue, simplify, pause, or expire. Without explicit renewal by applicable controllers, the trial expires. A discovery-only ecosystem is an acceptable outcome.
