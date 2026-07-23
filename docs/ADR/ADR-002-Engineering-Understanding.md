# ADR-002: Engineering Understanding Is the Canonical Representation of Every Project

**Document ID:** AADR-002  
**Status:** Accepted  
**Date:** 23 July 2026  
**Decision Makers:** Atlas Foundation  
**Supersedes:** None

---

# Context

Engineering projects generate large amounts of information throughout their lifecycle.

This information exists in many forms, including:

- Drawings
- BIM models
- CAD geometry
- Documents
- Specifications
- Calculations
- Simulations
- Site observations
- Photographs
- Sensor data
- Engineering discussions
- Human experience

Traditional software treats these artifacts as the primary representation of a project.

However, these artifacts describe a project—they do not fully represent the engineering understanding of the project.

Atlas requires a canonical representation that captures not only information, but also meaning, relationships, intent, reasoning, confidence, and accumulated engineering knowledge.

---

# Decision

Atlas shall maintain **Engineering Understanding** as the canonical representation of every project.

Every model, drawing, document, simulation, regulation, observation, and engineering decision contributes to this continuously evolving Engineering Understanding.

Engineering Understanding is the authoritative representation of project knowledge within Atlas.

All other representations are inputs to, or views of, this understanding.

---

# Definition

Engineering Understanding is the continuously evolving engineering comprehension of a project maintained by Atlas.

It integrates information, relationships, reasoning, engineering knowledge, historical decisions, constraints, intent, and confidence into one shared understanding.

Engineering Understanding is not a file.

It is not a BIM model.

It is not a Digital Twin.

It is the engineering meaning derived from all available evidence.

---

# Components of Engineering Understanding

Engineering Understanding continuously integrates:

- Geometry
- Semantic Objects
- Engineering Relationships
- Project Context
- Design Intent
- Engineering Constraints
- Codes and Standards
- Engineering Rules
- Simulation Results
- Engineering Memory
- Decision History
- Engineering Knowledge
- Current Reasoning
- Explainability
- Confidence

These components evolve continuously throughout the project lifecycle.

---

# Sources of Understanding

Engineering Understanding may be improved through:

- Architectural models
- Structural models
- MEP models
- Drawings
- Site inspections
- Construction progress
- Engineering calculations
- Simulations
- Regulations
- Standards
- Human expertise
- User interaction
- Sensor data
- Future information sources

Every new piece of validated evidence contributes to Engineering Understanding.

---

# Architectural Consequences

This decision establishes the following architectural responsibilities.

The Hivemind maintains Engineering Understanding.

The Knowledge Graph structures Engineering Understanding.

Engineering Memory preserves Engineering Understanding.

Continuous Reasoning improves Engineering Understanding.

Semantic Objects contribute to Engineering Understanding.

Engineering Capabilities consume and enrich Engineering Understanding.

No subsystem owns the project independently.

All subsystems collaborate through Engineering Understanding.

---

# Engineering Understanding Lifecycle

Engineering Understanding continuously evolves.

```
Evidence
        ↓
Interpretation
        ↓
Engineering Understanding
        ↓
Reasoning
        ↓
Validation
        ↓
Updated Engineering Understanding
        ↓
Knowledge Preservation
        ↓
Future Engineering Understanding
```

Understanding is never considered complete.

It evolves as evidence, engineering knowledge, and project conditions change.

---

# Alternatives Considered

## BIM Model as the Source of Truth

Rejected.

BIM primarily represents geometry and metadata.

Engineering Understanding extends beyond representation to include reasoning, intent, knowledge, confidence, and context.

---

## Digital Twin as the Source of Truth

Rejected.

Digital Twins describe operational state.

Atlas requires a representation capable of preserving engineering reasoning, historical knowledge, design intent, and explainability throughout the project lifecycle.

---

## Document-Centric Representation

Rejected.

Engineering knowledge cannot remain fragmented across isolated documents.

Atlas requires one continuously evolving understanding.

---

# Rationale

Engineering decisions depend upon understanding rather than information alone.

Data becomes information.

Information becomes knowledge.

Knowledge becomes understanding.

Atlas exists to continuously improve engineering understanding rather than simply accumulate engineering information.

This architectural decision ensures that every capability within Atlas contributes toward one shared objective.

---

# Impact

Every future subsystem shall exist to improve Engineering Understanding.

Every recommendation shall emerge from Engineering Understanding.

Every learning process shall strengthen Engineering Understanding.

Every engineering decision shall be traceable to Engineering Understanding.

Engineering Understanding becomes the central abstraction of the Atlas Engineering Cognition System.

---

# Status

Accepted as a foundational architectural decision of the Atlas Engineering Cognition Model (AECM).

---

> **Engineering Understanding is not information. It is the continuously evolving comprehension of a project.**

— Atlas Architecture Decision Record 002