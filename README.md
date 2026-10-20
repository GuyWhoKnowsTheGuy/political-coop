# Political Co-op

**Tech-first political infrastructure. Built to outlive its builders.**

## TL;DR

Political Co-op is a proposed tech-first, politically neutral political infrastructure cooperative. Its first project is an affordable **School Board Campaign OS**: reusable infrastructure for local school-board candidates. School-board campaigns provide a focused starting point for testing which tools and support actually help, rather than attempting an all-purpose political platform.

**[Try the working proof of concept](https://guywhoknowstheguy.github.io/school-board-campaign-os-demo/).** It is an early proof of concept, not the final architecture or a finished product. This repository is a concept and request for comments (RFC), not the production application.

The infrastructure must serve candidates on equal terms, regardless of party or affiliation. The intended model is a generous **90-day free trial**, followed by an affordable monthly subscription: prove value first, then use recurring revenue to sustain maintenance, support, and compensated work. No final price has been set, and there should be no artificial lock-in.

**Build once. Steward forever.** Preserve knowledge and capability across elections, rather than repeatedly starting over. Design succession from inception, including a minimum 20-year transition toward youth operation and control, so the institution does not depend permanently on its founders.

## The Problem

Local candidates can end up assembling websites, contact lists, volunteer workflows, calendars, and security practices from scratch. After an election, tools may be abandoned and operational knowledge lost. Not every campaign faces this problem, but it is the recurring waste Political Co-op intends to address.

A durable shared service could retain reusable software and lessons while keeping each campaign's private information separate. What is worth sharing—and what candidates would actually pay for—needs evidence, not assumptions.

## First Product: School Board Campaign OS

The concept is a coherent set of tools and documented workflows, not a commitment to build everything ourselves. Possible infrastructure includes:

- Candidate onboarding and a campaign website
- Petition and ballot-access workflows
- Volunteer management and public voter-data tooling
- Constituent/contact management and email/SMS integrations
- Campaign calendars and document management
- A cybersecurity baseline
- Research/knowledge systems and AI-assisted workflows
- Compliance-supportive workflows
- Institutional postmortems and knowledge retention

**This is a discussion list, not a settled feature specification.** The actual MVP should be determined collaboratively with candidates and builders. Existing open-source projects may be better foundations than new code. Compliance support is not a substitute for qualified advice; public data is not permission for unrestricted use.

## Business Model

**90-day free trial → affordable monthly subscription → recurring revenue → sustainable maintenance and support.**

The product should demonstrate real value before asking a candidate to pay:

> If a school-board candidate cannot identify enough value after 90 days to willingly pay an affordable monthly subscription, we have not earned the subscription.

Revenue should eventually cover hosting, maintenance, development, security, customer support, and compensated workers—not leave essential operations permanently dependent on volunteers. Portability and a usable exit path are requirements, not premium features. Pricing, service boundaries, and post-election subscription needs remain open. See [business model](docs/business-model.md).

## Political Neutrality

The infrastructure must be usable by Libertarians, Democrats, Republicans, independents, other third parties, and nonpartisan candidates on equal terms. It must not belong to or favor the Libertarian Party or any other political party.

The initial bootstrap community happens to include Libertarian technologists. That community does not own the political direction of the infrastructure. Neutrality and independence are architectural requirements: access rules, campaign-data separation, and governance must not quietly confer party advantage. Technical administration must not automatically confer political or governance authority.

## Sustainable by Design

Political Co-op is **CIO-first**: establish institutional information infrastructure at formation, rather than retrofit it later. Start with version-controlled documentation, open standards, auditability, access governance, cybersecurity, credential recovery, and documented workflows. Preserve institutional memory and succession instructions; avoid single-person knowledge dependencies.

Default to **GPLv3** for project software unless a practical reason for another license is documented. This repository uses [GPLv3](LICENSE). Prioritize inspectability, forkability, interoperability, portability, public documentation, and maintainability over unnecessary vendor dependence.

**Build once. Steward forever.** This does not mean software is literally written once. It will be patched, replaced, forked, and rewritten. What persists is institutional capability, accumulated knowledge, and stewardship—not a particular codebase. [Principles](PRINCIPLES.md) describe the intended constraints; the technical stack is not chosen.

## Youth Succession

Design for long-term youth inheritance through a progressive transition toward youth operation and control over a **minimum 20-year period**. Youth interns and contributors may join from the beginning, but their recruitment is not a launch prerequisite.

This is succession engineering: train replacements continuously, document systems, distribute operational knowledge, and make leadership handoffs normal. The goal is an institution that survives its creators. Age ranges, safeguards, responsibilities, and governance mechanics remain to be worked out. See [youth succession](docs/youth-succession.md).

## Funding Schools

A secondary business concept is to use **Forever Funding** as the merchant/payment processor. Through it, Political Co-op could nominate eligible schools or school-supporting nonprofits to receive a portion of merchant-processing economics.

The long-term policy concept: **every subscribed school-board campaign should result in some funding benefiting the school/community it seeks to serve, whether the candidate wins or loses.** This must remain politically neutral and structurally separate from election outcomes. Processor capabilities, eligibility, and implementation require appropriate legal/compliance review; no claim about permissibility or campaign-finance treatment is made here.

## Current Status

- Concept stage, with an existing proof of concept
- Bootstrap community beginning to form
- Architecture and MVP intentionally open for discussion
- No production application in this repository

The cooperative's legal form and detailed governance are not settled. [VISION.md](VISION.md) expands on the intended direction.

## RFC #1

> **What is the minimum School Board Campaign OS that would provide enough real value that a school-board candidate would voluntarily pay an affordable monthly subscription after using it free for 90 days?**

Read [RFC #1](rfcs/0001-minimum-viable-school-board-campaign-os.md). Disagreement is welcome. **Criticism of the architecture is useful.** Tell us what should be removed, reused, tested, or reconsidered—and why.

## How to Contribute

- [Open an Issue](https://github.com/GuyWhoKnowsTheGuy/political-coop/issues) with a concrete problem or suggestion.
- Participate in [Discussions](https://github.com/GuyWhoKnowsTheGuy/political-coop/discussions).
- Propose an RFC or challenge an assumption.
- Suggest existing open-source projects we should reuse rather than rebuild.
- Identify legal/compliance questions before they become implementation mistakes.
- Contribute code later, as implementation begins.

No committee application or elaborate process is needed. See [CONTRIBUTING.md](CONTRIBUTING.md) for a short starting guide.
