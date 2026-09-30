# alvinmunk — Documentation Index

All documentation for the **alvinmunk** project, organised by audience.  
Start at the [root README](../README.md) for the project overview and quick start.

---

## Users

End-users who want to onboard, earn reputation, and use the app.

| Doc | What it covers |
| --- | --- |
| [USER_GUIDE.md](./USER_GUIDE.md) | End-user walkthrough — onboard, vouch/claim, quests, tips, leaderboard, profile, FAQ |
| [BLOG.md](./BLOG.md) | How the sybil-resistant proof-of-people design works (async vouch, two-track anti-sybil, passkey + fee-sponsorship + no-standing-backend) |

---

## Contributors

Developers and community members who want to contribute code, fix bugs, or run the project locally.

| Doc | What it covers |
| --- | --- |
| [../CONTRIBUTING.md](../CONTRIBUTING.md) | How to contribute — branch conventions, PR process, code style |
| [ON_CHAIN_EVENTS.md](./ON_CHAIN_EVENTS.md) | Frozen on-chain event shapes — do not change without a migration |
| [ECOSYSTEM.md](./ECOSYSTEM.md) | Open-source / community: Drips Wave maintainer, 26 bountied issues, 15 merged external-contributor PRs |
| [SECURITY_REVIEW.md](./SECURITY_REVIEW.md) | Self-audit — Scout + cargo-audit + cargo-deny + clippy + no-`unsafe`; 4 critical findings fixed, 22 medium triaged |
| [AGENT_HANDOFF.md](./AGENT_HANDOFF.md) | Context handoff notes for AI-assisted development sessions |

---

## Operators / Deploy

Teams or individuals deploying their own instance to testnet or mainnet.

| Doc | What it covers |
| --- | --- |
| [DEPLOY.md](./DEPLOY.md) | Full "deploy your own" runbook — keys → contracts → `.env.local` → web app → attester/faucet/passkey secrets |
| [DEPLOY_MAINNET.md](./DEPLOY_MAINNET.md) | Mainnet cutover checklist and runbook |
| [PASSKEY_HANDOFF.md](./PASSKEY_HANDOFF.md) | Passkey infrastructure handoff — wiring `smart-account-kit`, WASM hash, LaunchTube URL |
| [PASSKEY_WIRING.md](./PASSKEY_WIRING.md) | Step-by-step passkey wiring for Face ID / WebAuthn onboarding |

---

## Product & Design

Designers, PMs, and stakeholders who shape the product vision and visual identity.

| Doc | What it covers |
| --- | --- |
| [product/README.md](./product/README.md) | Product & Design package overview — read order, non-negotiables, strategic frame |
| [product/BRAND_DESIGN.md](./product/BRAND_DESIGN.md) | Who we are, how we look & sound, the constellation metaphor, color/type/motion/voice |
| [product/DESIGN_SYSTEM_TOKENS.md](./product/DESIGN_SYSTEM_TOKENS.md) | Implementable tokens — CSS variables, color/type/space/radius/motion scales |
| [product/FRONTEND_PAGES_COMPONENTS.md](./product/FRONTEND_PAGES_COMPONENTS.md) | Every page + every component, their states and jobs |
| [product/FRONTEND_CONTENT.md](./product/FRONTEND_CONTENT.md) | Real copy for every screen + the microcopy library |
| [product/DEPENDENCIES.md](./product/DEPENDENCIES.md) | The exact frontend stack/libraries, versions, install, risks |
| [product/PRODUCT_MARKET_FIT.md](./product/PRODUCT_MARKET_FIT.md) | Beachhead, the "aha", activation, GTM, how the end user meets us |
| [product/BUSINESS_MODEL.md](./product/BUSINESS_MODEL.md) | How it sustains itself: two-track economics, revenue, treasury, grants |
| [product/DEV_DOCS_OUTLINE.md](./product/DEV_DOCS_OUTLINE.md) | The `/docs` "for devs" surface — reputation as a readable primitive |
| [MARKETING.md](./MARKETING.md) | Launch thread, promotion strategy, and marketing kit |
| [GTM.md](./GTM.md) | Go-to-market plan and growth tactics |
| [PITCH_DECK.md](./PITCH_DECK.md) | Pitch deck outline / speaker notes (problem → proof-of-people → traction → ask) |
| [pitch-deck.pdf](./pitch-deck.pdf) | Designed 12-slide deck (brand-skinned) |
| [IDEA_SUBMISSION.md](./IDEA_SUBMISSION.md) | Original idea submission document |
| [PRD.md](./PRD.md) | Product Requirements Document |
| [SPRINTS.md](./SPRINTS.md) | Sprint-by-sprint roadmap and build order |

---

## Program / Archive

Belt-program submission evidence and user-research data.

| Doc | What it covers |
| --- | --- |
| [BELT_SUBMISSIONS.md](./BELT_SUBMISSIONS.md) | White → Blue belt submission screenshots, tx hashes, and rubric tables (Rise In Stellar Journey to Mastery) |
| [USER_FEEDBACK.md](./USER_FEEDBACK.md) | Raw user feedback, planned iterations, and the weighted-vouch backlog item |
| [DEMO_SCRIPT.md](./DEMO_SCRIPT.md) | Demo walkthrough script for live presentations and recorded walkthroughs |
| [feedback/responses.xlsx](./feedback/responses.xlsx) | Exported Google Form responses (Excel) |
| [feedback/responses.csv](./feedback/responses.csv) | Exported Google Form responses (CSV) |
| [testnet-traction.csv](./testnet-traction.csv) | On-chain traction data snapshot from Soroban RPC |
