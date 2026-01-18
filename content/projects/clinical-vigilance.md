---
title: "Clinical Vigilance AI"
client: "Telstra Health"
tags:
  - AI Strategy
  - Product Management
  - Healthcare
  - Innovation
year: "2025"
description: "Led a 12-week AI Innovation Sprint to design an AI-enhanced clinical handover system for aged care. The initiative helped a large healthcare organisation leverage its data moat to compete with nimbler competitors, resulting in $345K investment approval and 340% projected ROI."
image: "/images/projects/clinical-vigilance/cv02.png"
order: 0
---

## Challenge

Telstra Health, one of Australia's largest health technology providers, faced a critical competitive challenge. Despite having significant advantages—a substantial customer base, deep domain expertise, and millions of clinical records—the organisation was being outpaced by smaller, more agile healthtech startups shipping AI features in weeks while internal initiatives took quarters.

The organisation needed to prove it could innovate at startup pace without sacrificing the rigour healthcare demands. As Innovation Lead, I was tasked with:

1. Working across the entire product department to identify high-value AI use cases
2. Creating a prioritisation framework based on effort and impact
3. Taking 2 use cases through a rigorous 12-week AI Innovation Sprint
4. Delivering validated prototypes and business cases ready for investment decisions

![Image](/images/projects/clinical-vigilance/cv01.png)

## Approach

### Discovery and Prioritisation

I conducted workshops across all product teams to surface AI opportunities, generating 15+ potential use cases spanning clinical decision support, documentation automation, predictive analytics, and operational efficiency.

Using a two-dimensional prioritisation matrix assessing clinical value, commercial potential, technical feasibility, and regulatory considerations, **Clinical Vigilance** emerged as the highest-priority use case.

**Why Clinical Vigilance?**

Aged care facilities generate hundreds of progress notes daily across 50-150 residents. Nurses document extensively, but subtle deterioration patterns are buried within predominantly normal observations. The challenge: nursing staff can't identify early warning signs before they become acute clinical events.

This problem was severe (hair-on-fire), technically feasible with modern LLMs, and Telstra Health possessed a unique data advantage—millions of aged care progress notes that competitors couldn't access.

### Solution Design

Following the **AI Cake philosophy**, I designed Clinical Vigilance to be deeply integrated into existing workflows rather than bolted on as a separate tool:

- **Invisible Intelligence**: AI summaries appear at natural handover touchpoints—not in a separate dashboard
- **Problem-First**: Started with handover friction, not "what can LLMs do?"
- **Human-AI Collaboration**: AI surfaces concerns; clinicians make decisions
- **Source Traceability**: Every AI insight links back to original progress notes

### Agentic Development with Claude Code

To accelerate development and ensure rigorous evaluation, I used **Claude Code** to build an agentic workflow that automated key parts of the testing pipeline:

- **Synthetic Data Generator**: 200 resident profiles with embedded deterioration patterns
- **Summary Generation Pipeline**: Batch generation across severity categories
- **Evaluation Harness**: Structured framework for stakeholder scoring

### Four-Dimensional Evaluation Framework

I designed a comprehensive evaluation framework specifically for aged care clinical summaries:

1. **Clinical Accuracy & Completeness**: Factual correctness, critical information capture, AN-ACC documentation
2. **Usability for Handover**: Prioritisation, actionability, efficiency vs. raw notes
3. **Clarity & Readability**: Accessible language for ENs and care workers
4. **Person-Centred Language**: Dignified terminology per Dementia Australia Guidelines

![Image](/images/projects/clinical-vigilance/cv02.png)

## Solution

The redesigned Clinical Vigilance system features:

**Severity-First Hierarchy**

Prominent AMBER/GREEN/RED badges with trend indicators showing 7-day progression at a glance. Nurses can immediately identify residents requiring attention.

**7-Day Deterioration Timeline**

Visual pattern detection showing severity changes over time with annotated key events—falls risk progression, cardiac deterioration, infection indicators.

**Action-Oriented Structure**

Clear separation of "Actions Required" (medication review, pain management follow-up) from "Monitor Closely" items (bowel activity, wound care), each with source links and priority badges.

**Inline Source Attribution**

Every AI-generated insight includes numbered citations linking directly to original progress notes with timestamps, author attribution, and preview snippets—meeting stringent audit requirements.

**AI Confidence Transparency**

Footer showing confidence percentage, notes analysed, and time span—ensuring clinical staff understand the basis for AI recommendations.

![Image](/images/projects/clinical-vigilance/cv03.png)

## Outcomes

The Clinical Vigilance sprint delivered measurable impact:

**Business Results**

- **$345K proof-of-concept investment approved** by executive team
- **340% projected 3-year ROI** with 14-18 month payback period
- **3 pilot customers committed** before formal launch
- **First-mover advantage** in AI-enhanced aged care

**Validation Metrics**

- **94% clinical accuracy** (true positive rate for deterioration detection)
- **100% source attribution accuracy**
- **4.3/5 overall evaluation score** across four dimensions
- **89% of clinical staff** said they would use daily

**Organisational Transformation**

The sprint proved that Telstra Health's scale and data advantages could be unlocked without being hamstrung by organisational complexity. In 12 weeks, we accomplished what traditional processes would have taken 9-12 months:

- Evaluated 15+ use cases across all product teams
- Built and tested a functional AI prototype
- Validated with real customers
- Secured executive investment approval
- Established a repeatable framework for future initiatives

The sprint methodology I developed addressed the specific challenges of innovation within a large, process-oriented organisation—navigating siloed teams, risk-averse governance, and consensus-driven culture while maintaining clinical rigour and regulatory compliance.

This wasn't just a successful product initiative—it was proof that a large healthcare organisation could move at startup pace when it mattered.
