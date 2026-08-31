# Claude Note Analyzer

A lightweight note-taking and note-analysis system designed for use with Claude.

This is **not an app**. It is a small set of Markdown instruction files that can be added to a Claude Project or used as project knowledge/instructions.

The goal is to turn messy school material into clean, understandable, study-ready notes.

## What It Can Do

- Organize jumbled or incomplete notes
- Turn PowerPoint presentations into useful notes
- Analyze text, diagrams, charts, and images in slides
- Reduce long slides without removing important information
- Group related ideas together
- Explain difficult concepts in simple college-level language
- Preserve professor examples, definitions, numbers, formulas, and frameworks
- Give extra attention to confirmed test material
- Identify material that appears especially testable without pretending it is confirmed
- Follow a consistent visual note-taking style

## Core Principle

The system separates three things:

1. **Style references** tell Claude how the notes should look.
2. **Course material** tells Claude what the notes should contain.
3. **Test-priority instructions** tell Claude what deserves extra attention.

Style examples are never treated as course content.

## Files

- `INSTRUCTIONS.md` — Claude's overall role and behavior
- `NOTE_STYLE.md` — how finished notes should look
- `ANALYSIS_RULES.md` — how Claude should analyze messy notes, PowerPoints, visuals, and course material
- `TEST_PRIORITY.md` — how confirmed and possible test material should be handled
- `USAGE.md` — simple prompts for using the system
- `examples/STYLE_REFERENCE_RULE.md` — explains how style examples should be interpreted

## How to Use With Claude

Create a Claude Project and add these Markdown files to the project knowledge or instructions.

Then use a simple instruction such as:

> Follow the note-taking system in the project files. Analyze the attached material and turn it into study-ready notes.

You can also tell Claude what is important for an upcoming test before it analyzes the material.

Example:

> My professor confirmed that EOQ, safety stock, and inventory turnover will be on the test. Treat those topics as TEST PRIORITY. Now analyze the attached PowerPoint and create notes.

## Important

Claude should never claim something is definitely on a test unless the student, professor, study guide, or supplied course material explicitly confirms it.
