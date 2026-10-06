---
name: interactive-html-explainer
description: Make a tiny browser-based explorable that teaches through a slider, button, or direct manipulation. Use when: A concept becomes clearer when someone can change a value and see what happens.
license: MIT
metadata:
  author: Edward Xiong
  version: 1.0.0
---

# Interactive HTML Explainer

Make a tiny browser-based explorable that teaches through a slider, button, or direct manipulation.

## When to use

A concept becomes clearer when someone can change a value and see what happens.

## Workflow

1. Pick one concept and one visual metaphor.
2. Write the learner’s prediction before showing the result.
3. Build a self-contained HTML/CSS/JS page with labels and keyboard support.
4. Explain the relationship the interaction reveals.

## Output

Return a usable result for the user’s actual task. State assumptions, evidence, and uncertainty where they affect the result. Keep the output format suited to the job: working HTML, a storyboard, a decision brief, a draft, code, or a short answer. Do not claim that a result was tested, published, or verified unless that action was completed.

## Starter prompt

> Create one self-contained HTML file that teaches [concept] by letting a learner manipulate [input]. Show the idea visually, label units, and update the result immediately. Give the learner one prediction question before the control and one reflection question after it. Use semantic HTML, keyboard-accessible controls, responsive layout, and no external libraries. Explain the model’s limitations.

## Quality check

Before delivery, check that the result answers the stated need, follows the requested format, and makes any important limitation visible. Invite the user to adjust the result when taste or judgment belongs to them.
