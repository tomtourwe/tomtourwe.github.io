---
title: "What experts look for in a strong R&D proposal"
permalink: "/evaluation-guide/"
layout: post
---

This article provides an overview of the topics I evaluate critically in an R&D proposal as a reviewer. It explains at a high level why each topic is important and links to other articles that provide more details. Each of these detailed articles focuses on specific questions I typically ask, the patterns that raise concerns, and what distinguishes proposals that get funded from those that don't.

By understanding these topics, why they are imporant, and the questions they trigger, you can better anticipate feedback and significantly improve the quality and credibility of your proposal.




---
## Problem definition: what customer problem are you solving, and does it need AI?

Strong proposals start with a concrete customer problem, not with a technology looking for an application. As an expert, I want to understand three things clearly:

**First, what is the actual problem?** Vague statements about "inefficient processes" or "need for better decision support" don't work. Strong problem definitions describe specific operational pain: what goes wrong, how often, what does it cost, what customers currently do about it, and why their current approach falls short. Customer quotes, concrete data, or operational metrics make the problem very tangible.

**Second, why does this problem matter?** Beyond describing the problem, you must prove significance. How many customers experience this problem? What is the impact on their business? Why hasn't it been solved already? What happens if it remains unsolved? The goal is to help me understand this problem is worth the investment.

**Third, why is AI the right tool for this problem?** It’s not enough to say AI is involved — you need to show that the problem fundamentally _requires_ AI. This means explicitly linking the customer problem to what AI is uniquely good at: prediction, classification, recommendation, language understanding, vision, planning, etc. Strong explanations make this link concrete, for example: “Unplanned equipment downtime → time-series prediction on sensor data to detect a known failure 24–48 hours in advance.” Weak explanations stay abstract: “AI will predict failures.” The goal is for me to immediately recognize that the problem maps cleanly to a known AI technique, and why non-AI approaches are not sufficient, for example because fixed rules or manual analysis can not capture the important but subtle patterns. 

**In-depth article →** [Problem statements that convince](/2026-01-10-problem-statements-that-convince)

---

## Business Case: what does this mean commercially?

A strong proposal does not only provide a convincing problem definition and strong technical expertise, but also needs a credible business case. VLAIO especially asks for this. 

A common weakness in many proposals is that numbers are presented without any motivation or justification. 

**Start with your envisioned business model.** How will customers pay for your solution? SaaS subscription? Perpetual license? Usage-based pricing? Be specific, because the model affects everything: customer acquisition costs, revenue predictability, support requirements.

**Justify your pricing.** Don't just state prices — explain why those specific numbers. Strong justifications anchor pricing in customer value delivered, competitive positioning, or established domain norms. If you're charging €1000/month, I want to know why not €500 or €2000.

**Build projections bottom-up, not top-down.** Weak proposals start with total addressable market figures: "The global market is €12B, we'll capture 1%." Citing reports from McKinsey or Gartner about massive markets doesn't convince me — these describe theoretical market size, not your realistic path to customers.

Strong proposals start with customers you can actually reach. Year 1: three beta customers from your existing network with confirmed interest. Year 2: expansion based on specific sales capacity and realistic conversion rates. Year 3: geographic expansion with clear justification for growth rates.

Every number should trace back to concrete actions: how many salespeople, their realistic capacity, market penetration constraints, sales cycle length. Growth rates should decrease over time as you saturate accessible markets—this shows you understand real business dynamics.

When I ask questions your numbers, you should have clear answers, not market research about billion-dollar opportunities.

**In-depth article →** [Building a credible business case -- Coming soon]()

---

## Technical Expertise: can you execute this?

One of the most common weaknesses in AI-related proposals is overstating the team's AI capability. When evaluating proposals, I look for evidence that people working on AI technology genuinely understand how these systems work, not just how to use them. For AI-related projects, this is particularly relevant because the gap between _using AI_ and _understanding AI_ is enormous.

Many proposals list team members as "AI engineers" or claim that "full stack engineers" will handle AI development. This immediately raises concerns. AI development — especially in innovation projects — requires people who understand how these systems work internally, not just how to use existing frameworks.

The problem is straightforward: if your project is really innovative, you should be working beyond what existing tools readily provide. When models don't perform as expected (and in R&D, this happens regularly), you need people who can diagnose whether the issue is with the data, the model architecture, the training approach, or the fundamental problem formulation. This requires understanding what's happening under the hood.

I'm typically looking for concrete evidence of AI capability: specific projects where team members have worked with particular techniques, formal training in machine learning or related fields, and demonstrated ability to go beyond applying standard tools. Generic statements like "experience with AI" or lists of popular frameworks aren't convincing at all. 

The proposals that succeed show credible technical depth through specificity: naming the actual techniques used in past work, describing concrete outcomes, and demonstrating understanding of how different AI approaches work and when they apply.

**In-depth article →** [Credible AI expertise in proposals -- Coming soon]()

---

## Choosing the Right Partners

Project success often depends on partnerships — with AI specialists, technology providers, research institutions, or consultants. I pay close attention to how these partnerships are structured and whether they make sense for your project.

For AI-heavy projects specifically, partner selection reveals a lot about whether you understand what you're building. Generic AI consulting firms that claim expertise in everything are less convincing than specialized partners with demonstrated experience in your specific domain— vision, NLP, recommendation systems, planning, or whatever your project actually requires.

Beyond partner selection, proposals must show realistic effort distribution. Projects where 80-90% of work is outsourced to partners while your team has minimal involvement raise immediate concerns. Even when deep expertise comes from partners, strong proposals show substantial internal contribution: defining requirements, providing domain knowledge, integrating results, and building internal capability.

The partnership structure should also address long-term sustainability. What happens after the project ends? Do you have plans to hire or develop similar expertise internally? Can you maintain and extend the solution? Proposals that create permanent dependency on external partners are weaker than those with clear paths to internal capability.

**In-depth article →** [Working with an AI Partner](/2025-12-27-working-with-an-AI-partner/)

---

## Working with Proposal Writers

Many organizations work with external consultants to help structure and write their proposals. This can be valuable, but I can often tell when a proposal has been written by someone who doesn't deeply understand the technology or domain.

The fundamental issue is that even experienced proposal writers cannot create content you don't have. They can help with structure, language, and alignment with funding criteria — but the substance must come from you. Your domain expertise, technical understanding, market insights, and business vision form the foundation.

Strong proposals result from real collaboration where roles are clear: you provide the deep knowledge of what you're building, why you're building in and how you will do so, while the writer helps translate that into a coherent, well-structured document that meets evaluation criteria.

When selecting a proposal writer, look beyond general funding experience. For AI-driven projects especially, writers with relevant technical depth — understanding what different AI techniques can and cannot do, what constitutes genuine innovation versus standard application — produce stronger proposals because they can help identify and articulate real technical challenges.

Generic proposal writers often produce impressive-sounding but technically hollow proposals. They list popular techniques without understanding which approaches actually make sense for the problem, or why certain methods are needed. I easily recognize this pattern.

**In-depth article →** [Working with a Proposal Writer](/2025-12-31-working-with-a-proposal-writer/)

---

## Using This Guide

Before finalizing your proposal, review each area above and ask:

**Problem definition:**
- Can someone outside your domain understand the customer pain?
- Can you map your problem to a specific AI capability with technical detail?

**Business case:**
- Can you defend every number with concrete actions and realistic constraints?
- Are you building bottom-up from reachable customers, not top-down from TAM?

**Technical expertise:**
- Can you point to specific relevant experience for each person on the core team?
- Do you have concrete evidence of capability, not just generic claims?

**Partners:**
- Do partners have demonstrated expertise in your specific domain?
- Is effort distribution realistic, with substantial internal involvement?

**Proposal development:**
- Are you bringing genuine substance, or expecting a writer to create it?
- Does your writer understand the technology well enough to help articulate real challenges?

The difference between funded and rejected proposals often isn't the underlying idea — it's how credibly and specifically that idea is presented. Strong proposals demonstrate understanding through concrete detail, realistic planning, and honest acknowledgment of challenges. They make me as an expert confident you know what you're doing.

This confidence comes from substance, not from claims. It comes from showing you've thought through the hard questions, understand the real challenges, and have specific, defensible answers.
