# Page outlines - learn-asking-right-questions-as-de-with-phoebe

Internal build document. Each page MIRRORS the same-numbered DA page section by section (same
sections, figure genres, table shapes, quiz style, build-along shape), with the content below.
DA pages: /Users/phoebe.fu/Documents/Claude_Work/github_repo/learn-asking-right-questions-as-da-with-phoebe/courses/
Facts come from assets/asking-bank-de.js (quote teach-back lines exactly); numbers only from the map.

## 01-the-gap-from-the-engineers-chair.html · The gap, from the engineer's chair
h1: "The gap, from the <span class="accent">engineer's chair</span>". Mirror DA session 1, EXCEPT the Six Doors are not restated: Part 2 gives the six names in one line and links the DA session 1 corridor, and spends its minutes on the data-state door instead.
- Part 1 "Two tunes, and the word match": tappers and listeners (Newton 1990 via Heath and Heath 2007; reported), curse of knowledge (Camerer 1989). To Adeline "the numbers never match" means "I could not answer the auditor"; to the engineer it means a join, a sync, a reconciliation job. Figure: her tune (the auditor's letter, the two percent) against his (two tables and an arrow). Real world (constructed): the integration project that stalled the week Kenneth went on leave (f23).
- Part 2 "The data-state door, opened widest, but not first": one outcome question first to earn trust (g01, last time two numbers did not match), then every system one sale touches: till, bank settlement, ledger kept by an outsourced bookkeeper, the stock spreadsheet (f08, f11, f14). DalleMule and Davenport 2017 single source of truth vs multiple versions (reported); Reis and Housley 2022 starting / scaling / leading with data (reported). Figure: one sale drawn travelling through four systems, each hand-off numbered, the timing gap marked in the accent colour.
- Part 3 "The teach-back line for an engineer": teach-back lines for g08, g09, g06 quoted exactly. Figure: the question, the teach-back, the fact that comes back (settlement lands two days late), and the lesson that stays ("a mismatch is usually timing, not truth").
- Build-along: the engineer's Six Doors sheet for "our numbers never match", data-state row marked widest, with one outcome question placed first and the reason written beside it.
- Quiz: why "match" is two questions; why one outcome question goes before door 4; why a hand-off is where a number changes. Covered rows: Newton/Heath (reported), Camerer 1989, DalleMule and Davenport 2017 (reported), Reis and Housley 2022 (reported), Harbourline constructed. Footer: Course home / Next 02.

## 02-every-system-a-number-passes-through.html · Every system a number passes through
h1: "Every system a <span class="accent">number</span> passes through". Mirror DA session 2, deeper on door 4 because it is this role's widest door.
- Part 1 "Recorded, typed, or not recorded": the three origins (till, typed Friday sheet, WhatsApp), plus the engineer's fourth: exported by a person on a schedule (Priya's 38 CSVs every Monday, f07; the bookkeeper's one export a month by contract, f14, f18). Lohr 2014 and CrowdFlower 2016 quoted separately.
- Part 2 "Five rungs, as questions" (DAMA five level names, no level 0, reported; questions are ours) applied per system: the POS sits higher than the stock sheet; the 2019 macro nobody understands is rung 1. Link DA session 2 for the ladder in depth.
- Part 3 "Owners, logins, the one key, and the real copy": Kenneth's login (gate 3); the vendor API nobody has used (f11); three stock sheets and the one on Priya's laptop (f13); refunds only in accounting (f09). Figure: the lineage map as she can read it: till -> bank -> ledger, till -> CSV -> Priya -> spreadsheet, with owner, login and read frequency on each box, the one key in the accent colour, and the declared-real copy marked.
- Build-along: draw the lineage from her answers: every number on the month-end pack, its path, each hand-off, owner, login, how often read, and which copy is declared real. Last step: "which arrow is wrong?".
- Quiz: why a copy must be declared real before it is moved; why the bookkeeper's contract is a data-state fact; why Kenneth only comes out once trust exists. Footer: Prev 01 / Next 03.

## 04-teaching-while-you-ask.html · Teaching while you ask
Mirror DA session 4.
- Words she would have to ask about, for an engineer: pipeline, ETL, CDC, schema, idempotent, SLA, warehouse, medallion; plain replacements.
- The one concept worth ninety seconds: "most mismatches are timing, not truth", because "so finance's number is just wrong?" is the belief waiting to happen (x04). Written in full: card settlements land two days late, cash weekly, refunds only in the ledger; what that means for her month-end on day five.
- Twelve teach-back lines quoted exactly from the DE bank's open questions for the build-along.

## 05-three-projects-starting-with-one-real-copy.html · Three projects, starting with one real copy
h1: "Three projects, starting with <span class="accent">one real copy</span>". Mirror DA session 5.
- Outcome in her words: the auditor stops asking, and Priya's Monday takes one hour instead of six (f21).
- Three candidates: (1) declare one stock sheet real and retire the other two; (2) replace Priya's 38 manual downloads with one scheduled export script from what exists, run by Priya, documented (and the vendor API evaluated second, not first); (3) a written month-end reconciliation that states the timing gap (settlement lag, cash deposits, refunds) so finance and POS agree on why they differ before anything is automated. ICE with the combination rule written down, contested. No new tool before a copy is declared real; nothing that depends on Kenneth's login after January.
- Pilot: four outlets, Priya two hours a week, test = the auditor's written answer due in eight weeks and a one-hour Monday, Q1 budget.

## 06-the-mock-meeting-and-the-brief.html · The mock meeting and the one-page brief
Mirror DA session 6.
- Ruler with THIS course's canon: fast 17, jargon 15, shuffle 27.6, doors 47, tuned 51, ceiling 62.
- Block 1 quotes her: "I could not tell him." Block 3 is the lineage as five boxes. Block 4: first is the winner on session 5's grid, the written month-end bridge that declares one revenue number real from the bookkeeper's existing export and needs no admin login (read session 5 for its exact wording and the runner-up), and "no new pipeline yet" is the line that most needs her agreement. Block 5: the auditor stops asking; Priya's Monday is one hour. Pilot lines the tuned run never heard (board and auditor dates, Priya's two hours) are written as "to confirm with you", as session 5 does.
- Ship gate rows reworded for an engineer (every system named, the real copy declared, the timing gap written, no step depending on one login, plus the DA rows on leading questions, read-aloud, names and days). Kenneth's departure shapes block 4 and never appears in the brief.
- Where to next: the three siblings (DA, DS, AI) and the hub.
