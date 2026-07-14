# AlgoBridge Learn

**Learn to code by watching it think — not just reading about it.**

![Status](https://img.shields.io/badge/status-active-brightgreen) ![Free](https://img.shields.io/badge/cost-free%20forever-blue) ![Made by](https://img.shields.io/badge/built%20by-a%20high%20schooler-orange)

[Live site →](https://ak3036811-gif.github.io/algobridge-learn/) · Built by [Ayush Kumar](https://ak3036811-gif.github.io/Main-Website/), Grades 11–12

---

## The problem

I started AlgoBridge as a set of free, in-person coding workshops for students who couldn't afford tutors or bootcamps. After almost every session, the same question came up: *"Where do I keep learning after today?"*

Most beginner coding resources fall into one of two traps: they hand you the answer the moment you're stuck (so you never actually struggle, and nothing sticks), or they dump too much information at once and you bounce off. Watching 218 students across 5 NGO cohorts hit these exact walls in person is what shaped this platform — every feature here exists because a specific friction point showed up in a workshop.

AlgoBridge Learn is my attempt to build a coding platform that's designed around *how learning actually works*, not around what's easiest to build.

## Research basis

Every core feature maps to a specific finding from learning science and cognitive psychology. I didn't want to build something and retrofit a justification — I wanted the pedagogy to come first.

| Feature | Research it's built on |
|---|---|
| **Productive Struggle Timer** — hints unlock only after a few minutes of independent work | Desirable difficulties (Bjork, 1994) — some struggle during learning builds stronger long-term memory |
| **Blank-function retrieval exercises** — you write the answer, not recognize it | Active recall / test-enhanced learning (Roediger & Karpicke, 2006) |
| **AI Tutor** — asks guided questions instead of giving answers, hint hierarchy of question → explanation → solution | Intelligent tutoring systems research (VanLehn, 2011) |
| **Mistake Log** — students log and revisit their own misconceptions | Metacognitive monitoring (Dunlosky et al., 2013) |
| **Progressive unlock system, single-problem workspace** | Cognitive load theory (Sweller, 1988) |
| **Adaptive resurfacing of past topics** | Spaced repetition / distributed practice (Cepeda et al., 2006) |

I also ran a small independent study on AI-assisted learning, looking at whether students who used AI to build understanding and then solved independently outperformed students who used AI passively. That finding — that *how* you use an AI tutor matters more than whether you use one — is the design thesis behind the AI Tutor: every prompt is built to send you back to your own thinking, not replace it.

## What I built

- **Three structured learning paths** (Beginner → Intermediate → Advanced), progressively unlocked, covering programming foundations through algorithms, data structures, and systems basics
- **210 practice problems**, filterable by topic and difficulty, separate from the lesson content so practice and instruction are distinct
- **An AI tutor** with a Socratic hint hierarchy, tied to whatever lesson/problem the student is currently on
- **A live algorithm visualizer** (e.g., merge sort) that runs on real, shuffleable data
- **A learning analytics dashboard** tracking retrieval strength, "productive struggle" time, an overconfidence gap (self-rated confidence vs. actual performance), and a 7-day retention forecast — explicitly framed as a *learning* dashboard, not a leaderboard
- **Multi-language UI** (EN/HI/DE/FR/ES/ZH/JA/AR)

**Stack:** HTML/CSS/JS

## Evidence from the workshops

This isn't a formal research study — it's a simple pre/post comparison I ran myself while teaching: I compared how many students got problems correct in the first class of a cohort versus the last. Across 218 students in 5 NGO cohorts, that comparison went from an average of 21% correct to 81% correct. I'm not claiming causality or controlled conditions here — it's an honest snapshot of what I observed while teaching, and it's the reason several platform features (the Mistake Log and Productive Struggle Timer especially) exist: they're direct responses to friction I watched students hit in person.

## What's next

- A proper backend/accounts system so progress persists across devices
- Expanding the practice problem set and building out the Advanced track further
- Running a more rigorous, controlled version of the AI-tutor study

## Links

- Live site: https://ak3036811-gif.github.io/algobridge-learn/
- Portfolio: https://ak3036811-gif.github.io/Main-Website/
- Writing on AI & education: https://itsreadingtimee.blogspot.com

---

*AlgoBridge Learn is a student-built project. All curriculum is original.*
