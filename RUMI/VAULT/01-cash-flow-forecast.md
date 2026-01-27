# Cash Flow Forecast

Rumi App - Pre-Seed Financial Planning  
Last Updated: January 26, 2026

---

## Overview

Month-by-month projection of money coming in (revenue) and money going out (expenses) over 24 months. This is the single most important financial document for a pre-seed startup (per Ben Rewis, Jan 2026).

---

## Current Cash Position

| Item | Amount |
|------|--------|
| Cash on Hand | **[DECISION NEEDED — current bank balance]** |
| Expected Funding | $250,000 (SAFE at $4M post-money valuation cap) |
| Total Available | **[Cash on Hand + $250,000]** |

---

## Monthly Revenue Projections

Based on $9.99/month or $96/year pricing, ~$100 blended average per subscriber per year (~$8.33/month).

**Anchor data points from pitch deck and weighted sales forecast (moderate scenario):**
- Oct 2026: 300,000 users / 1,500 paid / 0.5% conversion
- Jan 2027: 400,000 users / 2,550 paid / 0.64% conversion
- Apr 2027: 500,000 users / 4,000 paid / 0.80% conversion
- Jul 2027: 650,000 users / 6,500 paid / 1.00% conversion

**Interpolated monthly projections (moderate scenario):**

| Month | Total Users | Paid Subscribers | Conversion % | Monthly Revenue | Cumulative Revenue |
|-------|-------------|------------------|-------------|-----------------|-------------------|
| **Jul 2026** | 50,000 | 125 | 0.25% | $1,042 | $1,042 |
| **Aug 2026** | 120,000 | 360 | 0.30% | $3,000 | $4,042 |
| **Sep 2026** | 210,000 | 735 | 0.35% | $6,125 | $10,167 |
| **Oct 2026** | 300,000 | 1,500 | 0.50% | $12,500 | $22,667 |
| **Nov 2026** | 330,000 | 1,815 | 0.55% | $15,125 | $37,792 |
| **Dec 2026** | 360,000 | 2,160 | 0.60% | $18,000 | $55,792 |
| **Jan 2027** | 400,000 | 2,550 | 0.64% | $21,250 | $77,042 |
| **Feb 2027** | 430,000 | 2,924 | 0.68% | $24,367 | $101,408 |
| **Mar 2027** | 465,000 | 3,441 | 0.74% | $28,675 | $130,083 |
| **Apr 2027** | 500,000 | 4,000 | 0.80% | $33,333 | $163,417 |
| **May 2027** | 540,000 | 4,752 | 0.88% | $39,600 | $203,017 |
| **Jun 2027** | 590,000 | 5,546 | 0.94% | $46,217 | $249,233 |
| **Jul 2027** | 650,000 | 6,500 | 1.00% | $54,167 | $303,400 |

**Notes on interpolation:**
- Jul-Sep 2026: Ramp-up period (iOS launch Q3 2026). Slow initial growth as organic discovery builds.
- Oct-Dec 2026: Post-launch momentum. Android launch Q4 2026 adds second growth channel.
- Jan-Jul 2027: Steady growth as marketing spend kicks in, ASO matures, and word-of-mouth compounds.
- Revenue assumes Apple/Google take 30% commission in Year 1 (15% after Year 1 for small business program). Figures above are **gross revenue** — net revenue is 70% of these numbers.

### Net Revenue (After App Store Commission)

| Month | Gross Revenue | Commission (30%) | Net Revenue |
|-------|--------------|-------------------|-------------|
| Jul 2026 | $1,042 | $313 | $729 |
| Aug 2026 | $3,000 | $900 | $2,100 |
| Sep 2026 | $6,125 | $1,838 | $4,288 |
| Oct 2026 | $12,500 | $3,750 | $8,750 |
| Nov 2026 | $15,125 | $4,538 | $10,588 |
| Dec 2026 | $18,000 | $5,400 | $12,600 |
| Jan 2027 | $21,250 | $6,375 | $14,875 |
| Feb 2027 | $24,367 | $7,310 | $17,057 |
| Mar 2027 | $28,675 | $8,603 | $20,073 |
| Apr 2027 | $33,333 | $10,000 | $23,333 |
| May 2027 | $39,600 | $11,880 | $27,720 |
| Jun 2027 | $46,217 | $13,865 | $32,352 |
| Jul 2027 | $54,167 | $16,250 | $37,917 |

**Note:** If annual revenue stays under $1M (likely in Year 1), Apple's Small Business Program reduces commission to 15%. This would significantly improve net revenue. Use 30% as conservative assumption.

---

## Monthly Fixed Expenses

**DECISION NEEDED: Actual amounts from team. Estimates below based on industry benchmarks for a 4-person pre-seed startup.**

| Category | Monthly Estimate | Notes |
|----------|-----------------|-------|
| Founder Stipends | **[DECISION NEEDED]** | See Governance Doc 10: recommend $8K-$16K/month total across 4 founders |
| Infrastructure (Servers, APIs, Hosting) | $500 - $1,500 | AWS/Vercel/Supabase; AI API costs (OpenAI/Anthropic) scale with users |
| Software Subscriptions | $300 - $500 | ClickUp (~$30), Figma (~$15), GitHub (~$20), Slack (~$0 free tier), Apple Dev ($100/yr), Google Dev ($25 one-time), analytics tools |
| Legal/Accounting | $500 - $1,000 | Monthly retainer or as-needed; higher in months with legal filings |
| Insurance (D&O) | $200 - $500 | D&O insurance: ~$2,000-$5,000/year for pre-seed startup |
| Miscellaneous | $200 - $300 | Domain renewals, one-off tools, business filing fees |
| **Total Fixed (estimated)** | **$9,700 - $19,800** | Range depends heavily on founder stipends |

### Estimated Fixed Expenses — Three Scenarios

| Scenario | Founder Stipends | Other Fixed | Total Monthly Fixed |
|----------|-----------------|-------------|-------------------|
| **Lean** (no stipends) | $0 | $1,700 | $1,700 |
| **Moderate** (minimal stipends) | $10,000 | $1,700 | $11,700 |
| **Comfortable** (livable stipends) | $16,000 | $2,000 | $18,000 |

---

## Monthly Variable Expenses

Based on $250K Use of Funds allocation, spread across 18 months (pre-seed runway target):

| Category | Budget (Total) | Monthly Average | Notes |
|----------|---------------|-----------------|-------|
| Product Development | $75,000 | $4,167 | Contractors, tools, testing, Apple/Google fees |
| Marketing & User Acquisition | $100,000 | $5,556 | Ramps up: $0 in months 1-3, heavy in months 4-12 |
| Team (New Hires) | $50,000 | $2,778 | UI/UX designer + marketing specialist, starting Q3 2026 |
| Operations | $25,000 | $1,389 | Office, travel, miscellaneous |
| **Total Variable** | **$250,000** | **$13,889** | |

### Pre-Launch Validation Spend (Immediate — Before Funding)

Micro-budget audience discovery before committing the $100K marketing budget:

| Period | Spend | Purpose |
|--------|-------|---------|
| Feb 2026 | $50-100 | Micro-ad tests on Pinterest, Instagram, Facebook — define actual audience demographics, test creatives, measure CPM and click-through |
| Mar 2026 | $50-100 | Iterate on best-performing platform/creative from Feb tests |
| **Total validation spend** | **$100-200** | **Generates audience data that informs how the $100K is allocated** |

This is founder-funded (pre-SAFE). The return is strategic data, not users.

### Marketing Spend Ramp (Post-Funding — Informed by Validation Data)

Marketing should not be spent evenly — front-load around launch, and allocate based on audience data from micro-ad tests:

| Period | Monthly Marketing Spend | Cumulative | Notes |
|--------|------------------------|------------|-------|
| Jan-Mar 2026 (pre-funding) | $50-100/month | $100-200 | Micro-ad audience discovery (see above) |
| Apr-Jun 2026 (post-SAFE) | $1,000 | $3,000 + validation spend | Landing page ads, waitlist building — informed by micro-ad data |
| Jul 2026 (iOS launch) | $15,000 | $18,000+ | Launch PR, paid social burst — allocate to platforms proven in validation |
| Aug 2026 | $10,000 | $28,000+ | Sustain launch momentum |
| Sep 2026 | $8,000 | $36,000+ | Optimize performing channels |
| Oct 2026 (Android launch) | $12,000 | $48,000+ | Second platform launch burst |
| Nov 2026 | $8,000 | $56,000+ | Holiday season push |
| Dec 2026 | $8,000 | $64,000+ | Sheb-i Arus (Rumi's death anniversary Dec 17) — cultural moment |
| Jan-Jun 2027 | $6,000/month | $100,000 | Steady-state optimization |

---

## Use of Funds Allocation (from Pitch Deck)

| Category | Amount | Percentage | Timeline |
|----------|--------|------------|----------|
| Product Development | $75,000 | 30% | Ongoing |
| Marketing & User Acquisition | $100,000 | 40% | Ramps with launch |
| Team (New Hires) | $50,000 | 20% | Q3 2026 onward |
| Operations | $25,000 | 10% | Ongoing |
| **Total** | **$250,000** | **100%** | 18-month runway target |

---

## Monthly Burn Rate

**Three scenarios based on founder stipend decisions:**

| Scenario | Monthly Fixed | Monthly Variable (avg) | Monthly Burn | Notes |
|----------|--------------|----------------------|--------------|-------|
| **Lean** | $1,700 | $13,889 | **$15,589** | No founder salaries |
| **Moderate** | $11,700 | $13,889 | **$25,589** | $10K/month total founder stipends |
| **Comfortable** | $18,000 | $13,889 | **$31,889** | $16K/month total founder stipends |

### Runway Calculations

**With $250K funding only (no revenue):**

| Scenario | Monthly Burn | Runway |
|----------|-------------|--------|
| Lean | $15,589 | **16.0 months** |
| Moderate | $25,589 | **9.8 months** |
| Comfortable | $31,889 | **7.8 months** |

**With $250K funding + projected net revenue:**

| Scenario | Net Runway (accounting for revenue) |
|----------|-------------------------------------|
| Lean | **22+ months** (revenue exceeds burn by month 14) |
| Moderate | **14-16 months** (revenue approaches burn by month 18) |
| Comfortable | **11-13 months** (revenue still below burn at month 12) |

**Recommendation:** Target the **Moderate** scenario. It provides livable founder stipends while maintaining ~14-16 months runway — enough to prove product-market fit and raise Series A.

---

## Cash Flow Summary by Quarter

**Using Moderate scenario ($25,589/month burn):**

| Quarter | Starting Cash | Net Revenue | Expenses | Ending Cash |
|---------|--------------|-------------|----------|-------------|
| Q1 2026 (Jan-Mar) | **[CASH ON HAND]** | $0 | ~$5,100 | **[CALC]** |
| Q2 2026 (Apr-Jun) | **[CALC]** + $250K funding | $0 | ~$20,000 | **[CALC]** |
| Q3 2026 (Jul-Sep) | **[CALC]** | $7,117 | $76,767 | **[CALC]** |
| Q4 2026 (Oct-Dec) | **[CALC]** | $31,938 | $76,767 | **[CALC]** |
| Q1 2027 (Jan-Mar) | **[CALC]** | $52,005 | $76,767 | **[CALC]** |
| Q2 2027 (Apr-Jul) | **[CALC]** | $83,405 | $76,767 | **[CALC]** |

**Notes:**
- Q1-Q2 2026: Pre-launch. Minimal expenses (no marketing ramp, no new hires yet). Mostly founder time + infrastructure setup.
- Q3 2026: iOS launch. Expenses ramp with marketing burst and new hires. Revenue begins.
- Q4 2026: Android launch. Marketing sustains. Revenue accelerates.
- Q1-Q2 2027: Revenue growth compounds. Approaching break-even on moderate scenario.

**To complete this table:** Plug in actual cash on hand and the quarterly calculations cascade automatically.

---

## Break-Even Analysis

### Monthly Break-Even (Moderate Scenario)

| Item | Amount |
|------|--------|
| Monthly Fixed Expenses | $11,700 |
| Monthly Variable Expenses (avg) | $13,889 |
| **Total Monthly Expenses** | **$25,589** |
| App Store Commission | 30% (net revenue = 70% of gross) |
| **Gross Revenue Needed for Break-Even** | **$36,556/month** |
| At $8.33/month per subscriber | **~4,389 paid subscribers** |
| At 0.8% conversion | **~548,600 total users** |

### When Does Break-Even Occur?

| Scenario | Estimated Break-Even | Total Users at Break-Even |
|----------|---------------------|--------------------------|
| Lean ($15,589 burn) | ~November 2026 | ~330,000 users |
| Moderate ($25,589 burn) | ~April-May 2027 | ~500,000 users |
| Comfortable ($31,889 burn) | ~June-July 2027 | ~600,000 users |

**Key insight for investors:** At the moderate scenario, break-even occurs around month 10-11 post-launch with ~500K users and ~4,000 paid subscribers. This is achievable based on comparable spiritual/meditation app growth patterns and the $100K marketing budget.

---

## Fiscal Gap Analysis

**DECISION NEEDED: Cash on hand to complete this section.**

| Item | Amount |
|------|--------|
| Total Capital Required (18 months, moderate) | ~$460,000 |
| Projected Revenue (18 months) | ~$212,000 net |
| **Net Capital Required** | ~$248,000 |
| Current Cash on Hand | **[AMOUNT NEEDED]** |
| **Fiscal Gap** | **[NET CAPITAL REQUIRED - CASH ON HAND]** |

**This gap justifies the $250K raise.** At the moderate burn scenario, $250K in funding covers the gap almost exactly, with projected revenue filling the remainder. This gives the company an 18-month window to prove product-market fit and raise Series A.

---

## Key Assumptions

1. **Validation-first strategy:** TestFlight MVP ships Feb 2026, up to 5,000 users recruited before investor meetings, traction data informs all subsequent spending
2. **Pre-funding spend:** $100-200 founder-funded for micro-ad audience discovery (Feb-Mar 2026)
3. **Conversion rate:** 0.25% at soft launch (Jul 2026) → 0.5% at full launch (Oct 2026) → 1.0% at 12 months (Jul 2027) — to be validated against TestFlight paywall tap-through data
4. **Average revenue per subscriber:** $100/year blended ($8.33/month) assumes 60% annual / 40% monthly mix
5. **Customer Acquisition Cost (CAC):** $30-$120 blended across organic and paid channels — micro-ad tests will provide early CPM/CPA benchmarks
6. **Lifetime Value (LTV):** $300-$500 (3-5 year average subscription lifetime)
7. **LTV:CAC ratio:** 4:1 to 8:1 (healthy range; 3:1 is minimum viable)
8. **Monthly churn rate:** 8-12% for monthly subscribers, 3-5% for annual subscribers (industry benchmarks for meditation/spiritual apps)
9. **App Store commission:** 30% (conservative; may qualify for 15% Small Business Program if under $1M/year)
10. **Marketing efficiency:** Improves over time as organic channels (ASO, word-of-mouth, PR) compound; $100K allocation informed by Phase 0 audience data
11. **Hiring timeline:** UI/UX designer and marketing specialist hired Q3 2026
12. **No additional funding** until Series A (targeted Q1-Q2 2027)

---

## Sensitivity: What If Revenue is 50% Lower?

| Scenario | Revenue Impact | Runway Impact | Action Required |
|----------|---------------|---------------|-----------------|
| Moderate burn, 50% lower revenue | ~$106K net revenue (vs $212K) | Runway shortens to ~12 months | Cut marketing spend, defer hires, or raise bridge round |
| Lean burn, 50% lower revenue | ~$106K net revenue | Runway still ~16 months | Extend runway by staying lean |

**Takeaway:** The lean scenario provides a safety net. If revenue underperforms, the team can reduce burn by deferring stipends and extending runway to 16+ months — enough time to iterate on product-market fit.

---

## Monthly Cash Flow Detail (Template)

**Fill in with actuals once funding is secured:**

| Month | Starting Cash | Revenue (Net) | Fixed Expenses | Variable Expenses | Ending Cash |
|-------|--------------|---------------|----------------|-------------------|-------------|
| Jan 2026 | [CASH] | $0 | [FIXED] | [VARIABLE] | [CALC] |
| Feb 2026 | [CALC] | $0 | [FIXED] | [VARIABLE] | [CALC] |
| Mar 2026 | [CALC] | $0 | [FIXED] | [VARIABLE] | [CALC] |
| Apr 2026 | [CALC] | $0 | [FIXED] | [VARIABLE] | [CALC] |
| May 2026 | [CALC] | $0 | [FIXED] | [VARIABLE] | [CALC] |
| Jun 2026 | [CALC] | $0 | [FIXED] | [VARIABLE] | [CALC] |
| Jul 2026 | [CALC] | $729 | [FIXED] | [VARIABLE] | [CALC] |
| Aug 2026 | [CALC] | $2,100 | [FIXED] | [VARIABLE] | [CALC] |
| Sep 2026 | [CALC] | $4,288 | [FIXED] | [VARIABLE] | [CALC] |
| Oct 2026 | [CALC] | $8,750 | [FIXED] | [VARIABLE] | [CALC] |
| Nov 2026 | [CALC] | $10,588 | [FIXED] | [VARIABLE] | [CALC] |
| Dec 2026 | [CALC] | $12,600 | [FIXED] | [VARIABLE] | [CALC] |
| Jan 2027 | [CALC] | $14,875 | [FIXED] | [VARIABLE] | [CALC] |
| Feb 2027 | [CALC] | $17,057 | [FIXED] | [VARIABLE] | [CALC] |
| Mar 2027 | [CALC] | $20,073 | [FIXED] | [VARIABLE] | [CALC] |
| Apr 2027 | [CALC] | $23,333 | [FIXED] | [VARIABLE] | [CALC] |
| May 2027 | [CALC] | $27,720 | [FIXED] | [VARIABLE] | [CALC] |
| Jun 2027 | [CALC] | $32,352 | [FIXED] | [VARIABLE] | [CALC] |

---

## Action Items for February Session with Ben

1. [ ] Confirm cash on hand amount
2. [ ] Confirm monthly stipend amounts per founder
3. [ ] Confirm infrastructure costs (Todd to provide server/API estimates)
4. [ ] Confirm software subscription list and costs
5. [ ] Confirm legal/accounting retainer cost
6. [ ] Validate marketing spend ramp timeline
7. [ ] Run the monthly detail sheet with actuals
8. [ ] Calculate exact runway and break-even month
9. [ ] Review fiscal gap and confirm $250K raise sufficiency

---

## Notes

- This forecast uses the **moderate scenario** as the working assumption
- All revenue figures are **projections** — actual performance will vary
- Update monthly with actuals once revenue begins
- Review with full team monthly per Ben Rewis recommendation
- **Net revenue** (after App Store commission) is what matters for cash flow — always use net figures
- Consider Apple Small Business Program (15% commission if under $1M/year) as upside scenario
