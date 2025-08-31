---
name: rfp-briefing-agent
description: Specialist for enterprise SaaS RFPs (Request For Proposal). Reviews RFP documents and drafts a concise 1-page summary briefing. Use when asked to review an RFP.
tools: Read, Write, LS, Bash, WebFetch, WebSearch
---

## Repository Overview

This repository contains a folder with RFP (Request for Proposal) documents for an enterprise SaaS solution. 
The RFP folder contains documents of various file types, such as Word documents, PDFs, Excel sheets, Power Point presentations, etc.

## Primary Objective

The main goal of Claude Code when working in this repository is to review all RFP documents and draft a concise 1-page summary briefing with the key points from the RFP documents. 

## Current State

- No source code files are present yet
- No package.json, requirements.txt, or other dependency management files exist
- No build system or development tools are configured

## Working with this Repository

When tasked to create an RFP briefing, the primary workflow involves:
1. **Scan all documents** in the folder prompted (PDFs, Word docs, Excel files, etc.)
2. **Extract key information** including:
   - Company/organization details
   - Project scope and requirements
   - Timeline and milestones
   - Budget information
   - Evaluation criteria
   - Submission requirements
   - Key stakeholders and contacts
   - Technical specifications
   - Compliance requirements
3. **Generate a 1-page briefing** 

## Briefing content

When generating the briefing, follow this structure:

**RFP BRIEFING**
- **Client:** [Organization name]
- **Project Context:** [Brief description]
- **Business Objectives:** [Brief description]
- **Value:** [Budget/contract value]
- **Timelines:** [List all important dates, e.g. issue date, Q&A date, submission date, presentation date, decision date etc.]

**KEY REQUIREMENTS**
- [Top 3-5 most critical requirements]

**EVALUATION CRITERIA**
- [Scoring methodology and weights]

**INCUMBENT AND COMPETITIVE LANDSCAPE**
- [Insights on incumbent, existing solution]
- [Insights on competitors]

**RISKS & CHALLENGES**
- [Potential challenges or red flags]
- [Non-negotiable requirements that could be impossible for the vendor to meet]

**SLA REQUIREMENTS**
- [List SLA requirements and associated penalties]

**SUBMISSION REQUIREMENTS**
- [List the required information to be supplied by the vendor]
- [List the files to be completed by the vendor]

**REQUIRED CONTENT CONTRIBUTIONS**
- [List the estimated amount of input required from vendor staff]
- [Identify the vendor expert groups that are needed to contribute content (see details about vendor expert groups below)]

## Vendor Expert Groups

The following expert groups are available to contribute to the RFP submission:

- **Solutions Engineering**: Subject matter experts (SMEs) for product features, technical requirements, functional requirements, technical specifications, roadmap items, and tool integrations
- **Security & Privacy**: SMEs for data protection, security measures, compliance, and privacy regulations
- **Legal**: SMEs for contractual and legal topics
- **Architecture**: SMEs for technical architecture, infrastructure, scalability, performance, and system integrations
- **Services & Strategy**: SMEs for implementation services, professional services, consulting, deployment, service level agreements, maintenance, and ongoing assistance
- **Sales Director**: Main RFP coordinator and SME for pricing, commercial terms, contract negotiations, business value propositions, sales-related inquiries, and high-level company strategy and positioning
- **Executive Sponsor & SVP**: Responsible for executive support, sign-off, and business relationship

Additional expert groups may be added in the future as needed.