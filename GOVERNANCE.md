# DevHound Governance Model

Last Updated: 2026-08-05  
Version: 1.0.0  

## 1. Overview
DevHound operates under a Benevolent Dictator for Life (BDFL) governance structure combined with an advisory review process. The primary objective is maintaining project architectural integrity, security sandbox boundaries, and brand identity enforcement across all distribution channels.

## 2. Roles & Responsibilities

### Benevolent Dictator for Life (BDFL)
* **Current Lead**: `@bilbywilby`
* **Authority**: Holds final decision-making authority over architecture, breaking changes, core code merges, financial allocation from `FUNDING.json`, and trademark licensing under `BRAND.md`.

### Core Maintainers
* **Requirements**: Consistent code or documentation contributions over a 6-month period, demonstrating adherence to technical and brand compliance standards.
* **Privileges**: PR review and merge permissions on feature branches, issue triage, and candidate release testing.
* **Responsibilities**: Auditing pull requests for compliance, maintaining CI runner uptime, and enforcing code quality metrics.

### Advisory Council
* **Composition**: Up to 3 elected community members or corporate sponsors contributing above the Sponsor tier defined in `FUNDING.json`.
* **Scope**: Provides input on roadmap priorities, feature requests, and community fund allocation. Holds advisory review rights; final execution remains with the BDFL.

## 3. Decision-Making Process

### Consensus Seeking
1. Technical proposals and feature additions begin as an issue or Request for Comments (RFC) pull request.
2. Discussion must remain open for a minimum of 72 hours to accommodate asynchronous global feedback.
3. If core maintainers reach consensus without explicit objection from the BDFL, the proposal moves to implementation.

### Escalation & Veto
* In the event of unresolved technical disagreements or brand compliance conflicts, any maintainer may tag `@bilbywilby` for final determination.
* The BDFL veto applies to architectural shifts that impact sandbox security, breaking API changes, or unauthorized modifications to trademark assets (such as the "D" collar tag mascot).

## 4. Financial Governance
* Fund collection and distribution follow the breakdown declared in `FUNDING.json`.
* The BDFL manages expenditure approvals for infrastructure runner costs, domain/trademark renewals, and maintainer stipends.
* Financial statements are published quarterly in `/docs/financials/`.

## 5. Succession Planning
If the BDFL becomes inactive for a period exceeding 90 consecutive calendar days without prior notification:
1. Operational leadership transfers to the senior active Core Maintainer.
2. Control of repository permissions and infrastructure credentials shifts according to the pre-configured emergency contingency key escrow.
3. 
