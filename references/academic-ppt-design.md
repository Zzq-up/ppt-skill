# Academic PPT Design Guidelines

## Overview

This document defines the design principles for creating graduate-level academic paper presentation slides.

The target presentation style is:

- Research-oriented.
- Clean and professional.
- Human-designed rather than AI-generated.
- Suitable for laboratory seminars, research group meetings, and academic discussions.

The presentation should help the audience understand the research story instead of simply displaying paper content.

---

# Core Design Principles

## 1. Prioritize Research Communication

Every slide should answer one question:

> What is the most important message the audience should remember from this slide?

A slide should contain:

- One central idea.
- A clear visual focus.
- Minimal supporting text.

Avoid:

- Copying paragraphs from papers.
- Listing too many technical details.
- Using slides as paper documents.

---

# Visual Style

## Overall Style

Recommended:

- Minimalist academic style.
- Clean background.
- Strong information hierarchy.
- Balanced whitespace.
- Consistent alignment.

Avoid:

- Business presentation style.
- Excessive decorative elements.
- Colorful templates.
- AI-generated infographic style.

---

# Color Guidelines

## Recommended Color System
The background of the title area can be blue or other color,may be you can ask the user for the answer , to make the title stand out.
Use:

- One primary academic color.
- One secondary accent color.
- Neutral background.

Examples:

- Dark blue + light blue.
- Green + gray.
- Black + white + one highlight color.

Avoid:

- Multiple bright colors.
- Neon colors.
- Large gradient backgrounds.
- Excessive shadows.

Colors should support information hierarchy rather than decoration.

---

# Typography

## Font Principles

Use:

- Clear hierarchy.
- Large titles.
- Comfortable reading size.

Recommended hierarchy:

Title:

- Large.
- Short.
- Clear.

Main content:

- Short phrases.
- Keywords.
- Structured explanations.

Avoid:

- Full sentences copied from papers.
- Small unreadable text.
- Excessive bold text.

---

# Layout Guidelines

## One Slide One Message

Each slide should focus on one topic:

Examples:

Good:

"Why Existing RAG Safety Evaluation Fails"

Bad:

"Background + Related Work + Method + Results"

---

## Preferred Layout Types

### 1. Framework Explanation

Use:

- Paper framework figure.
- Pipeline diagram.
- Architecture illustration.

Layout:

```
Title

        Main Figure

Short explanation
```

---

### 2. Comparison Slide

Use:

- Tables.
- Comparison diagrams.

Example:

| Method   | Advantage | Limitation |
| -------- | --------- | ---------- |
| Method A | ...       | ...        |
| Method B | ...       | ...        |

Avoid dense paragraphs.

---

### 3. Experimental Result Slide

Priority:

1. Original paper result figure.
2. Simplified chart.
3. Key observation.

Always explain:

- What is measured?
- Why does it matter?
- What conclusion can be drawn?

---

# Image Usage Rules

## Principle

Academic PPTs should be:

> Figure-driven rather than text-driven.

---

## Preferred Image Sources

Priority order:

### Level 1: Original Paper Figures

Always prefer:

- Method framework diagrams.
- Model architecture.
- Algorithm pipeline.
- Dataset statistics.
- Experimental result figures.

The original figure should be directly extracted from the paper PDF whenever possible.

---

### Level 2: Modified Paper Figures

Allowed:

- Crop unnecessary regions.
- Highlight important components.
- Add annotations.

Do not:

- Change the meaning.
- Modify experimental results.
- Remove important information.

---

### Level 3: Self-created Diagrams

Only create new diagrams when:

- The paper explanation requires additional abstraction.
- The original figure is too complicated.

The generated diagram should faithfully represent the paper.

---

# Paper Figure Processing Rules

When using figures from papers:

1. Identify the purpose of the figure.
2. Crop the useful region.
3. Remove unnecessary labels.
4. Add explanation annotations.
5. Connect the figure to the speaking points.

Never place a figure without explanation.

---

# Avoid AI-generated PPT Characteristics

The final PPT should NOT contain:

- Every slide using identical layouts.
- Large empty title areas.
- Excessive bullet points.
- Generic icons.
- Decorative illustrations without meaning.
- Artificial marketing language.

Avoid phrases:

- "This innovative method revolutionizes..."
- "In today's rapidly developing AI era..."

Prefer:

- "Existing methods suffer from..."
- "The authors propose..."
- "Experimental results demonstrate..."

---

# Academic Storytelling Structure

A good paper presentation follows:

Problem:

Why does this research matter?


Gap:

What cannot be solved by existing methods?


Idea:

What is the proposed solution?


Evidence:

How do experiments verify effectiveness?



Discussion:

What are limitations and future directions?

---

# Final Quality Checklist

Before generating the final PPT:

## Content

- [ ] Research motivation is clear.
- [ ] Contributions are understandable.
- [ ] Method explanation is accurate.
- [ ] Experiments are correctly interpreted.

## Visual

- [ ] Figures are readable.
- [ ] Layout is balanced.
- [ ] Colors are consistent.
- [ ] Text density is acceptable.

## Presentation

- [ ] Each slide supports oral explanation.
- [ ] Audience can follow the research story.
- [ ] The PPT looks manually designed by a researcher.
