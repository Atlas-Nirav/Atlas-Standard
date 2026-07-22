# Atlas Principles

**Document ID:** APS-001  
**Version:** 0.1.0  
**Status:** Active  
**Last Updated:** 22 July 2026

---

# Purpose

These principles define how Atlas is engineered.

Unlike the Vision or Mission, these principles are actionable. Every architectural decision, feature, model, workflow, and engineering system should align with them.

If a proposed solution violates one or more of these principles, it should be reconsidered before implementation.

---

# 1. Truth Before Plausibility

Atlas prioritizes engineering correctness over convincing answers.

When sufficient evidence is unavailable, Atlas communicates uncertainty rather than making assumptions.

Correctness always takes precedence over confidence.

---

# 2. Understand Before Recommending

Atlas must understand the building before suggesting changes.

Recommendations should emerge from a comprehensive understanding of geometry, engineering relationships, project context, regulations, constraints, and intent.

Understanding precedes optimization.

---

# 3. Continuous Engineering Reasoning

Engineering reasoning is continuous.

Atlas evaluates engineering consequences as projects evolve instead of waiting for user prompts.

Reasoning is proactive by default.

---

# 4. Every Building Has One Intelligence

Buildings are complete engineering systems.

Architecture, structural engineering, MEP, construction, planning, operations, sustainability, and future disciplines contribute to one shared engineering intelligence.

No discipline should operate in isolation.

---

# 5. Every Object Is Semantic

Every engineering object carries meaning beyond its geometry.

A wall is not merely a surface.

It possesses purpose, material, structural role, relationships, history, constraints, and engineering intent.

Atlas preserves this meaning throughout the project's lifecycle.

---

# 6. Preserve Knowledge By Default

Engineering knowledge is never disposable.

Design decisions, revisions, assumptions, calculations, lessons learned, and reasoning should become reusable knowledge whenever possible.

Every completed project should strengthen future projects.

---

# 7. Explain Every Recommendation

Atlas should explain why a recommendation exists.

Recommendations should be transparent, traceable, and supported by engineering principles whenever possible.

Users should understand the reasoning, not just the outcome.

---

# 8. Human Expertise Remains Authoritative

Atlas supports engineering professionals.

Final responsibility for engineering decisions remains with qualified humans.

Atlas augments expertise rather than replacing it.

---

# 9. Engineering Before Automation

Automation exists to reduce repetitive work, not engineering judgment.

Automation should never bypass critical engineering reasoning.

Efficiency must never compromise correctness.

---

# 10. Learn Without Forgetting

Atlas continuously expands its engineering knowledge while preserving previously validated knowledge.

Learning should strengthen engineering intelligence without sacrificing reliability or consistency.

---

# 11. Technology Is Replaceable

Programming languages evolve.

Frameworks evolve.

Artificial Intelligence evolves.

Engineering principles endure.

Atlas should be designed so that technology can change without altering its core engineering intelligence.

---

# 12. Build For Generations

Every architectural decision should consider long-term maintainability.

Atlas is intended to evolve over decades.

Short-term convenience must never compromise long-term sustainability.

---

# Engineering Decision Test

Before implementing any feature, ask:

- Does it improve Atlas's understanding of the building?
- Does it preserve engineering knowledge?
- Does it strengthen continuous reasoning?
- Does it improve transparency?
- Does it respect human expertise?
- Will this decision still make sense ten years from now?

If the answer to any of these questions is "No", reconsider the design.

---

> **Good engineering solves today's problem.**
>
> **Great engineering becomes knowledge that solves tomorrow's problems.**

— Atlas Principles