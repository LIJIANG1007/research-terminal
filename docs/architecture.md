# Research Terminal Architecture

> Build the world's most trustworthy AI research operating system.

---

# Vision

Research Terminal is an open AI research operating system.

Instead of merely answering questions, it helps people think like professional researchers.

The goal is not to generate more content.

The goal is to generate better thinking.

---

# Design Philosophy

Research Terminal follows several fundamental principles.

## Evidence First

Evidence comes before conclusions.

Research begins by collecting facts rather than defending opinions.

---

## Transparent Reasoning

Reasoning should be explicit whenever possible.

Users should understand why a conclusion was reached.

---

## Uncertainty Awareness

Not every question has a certain answer.

Research Terminal expresses confidence and uncertainty honestly.

---

## Continuous Learning

New evidence should continuously improve previous conclusions.

No conclusion is permanent.

---

# System Architecture

Research Terminal consists of four layers.

```
                User
                  │
                  ▼
         Research Terminal
                  │
      ┌───────────┼───────────┐
      ▼           ▼           ▼
 Methodology    Skills    Connectors
                  │
                  ▼
               Agents
```

Each layer has a single responsibility.

---

# Components

## Methodology

Defines how AI should think.

Examples:

- Research First Principles
- RTM
- Bayesian Updating

---

## Skills

Perform individual research tasks.

Examples:

- Company Analysis
- Macro Research
- News Analysis
- Portfolio Review

---

## Connectors

Provide reliable external information.

Examples:

- AkShare
- SEC EDGAR
- Yahoo Finance
- FRED
- Financial News APIs

---

## Agents

Coordinate multiple skills to complete complex research workflows.

Agents should focus on orchestration rather than individual reasoning.

---

# Research Workflow

Every research task should generally follow this sequence.

1. Define the question

2. Collect evidence

3. Identify missing information

4. Generate multiple hypotheses

5. Evaluate supporting evidence

6. Evaluate contradictory evidence

7. Estimate probabilities

8. Produce the current best conclusion

9. Describe remaining uncertainty

10. Recommend future research

---

# Long-Term Goal

Research Terminal aims to become an extensible AI research platform where new methodologies, skills, connectors, and agents can be added independently while sharing a common research philosophy.
