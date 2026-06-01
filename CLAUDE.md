# Game Theory: Predictive History — Course Authoring Guide

## What This Project Is

A 25-day self-study course built on Prof. Jiang Xueqin's *Predictive History* YouTube series. Each daily guide accompanies one episode. The course is grounded in actual episode transcripts and applies Prof. Jiang's framework to everyday decision-making.

**Channel:** [Predictive History](https://www.youtube.com/@PredictiveHistory)
**Transcripts:** stored locally in `transcripts/` (gitignored — fetch with `python3 transcripts/fetch.py`)

---

## Prof. Jiang's Framework

Stated explicitly in Episode 1. Every situation is a game with three components:

1. **Players** — who are the real participants, ranked by actual power?
2. **Rules** — what are the constraints (boundary conditions) that can't be changed?
3. **Incentives** — what does each player actually benefit from (not what they say)?

> *"If you figure out who the players are, if you understand the rules, you understand the incentives — then you understand how the game works and therefore you can predict how the game will turn out."*

Do NOT substitute a different framework (e.g. "Structure / Incentives / History") — this is what he actually teaches.

---

## Content Standards

### 1. Transcript-First Rule

Every daily guide must be grounded in the actual episode transcript. Do not invent, infer, or fabricate what Prof. Jiang says.

**Workflow for each episode:**
1. Read the transcript from `transcripts/NN-slug.txt`
2. Identify Prof. Jiang's actual arguments, examples, and vocabulary
3. Write the guide from the transcript — not from the episode title alone
4. Label any section that goes beyond the transcript as **Synthesis**

### 2. Guide Format (every day)

```
# Day N: [Title]
**Episode:** #N | **Watch:** [YouTube URL] | **Series:** Predictive History — Prof. Jiang Xueqin

## What This Episode Is About
## Learning Objectives
## Core Concepts
## Key Terms
## In Your Own Life
## Think About It
## Tomorrow  (or ## What's Next for Day 25)
```

### 3. Key Terms Table

```
| Term | Meaning |
```

- Chinese characters go in parentheses after the term: `| Face (面子) | ... |`
- Use **simplified Chinese** throughout (e.g. 战国 not 戰國)
- Add Chinese for all important concepts, even when Prof. Jiang uses the English term — use standard simplified Chinese translations
- **No pinyin** — characters only
- Skip Chinese only for acronyms (PISA, DEI) or terms with no meaningful Chinese equivalent

### 4. Chinese Vocabulary Rules

- Characters only, no pinyin
- Sourced from the transcript — do not invent
- Synthesis terms (e.g. from Art of War) must be labeled as **Synthesis**

### 5. Synthesis Connections

Where relevant, you may draw connections to classical strategic texts (e.g. *Art of War* 孫子兵法, *The Prince*, *Thucydides*) or other game-theoretic traditions. These must be:
- Clearly labeled **Synthesis** so readers know it goes beyond the episode
- Genuinely illuminating — only include if the connection adds insight, not for decoration

---

## What to Do When You Don't Have a Transcript

Mark the file with this banner:

```
> **Draft — not yet verified against the episode transcript.**
> Replace with transcript-grounded material before use.
```

---

## Transcript Status

| Episodes | Status |
|----------|--------|
| 1–29 | ✅ All rewritten from actual transcripts |

Run `python3 transcripts/fetch.py` to fetch all transcripts locally.

---

## File Structure

```
week-01/day-01-dating-game.md       ← Days 1-5
week-02/day-06-worlds-bank.md       ← Days 6-10
week-03/day-11-law-of-escalation.md ← Days 11-15
week-04/day-16-pax-judaica-rising.md← Days 16-20
week-05/day-21-world-war-trump.md   ← Days 21-25
week-06/day-26-holy-empire-of-ai.md ← Days 26-29
transcripts/                        ← gitignored local transcripts
README.md                           ← 29-day index and framework
CLAUDE.md                           ← this file
```

---

## Authoring Checklist (per guide)

- [ ] Transcript read before writing
- [ ] Core Concepts reflects Prof. Jiang's actual arguments and examples
- [ ] Chinese terms sourced from transcript, characters only, no pinyin
- [ ] Synthesis sections clearly labeled
- [ ] "In Your Own Life" applies the episode's ideas (not generic game theory)
- [ ] Draft banner removed
