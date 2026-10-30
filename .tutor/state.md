# Tutor state (private)

- **Current session number:** 5 (check-in delivered as files 2026-10-28, quiz pending). Next is Session 6.
- **Last surprise test:** none. Rules: no surprise test before session 4, never two in a row, aim for one every 6–8 sessions. Roll `random.random()` against p = min(0.9, 0.08 × (sessions since last test, or since session 0)). Hold off if 2+ sessions are pending.
- **Pending grading:** Session 2 (2026-10-25), Session 3 (2026-10-26), Session 4 (2026-10-27), Session 5 (2026-10-28); keys in `.tutor/keys/`. All four blank as of 30 Oct run (2nd consecutive hold day); no email reply to the cadence question.
- **Analysis written:** `analysis/2026-10-28.md` (after S5; main finding: consistency, not content). Next analysis after S10 or the first surprise test, or when answers first arrive if trends shift sharply.
- **Session 6 plan:** if any answers are in, grade ALL pending sessions in one combined `result.md` per session (+ answer-key.md each), update per-topic accuracy, then resume with A8 board composition (Sec 149(1) min/max directors and 15-director cap, woman director per Rule 3, resident director Sec 149(3) 182 days) plus revision of any misses; go at 2 topics/session to recover pace. If ALL of S2–S5 are still blank: do NOT create a new session folder or quiz (avoid piling up). Just add a run-log line, and send a short reminder email pointing to S5 (5 Qs) and `/id-session`. Resume new content only when answers arrive. Consider asking Chintan (in email) whether a lower cadence (e.g. 3 runs/week) would suit better.
- **(Done) Session 5:** check-in only: Sec 149 one-screen map + 5-Q check (A2 50-cr "exceeding" trap, A1 relative-employee proviso, A3 2-year deadline, A5 evaluation by entire board, A6 sitting fee outside caps). No surprise roll (4 pending).
- **(Done) Session 4:** revision only, as planned: A4–A7 one-pagers + 6-Q recap (A4 ×2, A5, A6, A7, B1). No surprise roll (2+ pending).
- **(Old) Session 4 plan:** if Sessions 2 and 3 are still both blank, this makes 2+ pending: do NOT add new topics and do NOT roll for a surprise test. Instead deliver a short revision sheet (A4–A7 one-pagers) plus a 6-question mixed recap, and nudge Chintan. If answers are in: grade both, then A8 board composition (Sec 149(1) min/max directors, woman director per Rule 3, resident director Sec 149(3)) with revision of any misses.
- **(Done) Session 3:** A6 remuneration (Sec 149(9), 197(1)/(5)/(7), Rule 4 sitting fee Rs 1 lakh, Schedule V Sec II 12/17/24 lakh, Reg 17(6)(a)/(b)/(ca)) and A7 liability (Sec 149(12), 2(60)(vi), 463, MCA GC 01/2020, IBC 66(2)). Light: 8 MCQs incl. 2 revision (A3 overlap, B1 1/3 rounding).
- **Mode (from 2026-10-25): hybrid fallback.** Routine fires deliver files; interactive `/id-session` takes priority whenever Chintan runs it and should grade pending answers.md or quiz the file content in chat.
- **Mode (2026-10-20 to 2026-10-24):** interactive in-chat sessions via `/id-session`.

## Study plan (~7 weeks, ~30 min/day, starting 20 Oct 2026)

| Week | Focus |
|---|---|
| 1 | A1–A3, B1 fundamentals (done S1); A4, A5 (S2); A6, A7 (S3); A8 board composition |
| 2 | A9 disqualification/removal/resignation, A10 duties (Sec 166), A11 board meetings, A12 committees (Sec 177, 178), A15 disclosure of interest |
| 3 | A13 RPT (Sec 188) + B4 LODR RPT, A14 loans/investments, A16 board's report, A17 auditors, A18 vigil/fraud, A20 CSR |
| 4 | SEBI: B2, B3, B5, B6 LODR; B7 PIT; B8 SAST; B9 ICDR basics |
| 5 | Accountancy C1–C7 (statements, ratios, audit reports, red flags) |
| 6 | Corporate governance D1–D6 and case studies; related laws E1–E5; A19, A21–A24 overviews |
| 7 | Mixed revision, timed mocks; book the exam once mixed scores are ≥ 70% |

Pacing rules: move on when a topic is above 75%, revise when it is below 60%, and slow down if answers are not being submitted.

## Notes on how Chintan learns

- S1: 8/10. Strong on the direct threshold and independence tests. Slipped on second-layer rules (an overlap counted once; the ratio switching with chair type), so build in "rule plus exception" questions.
- Asks definitional doubts (pecuniary relationship, KMP). Define jargon up front in lessons.
- No AskUserQuestion tool in this environment, so the quiz runs in chat with batches of 4 and typed letters. Watch for typos in replies (S1: typed "3B" for Q4).
- Has not yet submitted any file-based answers (S2–S4 blank as of 28 Oct). Chat mode worked better (S1); keep nudging `/id-session`.

## Run log

- 2026-10-30 (scheduled routine): S2–S5 still blank, no email reply (Gmail search: only tutor emails). Held again: no new folder/quiz, no surprise roll. Emailed a short reminder offering a 10-minute minimum (S5 only). Next: if still blank on 31 Oct, log only and skip the email; from 1 Nov email every other day (1, 3, 5 Nov). If blank through 3 Nov, send one email proposing a pause plus a 3-runs/week restart, and pause new content until Chintan replies.
- 2026-10-29 (scheduled routine): S2–S5 still blank, no email reply. Per plan: no new session folder or quiz, no surprise roll. Logged the run and emailed a short reminder (start with S5, 5 Qs; or `/id-session`). Same rule next run: if still blank, log + brief reminder only; from 1 Nov consider emailing only every other day to avoid inbox noise.
- 2026-10-28 (scheduled routine): S2–S4 still blank (pending, not fails). Per plan: no new topic; delivered S5 as a 5-Q check + Sec 149 map; wrote analysis/2026-10-28.md. No web verification needed (provisions already verified in S1–S3). Emailed via Gmail (also offered a lower cadence).
- 2026-10-27 (scheduled routine): S2 and S3 still blank (pending, not fails). Delivered revision-only Session 4 per plan. No web verification needed (no new provisions). Committed via local git.

- 2026-10-26 (scheduled routine): S2 answers blank, so pending (not a fail). Delivered light Session 3 (A6, A7, 8 MCQs). Verified Schedule V Sec II NED limits (18 Mar 2021 amendment) via web search. Local Bash was unavailable (auto-mode classifier errors), so the commit was pushed through the GitHub MCP push_files tool; no `random` roll needed (session < 4). Emailed via Gmail.
- 2026-10-25 (scheduled routine, 5th fire): no interactive session since 20 Oct and no reply. Switched to file delivery: Session 2 (A4, A5) + 10-MCQ quiz. Verified the Reg 25(2A) deemed-approval proviso and Rule 4(2) vacancy timeline. Emailed Chintan with Gmail.
- 2026-10-24 / 23 / 22 / 20 (scheduled routine): fired during interactive mode; no content, notifications sent.
- 2026-10-20 (interactive): recap, doubts on pecuniary relationship and KMP, quiz 8/10. Wrote session.md.
- 2026-10-20: First run. Created layout, syllabus and plan; delivered Session 1. Facts verified on the IICA databank self-assessment page and secondary sources (50 Qs, 75 min, no negative marking).
