---
title: Course Description Assessment
description: Quality assessment of the Evolution course description against the intelligent-textbook scoring rubric
---

# Course Description Assessment

**Course:** Evolution — Natural Selection and the Tree of Life  
**Assessed:** 2026-05-13  
**Skill version:** Course Description Analyzer v0.03

---

## Overall Score: 97 / 100

**Quality Rating: Excellent — Ready for learning graph generation**

---

## Detailed Scoring Breakdown

| Element | Points Possible | Points Earned | Notes |
|---|---|---|---|
| Title | 5 | 5 | Clear, descriptive, specific to scope |
| Target Audience | 5 | 5 | Grades 9–12, no prior biology required — explicit |
| Prerequisites | 5 | 5 | Explicitly stated as "None" with detail |
| Main Topics Covered | 10 | 10 | 13 rich, well-scoped topics covering full course arc |
| Topics Excluded | 5 | 5 | Clearly bounded: cell bio, Mendelian genetics, full ecology, anatomy |
| Learning Outcomes Header | 5 | 5 | "After completing this course, students will be able to:" present |
| Remember Level | 10 | 10 | 8 specific, actionable recall outcomes with concrete vocabulary |
| Understand Level | 10 | 10 | 10 specific outcomes using explain/describe/distinguish |
| Apply Level | 10 | 10 | 8 outcomes, many referencing MicroSim use explicitly |
| Analyze Level | 10 | 9 | 8 strong outcomes; one is slightly less measurable ("examine the tree of life") |
| Evaluate Level | 10 | 10 | 7 outcomes including misconception correction and ethical reasoning |
| Create Level | 10 | 10 | 7 outcomes including capstone project ideas and MicroSim design |
| Descriptive Context | 5 | 3 | Course overview is excellent; the "Why This Course Matters" section adds richness. Slight deduction: no explicit mention of estimated contact hours or pacing |

**Total: 97 / 100**

---

## Gap Analysis

### Minor Gaps (–3 points)

1. **No pacing or contact hours estimate** (–2): The course description does
   not indicate how many weeks, semesters, or class periods this course spans.
   Learning graph generation works best when the generator knows whether to
   target ~100 concepts (semester) or ~200 concepts (full year).
   *Recommended fix:* Add a line like "Designed for a one-semester (18-week)
   high school course meeting 5 days per week."

2. **One Analyze outcome is broad** (–1): "Examine the tree of life at
   multiple scales using the Tree of Life MicroSim and identify patterns in
   diversity, extinction, and adaptive radiation" — the verb "examine" is
   weaker than the rubric prefers. A stronger verb (e.g., "compare,"
   "contrast," "deconstruct") would make this outcome fully measurable.

---

## Improvement Suggestions

These are prioritized by impact on concept graph generation:

1. **Add a pacing note** to the Course Format section:
   > "Designed for a one-semester (18-week) high school course, 5 days/week,
   > approximately 90 contact hours."

2. **Strengthen one Analyze outcome** — change "Examine the tree of life..."
   to "Compare diversity, extinction rates, and adaptive radiation patterns
   across major clades using the Tree of Life MicroSim and identify which
   transitions correlate with mass extinction events."

3. **Optional enrichment**: Consider adding a brief note on assessment
   format (formative quizzes, midterm, capstone) to help the learning graph
   generator assign concept weights.

---

## Concept Generation Readiness

**Estimated concept yield from current description: 220–260 concepts**

| Source | Estimated Concepts |
|---|---|
| 13 main topics (avg. 12–15 concepts each) | 156–195 |
| 12 MicroSim types (avg. 3–5 unique concepts each) | 36–60 |
| Bloom's Taxonomy outcomes (novel concepts implied) | 20–30 |
| Cross-cutting themes (time, scale, evidence types) | 10–15 |
| **Total estimate** | **222–300** |

The course description is rich enough to support a full 200-concept learning
graph with room for the generator to choose the most pedagogically important
subset. The explicit MicroSim list is a particular strength: each simulation
implies a cluster of related concepts that students must understand to use it
meaningfully.

---

## Next Steps

- Score ≥ 85: **Ready to proceed with learning graph generation.**
- Run the `learning-graph-generator` skill to enumerate ~200 concepts, assign
  dependencies, and produce a concept taxonomy and quality report.
- Optionally address the two minor gaps above before running the generator
  for maximum concept yield.
