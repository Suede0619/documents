# Product Owner Charter

Rumi App - CPO/Product Owner Role Definition  
Last Updated: January 26, 2026

---

## Overview

Defines the Product Owner role, authority, and decision-making scope. Critical for controlling MVP iterations based on customer feedback. Per Ben Rewis (Jan 21, 2026): Formalize the product owner role — someone must control MVP iterations and make trade-off calls on feature/function loading.

---

## Role Definition

**Title:** Product Owner (CPO Function)  
**Current Assignment:** Yalor Mewn (COO serving as IPO)  
**Reports To:** John Wyrick (CEO)  
**Collaborates With:** Todd Bowden (CTO), Stuart Paul (CDO)  

**Status:** Yalor serves as interim Product Owner alongside COO duties. This dual-hat is appropriate at pre-seed (4-person team). Revisit when team exceeds 8 people or when operational duties consistently conflict with product decisions. A dedicated PO hire is a post-Series A consideration.

---

## Purpose

The Product Owner is the single point of accountability for:
- **What** gets built
- **In what order** it gets built
- **Based on** customer feedback and business priorities

This role prevents design-by-committee and ensures rapid, focused iteration.

---

## Decision-Making Authority

### Full Authority (No Approval Needed)

| Decision Type | Examples |
|---------------|----------|
| Feature prioritization | "Journey X ships before Journey Y" |
| Sprint scope | "We cut feature Z this sprint" |
| Bug priority | "This is P1, fix immediately" |
| UX trade-offs | "Simpler flow beats more options" |
| Beta group selection | "Add these 20 users to Group A" |
| Feedback triage | "This request goes to backlog" |
| Content scheduling | "This verse ships Monday, not Friday" |

### Requires CEO Consultation

| Decision Type | Examples | Response Time |
|---------------|----------|---------------|
| Major feature cuts | Removing announced features | 24-48 hours |
| Pricing changes | Any subscription price adjustments | 48 hours |
| Content tone | Anything affecting spiritual integrity | 24 hours |
| Platform priorities | iOS vs Android timing | 48 hours |
| Public commitments | Press, investor communications | 24 hours |

### Requires Team Consensus

| Decision Type | Examples | Process |
|---------------|----------|---------|
| Roadmap changes | Q3 vs Q4 feature moves | Tuesday Release Discussion |
| New content verticals | Adding Hafez, Shams timing | Founder Sync meeting |
| Major UX overhauls | Complete redesign of core flows | Founder Sync meeting |
| Hiring priorities | Which role to fill first | Founder Sync meeting |

---

## Key Responsibilities

### 1. Backlog Management

- Maintain prioritized product backlog in ClickUp
- Write clear user stories and acceptance criteria
- Ensure backlog is visible and understood by team
- Say "no" to requests that dilute core mission
- Groom backlog: keep 2 sprints of work defined and ready at all times

### 2. Customer Feedback Loop

- Review all beta feedback weekly (Friday testing + ongoing)
- Talk to users directly: **minimum 5 users per month** (calls, surveys, or in-depth interviews)
- Translate feedback into actionable backlog items
- Track feature requests and patterns in a feedback log
- Share monthly "Voice of Customer" summary with team

### 3. Sprint Planning

- Define sprint goals and scope (Tuesday Release Discussion)
- Make trade-off calls when capacity is limited
- Ensure Definition of Done is clear for each item
- Accept or reject completed work (Wednesday QA)
- Target: 80%+ sprint completion rate

### 4. Stakeholder Communication

- Communicate priorities to team at Tuesday meetings
- Report progress to CEO weekly (async or 1:1)
- Report to advisor (Ben) monthly
- Manage expectations on timelines — never over-promise
- Align marketing with product capabilities (no announcing features before they ship)

### 5. Metrics Ownership

- Define success metrics for each feature before development begins
- Track and report on product KPIs weekly (see metrics table below)
- Use data to inform prioritization decisions
- Run A/B tests when warranted (paywall placement, onboarding flow)
- Present metrics dashboard at monthly team review

---

## Product KPIs Owned by Product Owner

| Metric | Target | Frequency | Tool |
|--------|--------|-----------|------|
| Sprint completion rate | 80%+ | Weekly | ClickUp |
| Feature adoption rate (% of users using new feature within 7 days) | 30%+ | Per feature launch | Mixpanel |
| Daily Active Users (DAU) | Growing 5% WoW post-launch | Weekly | Mixpanel |
| Weekly Active Users (WAU) | Growing 5% WoW post-launch | Weekly | Mixpanel |
| Session length (avg) | 5-10 minutes | Weekly | Mixpanel |
| D1 / D7 / D30 retention | 40% / 20% / 10% (industry benchmark) | Monthly | Mixpanel |
| NPS (Net Promoter Score) | 40+ (good), 50+ (excellent) | Quarterly | Typeform |
| Time from feedback to fix (P1 bugs) | < 48 hours | Weekly | ClickUp |
| Backlog health (groomed items) | 2 sprints ahead | Weekly | ClickUp |
| Free-to-paid conversion rate | 0.5% at launch → 3% at scale | Monthly | App Store Connect + Mixpanel |
| Guided Journey completion rate | 70%+ | Monthly | Mixpanel |

---

## Relationship to Other Roles

### With CEO (John Wyrick)
- Product Owner proposes priorities; CEO has veto on spiritual integrity issues
- Weekly async update (Slack or ClickUp summary)
- CEO sets vision ("where we're going"); PO executes ("what we build this week")
- Escalation path: PO → CEO for content/tone questions

### With CTO (Todd Bowden)
- PO defines "what" and "why"; CTO defines "how" and "when"
- Joint ownership of sprint commitments — neither overrides the other
- CTO advises on technical feasibility before PO commits to scope
- PO respects technical debt needs (allocate ~20% of sprint capacity to tech debt)

### With CDO (Stuart Paul)
- Collaborative on UX decisions — design proposes, PO evaluates against priorities
- PO has final call on UX trade-offs when time is limited
- Design reviews happen before sprint commitment, not after development
- Joint ownership of user experience quality
- Marketing alignment: PO aligns product launches with marketing cadence

### With Advisor (Ben Rewis)
- PO presents product progress at monthly sessions
- Advisor provides strategic input on prioritization and category positioning
- PO incorporates advice as appropriate — advisor is consultative, not directive

---

## Escalation Process

| Level | Situation | Who Decides | Response Time |
|-------|-----------|-------------|---------------|
| Level 1 | Day-to-day product decisions | Product Owner | Immediate |
| Level 2 | Significant scope or direction changes | CEO consultation | 24-48 hours |
| Level 3 | Major strategic shifts or pivots | Full team discussion | Next Founder Sync |
| Level 4 | Deadlock between PO and another founder | CEO breaks tie | 48 hours |

---

## Anti-Patterns to Avoid

### Product Owner Should NOT:
- Make technical architecture decisions (CTO domain)
- Override spiritual/content tone (CEO domain)
- Ignore customer feedback for personal preferences
- Commit to dates without CTO input on feasibility
- Design UI/UX solutions (CDO domain — PO defines the problem, not the solution)
- Say yes to everything (the most important PO skill is saying "no")
- Skip sprint rituals when things get busy

### Product Owner SHOULD:
- Say "no" frequently and clearly — with rationale
- Prioritize ruthlessly based on mission + metrics
- Be customer-obsessed (5+ user conversations/month)
- Make fast decisions with incomplete data
- Change mind when evidence warrants — without ego
- Protect the team from scope creep and stakeholder overload
- Celebrate shipped work and team wins

---

## Tools and Processes

| Tool | Purpose | Cost | Status |
|------|---------|------|--------|
| **ClickUp** | Backlog management, sprint tracking, task assignment | ~$7/user/month (Business plan) | In use |
| **Mixpanel** | Product analytics, user behavior, retention, funnels | Free up to 20M events/month | Recommended — set up at launch |
| **TestFlight** | iOS beta distribution | Free (Apple) | In use |
| **Typeform** | User surveys, NPS tracking, feedback forms | Free tier (10 responses/month) or $25/month | Recommended |
| **Slack** | Team communication, async standups | Free tier | In use |
| **Loom** | Video walkthroughs, bug reports, demos | Free tier | Recommended |
| **Notion** or **ClickUp Docs** | Feedback log, Voice of Customer summaries, meeting notes | Included in ClickUp | In use |

**Why Mixpanel:** Best-in-class product analytics for mobile apps. Free tier is generous (20M events/month — more than enough through Series A). Alternative: Amplitude (similar, also free tier). PostHog is open-source if self-hosting is preferred.

**Why Typeform:** Clean, mobile-friendly surveys that match the app's contemplative aesthetic. Alternative: Google Forms (free, less polished) or in-app feedback via custom build.

---

## Charter Activation

This charter is effective upon team agreement and signature.

### Signatures

| Name | Role | Date |
|------|------|------|
| John Wyrick | CEO — Grants PO authority as defined | **[DATE]** |
| Yalor Mewn | Product Owner — Accepts responsibilities | **[DATE]** |
| Todd Bowden | CTO — Agrees to PO/CTO collaboration model | **[DATE]** |
| Stuart Paul | CDO — Agrees to PO/CDO collaboration model | **[DATE]** |

### Review Schedule
- **Quarterly:** Review charter effectiveness at Founder Sync
- **On trigger:** Review if PO role changes, team grows past 8, or product direction shifts significantly
- **Annual:** Full charter refresh

---

## Notes

- This charter formalizes what Ben Rewis identified as critical: clear product decision authority
- The PO role is not about having all the answers — it's about having the authority to decide quickly
- Speed of iteration is the pre-seed startup's primary competitive advantage
- A bad decision made quickly and corrected is better than no decision made slowly
