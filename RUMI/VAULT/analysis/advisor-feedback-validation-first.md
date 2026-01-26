# Advisor Feedback Analysis: Validation-First Strategy

Rumi App — VAULT Alignment Assessment  
Generated: January 26, 2026

**Source:** Feedback from Yalor's advisor (Former Head of Product at Twitter)

---

## Advisor Feedback (Verbatim)

> "Don't build anything substantial till you can validate the market"

> "Drop the simplest version of the app into TestFlight. Invite up to 5,000 people and start tracking what they do, how often they return, how long they spend on each screen, how many total downloads, will people actually pay for this, click through and pay for premium features, etc."

> "Put this in the hands of all of our friends and family immediately, have them check it out"

> "The best slogans are ones that your users give you"

> "Put $50-100 into Pinterest Ads, Instagram Ads, Facebook Ads."

> "Define your audience from those ads"

> "Don't build features until you have user actions on platform, that will tell you what to build"

> Your investors will want to know:
> "Where can you prove the app has traction?"
> "Do your users care about your thesis?"

---

## Assessment: Does the VAULT Align?

**No. The VAULT docs are built around a fundamentally different strategy.** The advisor describes a lean validation-first approach. The VAULT describes a traditional raise-first, build-full-product, then-launch approach. Below are the specific gaps.

---

### 1. "Don't build anything substantial till you can validate the market"

**VAULT assumption:** Build full iOS app (wireframes, mockups, full UI, development, beta, launch) targeting Sep-Oct 2026 public release, then validate with users.

**Advisor says:** Validate *first*, build after. The VAULT has no validation phase before significant build investment. The PRD, release train, cash flow forecast, and timeline all assume building a polished product before getting real user data.

**Gap:** No validation phase exists in any VAULT document.

---

### 2. "Drop the simplest version into TestFlight. Invite up to 5,000 people."

**VAULT assumption:** TestFlight appears in the timeline as "Beta build on TestFlight — Jul-Aug 2026" with 100-150 beta users (Doc 06). This is 6+ months away, small scale, and positioned *after* full UI design, hiring, and significant spend.

**Advisor says:** Get something into TestFlight *now* (or very soon), at much larger scale (5,000 people), and use that data to guide everything else.

**Gap:** TestFlight is 6 months out, limited to 150 users, and treated as QA — not as the primary learning tool.

---

### 3. "Start tracking what they do — how often they return, how long on each screen, downloads, will people pay"

**VAULT assumption:** Analytics (Mixpanel) is listed as a "Medium Priority — Before Launch" task for Todd (task #21 in Todd's task list). Beta metrics are an afterthought, not the foundation.

**Advisor says:** Tracking is the *purpose* of the MVP. Ship to learn, not to impress.

**Gap:** Analytics is deprioritized. No tracking framework defined for a validation build.

---

### 4. "Put $50-100 into Pinterest Ads, Instagram Ads, Facebook Ads. Define your audience from those ads."

**VAULT assumption:** Marketing budget is $100K, front-loaded around a polished launch (Jul 2026). Pre-launch marketing spend is $1,000/month for "landing page ads, waitlist building" (Doc 01). No mention of micro-spend audience discovery.

**Advisor says:** Spend tiny amounts *now* to learn who your actual audience is before committing $100K.

**Gap:** No micro-budget audience discovery phase exists. The $100K marketing plan assumes the audience is already defined.

---

### 5. "Don't build features until you have user actions on platform"

**VAULT assumption:** The PRD defines 7 core screen categories, guided journeys with 5-step flows, Masnavi library with search/browse/bookmark, premium/paywall screens — all designed upfront. Feature scope is assumption-driven, not data-driven.

**Advisor says:** Let user behavior on a minimal version tell you what to build. Features should emerge from data, not from a PRD.

**Gap:** The PRD is spec-driven, not data-driven. Every feature is pre-planned rather than validated.

---

### 6. "Where can you prove the app has traction?" / "Do your users care about your thesis?"

**VAULT assumption:** Traction proof comes from beta user metrics collected Jul-Aug 2026 (6+ months from now). Investor meetings target Apr 2026 — *before* any traction data exists.

**Advisor says:** You need traction proof *before* investor meetings. The simplest version of the app on TestFlight with real usage data IS the traction.

**Gap:** The timeline has investor meetings in April 2026 with zero traction data. The data room checklist (Doc 08) lists "Beta User Metrics" as not started.

---

### 7. "The best slogans are ones your users give you"

**VAULT assumption:** Brand identity, positioning, tone of voice, and design principles are all defined upfront in the PRD (extensive sections on "Sanctuary, not a feed," design principles, brand attributes). These are founder-generated, not user-validated.

**Gap:** Brand language is assumed, not discovered. No mechanism exists to capture user language.

---

## Proposed VAULT Changes

### A. PRD (rumi-app-prd.md) — Add Phase 0: Validation

Add a new phase before the current timeline:

1. **Minimum TestFlight Build** — Strip the app to the simplest possible version:
   - Daily verse (Farsi + English + modern retelling)
   - One guided journey
   - Basic analytics (Mixpanel)
   - Paywall screen (even if no payment processing — measure tap intent)
2. **Deploy to TestFlight** — Target: within weeks, not months
3. **Invite up to 5,000 users** — Friends, family, waitlist, spiritual communities
4. **Track everything:**
   - DAU, session length, return rate
   - Screen time per feature
   - Paywall tap-through rate
   - Daily verse engagement (open rate, read time, save rate)
   - Guided journey start rate, completion rate, return rate
5. **Run micro-ad tests** — $50-100 on Pinterest/Instagram/Facebook to discover actual audience demographics
6. **Capture user language** — What words do real users use to describe the app? These become the slogans and positioning.
7. **Use findings to inform** what to build next, feature priority, and marketing language

### B. Timeline — Shift Sequence

**Current:**
```
Wireframes → Incorporation → Investor Meetings → SAFE → Hire → Build → Beta → Launch
```

**Proposed:**
```
TestFlight MVP → Micro-ad tests → Traction data → Incorporation → Investor Meetings (with data) → SAFE → Hire → Build full product → Launch
```

This means Todd should be building a minimal TestFlight version *now*, not waiting for wireframes/mockups.

### C. Release Train (Doc 06) — Add Early Validation Cadence

**Current:** Release train starts "~June 2026, 4 weeks before iOS launch"

**Proposed:** Start a lightweight validation cadence immediately once the TestFlight MVP ships. Weekly builds focused on learning, not features. The formal release train (Doc 06) remains for the full product phase.

### D. Cash Flow Forecast (Doc 01) — Add Micro-Budget Validation Line

Add a line item for $50-$100/month ad spend for audience discovery (Feb-May 2026). This is trivially small but strategically important — it generates audience definition data before committing the $100K marketing budget.

### E. Sales Forecast (Doc 02) — Add Pre-Launch Validation Data

Add a section for "Pre-Launch Validation Metrics" that captures TestFlight data before the full launch projections kick in. This gives investors real numbers rather than interpolated assumptions.

### F. Data Needed Summary (Doc 00) — Add Validation Decisions

Add new critical decisions:
- What is the minimum viable TestFlight build? (Todd to define)
- Who are the first 500-5,000 TestFlight users? (All founders to recruit)
- What ad platforms and audiences for $50-100 micro-tests? (Stuart/Yalor)
- What metrics define "validation"? (DAU threshold, return rate, paywall intent)

### G. Task Lists — Reprioritize

- **Todd:** "Ship simplest TestFlight build" becomes the new #1 BLOCKING task (above technical architecture doc)
- **Stuart:** "Run $50-100 micro-ad tests" becomes a new HIGH PRIORITY task
- **Yalor:** "Recruit first 500-5,000 TestFlight users" becomes a new BLOCKING task
- **John:** "Provide minimum content for TestFlight MVP" (daily verses + one guided journey) becomes BLOCKING

### H. Investor Data Room Checklist (Doc 08) — Add Validation Items

Add to Section 6 (Product & Technology):
- TestFlight Usage Metrics (DAU, retention, session length, feature engagement)

Add to Section 9 (Market & Customers):
- Ad Audience Discovery Results (demographics, CPM, click-through by platform)
- User Language Quotes (how real users describe the app)

These become powerful data room items: "Here's what 2,000 real users did on our app."

---

## Strategic Summary

The advisor's feedback represents a significant strategic shift:

| Dimension | Current VAULT Approach | Advisor's Approach |
|-----------|----------------------|-------------------|
| Build philosophy | Build it right, then ship | Ship the minimum, learn, then build what matters |
| Timeline | 6-8 months to TestFlight | Weeks to TestFlight |
| Beta scale | 100-150 users | Up to 5,000 users |
| Feature decisions | PRD-driven (assumption) | Data-driven (user behavior) |
| Marketing | $100K post-launch | $50-100 now for audience discovery |
| Investor story | "Here's our plan" | "Here's our traction" |
| Brand language | Founder-defined | User-discovered |
| Analytics priority | Medium (before launch) | Blocking (core purpose of MVP) |

Both approaches are valid. But the advisor's approach is more aligned with current pre-seed investor expectations — investors want to see *evidence of demand*, not just a beautiful plan.

The strongest position for investor meetings: walk in with TestFlight data showing X thousand users, Y% daily return rate, Z% paywall tap-through, and real quotes from users describing why they love the app. That story closes a SAFE faster than any slide deck.

---

## References

- [PRD](../rumi-app-prd.md) — Current product and timeline assumptions
- [Doc 01 — Cash Flow Forecast](../01-cash-flow-forecast.md) — Marketing spend allocation
- [Doc 02 — Weighted Sales Forecast](../02-weighted-sales-forecast.md) — Revenue projections
- [Doc 06 — Release Train Schedule](../06-release-train-schedule.md) — Beta cadence
- [Doc 08 — Investor Data Room Checklist](../08-investor-data-room-checklist.md) — Due diligence items
- [Doc 00 — Data Needed Summary](../00-data-needed-summary.md) — Outstanding decisions
