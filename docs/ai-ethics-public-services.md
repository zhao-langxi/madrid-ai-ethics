# AI ethics in public services

**Status:** Essay outline · high-level public frame  
**Scope:** General principles for government-facing and civic systems — public-safe framing only; no private research or participant data

## Why this doc exists

Spring 2026 coursework included EU politics and strategic management; daily life included Spanish bureaucracy and public-facing digital tools. ServeAI at IU ([PIT-UN](https://www.pit-un.org/) public-interest AI track) asks similar questions for **community organizations**: when should automation help, and when does it erode trust?

This note stays at the **policy and product ethics** layer — suitable for public GitHub. It does not describe private lab work, sensitive data pipelines, or participant-facing systems.

## Core claim

AI in public services is not neutral efficiency. It encodes **who gets fast answers, who gets flagged, and who has to prove they belong** — often amplifying existing friction for outsiders.

Builders should treat that as a design requirement, not a post-launch scandal.

## Principles (working draft)

### 1. Transparency over theater

Citizens should know when a decision involves automated scoring, routing, or generation — and what human override exists. “AI-powered” marketing without appeal paths is a liability.

### 2. Access before automation

If the baseline service is already unusable for non-native speakers or first-time users, adding a chatbot does not fix access. It adds a second failure mode.

See: [language and civic access](./language-and-civic-access.md).

### 3. Accountability and auditability

Public systems need logs a human can review: what was submitted, what rule fired, who can reopen the case. Black-box convenience is incompatible with democratic accountability.

### 4. Data minimization and purpose limitation

Collect what the process requires — not what a vendor’s default form includes. Retention and deletion rules should be explainable to the person affected, not buried in a procurement appendix.

### 5. Non-discrimination by proxy

Training data and proxy features (zip code, language preference, device type) can reproduce structural exclusion. Impact review should include **outsider personas**, not only average users.

### 6. Staff maintainability

Community clinic lesson (ServeIT): the handoff matters. Public AI tools must be operable by civil servants and partner staff **without** a vendor on permanent retainer — same bar as accessible nonprofit web.

## EU framing (course-informed, non-expert)

`POLS-Y 350` (Politics of the European Union) provided vocabulary for multi-level governance, regulatory harmonization, and digital policy debates at the EU layer. Useful for reading headlines and white papers — **not** a claim of legal expertise.

Questions worth tracking in public discourse:

- Where do EU AI Act categories meet local implementation reality?
- How do “digital single market” goals show up (or don’t) in everyday civic apps?
- Who benefits when automation is centralized vs. delegated to municipalities?

## ServeAI parallel (community scale)

ServeAI focuses on **public-interest AI for nonprofits and community partners** — guides, responsible adoption, accessibility alongside automation. Different scale than national government, same ethical spine:

| Question | Public service | Community org |
|----------|----------------|---------------|
| Who is harmed if this fails? | Citizens with deadlines | Clients with urgent needs |
| Can staff override the model? | Must be yes | Must be yes |
| Is the data scope honest? | Procurement problem | Partner trust problem |

Clinic links: [ServeAI](https://serveit.luddy.indiana.edu/serve-ai/) · [serveit-accessibility repo](https://github.com/zhao-langxi/serveit-accessibility).

## What this doc deliberately excludes

- Health-system integrations, sensitive data pipelines, or private research AI
- Participant identifiers, field study instruments, or non-public lab protocols
- Vendor-specific procurement documents or non-public partner data

## Open questions (to expand)

- [ ] One-page “outsider impact review” template for student builders
- [ ] Reading list: EU AI governance primers + accessible civic UX (public sources only)
- [ ] Cross-link updated ServeAI public guides when published

## See also

- [Systems friction abroad](./systems-friction-abroad.md)
- [From Madrid to ServeIT](./from-madrid-to-serveit.md)
- [How I work · part 5 — ethics as requirements](https://jadexzhao.github.io/jadexzhao/how-i-work.html)
