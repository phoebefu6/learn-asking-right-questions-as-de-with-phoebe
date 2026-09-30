# learn-asking-right-questions-as-de-with-phoebe - source map

Internal build document. Not linked from any audience-facing page.

Bucket `deng`, difficulty 2, audience both, 6 sessions, single track, no code. One of four
sibling courses sharing one framework, one company and one simulator engine.

**The framework, the shared sources, their evidence tiers and the "never print" list live in ONE
place:** `learn-asking-right-questions-as-da-with-phoebe/materials/official-course-map.md`. Never
restate or fork them here. This file holds only what differs for the data engineer.

Built 2026-09-30.

---

## The role's request and widest door

Harbourline and Adeline Tan are the same constructed case as the DA course. Her request to the
data engineer: "Our numbers never match. Finance says one thing, the POS says another, and the auditor asked which one was right."

**Widest door: Data state.** An engineer's output is a pipeline other people trust. The facts that decide whether it is right are every system a number passes through, who can log in to each, how often each is read, and which copy is declared real; they sit behind door 4. One outcome question goes first to earn the trust door 4's sensitive facts need.

Seams: `learn-data-pipelines` d1 owns tracing one order to a dashboard; `learn-data-observability` owns detecting a broken table; `learn-data-orchestration` owns scheduling. This course owns the meeting before any of them: getting the real data state out of a person who has never seen a schema.

---

## The bench (`assets/asking-live.js`, byte-identical to the DA copy, + `assets/asking-bank-de.js`)

Verified headlessly in node on 2026-09-30. 24 facts worth 68 points, 37 questions,
45-minute budget, cut at 20 minutes.

| Preset | Net value | After 20 min | Facts | Doors | False beliefs |
|---|---|---|---|---|---|
| ANTI: the efficient interview | 17 | 0 | 11 | 5 | 5 |
| The technical opener | 15 | 0 | 5 | 2 | 0 |
| Any order at all (mean of 200) | 27.6 | 13.8 | 12.3 | 5.5 | 2.5 |
| Six Doors, door by door | 47 | 20 | 16 | 6 | 0 |
| Six Doors, tuned for an engineer (data state widest) | 51 | 24 | 17 | 6 | 0 |
| Ceiling (optimizer reads the sheet) | 62 | 34 | | | |

The ceiling order opens with "what happens when Priya is away" before the interviewer has heard the name; optimal against a known sheet is not a method.

Random: best 45, worst 5.

The five false beliefs a leading question records on this bank: "the POS is the source of truth" (the two percent is settlement timing), "pull everything daily" (month-end needs day three, Monday needs weekly), "the vendor API is in use" (nobody has touched it), "finance is simply wrong" (the gap is mostly settlement timing; refunds, which exist only in accounting, are the rest), "stock lives in the POS" (three spreadsheets).

**Findings claimed:** the ordering only (fast and jargon below random, random below the doors,
the role-tuned order at or above the printed order), and the mechanism (jargon costs minutes and
trust, leading questions record wrong beliefs, the most sensitive fact needs trust 3). Never the
numbers as facts about a real business.

---

## Sessions

Same arc as the DA course; session 1 of this course is a short role-framed page that links the
DA session 1 for the corridor and does not restate the six doors.

| # | Title | Role emphasis |
|---|---|---|
| 1 | The gap, from the engineer's chair | the role's tune, the widest door, links the canonical Six Doors |
| 2 | Every system a number passes through | the same five-rung ladder, framed for what this role needs from it |
| 3 | The engineer's questions, and the bench | this bank, this ladder |
| 4 | Teaching while you ask | the one concept per meeting for this role |
| 5 | Three projects, starting with one real copy | three candidates fitted to this role's output |
| 6 | The mock meeting and the one-page brief | the brief with this role's block 4 |

---

## Design system

Palette: **rust and teal.** Scaffolded from the DA course, every hex recomputed; 22 text-on-fill pairs
checked, 0 failures (lowest 5.80).

| Token | Hex |
|---|---|
| deep | `#7C2D12` |
| primary | `#9A3412` |
| mid | `#A8431A` |
| soft | `#F5C9B0` |
| tint | `#FDF4EE` |
| ink | `#2A1A12` |
| muted | `#6B5448` |
| faint / hairline | `#E2CFC3` / `#EEE0D6` |
| accent | `#0E6B6B` |
| accent-ink | `#084C4C` |
| accent tint | `#E4F3F3` |
| paper | `#FFFDFB` |
| code-bg / code-ink | `#2A1A12` / `#EEE0D6` |

Figure grammar: identical to the DA course's hand-drawn grammar with this palette substituted.
`PASSPORT_KEY` = `lwp-passport:asking-right-questions-as-de`.
