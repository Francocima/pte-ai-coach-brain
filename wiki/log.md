# Wiki Log

Append-only record of all operations.

---

## 2026-05-19 — Initial ingest (25 raw files)

**Sources ingested:**
- `3–15 Days PTE Study Plan _ Full Strategy to Score 79+🔥.md`
- `Crack PTE Exam in 1 Hour _ Full PTE Course 2026 _ 22 Modules Live Demo.md`
- `PTE Academic & UKVI test format_ Speaking & Writing.md` + variants (1–8)
- `PTE Academic & UKVI test format_ Reading.md` + variants (1–4)
- `PTE Academic & UKVI test format_ Listening.md` + variants (1–7)
- `PTE Writing Essay_ 10 Secret Hacks To Score 90_90 🔥.md`
- `PTE-Academic-Test-Taker-Score-Guide.pdf` — **could not be read** (poppler-utils not installed on this machine)

**Pages created (11):**
- `pte-overview.md`
- `speaking-modules.md`
- `reading-modules.md`
- `listening-modules.md`
- `scoring-strategy.md`
- `study-plan.md`
- `essay-writing.md`
- `write-from-dictation.md`
- `fluency-training.md`
- `note-taking.md`
- `reading-fill-in-the-blanks.md`

**Pages created (infrastructure):**
- `index.md`
- `log.md`

**Known gap:** Score guide PDF not ingested. Install `poppler` (`brew install poppler`) to enable PDF reading, then re-ingest.

---

## 2026-05-19 — Ingest (2 new raw files)

**Sources ingested:**
- `PTE Essay Writing Guide _ PTE Writing Essay Template 2026.md` (ptetutoringonline.com.au)
- `pte-writing-essay-template-for-90-score.pdf` (Gurully)

**Pages updated (1):**
- `essay-writing.md` — Added 5th essay type (Two-Part Question), scoring rubric descriptors per level, sentence starter templates with adaptation caveat, academic phrase bank, pre-submit checklist; updated sources and summary

**Pages created (1):**
- `essay-sample-questions.md` — 10 model essay questions with full worked answers (Q1–Q10)

**Infrastructure updated:**
- `index.md` — Added essay-sample-questions.md entry; updated essay-writing.md description

---

## 2026-05-19 — Mock test practice answers added

**Source**: Franco's mock test results (2026-05-19)

**Pages created (1):**
- `swt-practice-answers.md` — 2 Summarize Written Text passages with platform-suggested answers, critiques, and improved model answers

**Key insight recorded**: Platform correction agent prioritises content coverage but produces weak grammar (coordination chains) and heavy verbatim lifting. Use platform answers as content checklists only.

**Infrastructure updated:**
- `index.md` — Added "Practice & Worked Examples" section with swt-practice-answers.md entry

---

## 2026-05-20 — Ingest (3 new raw files, SWT technique)

**Sources ingested:**
- `PTE Summarize Written Text Guide 2026.md` (OneAustraliaGroup)
- `PTE Writing Summarize Written Text Scoring Tips.md` (Edubenchmark)
- `PTE Writing_ Summarize Written Text Masterclass _ After Changes _ Tips, Strategies & Template.md` (Language Academy PTE, YouTube transcript)

**Pages created (1):**
- `swt-technique.md` — Full SWT strategy: scoring breakdown, kill switch logic, post-2025 Pearson changes (human review + higher contribution ~40 pts total), copy-paste + connector method, word count target (60–65), vocabulary synonym trick, templates, common mistakes

**Pages updated (1):**
- `swt-practice-answers.md` — Added cross-link to swt-technique.md in intro and related pages

**Infrastructure updated:**
- `index.md` — Added swt-technique.md under High-Impact Technique Pages

**Key insight recorded**: Post-2025 Pearson changes added human review for content and raised SWT's contribution to ~22 writing + ~18 reading = ~40 points total. The copy-paste strategy (extract sentences, connect with commas + connectors, replace 2–3 words with synonyms) remains valid and recommended by Language Academy after the changes.

---

## 2026-05-27 — Ingest (3 new raw files, APEUni guides)

**Sources ingested:**
- `Free PTE Exam Tutorials & Material.md` (APEUni — SWT guide)
- `Free PTE Exam Tutorials & Material (1).md` (APEUni — Write Essay guide)
- `Free PTE Exam Tutorials & Material (2).md` (APEUni — Summarize Spoken Text guide)

**Pages updated (3):**
- `swt-technique.md` — Added APEUni 3-rule sentence selection filter (topic relevance, no examples, prefer conclusions); added conjunction warning section (however/therefore/moreover are adverbs, not conjunctions — comma splice breaks Form score)
- `essay-writing.md` — Added 17% Writing contribution stat; restructured time allocation into high-level (plan/write/proofread) and detailed (intro/body/conclusion) breakdown
- `note-taking.md` — Added SST note density target (1 main point per 2–3 audio sentences), fallback rule (write at least 5 sentences you can understand), daily practice recommendation (2–3 tasks/day)

**Key insight recorded**: The conjunction warning in SWT is the most critical new finding — transitional adverbs (however, therefore, moreover) cannot join two clauses into one sentence without a proper conjunction or semicolon. This is a common grammar error that directly breaks the Form score.

---

## 2026-06-04 — Major ingest (16 new raw files: SST, speaking tasks, official Score Guide)

**Sources ingested:**
- `Best Way to Master Summarize Spoken Test in PTE Listening.md` (Language Academy)
- `Summarise Spoken Text Masterplan New Template_.md` (Skills PTE / Nakul, YouTube transcript)
- `The Latest Summarize Spoken Text Templates (2026).md` (PTE Tutoring Online)
- `PTE 2026 Update! Retell Lecture Strategy That Actually Works!.md` (A One Australia PTE)
- `PTE Summarize Group Discussion_ The ULTIMATE Blueprint for 90! (Masterclass).md` (Language Academy PTE)
- `Prepare for PTE Academic _ Summarize group discussion _ Everything you need to know 💡.md` (Pearson, official)
- `PTE Respond to a Situation Strategy 90 Score Method.md` (Sandeep / Best PTE Coaching)
- `Prepare for PTE Academic _ Respond to a situation _ Everything you need to know 💡.md` (Pearson, official)
- `The do's and don'ts of the Describe Image question type in PTE Academic.md` (Pearson, official)
- `Top 10 PTE Speaking Tips to Boost Your Score.md` (Boston Institute)
- `PTE-Academic-Test-Taker-Score-Guide.pdf` (Pearson, official) — **now successfully read** (resolves the 2026-05-19 known gap; PDF read worked this session)
- Also reconciled: `PTE Summarize Written Text Guide 2026.md`, `PTE Writing Summarize Written Text Scoring Tips.md`, `PTE Writing_ Summarize Written Text Masterclass...md`, `Free PTE Exam Tutorials & Material.md` (SST word-limit cross-refs)

**Pages created (6):**
- `pte-score-guide.md` — official scoring anchor: AI+human model, the 7 human-reviewed tasks, per-trait maxima for all 22 question types, IELTS (July 2025) + CEFR alignment, admission benchmarks, automated scoring engines (IEA/KAT, Versant)
- `sst-technique.md` — Summarize Spoken Text: official 12-mark scoring, the "meaningful sentence" rule (directly addresses Franco's exam feedback), three-phase method, template scaffolding, template-safety warning
- `retell-lecture.md` — three-column notes, pre-audio image trick, 38–40s rule, recovery phrases, post-Aug-2025 human review
- `summarize-group-discussion.md` — per-speaker notes, "structure not template" (avoids human flagging), synthesis-level Content requirement, relevance-over-attribution
- `respond-to-a-situation.md` — NEW Aug-2025 task: Situation/Person/Goal decode + SIMPLE framework, relevant-and-sufficient Content, anti-memorisation
- `describe-image.md` — official do's/don'ts, the memorised-template=0 trap, Content rubric, safe frame

**Pages updated (5):**
- `swt-technique.md` — **corrected Content max from 2 → 4** (the table summed to 7 but was labelled 9; official guide + Language Academy confirm 4); added official scoring source, human-review note, SST cross-link
- `speaking-modules.md` — **corrected Answer Short Question** (3–4 → 5–6 questions; Speaking → **Listening only**); added official traits per task; flagged Describe Image memorised-template=0 risk; updated Respond to a Situation (new Aug-2025, anti-memorisation supersedes old "use keywords directly" advice); linked all 5 deep-dive pages
- `note-taking.md` — SST corrected to 1 question; added three-column/38–40s refinement pointer for Retell Lecture; cross-linked deep-dives
- `scoring-strategy.md` — added IELTS/CEFR target translation (79+ ≈ IELTS 8.0, C1); **moved Answer Short Question out of the skip list** (it scores Listening — free point); flagged −1 negative marking on MCMA; relabelled marks as coaching estimates deferring to official guide
- `index.md` — added Score Guide to Core Reference; added "Speaking Task Deep-Dives" section (4 pages) + SST under technique pages

**Contradictions resolved (official guide wins):**
1. SWT Content max: wiki/Edubenchmark said 2 → **official 4**
2. SST Content max: Nakul's video said 2 → **official 4**
3. Answer Short Question: wiki said Speaking/3–4q/skip → **official Listening/5–6q/free point**
4. SST & SWT Form: coaches say "outside band = 0" → **official gives partial credit** (SST 40–49/71–100 = 1; SWT band is the hard one). Advised aiming for full-credit band regardless.
5. Describe Image: coaching template vs official "memorised = 0 Content" → resolved as "flexible frame filled with real image data."

**Key insight recorded**: The official Score Guide confirms **7 task types get human Content review** (Describe Image, Retell Lecture, Respond to a Situation, SGD, SWT, Write Essay, SST) and that **memorised/pre-prepared material is classified as irrelevant → Content 0 → no further scoring**. This is the single mechanism behind every "don't use templates / don't write meaningless keyword sentences" warning across the wiki, including the exam feedback Franco received on SST.

---

## 2026-06-04 — Answer-strategy cheat sheet (synthesis page)

**Trigger**: Franco asked for an answer-strategy page covering each question type across the pillars (his focus is answer strategy, not timing).

**Pages created (1):**
- `answer-strategy.md` — single cheat sheet covering all **22 question types** across the three parts. Each block: top-answer move + exact steps + bottom-band trap + deep-dive link. Opens with the universal rule (reformulate connected content, never keyword-fill a template; memorised = Content 0) and closes with an effort-priority list. Chose one consolidated page over 12 fragmentary per-question files to respect simplicity; the 9 high-value tasks link out to their existing deep-dives.

**Infrastructure updated:**
- `index.md` — added Answer Strategy under Core Reference

**No new sources** — pure synthesis of the official Score Guide + existing deep-dive pages.
