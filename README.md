# Independent Director Exam – Daily Prep

This is your personal study repo for the **Independent Director Online Proficiency Self-Assessment Test**, run by IICA under Rule 6 of the Companies (Appointment and Qualification of Directors) Rules, 2014.

A tutor session runs **every day at 10:00 AM IST**. Each session adds a new folder under `sessions/` and pushes it to `main`.

## How to use it each day (~30 minutes)

1. Open `sessions/<today>/lesson.md` and read the lessons (about 15 min).
2. Try `sessions/<today>/quiz.md` **without looking anything up**, the way you would in the real exam.
3. Write your answers in `sessions/<today>/answers.md`, one per line, like:
   ```
   Q1: B
   Q2: D
   ```
   Add anything you're unsure about under **Doubts / questions for tutor**.
4. Commit and push (or edit the file directly on GitHub) **before 10 AM the next day**.
5. The next session grades it and adds `answer-key.md` and `result.md` to that day's folder, and answers your doubts.

If you miss a day, nothing breaks. Ungraded sessions stay pending, and the tutor slows down and revises instead of adding more.

## Files

| File / folder | What it is |
|---|---|
| `syllabus.md` | Full topic map with your status per topic |
| `progress.md` | Session log, scores, per-topic accuracy, weak areas |
| `sessions/YYYY-MM-DD/` | `lesson.md`, `quiz.md`, `answers.md` (yours), later `answer-key.md` + `result.md` |
| `analysis/` | Progress reviews every few sessions and after surprise tests |
| `.tutor/` | The tutor's private notes and answer keys. **Please don't open `.tutor/keys/`**, or you'll see the answers before grading. |

## Surprise tests

About once every 6–8 sessions (never in the first 3), a session is a **SURPRISE TEST**: 25 mixed MCQs in 35 minutes, with no lessons that day. Answer it the same way, in `answers.md`.
