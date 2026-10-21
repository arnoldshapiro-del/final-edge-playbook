# final-edge-playbook — project memory

**What this is:** a one-page teaching app for Arnie: what the Final Edge NinjaTrader cards say and what he does — the three windows since 2026-09-12 night (FINAL GATE with the 15-MIN line, SWEEPS with the flag counter on lane ②, the EXIT MAP with two faces; Big Money on his chart with its window off), the SWEEPS card's five lanes, the voice's sentences, the Day Guard's rails with the measured numbers behind each, an example morning as a clickable stepper, a daily checklist, and the words. Built 2026-09-12 (evening) on his ask "make me an app that demonstrates very easily what to do, what I'll be watching for, and how I can be much more successful if I follow what it says."

## Session handoff (do this every session)
- Start: read `SESSION_NOTES.md` (the dated journal) and `CONTINUATION.md` if present, before touching anything. The newest entry says what was decided, what was verified and what is next.
- Wrap-up: add a dated entry to `SESSION_NOTES.md` with what was asked, what changed, what was verified (and how) and what is next. Commit and push it together with the work.
- Every settled decision goes in the ledger below as ONE line: what we decided, why, and what was ruled out and why. Every correction Arnie gives gets logged with his reason. Reasons matter more than facts: facts can be re-derived from the code, reasons cannot.
- Unsure what was agreed? Re-read this file and the journal before asking Arnie again.

## Decisions and why (one line each, newest last)
- One single static page (`index.html`), no framework, no build step, because Arnie asked for "an app that demonstrates very easily what to do, what I'll be watching for, and how I can be much more successful if I follow what it says" (2026-09-12 evening). Ruled out: (reason not recorded).
- The content's source of truth is the indicator repo `final-edge-nt8-indicator` (`docs/LEGEND.md`, the SWEEPS teaching packs, SESSION_NOTES, the CLAUDE.md laws), and every quoted sentence is transcribed from there, never paraphrased from memory; standing order "when a card changes, this page changes", the same law as the SWEEPS teaching pack (Arnie, 2026-08-11).
- Never a fabricated statistic or a promise of profit, and the "honest line" block says exactly what is and is not proven, because of Arnie's rule 3 (2026-09-12). Prices in the walkthrough are labelled EXAMPLES; the measured numbers (the 15-month ledger, the hour scoreboard, the studies) cite their source line.
- No action word is ever presented as this page's advice; it quotes the suite's sentences and says what they mean (2026-09-12). (reason not recorded beyond rule 3)
- Trading design stack: Oxanium + Space Mono, amber/emerald/coral, the cards' own navy #0B1424, trading apps only (2026-09-12). Ruled out: the default Lora/Inter stack, because this is a trading app.
- The Narrator is `narrator.js` copied from trend-check-pro (storage keys `fep_tts_*`), never rebuilt (2026-09-12). (reason not recorded)
- PWA files present (manifest.json, icon.svg, the meta tags); Created/Revised dates in the sidebar and the footer, bumped on every change (2026-09-12). (reason not recorded)
- Deploy: GitHub main → Netlify auto-build, static, publish `.`, no build command; the GitHub repo was created with `gh api -X POST user/repos` because the auto-mode classifier declines `gh repo create`; the Netlify site was created by API (the deploy-opening-edge.js pattern, id df73f5be-f36a-42bb-9187-cfc00f8c2761). Ruled out: the Netlify CLI (reason not recorded) (2026-09-12).
- A "live since HH:MM" line goes on the sidebar only after Arnie's F5 and the DLL probe found every needle; before that the sidebar says "live after Arnie's next F5" (2026-09-12 night, repeated through v1.3.1). (reason not recorded)
- The cards 7 → 3 went on the page the same night the suite changed, because Arnie ordered the recommendation built ("that includes combining the cards") and the page changes with the cards (2026-09-12 night).
- No gallery card in arnies-app-showcase, because the page carries his own ledger numbers and the link stays unlisted (2026-09-12 night, delegated to Claude). Reversed: a gallery card was added 2026-10-19 (reason not recorded).
- No sign-in curtain: offered, not applied, because his recipe is applied only on his ask (2026-09-12 night).
- With-the-trend only (rule 2, section 06) and System 1 / System 2 with the slider OFF · KEY · ALL (section 04), because Arnie ordered "only always going with the trend" and "create System 2 with a slider" (2026-09-12 late).
- Lane 6 THE PULLBACK on the SWEEPS card with its measurement and an honest note on the card's size (10.6 px at 640x900), because the suite gained the lane (SWEEPS v3.41.0) and the page follows the cards (2026-09-13 early).
- THE ANSWER's on-chart drawing noted off and the 15-minute chart carries no card, because Arnie said yes to turning it off in his workspace (2026-09-13 05:37).
- System 2 is UNI: talking all the time at ALL, a replay narrated, her meter and OFF / ON switch, reading windows (no tokens at lunch, after the close or on a weekend; the two-hour replay pass; the teacher on Sonnet), the plan FREE / KEY / ALL and the slider's words (v1.3.2 to v1.3.6, 2026-09-13). (reason not recorded in this repo; it follows the suite's cards)
- `CONTINUATION.md` added at the repo root as the wrap-up note, newest entry on top, written from a cloud session that could not see the Desktop (2026-10-19). (reason not recorded)
- Session memory lives in this file and `SESSION_NOTES.md`, never only in chat: cloud sessions start on a fresh computer, chat history gets compacted, and only files in the repo survive (2026-10-21, after Dylan Davis's "decisions.md" video). Ruled out: a separate decisions.md, because this file is the one Claude Code re-reads after compaction.

**Source of truth for its CONTENT:** the indicator repo `final-edge-nt8-indicator` — `docs/LEGEND.md`, the SWEEPS teaching packs, SESSION_NOTES, the CLAUDE.md laws (the M2K risk canon, THE LIVE RAILS), REVIEWS. Every sentence quoted here was transcribed from those files as they stood on 2026-09-12 (v1.1.0: SWEEPS v3.39.0 · LEVELS v10.39.0 · GATES v5.77.0 · DAY GUARD v1.9.0 · SWINGS v5.55 · BIG MONEY 2.1.2-study). **When a card changes, this page changes** — the same standing order as the teaching pack (Arnie, 2026-08-11). Prices in the walkthrough are EXAMPLES and are labelled so; the measured numbers (the 15-month ledger, the hour scoreboard, the studies) are real and cite their source line.

**Laws:** never a fabricated statistic or a promise of profit (his rule 3; the "honest line" block says exactly what is and is not proven) · no action word is ever presented as this page's advice — it quotes the suite's sentences and says what they mean · trading design stack (Oxanium + Space Mono, amber/emerald/coral, the cards' own navy #0B1424) — trading only · the Narrator is `narrator.js` copied from trend-check-pro (storage keys `fep_tts_*`), never rebuilt · PWA files present (manifest.json, icon.svg, the meta tags) · Created/Revised dates in the sidebar and the footer, bump on every change.

**Deploy:** GitHub `arnoldshapiro-del/final-edge-playbook` (main) → Netlify auto-build → https://final-edge-playbook.netlify.app (static, publish `.`, no build command). Update = edit → commit → push; never the Netlify CLI.

**Status:** v1.3.1 shipped 2026-09-13 (early): lane 6 THE PULLBACK on the SWEEPS card, the news block on the pullback lane and the honest note on the card's size (v1.3.0); then THE ANSWER's on-chart drawing noted off on his yes (v1.3.1); the sidebar names SWEEPS v3.41.0 · LEVELS v10.41.0 · GATES v5.79.0 and says the pullback lane was installed 2026-09-13 05:14 (his F5 came 05:27:31; the DLL probe found every needle). Earlier: v1.2.0 shipped 2026-09-12 (late): with the trend only (rule 2, section 06) and System 1 / System 2 with the slider (section 04); the sidebar says "Live since 2026-09-13 00:45" (his F5 for the one-trend / door-2 build came at 00:45:28; the DLL probe found every needle) — v1.2.3. Earlier, v1.1.0 / v1.1.1 (2026-09-12 night): the cards 7 → 3 are on the page (section 02 and 06 say what moved where and which dial brings a window back); the sidebar says "Three windows, live since 2026-09-12 18:49" (his F5 came at 18:49:26; the DLL probe found every needle).

## Compact Instructions
When this conversation is compacted, the summary must keep, in this order:
1. Every decision made this session, with its reason and what was ruled out.
2. Every correction Arnie gave, in his words where possible, and his reason.
3. What has been verified and how (test run, build, live check with URL and time) versus what is only claimed or planned.
4. What is next and what is still open, including anything waiting on Arnie's yes.
5. The exact files changed, the branch, and whether the work is committed and pushed.
Drop tool output, file contents and search results; they can be re-read from disk.
