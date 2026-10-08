# Note Taking Guidelines for AIML (Prime 2.0)

Whenever creating, extracting, or updating notes in this directory (`AIML/Prime 2.0`) from course screenshots or lectures, strictly follow these guidelines:

---

## 1. Directory & File Organization
- **Subfolder per Day/Topic**: Every day/module must have its own dedicated subfolder formatted as:
  `Day XX - [Topic Name]/` (e.g., `Day 01 - Intro to Machine Learning & Math Foundations/`).
- **Day Hub Note**: Inside each day subfolder, create a Day Hub note named `Day XX - [Topic Name].md`. It acts as the module overview and links to all topic notes for that day with:
  `> Navigation: [[Prime 2.0]]`
- **Topic Note Naming**: Individual topic notes inside the subfolder must be sequentially numbered: `01. [Topic Name].md`, `02. [Topic Name].md`, etc. (e.g., `01. Conditionals and Pattern Matching.md`). Do NOT repeat the `Day XX -` prefix inside individual topic filenames.
- **Strict Hierarchy in Navigation (Clean Obsidian Graph)**:
  - `[[AIML]]` is the root vault index. It links **only** to course hubs like `[[Prime 2.0]]`.
  - `[[Prime 2.0]]` links **only** to the Day Hub notes (`[[Day XX - Topic Name]]`).
  - Day Hub notes link to their individual topic notes (`[[01. ...]]`, `[[02. ...]]`).
  - Individual topic notes link **only** to their Day Hub: `> Navigation: [[Day XX - Topic Name]]`.
  - **NEVER** link individual topic notes directly to `[[AIML]]` or `[[Prime 2.0]]` (this keeps the graph organized in clean clusters and prevents spiderwebs).

---

## 2. Core Principles & Philosophy
- **Beginner-Friendly & Simple English**: Always write for someone learning for the first time. Use simple, everyday words. Avoid unnecessarily dense, academic, or heavy jargon. If a technical term is used, explain it instantly with simple intuition.
- **Relatable Real-World Analogies**: Anchor every concept in simple, everyday real-world examples (e.g., traffic signals, recipe cards, classroom attendance, TV remotes) before showing code.
- **Skip Practice & Question Videos**: Strictly **DO NOT** create individual files or notes for practice problems, coding exercises, or question videos (e.g., *Odd or Even*, *Multiplication Table*, *Vowel Count*, *Sum of N numbers*, *Factorial of N*, *Practice Examples*). Only create clear, conceptual, and interview-focused notes for core technical topics.
- **Interview-Ready in Plain Words**: Keep interview definitions and Q&A answers concise, natural, and easy to explain in a technical interview without sounding like a memorized dictionary.
- **Code Policy**: Provide short, clean, beginner-friendly Python examples with simple comments explaining what each line is doing.
- **No Emojis**: Strictly avoid emojis anywhere in notes (headings, text, callouts, tables). Keep notes clean, professional, and minimal.

---

## 3. Obsidian Formatting Standards
- **Tags**: Plain hashtags on line 1 (e.g., `#aiml #prime2 #python #interview-prep`).
- **No Frontmatter**: Do NOT use YAML frontmatter (`--- ... ---`).
- **No Top H1 Title**: Do NOT add an `# H1` heading at the top (Obsidian uses the file name). Start directly with tags and breadcrumbs.
- **Breadcrumb Navigation**: Topic notes link only to their parent Day Hub:
  `> Navigation: [[Day XX - Topic Name]]`
- **Callout Boxes**: Use standard Obsidian callouts for definitions and key takeaways:
  - `> [!NOTE]` for formal definitions
  - `> [!IMPORTANT]` for crucial interview traps and caveats
  - `> [!TIP]` for practical industry best practices

---

## 4. Standard Note Structure

```markdown
#aiml #prime2 #topic-tag #interview-prep

> Navigation: [[Day XX - Topic Name]]

---

## The Core Overview / Summary

[Brief high-level overview and a clean comparison table summarizing key algorithms / concepts]

| Concept / Algorithm | Simple Meaning | Key Formula / Mechanism | When to Use |
| :--- | :--- | :--- | :--- |
| ... | ... | ... | ... |

---

## 1. [Concept Name] — "[One-line intuitive question/summary]"

### Intuitive Mental Model
[How to think about this concept simply]

> [!NOTE]
> **Interview Definition:**
> [Clear, precise definition suitable for answering in an interview]

### Mathematical Formulation & Mechanics
[Formulas in LaTeX, variable definitions, and step-by-step logic]

---

## 2. Implementation & Code (If Applicable)
```python
# Clean, commented Python / PyTorch implementation
```

---

## Quick Interview Q&A (Cheatsheet)

### Q1: [Common Technical Interview Question]?
> **Answer:**
> [Concise, technically precise answer highlighting trade-offs]

### Q2: [Common Technical Interview Question]?
> **Answer:**
> [Concise, technically precise answer highlighting trade-offs]
```
