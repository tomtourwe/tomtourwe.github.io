---
title: "Problem statements that convince: from customer pain to AI solution"
layout: post
date: 2026-01-10
---

This article highlights aspects of problem statements that I find crucial for a convincing R&D proposal. A strong proposal starts with a concrete customer problem, not a technology looking for an application. From a my perspective as a reviewer, the critical questions are: what problem are you solving, why does it matter, and why is AI specifically the right tool to address it?

For a broader view of how evaluators judge AI and R&D proposals, see my [evaluation guide](/evaluation-guide).
.


---

### Describing a tangible customer problem

Vague problem statements are a very common weakness in proposals I review. This immediately makes me question whether the problem is real, measurable, and significant.

**Weak example:**
"Our customers struggle with inefficient processes and need better decision support".

**Strong example:**
"Manufacturing plants lose €50K-200K per unplanned downtime event. Our customers currently rely on preventive maintenance schedules, but 60% of breakdowns still occur unexpectedly. Maintenance teams waste time on unnecessary interventions while critical failures go undetected until production stops."

The difference is that strong problem statements are _specific_ and _explicit_. They typically include:
- Details that make the problem tangible and understandable, specific examples work best
- What the customer currently does to try to solve it, and why this doesn’t work satisfactorily
- Concrete consequences of the problem, e.g., costs, delays, or inefficiencies

Real customer quotes, incident data, or operational metrics make the problem tangible. If you can't quantify the pain or describe it in concrete operational terms, an expert can question whether the problem is substantial enough to warrant an R&D project.

### Explaining the problem is important

Beyond simply stating the problem, a strong proposal will also explain _why solving it is important_. Reviewers focus on questions such as 

- how many customers or target users experience the problem? Is it a niche issue or widespread?
- what is the business impact? E.g. revenue loss, cost increase, competitive disadvantage?
- Why hasn't this problem been solved yet? What makes it difficult?
- What happens if it remains unsolved?

**Weak example:** “Many customers experience equipment failures despite preventive maintenance. Existing solutions are insufficient, and we want to improve this situation.” 

**Strong example:** "Over 10 manufacturing plants at our customers experience unplanned equipment downtime. Production halts lead to significant revenue loss, increased operational costs, and dissatisfied customers. Predictive maintenance has not been adopted because the relevant data exists across different systems and has not been considered for this purpose; integrating, cleaning, and modeling it requires expertise that is currently not available."

The weak example is vague: it doesn’t quantify the impact, indicate how often failures occur, or explain why current methods fail. In contrast, the strong example clearly shows how many customers are affected, quantifies the impact, and explains why existing approaches fall short — naturally linking to the need for predictive modeling with AI. Providing these tangible details helps me, as a reviewer, understand why this is a problem worth solving.

### Connecting the problem to an AI solution

Even when the problem is real and significant, AI might not be _required_ to address it. AI is currently hyped, and simply stating that AI will be used to solve it problem is not sufficient to justify an R&D investment. You need to clearly explain why AI is necessary for this specific problem, and why more traditional approaches can not achieve the same results.

AI is required when the problem cannot be solved easily by humans. The patterns involved may be too complex, subtle, variable, or numerous to handle manually. AI can learn from large amounts of data, adapt as conditions change, and spot signals that simpler methods miss. For example, predicting unplanned equipment failures using sensor data could be possible with predictive modeling techniques, but would be nearly impossible with manual inspection alone. Similarly, finding the right information in a large customer service database can be solved with natural language understanding and retrieval, while conventional keyword search would miss context and nuance. These are examples of good AI mappings: clearly specifying the capability, the data used, and the output it produces. Importantly, the proposal should clearly and credibly show that you have access to the right data, in the right volumes, to make the AI solution possible.

Traditional approaches can fail for a specific problem because they rely on fixed rules, thresholds, or manually maintained logic. These methods cannot handle variation, scale, or subtle patterns, and the resulting solutions are usually fragile or incomplete. For example, in predictive maintenance, a rule-based system might trigger an alarm only when vibration or temperature crosses a fixed threshold. It would miss gradual changes or complex combinations of signals that indicate an impending failure. Similarly, a standard keyword search cannot retrieve the right documents in context. Fixed rules are rigid and brittle, while AI can learn from patterns across many sensors and adapt to evolving conditions.

Strong proposals specify:
- What AI capability is being used, e.g. prediction, language understanding, recommendation, ...
- What data feeds the AI system, and shows that it is available to the project partners in sufficient quantity and quality
- What specific techniques or approaches will be applied
- What outputs the AI produces

Weak statements like “we’ll use AI to optimize the process” or “machine learning will help us make better decisions” do not explain why AI is necessary and are unlikely to convince reviewers. Also, without evidence that the AI has sufficient data to work with, even a technically plausible approach appears speculative. By clearly contrasting what AI can achieve with what conventional methods cannot, and showing that you have the data needed to implement it, you demonstrate that AI is essential for solving the problem effectively.

## Key take-aways

Before submitting your proposal, ask yourself:

1. **Customer problem**: Can someone outside your domain understand the pain?
2. **Importance**: Is it clear why this problem is worth €100K+ in R&D investment?
3. **AI connection**: Is it clear why AI is required?
4. **Data readiness**: Is it motivated in a credible way that the partners have access to the right data, in sufficient quantity and quality, to make the AI solution feasible?

Proposals fail when they jump straight to "we'll use AI" without establishing why that's the right tool for this specific problem. The strongest proposals make evaluators think: "Of course, this proposal addresses a real problem, AI is the right tool, and they clearly have the data to make it work."
