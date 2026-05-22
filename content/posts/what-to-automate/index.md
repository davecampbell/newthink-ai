---
title: "What to Automate — and What to Leave Alone"
date: 2026-05-21
draft: false
description: "The most useful thing an AI consultant can tell you isn't what to automate. It's what not to. Here's the framework for making that call."
tags: [strategy, ai-thinking]
image: ""
---

There's a version of AI consulting that tries to put AI in everything. That's not how good deployments work — and it's not what builds trust with the teams who have to live with the results.

The most useful thing we can tell a client is sometimes: *don't automate that.*

Here's the framework we use to make the call.

## Three Types of Workflows

Every workflow your organization runs falls into one of three categories. The category determines whether the right answer is an AI agent, conventional automation, or keeping humans in the loop.

### Put an Agent In

The right candidate for an AI agent is a workflow that can be **distilled into rules** — there's a consistent logic to how it should be handled — but the **inputs are variable in format or content**. 

Examples: customer inquiries that always need to be categorized and routed, but arrive as emails, PDFs, voicemails, and web forms. Documents that need to be reviewed for specific clauses, but come in different formats from different counterparties. Support tickets that need to be triaged and assigned, but are written by different people with different levels of clarity.

The agent handles the inconsistency in format while applying the consistent logic. It calls tools — a CRM, a ticketing system, a database — to take action. One call to the language model as an orchestrating layer is usually all you need. More AI than that typically increases cost and decreases reliability without improving the output.

### Use Code Instead

If both the rules *and* the inputs are predictable, you don't need AI. Conventional code is faster, cheaper, more reliable, and easier to audit.

A payroll calculation doesn't need a language model. Neither does a nightly database export, a report that always pulls the same fields, or a form that routes to the same destination based on a dropdown value.

A lot of what gets pitched as "AI automation" is actually just automation. Know the difference before you build.

### Leave It Human

Some workflows require pattern recognition that comes from years of domain expertise, judgment calls that depend on organizational context, or decisions with enough consequence that a human needs to own the outcome. Those stay human.

This isn't a failure of AI. It's correct system design. An AI system that makes decisions it shouldn't be making erodes trust in the entire deployment. The goal is ROI — and ROI requires getting the boundaries right.

## Why This Matters More Than It Seems

Most organizations come to an AI engagement hoping to hear that AI can solve everything. The most valuable thing we can do early is be honest about where it can't.

When we tell a client "this workflow should stay manual" — and explain why — it builds more trust than a pitch that promises automation across the board. The client's team knows their operation. When our assessment matches what they've quietly suspected, it signals that we're actually paying attention, not just selling.

That trust is what makes the deployments that *do* get built actually stick.

## The Volume Question

One more filter that matters: frequency. A workflow that runs five times a month is a bad candidate for AI investment regardless of how well it fits the technical criteria. Look for the high-volume, repeated processes where efficiency gains compound.

A ten-percent improvement on a workflow that runs a thousand times a week is transformational. The same improvement on something that runs twice a month is a rounding error.

---

*Figuring out what to automate — and what to leave alone — is the first thing we do in every engagement. It's also the part that requires being in the room with the teams who do the work. [Let's talk about your operation.](/contact)*
