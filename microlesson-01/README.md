<h1>
  <span class="headline">[tktk Headline]</span>
  <span class="subhead">tktk Microlesson 01</span>
</h1>

**Learning objective:** By the end of this lesson, students will be able to tktk

## Foundations: AI Multi-Task Sequencing  
### Microlesson 1: From Vague to Clear—Refining PRDs and Tickets for AI

Welcome! In this lesson, you’ll learn how to turn a vague or incomplete PRD (Product Requirement Document) into a set of clear, AI-ready prompts and requirements.

---

## Why clarity matters for AI

> 💡 Large Language Models (LLMs) do best with clear, specific instructions.  
> Vague or underspecified PRDs can lead to code or analysis that’s off the mark.

A strong first step is surfacing what's missing and making every expectation explicit—just like you would if you were prepping a junior engineer (or an AI) to work on a project.

---

## Activity: Spot the gaps in a real PRD

**Work in pairs or small groups. Read the PRD below and highlight:**
- Anything that’s missing, ambiguous, or open to interpretation
- Any terms, metrics, or business rules that aren’t precisely defined
- Any “assumed” knowledge or steps that would confuse an AI assistant

[**Ambiguous PRD**](./assets/PRD.md)

---

## Brainstorm clarifying questions

Now, draft a list of clarifying questions you’d need answered before an AI (or junior dev) could deliver high-quality code or analysis.

Examples:
- How do you define “churn” for this project?
- Should retention be calculated by week, month, or quarter?
- What filters or segments should be available in the dashboard?
- How often does the dashboard need to update?

> 🧠 The best AI results come when you *ask for* what you actually need.

---

## Refactor for LLM-readiness

Rewrite key sections of the PRD, or write a short list of requirements, as if you were going to prompt an LLM to help you build this dashboard.

- Be specific about definitions, filters, calculations, outputs, and data sources.
- State any assumptions or edge cases that need to be handled.

Example:
- “Calculate churn as the percentage of paying customers who cancel in a given month.”
- “Visualize retention curves for new users, by product and region, updated weekly.”

---

## Share and discuss

- Share your top 2–3 clarifying questions or improved requirements with the class.
- What was the biggest source of ambiguity?
- How would missing details trip up an AI (or even a junior developer)?

---

**Next up:**  
You’ll learn how to turn your clarified requirements into a multi-step sequence of prompts that gets you from ticket to working code or analysis.
