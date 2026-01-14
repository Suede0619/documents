# User Testing Logic
## A/B Testing Framework for Mobile Products

**Purpose:** Systematic testing patterns to improve activation, revenue, and retention
**Stage:** Post-launch optimization (requires 500+ users)
**Source:** Consultant guidance for The Rumi App

---

## Overview

The most impactful A/B tests in mobile products focus on **onboarding, paywalls/pricing, navigation, and messaging**, all tied directly to activation, revenue, or retention. Below are concrete patterns you can copy and adapt.

---

## 1. Onboarding Flow Tests

Improving onboarding is often the **highest-leverage** mobile A/B testing area because it hits activation and early retention.

### Test 1.1: Login Options

**Variant A:** Email/phone only
**Variant B:** Email + Apple/Google/Facebook social login

**Primary Metric:** Onboarding completion rate
**Secondary Metric:** Day-1 retention

**Hypothesis:** Social login reduces friction → higher completion rate

---

### Test 1.2: Number of Onboarding Steps

**Variant A:** Minimal 1–2 screens explaining value prop
**Variant B:** Rich multi-step flow that asks intent, goals, or level (Duolingo-style)

**Metrics:**
- Completion rate
- Time-to-first-value
- Support tickets from new users

**Hypothesis:** Shorter onboarding improves completion, but richer onboarding may improve long-term retention

---

### Test 1.3: Progress Indicators and Checklists

**Variant A:** Multi-screen onboarding, no progress bar
**Variant B:** Same flow with a progress bar and checklist of key actions to complete

**Metrics:**
- Completion rate
- Percentage of users hitting "aha" feature

**Hypothesis:** Progress indicators reduce abandonment by setting expectations

---

## 2. Paywall and Pricing Tests

Subscription and IAP apps get **outsized gains** from systematic paywall experiments.

### Test 2.1: Paywall Layout and Copy

**Variant A:** Simple single-plan paywall, generic headline
**Variant B:** Highlighted "Most popular" plan, social proof, money-back copy, clearer benefits

**Metrics:**
- Paywall conversion rate
- ARPU (Average Revenue Per User)
- Refund rate

**Hypothesis:** Social proof and clear benefits increase conversion

---

### Test 2.2: Price-Point Testing

**Variant A:** Monthly at $7.99
**Variant B:** Monthly at $9.99

**Metrics:**
- Conversion to paid
- ARPU / LTV (Lifetime Value)
- Churn

**Important:** Don't judge by conversion alone - higher price may have lower conversion but higher revenue

---

### Test 2.3: Trial Length and Offer Framing

**Variant A:** 3-day free trial, then full price
**Variant B:** 7-day free trial, or "50% off first 3 months" intro offer

**Metrics:**
- Trial start rate
- Trial-to-paid conversion
- 60–90 day retention

**Hypothesis:** Longer trials build habit, but shorter trials may convert better

---

### Test 2.4: Plan Structure

**Variant A:** Monthly only
**Variant B:** Monthly + discounted annual, or bundled features vs unbundled

**Metrics:**
- Revenue per install
- Plan mix (% monthly vs. annual)
- Churn by plan

**Hypothesis:** Annual plans drive higher upfront revenue and lower churn

---

## 3. Navigation and In-App UX Tests

These tests remove friction to reach the core action and are usually **easy to implement**.

### Test 3.1: Primary Navigation Structure

**Variant A:** Bottom nav with 3 core tabs
**Variant B:** Bottom nav with 5 tabs, or different labeling/ordering

**Metrics:**
- Time to first key event
- Feature adoption rate
- Session length

**Hypothesis:** Simpler navigation improves focus on core features

---

### Test 3.2: CTA Position and Prominence

**Variant A:** Primary CTA below the fold or in secondary color
**Variant B:** Above-the-fold, high-contrast CTA, clearer verb ("Start workout" vs "Continue")

**Metrics:**
- Click-through to next step
- Task completion rate

**Hypothesis:** More prominent CTAs drive higher engagement

---

### Test 3.3: Empty States and Helper UI

**Variant A:** Blank screens when no data yet (e.g., no saved items)
**Variant B:** Guided empty states with example content, tips, and CTA to create/import

**Metrics:**
- Creation of first item/project
- Bounce rate from empty screens

**Hypothesis:** Guided empty states reduce confusion and drive first action

---

## 4. Messaging, Nudges, and Push Tests

Push and in-app messaging tests are **fast, iterative**, and directly tied to engagement.

### Test 4.1: Push Notification Copy

**Variant A:** Generic "Reminder" message
**Variant B:** Personalized copy with user name, last activity, or streak (e.g., "Ben, your 3-day streak is on the line")

**Metrics:**
- Push open rate
- App opens per user
- Target event completion

**Hypothesis:** Personalized copy increases relevance and open rate

---

### Test 4.2: Send Time and Trigger Rules

**Variant A:** Fixed time (e.g., 9am local) for all users
**Variant B:** Time based on last active or behavior triggers (e.g., 24 hours after cart add but no purchase)

**Metrics:**
- Open rate
- Conversion from notification to purchase/feature use

**Hypothesis:** Adaptive timing catches users when they're most receptive

---

### Test 4.3: In-App Upsell Prompts

**Variant A:** One generic upsell modal after signup
**Variant B:** Contextual prompts when user hits a specific threshold (e.g., 3rd session, feature limit)

**Metrics:**
- Click-through on upsell
- Conversion to paid
- User complaints (negative feedback)

**Hypothesis:** Contextual prompts feel less intrusive and convert better

---

## 5. Key Metrics and Guardrails

Measuring the right outcomes is as important as the variant design.

### Core Metrics to Watch

| Category | Metrics |
|----------|---------|
| **Activation** | Onboarding completion, first key action, time-to-value |
| **Engagement** | Session frequency, feature adoption, push open rate |
| **Monetization** | Paywall conversion, ARPU, LTV, refund rate |
| **Retention** | Day-1 / Day-7 / Day-30 retention; churn by variant |

### Guardrails

**Always:**
- ✅ Segment by platform (iOS/Android)
- ✅ Segment by channel (organic vs. paid acquisition)
- ✅ Segment by cohort date when possible

**Never:**
- ❌ Ship winners that only improve vanity metrics
  - Example: More trials but worse churn = bad
  - Always pair conversion metrics with retention/revenue

**Best Practice:**
- Run tests for **1-2 weeks minimum** (statistical significance)
- Test **one variable at a time** (A vs. B, not A vs. B vs. C vs. D)
- Define **success criteria before launching** test
- Document **learnings even if test fails** (negative results are valuable)

---

## 6. Test Prioritization Framework

### How to Choose Your Next Test:

**High-Impact Tests (Do First):**
1. **Onboarding completion** - Affects all downstream metrics
2. **Paywall conversion** - Direct revenue impact
3. **First key action** - Drives retention

**Medium-Impact Tests (Do Second):**
4. **Push notification engagement** - Improves retention
5. **Navigation/UX friction** - Incremental engagement gains
6. **Pricing experiments** - Optimize revenue per user

**Low-Impact Tests (Do Later):**
7. **Visual design changes** - Marginal gains
8. **Copy tweaks** - Small improvements
9. **Animation/motion** - Polish, not performance

### Impact vs. Effort Matrix:

```
High Impact │ ● Onboarding      ● Paywall
           │   completion        timing
           │
           │ ● Push copy      ○ Navigation
           │                    structure
           │
           │ ○ Visual        ○ Animation
Low Impact │   polish
           └─────────────────────────────
             Low Effort      High Effort
```

**Strategy:** Start with high-impact, low-effort tests (top-left quadrant)

---

## 7. Application to The Rumi App

If you share what kind of mobile product you are running (content, utility, subscription, marketplace, etc.), a short list of 3–5 high-impact test ideas can be tailored specifically to that context.

### The Rumi App Context:
- **Type:** Content + Subscription (meditation/spiritual wellness app)
- **Business Model:** Freemium (free daily verse, paid for guided journeys + full library)
- **User Behavior:** Daily habit formation (contemplative practice)
- **Key Metrics:** D1/D7/D30 retention, free-to-paid conversion, engagement (session length)

### Recommended First 5 Tests for The Rumi App:

#### **Test 1: Onboarding Length**
- **A:** 2 screens (Welcome → How It Works → Home)
- **B:** 4 screens (Welcome → How It Works → Choose Intent → Notification Setup → Home)
- **Hypothesis:** Shorter onboarding improves completion, but richer onboarding improves D7 retention
- **Metrics:** Onboarding completion, D1 retention, D7 retention

#### **Test 2: Paywall Timing**
- **A:** Show paywall after 1st Guided Journey attempt (Day 1-2)
- **B:** Show paywall after 3 daily verses + 1 journey attempt (Day 3-5)
- **Hypothesis:** Delayed paywall builds trust → higher conversion
- **Metrics:** Paywall conversion rate, D30 retention

#### **Test 3: Home Screen Layout**
- **A:** Daily verse fills screen, no journey prompt
- **B:** Daily verse + "Try a Guided Journey" card below
- **Hypothesis:** Journey prompt increases discovery → higher conversion
- **Metrics:** % users who try guided journey, time to first journey

#### **Test 4: Push Notification Copy**
- **A:** "Your daily verse is ready"
- **B:** "Good morning, [Name]. Today's verse on longing awaits."
- **Hypothesis:** Personalized, poetic copy increases open rate
- **Metrics:** Push open rate, verse read rate, D7 retention

#### **Test 5: Pricing Display**
- **A:** Monthly $8.88, Annual $84 (equal prominence)
- **B:** Annual $84 highlighted as "Most Popular," monthly smaller
- **Hypothesis:** Highlighting annual drives more upfront revenue
- **Metrics:** Annual vs. monthly subscription mix, revenue per install

---

## 8. Testing Workflow Template

Use this process for every test:

### Step 1: Hypothesis Formation (Day 1)
- **Question:** What are we trying to improve?
- **Hypothesis:** "We believe [change] will result in [outcome] because [reason]"
- **Example:** "We believe showing paywall on Day 3 (not Day 1) will result in 20% higher conversion because users will have built trust through daily verse habit"

### Step 2: Design Variants (Day 2)
- **Variant A (Control):** Current experience
- **Variant B (Test):** One clear change
- **Note:** Only change ONE variable at a time

### Step 3: Define Success Criteria (Day 3)
- **Primary Metric:** Main outcome (e.g., paywall conversion rate)
- **Secondary Metrics:** Supporting outcomes (e.g., D30 retention, refund rate)
- **Guardrails:** What can't get worse? (e.g., retention can't drop >5%)
- **Decision Rule:** "If B improves primary metric by X% without hurting guardrails, we ship it"

### Step 4: Implement & Launch (Days 4-5)
- Developers implement variant B
- QA test both variants
- Launch test at 50/50 split (or 90/10 if risky)

### Step 5: Collect Data (Days 6-19)
- Run test for 1-2 weeks minimum
- Monitor for statistical significance
- Watch guardrails (make sure nothing breaks)

### Step 6: Analyze Results (Day 20)
- **Winning Variant:** Which variant performed better?
- **Statistical Significance:** Is the difference real or random? (need p-value <0.05)
- **Guardrails Check:** Did any secondary metrics get worse?
- **Segment Analysis:** Did one variant work better for specific user types?

### Step 7: Make Decision (Day 21)
- **Ship Winner:** If B clearly wins and guardrails hold
- **Ship Control:** If A wins or B has negative side effects
- **Iterate:** If results are unclear, design new variant C based on learnings

### Step 8: Document (Day 22)
- Write up: Hypothesis, results, decision, learnings
- Share with team
- Add to testing knowledge base

### Step 9: Next Test (Day 23+)
- Pick next test from priority list
- Repeat process

---

## 9. Common Mistakes to Avoid

### ❌ Mistake 1: Testing Too Many Variables
**Wrong:** Change onboarding flow + paywall copy + pricing in one test
**Right:** Test one variable at a time so you know what caused the change

### ❌ Mistake 2: Not Running Long Enough
**Wrong:** Run test for 3 days, see Variant B is "winning," ship it
**Right:** Run for 1-2 weeks to account for day-of-week effects and reach statistical significance

### ❌ Mistake 3: Ignoring Segment Differences
**Wrong:** Look at aggregate results only
**Right:** Segment by platform (iOS/Android), channel (organic/paid), user type (new/returning)

### ❌ Mistake 4: Optimizing for Vanity Metrics
**Wrong:** Ship test that increases trial starts by 30% but increases churn by 20%
**Right:** Always pair conversion metrics with retention/revenue metrics

### ❌ Mistake 5: No Clear Hypothesis
**Wrong:** "Let's try a new onboarding and see what happens"
**Right:** "We believe showing social proof in onboarding will increase completion by 15% because users trust peer validation"

### ❌ Mistake 6: Testing Without Statistical Significance
**Wrong:** Variant B has 5% higher conversion with 50 users, ship it!
**Right:** Need 500+ users per variant for meaningful results (depends on baseline conversion rate)

---

## 10. Tools for A/B Testing

### Analytics & Testing Platforms:
- **Mixpanel:** Event tracking + A/B testing (free tier available)
- **Amplitude:** Product analytics + cohort analysis (free tier available)
- **Firebase:** Google's mobile analytics + A/B testing (free)
- **Optimizely:** Enterprise A/B testing platform (paid)

### Statistical Significance Calculators:
- **Evan Miller:** evanmiller.org/ab-testing (free online calculator)
- **Optimizely Calculator:** optimizely.com/sample-size-calculator

### Recommended Stack for The Rumi App:
- **Analytics:** Firebase Analytics (free, integrates with iOS)
- **A/B Testing:** Firebase A/B Testing (free)
- **Cohort Analysis:** Mixpanel free tier (first 100K events/month free)

---

## Final Notes

### When to Start A/B Testing:
- ✅ You have 500+ active users (for statistical significance)
- ✅ Analytics are properly instrumented (events tracked)
- ✅ You have 2-4 weeks of baseline data
- ✅ Core product experience is stable (not changing daily)

### When NOT to A/B Test:
- ❌ Pre-launch (not enough users)
- ❌ <100 users (can't reach statistical significance)
- ❌ Product is still in rapid prototyping phase
- ❌ You're testing a complete redesign (do qualitative user testing first)

### Remember:
**A/B testing is about learning, not just winning.**

Even "failed" tests teach you about user behavior. Document everything, iterate continuously, and always prioritize user value over vanity metrics.

---

**Document Source:** Consultant guidance for The Rumi App
**Date:** January 12, 2026
**Status:** Reference framework for post-launch optimization
**Related Documents:**
- `ux-plan-lean-mvp.md` (Phase 4 incorporates this framework)
- `comprehensive-ux-plan.md` (Phase 7 references this framework)
