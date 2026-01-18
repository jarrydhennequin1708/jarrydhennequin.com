---
title: "Merchant Onboarding Platform"
client: "etika"
tags:
  - Product Design
  - Fintech
  - UX Strategy
year: "2021"
description: "Designed a comprehensive merchant onboarding platform for etika that streamlines the journey from application to first transaction. The six-phase process with automated ABN verification and progressive disclosure reduced onboarding time from weeks to days while maintaining regulatory compliance."
image: "/images/projects/etika-merchant/mer01.png"
order: 7
---

## Challenge

etika's growth depended on rapidly expanding its merchant network, but the existing onboarding process was a bottleneck. Paper-based applications, manual ABN verification, and fragmented systems meant merchants waited weeks before processing their first transaction.

The existing process had critical pain points:

1. Lengthy manual verification of business credentials taking 5-7 business days
2. Merchants abandoning applications mid-way due to unclear requirements and multiple sessions
3. Compliance burden requiring documents to be collected across emails, calls, and portal uploads
4. No visibility for merchants into application status, creating support ticket volume

The challenge was to design a self-service onboarding experience that balanced merchant convenience with regulatory requirements for KYC, ABN verification, and bank account validation.

![Image](/images/projects/etika-merchant/mer02.png)

## Approach

I led the end-to-end product design for the merchant onboarding platform, working closely with compliance, operations, and engineering teams:

**Discovery and regulatory mapping**

- Mapped ASIC requirements for payment facilitators and BNPL providers
- Defined KYC/AML verification flows compliant with AML/CTF Act requirements
- Integrated ABR lookup for real-time ABN validation and entity verification
- Created multi-store architecture supporting merchants with multiple trading brands

**Progressive disclosure design**

- Broke the onboarding into six logical phases with clear progress indicators
- Implemented save-and-resume functionality so merchants could complete at their own pace
- Designed two review checkpoints that gate access until verification is complete
- Created conditional flows based on business type and operating history

**Two-sided platform architecture**

- Merchant-facing portal with guided forms, document upload, and status tracking
- Internal dashboard for operations team to manage review queues and approvals
- Automated notification system keeping merchants informed at each milestone

![Image](/images/projects/etika-merchant/mer03.png)

![Image](/images/projects/etika-merchant/mer04.png)

## Solution

The platform enables efficient merchant onboarding through six core phases:

**Registration and business verification**
Self-service account creation with SMS verification, followed by ABN lookup that auto-populates business details from the Australian Business Register. Merchants confirm their entity details without manual data entry, reducing errors and speeding up validation.

**Trading store configuration**
Multi-store support allowing merchants to add multiple brands under one account. Each store captures ecommerce platform, industry category, sales volumes, and shipping information needed for risk assessment and integration planning.

**Verification and banking**
Secure bank account linking with statement upload and OCR extraction. Identity verification for business owners through document upload and liveness checks, ensuring KYC compliance while minimising friction.

**Integration and go-live**
Automated API credential generation and platform-specific integration guides. Test transaction verification confirms the connection works before going live, with dedicated support from the nominated technical contact.

![Image](/images/projects/etika-merchant/mer05.png)

![Image](/images/projects/etika-merchant/mer06.png)

![Image](/images/projects/etika-merchant/mer07.png)

![Image](/images/projects/etika-merchant/mer08.png)

![Image](/images/projects/etika-merchant/mer09.png)

![Image](/images/projects/etika-merchant/mer10.png)

![Image](/images/projects/etika-merchant/mer11.png)

![Image](/images/projects/etika-merchant/mer12.png)

## Outcomes

The project delivered measurable improvements to merchant acquisition:

- **70% application completion rate** up from 45% with the previous manual process
- **Average onboarding time under 15 minutes** for initial submission (phases 1-3)
- **48-hour initial review turnaround** reduced from 5-7 business days
- **First transaction within 7 days** of approval for 80% of merchants

The platform demonstrates how thoughtful information architecture and progressive disclosure can transform a complex compliance-heavy process into a streamlined self-service experience, accelerating merchant acquisition while maintaining regulatory rigour.
