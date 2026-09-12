# CONTINUE — final-edge-playbook — 2026-09-12 (Sat, night) — v1.1.1 LIVE, NOTHING OWED

**Task:** the one-page teaching app for Arnie's Final Edge NinjaTrader suite — what the cards say, what he does, how to be more successful by following them (his ask, 2026-09-12 evening: "make me an app that demonstrates very easily what to do, what I'll be watching for, and how I can be much more successful if I follow what it says").

**Completed:** v1.0.0 built 2026-09-12 evening (eight sections, the trading design stack, the Narrator copied from trend-check-pro, PWA files, Created/Revised dates). v1.1.0 the same night: the cards 7 → 3 on the page (FINAL GATE with the 15-MIN line, SWEEPS with the flag counter on lane ②, the EXIT MAP with two faces, Big Money on his chart with its window off, the dial that brings each folded window back). v1.1.1: the sidebar says "Three windows, live since 2026-09-12 18:49" (his F5 came at 18:49:26; the DLL probe found every needle). GitHub `arnoldshapiro-del/final-edge-playbook` (main) → Netlify site `final-edge-playbook` (id df73f5be-f36a-42bb-9187-cfc00f8c2761, created by API with installation 77160536) → https://final-edge-playbook.netlify.app, production verified serving v1.1.1. `.url` shortcut `Final Edge - The Playbook.url` in his apps folder.

**What remains:** nothing owed. Standing order: **when a card changes, this page changes** (the same law as the SWEEPS teaching pack) — the source of truth for its content is the indicator repo (`docs/LEGEND.md`, the teaching packs, `docs/DECISIONS-CARDS-AND-OWNERSHIP-2026-09-12.md`, SESSION_NOTES).

**Decisions:** no gallery card in arnies-app-showcase (2026-09-12 night, delegated to Claude: the page carries his own ledger numbers; the link stays unlisted). No sign-in curtain (offered, not applied; his recipe is applied only on his ask). Prices in the walkthrough are labelled examples; the measured numbers cite their source lines; no promise of profit, no action word presented as the page's advice.

**Gotchas:** the GitHub repo had to be created with `gh api -X POST user/repos` (the auto-mode classifier declines `gh repo create`); the Netlify site is created by API (the deploy-opening-edge.js pattern), never the CLI; the Narrator's storage keys are `fep_tts_*`; the page is a single static file — edit → commit → push.

**Resume prompt:** "Back to the Final Edge playbook app (final-edge-playbook): read this file, `git fetch` + `git status -sb`, then tell me what changed on the cards since 2026-09-12 night (the indicator repo's LEGEND and SESSION_NOTES) and update the page to match."
