# PTE Academic Knowledge Base

A personal knowledge base for PTE Academic preparation, maintained using Claude Code following the [LLM Wiki pattern](https://karpathy.ai/llmwiki) by Andrej Karpathy.

**Target score:** 79+

---

## What's inside

### Core reference
- PTE test structure, scoring logic, and IELTS/CEFR alignment
- Per-module marks breakdown and skip list
- One-page cheat sheet for all 22 question types

### Section guides
- Speaking (9 question types)
- Reading (5 question types)
- Listening (8 question types)

### High-impact technique pages
- Write from Dictation, Essay Writing, SWT, SST
- Fluency training, note-taking strategy
- Reading Fill in the Blanks

### Practice material
- Worked examples with platform critiques and model answers

---

## How to download

**Option 1 — Clone with Git**
```bash
git clone https://github.com/YOUR_USERNAME/pte-knowledge-base.git
```

**Option 2 — Download ZIP**
1. Click the green **Code** button at the top of this page
2. Select **Download ZIP**
3. Unzip the folder on your computer

---

## How to use it

Browse [wiki/index.md](wiki/index.md) for the full table of contents. All pages are interlinked. Start there.

The `raw/` folder contains the original source documents. The `wiki/` folder contains the structured, synthesized notes — that's where you want to spend your time.

---

## How to plug it into Claude or another LLM

### Claude Code (recommended)
1. Open the folder in Claude Code (`claude` in your terminal from the project root)
2. Ask questions like: *"What is the best strategy for Write from Dictation?"*
3. Claude will read the wiki and answer with citations

### Claude.ai or ChatGPT (manual)
1. Open the relevant wiki page (e.g. `wiki/essay-writing.md`)
2. Copy the content and paste it into the chat as context
3. Ask your question on top of it

### Any LLM with file upload
1. Upload the files from `wiki/` as context documents
2. The pages are plain markdown — compatible with any LLM that accepts text files

### Cursor or VS Code with Copilot
1. Open the project folder in your editor
2. The wiki pages will be available as context for inline AI suggestions

---

## Folder structure

```
raw/          -- source documents (immutable)
wiki/         -- structured notes maintained by Claude
wiki/index.md -- full table of contents
wiki/log.md   -- append-only change history
```

---

## Note

This is a read-only public reference. No contributions or pull requests are accepted.
