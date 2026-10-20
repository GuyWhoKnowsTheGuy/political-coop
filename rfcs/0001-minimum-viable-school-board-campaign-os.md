# RFC #1: Minimum Viable School Board Campaign OS

Status: Open for discussion; not an approved feature specification.

## The question

> **What is the minimum School Board Campaign OS that would provide enough real value that a school-board candidate would voluntarily pay an affordable monthly subscription after using it free for 90 days?**

Disagreement is welcome. Criticism of the architecture is useful, including arguments that a proposed component should not exist.

## Context

Political Co-op proposes durable, politically neutral campaign infrastructure, starting with school-board candidates. The [early working proof of concept](https://guywhoknowstheguy.github.io/school-board-campaign-os-demo/) illustrates possibilities; it is neither the finished product nor a required production architecture.

Some local campaigns repeatedly assemble tools and lose useful operational knowledge afterward. We need to learn where this is a meaningful problem, which existing products already solve it, and where a maintained service could earn a subscription.

## Constraints

- Serve candidates on equal terms across parties and affiliations.
- Prove value during a 90-day free trial; do not invent a final price yet.
- Plan for affordable subscriptions that can support operations and compensated work.
- Provide portability and avoid artificial lock-in.
- Default project software to GPLv3, with documented practical exceptions.
- Include security, recovery, campaign-data separation, and maintainability in scope decisions.
- Document workflows so the service can outlive its initial operators.

## Questions worth answering

1. Which candidate and campaign stage should an initial pilot serve? What real workflow is currently painful?
2. What is the smallest end-to-end improvement a candidate could experience during 90 days?
3. What evidence would distinguish genuine value from a polished demo? Consider candidate interviews, observed tasks, repeat use, and willingness to pay—not just signups.
4. Which existing open-source projects or services should we integrate? What are their license, maintenance, portability, and support implications?
5. What should be explicitly excluded from the MVP?
6. Which jurisdiction-specific ballot-access, data-use, communications, and campaign-finance questions require qualified review before a pilot?
7. What would hosting, integrations, security, and human support cost? What happens between election cycles?
8. Can another operator recover and maintain the service using the documentation alone?

The [README's possible capabilities](../README.md#first-product-school-board-campaign-os) are prompts, not a backlog. A website plus one dependable workflow might beat a broad suite; evidence should decide.

## A lightweight response

Describe a candidate problem, the smallest useful workflow, tools we could reuse, evidence to collect, major risks, and what not to build. A short Issue or Discussion is enough; a pull request is welcome but not required.

## How this RFC can progress

Compare proposals openly, gather candidate feedback, and narrow the scope to a testable pilot. Record the chosen tradeoffs and unresolved risks before implementation. No architecture, feature bundle, price, or acceptance threshold is approved by this RFC.

The school-funding/payment concept and detailed succession governance should not substitute for establishing core product value. Both remain separate design work described in the supporting documents.
