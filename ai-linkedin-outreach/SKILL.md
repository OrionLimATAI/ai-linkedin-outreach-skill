---
name: ai-linkedin-outreach
description: Build responsible AI-assisted B2B LinkedIn outreach workflows, including ICP definition, lead sourcing, prospect research, personalization, connection messages, follow-up sequences, conversation tracking, reply handling, and scale controls. Use when planning or reviewing LinkedIn outbound, cold outreach, Apify-style lead sourcing, AI sales development workflows, Claude Cowork-inspired outreach systems, or prospecting playbooks.
---

# AI LinkedIn Outreach

Use this skill to design responsible B2B LinkedIn outreach workflows that combine AI assistance with human judgment. The goal is relevant, researched, low-pressure outreach, not spam automation.

This skill is inspired by the public Claude Cowork outreach workflow from Oleg's free resource. Do not copy the source text verbatim; use the process as a reference and produce original, user-specific playbooks and messages.

## Source Handling

Read `references/source-notes.md` when attribution or source context is needed. Keep all public outputs original and include the source link when explaining where the workflow inspiration came from.

## Operating Principles

- Optimize for relevance, credibility, and consent.
- Treat AI as a research and drafting assistant, not an unchecked sender.
- Keep outreach specific to the recipient's role, company, trigger, and likely pain.
- Use platform automation carefully and respect LinkedIn rules, privacy rules, and local regulations.
- Do not invent prospect facts, customer proof, metrics, mutual connections, or personalization details.
- Prefer smaller, higher-quality batches over high-volume sending.

## Required Inputs

- Offer, product, or service
- Target market, geography, and industry
- Ideal customer profile and disqualifiers
- Buyer personas and buying triggers
- Proof points, case studies, or allowed claims
- Lead source or prospect list
- Sender profile and positioning
- Outreach limits, review requirements, and compliance constraints

If any input is missing, use explicit placeholders and name what must be confirmed before sending.

## Workflow

1. Define the outreach strategy.
   - Clarify ICP, persona, pain, trigger, offer, proof, CTA, and exclusions.
   - State why this buyer would care now.
   - Define what a good reply, bad-fit reply, and handoff-ready reply look like.

2. Prepare the sender profile.
   - Make the profile credible for the target audience.
   - Align headline, about section, featured content, and recent activity with the outreach theme.
   - Do not overstate role, authority, partnerships, or customer relationships.

3. Build the lead list.
   - Use a narrow source query, clear filters, and disqualifiers.
   - When using lead-sourcing tools, capture source URL, role, company, location, relevance signal, and confidence.
   - Remove competitors, students, vendors, recruiters, irrelevant regions, and low-confidence records.

4. Research each prospect.
   - Use public professional signals only.
   - Identify role relevance, company context, trigger, likely business problem, and message angle.
   - Mark uncertain details as uncertain rather than turning them into claims.

5. Draft the connection message.
   - Keep it short, specific, and non-pushy.
   - Use one personalization angle.
   - Avoid fake familiarity, exaggerated praise, and long product pitches.
   - Use a soft CTA such as asking whether the topic is relevant.

6. Draft the follow-up sequence.
   - Use 2-4 follow-ups maximum unless the user explicitly asks otherwise.
   - Each follow-up should add a new reason to care, proof point, resource, or question.
   - Stop after disinterest, no-fit signals, or opt-out.

7. Run a human-reviewed outreach pass.
   - Review every message before sending when the target list is new.
   - Check personalization, claim safety, CTA, tone, and relevance.
   - Track sent date, message variant, prospect status, reply status, and next step.

8. Scale with controls.
   - Scale only after positive reply quality is proven.
   - Keep daily volume conservative and consistent with platform rules.
   - Rotate angles based on relevance, not to bypass limits.
   - Monitor acceptance rate, reply rate, positive reply rate, meeting conversion, and negative feedback.

9. Manage conversations.
   - Classify replies as interested, curious, not now, wrong person, objection, no fit, or opt-out.
   - Suggest concise responses that answer the actual reply.
   - Hand off sales-ready conversations with context, pain, trigger, offer angle, and recommended next step.

## Output Contracts

### Outreach Strategy

Return:

- ICP and exclusions
- Persona and trigger
- Pain hypothesis
- Offer angle
- Proof points and claim risk
- Lead sourcing plan
- Personalization fields
- Message rules
- Follow-up cadence
- Success metrics
- Safety and compliance notes

### Lead List Review

Return:

- Fit score
- Reason for fit
- Personalization angle
- Missing data
- Risk flags
- Suggested segment
- Recommended message angle

### Message Pack

Return:

- Connection request
- Follow-up 1
- Follow-up 2
- Optional final follow-up
- Reply handling snippets for common responses
- Notes explaining personalization and claim safety

### Conversation Handoff

Return:

- Prospect and company
- What they replied
- Likely intent
- Recommended response
- Sales handoff summary
- Next step and owner

## Message Style

- Use plain, professional language.
- Keep connection notes short.
- Mention only one clear relevance reason.
- Use concrete business language instead of vague "AI transformation" claims.
- Avoid pressure, guilt, exaggerated urgency, or manipulative scarcity.
- Do not make the first message a full pitch.

## Quality Checklist

Before finalizing, check:

1. The target persona is narrow enough.
2. The personalization fact is public, accurate, and relevant.
3. The message does not invent familiarity or proof.
4. The CTA is easy to answer.
5. The follow-up cadence is respectful.
6. Opt-out and disinterest are respected.
7. Metrics and claims are verified or marked as placeholders.
8. Scaling advice does not encourage spam or platform abuse.
