# Investor Data Room Checklist

Rumi App - Due Diligence Preparation  
Last Updated: January 26, 2026

---

## Overview

Master list of all documents investors will request during due diligence. Per Ben Rewis: prepare for the "proctological exam" of VC scrutiny. Having a complete, organized data room signals professionalism and accelerates funding timelines.

---

## Document Status Legend

- ✅ Complete — Ready for investor review
- 🟡 In Progress — Draft exists, needs completion
- ⬜ Not Started — Needs to be created
- ❌ Not Applicable — Not relevant at this stage

---

## 1. Company Overview

| Document | Status | Location | Owner | Notes |
|----------|--------|----------|-------|-------|
| Pitch Deck (16 slides) | ✅ | /decks/rumideck.pdf | SP/YM | Updated Jan 2026 |
| Executive Summary (1-pager) | ⬜ | — | YM | Needed: condensed version of deck for quick investor review |
| Company Fact Sheet | ⬜ | — | YM | 1-page: team, stage, ask, market, traction |
| Product Demo Video | ⬜ | — | TB/SP | Screen recording of core flows (2-3 minutes) |
| Product Screenshots | ✅ | /decks/ | SP | 16 deck page images |
| Landing Page | 🟡 | — | SP/YM | Copy exists (/landing/copy.md), needs live deployment |

**Action needed:** Executive summary and product demo video are high-impact, low-effort items. Create before first investor meeting.

---

## 2. Corporate Documents

| Document | Status | Location | Owner | Action Needed |
|----------|--------|----------|-------|---------------|
| Certificate of Incorporation | ⬜ | — | YM | **CRITICAL:** File with Delaware (recommended). Use Clerky or Stripe Atlas. ~$500-$800 |
| Bylaws / Operating Agreement | ⬜ | — | YM | Generated during incorporation (Clerky includes) |
| Good Standing Certificate | ⬜ | — | YM | Order from state after incorporation |
| EIN / Tax ID | ⬜ | — | YM | Apply at IRS.gov (free, instant online) |
| Board Resolutions | ⬜ | — | YM | Initial board resolution adopting bylaws, appointing officers, authorizing shares |
| Shareholder/Member Agreements | ⬜ | — | YM | Part of incorporation package |
| Previous Funding Documents | ❌ | — | — | No prior funding |

**Target completion: Before first investor meeting.** Incorporation is a prerequisite for issuing a SAFE. Budget: $800-$2,500 via Clerky.

---

## 3. Cap Table & Equity

| Document | Status | Location | Owner | Notes |
|----------|--------|----------|-------|-------|
| Cap Table (current) | 🟡 | /VAULT/09-cap-table.md | YM | Template complete with recommendations; awaiting equity split decision |
| Founder Equity Agreements | 🟡 | /equity/ | Team | Philosophy documented (suedeEquity.md, yalor.md); formal agreements not executed |
| Vesting Schedules | 🟡 | /VAULT/09-cap-table.md | Team | 4yr/1yr cliff defined; start dates needed |
| Option Pool Summary | 🟡 | /VAULT/09-cap-table.md | Team | 15% recommended; awaiting confirmation |
| Advisor Agreement (Ben Rewis) | ⬜ | — | YM | Use FAST Agreement template; 0.5-1.0% recommended |
| SAFE Document (for investors) | ⬜ | — | YM | Use YC Post-Money SAFE template (free at ycombinator.com) |

**Action needed:** Finalize equity split, then execute formal agreements. Cannot issue SAFE without cap table in place.

---

## 4. Financial Documents

| Document | Status | Location | Owner | Notes |
|----------|--------|----------|-------|-------|
| Cash Flow Forecast (24-month) | 🟡 | /VAULT/01-cash-flow-forecast.md | YM | Template complete with projections; needs actual cash on hand and expense data |
| Weighted Sales Forecast | 🟡 | /VAULT/02-weighted-sales-forecast.md | YM | Q4 2026 through Q3 2027 complete; needs team validation |
| Historical Financials | ⬜ | — | YM | P&L and balance sheet (even if minimal pre-revenue) |
| Bank Statements (6 months) | ⬜ | — | YM | Provide when requested by investors |
| Tax Returns | ❌ | — | — | Not applicable (pre-revenue, likely no filing yet) |
| Use of Funds Breakdown | ✅ | Pitch deck slide 16 | SP/YM | $250K: 30% product, 40% marketing, 20% team, 10% ops |
| Burn Rate Analysis | 🟡 | /VAULT/01-cash-flow-forecast.md | YM | Three scenarios modeled; needs actual data |
| Revenue Projections | ✅ | Pitch deck slide 9 + /VAULT/02-weighted-sales-forecast.md | YM | Conservative through aggressive scenarios |

---

## 5. Team & HR

| Document | Status | Location | Owner | Notes |
|----------|--------|----------|-------|-------|
| Founder Bios (deck format) | ✅ | Pitch deck slide 15 | SP | In deck |
| Founder Bios (detailed) | ✅ | /BIO/rumi-background-summary.md, /equity/ | Various | Spread across documents |
| LinkedIn Profiles | ⬜ | — | All | **Each founder must have an updated LinkedIn profile** |
| Org Chart (current + projected) | 🟡 | /VAULT/04-organizational-chart.md | YM | Complete with salary benchmarks; equity % pending |
| Job Descriptions (planned hires) | ✅ | /VAULT/05-job-descriptions.md | YM/SP | 6 roles defined with compensation ranges |
| Key Employee/Founder Agreements | ⬜ | — | YM | Formal stock purchase agreements not yet executed |
| IP Assignment Agreements | ⬜ | — | YM/Legal | **CRITICAL for investors.** Must confirm company owns all content, code, and designs |
| Background Checks | ❌ | — | — | Not standard at pre-seed |

**Action needed:** IP assignment agreements are the #1 legal item investors will ask about. John's Masnavi translations and retellings must be formally assigned to the company.

---

## 6. Product & Technology

| Document | Status | Location | Owner | Notes |
|----------|--------|----------|-------|-------|
| Product Roadmap | ✅ | Pitch deck slides 13-14 | YM/SP | In deck |
| Technical Architecture Document | ⬜ | — | TB | Diagram showing: app → API → database → AI layer → content management |
| App Store Listing (draft) | ⬜ | — | SP/YM | Title, subtitle, description, keywords, screenshots |
| **TestFlight Usage Metrics** | ⬜ | — | TB/YM | **Up to 5,000 TestFlight users — DAU, retention (D1/D7/D30), session length, feature engagement, paywall tap-through** |
| User Feedback Summary | ⬜ | — | YM | Compile best quotes, ratings, and insights from TestFlight users |
| Competitive Analysis | ✅ | /consciousBiz/competitor-analysis-2026.md | SP | Comprehensive: Calm, Headspace, Insight Timer, Waking Up, Pattern |
| IP/Patent Documentation | ⬜ | — | YM | Content is public domain; proprietary layer is translations + retellings + AI |

**Action needed:** TestFlight MVP with Mixpanel analytics is the #1 priority. Ship the simplest version to TestFlight, recruit up to 5,000 users, and collect traction data before investor meetings. This data is the strongest item in the data room — "Here's what X thousand real users did on our app."

---

## 7. Content & IP

| Document | Status | Location | Owner | Notes |
|----------|--------|----------|-------|-------|
| Content Inventory | ✅ | Various | JW | 25,000 couplets (Masnavi), 2,000+ modern retellings, guided journeys |
| Content Licensing | ✅ | — | JW | Masnavi is public domain (13th century). No licensing required for source text. |
| Translation Rights | ⬜ | — | JW/YM | John's translations are original work — IP assignment to company needed |
| Third-Party Content Agreements | ❌ | — | — | No third-party content used (all original translations and retellings) |
| Trademark Application | ⬜ | — | YM | File for "Rumi App" and/or "Rumi Sanctuary" at USPTO. ~$250-$350 per class. |

---

## 8. Legal & Compliance

| Document | Status | Location | Owner | Action Needed |
|----------|--------|----------|-------|---------------|
| Terms of Service (draft) | ⬜ | — | YM/Legal | Required before App Store launch. Template services: Termly, iubenda (~$100/yr) |
| Privacy Policy (draft) | ⬜ | — | YM/Legal | Required before App Store launch. Must cover data collection, analytics, payments. |
| GDPR/CCPA Compliance Plan | ⬜ | — | TB/YM | If serving EU users: GDPR consent, data deletion, DPO. If serving CA users: CCPA notice. |
| Pending Litigation | ✅ | — | — | **None.** Clean record. |
| Material Contracts | ⬜ | — | YM | List any vendor contracts, API agreements, partnership MOUs |
| Insurance Policies | ⬜ | — | YM | D&O insurance: ~$2,000-$5,000/year. Obtain before or shortly after funding. |
| IP Assignment Agreements | ⬜ | — | YM/Legal | **CRITICAL.** See notes in section 5 and 7 above. |

---

## 9. Market & Customers

| Document | Status | Location | Owner | Notes |
|----------|--------|----------|-------|-------|
| Market Size Analysis | ✅ | Pitch deck slide 3 | SP/YM | $6.2B → $19B by 2034, 35.2% CAGR |
| Target Customer Profiles | ✅ | Various | YM | Spiritual seekers, Rumi book readers, meditation app users |
| **Ad Audience Discovery Results** | ⬜ | — | SP/YM | **Demographics, CPM, click-through by platform from $50-100 micro-ad tests on Pinterest/Instagram/Facebook** |
| **User Language Quotes** | ⬜ | — | YM | **How real TestFlight users describe the app in their own words — becomes marketing copy and investor pitch language** |
| Customer Testimonials | ⬜ | — | YM | From up to 5,000 TestFlight users — collect best quotes |
| NPS/Satisfaction Data | ⬜ | — | YM | Run NPS survey on TestFlight users |
| Waitlist Size | ⬜ | — | YM | Track from landing page signups |
| Category Positioning | ✅ | /consciousBiz/Play Bigger Book Strategy*.md | YM | "Spiritual Companion App" category defined |

**Action needed:** Ad audience discovery and user language quotes are new high-priority items. These turn the investor pitch from "Here's who we think our users are" into "Here's who our users actually are, in their own words."

---

## 10. Go-to-Market

| Document | Status | Location | Owner | Notes |
|----------|--------|----------|-------|-------|
| GTM Strategy | ✅ | Pitch deck slide 10 | YM | In deck |
| Marketing Plan (detailed) | ⬜ | — | YM | Expand deck GTM into month-by-month execution plan |
| PR/Press Target List | 🟡 | Various | YM | Publications identified: Well+Good, Psychology Today, Lion's Roar, Mindful Magazine, Tricycle |
| Partnership Pipeline | ⬜ | — | YM | Yoga studios, meditation centers, bookstores, spiritual communities |
| Acquisition Channel Analysis | 🟡 | /VAULT/02-weighted-sales-forecast.md | YM | CAC estimates and channel mix defined in sales forecast |

---

## Investor-Specific Requests

Track additional requests from specific investors as conversations progress:

| Investor | Request | Status | Due Date | Owner |
|----------|---------|--------|----------|-------|
| — | — | — | — | — |
| — | — | — | — | — |

---

## Data Room Setup

### Recommended Platform: **DocSend** or **Google Drive**

| Platform | Pros | Cons | Cost |
|----------|------|------|------|
| **DocSend** | Track who views what, watermarking, professional | $10/month | Best for active fundraising |
| **Google Drive** | Free, easy sharing, familiar | No tracking, less professional | $0 |
| **Notion** | Clean layout, easy updates | No view tracking | $0-$10/month |

**Recommendation:** Start with **Google Drive** (organized folder structure) for initial conversations. Move to **DocSend** when actively sending decks to multiple investors (view tracking is valuable for follow-up timing).

### Folder Structure
```
/Rumi App Data Room
  /1-Company Overview
    - Pitch Deck (PDF)
    - Executive Summary (PDF)
    - Product Demo Video (MP4/link)
    - Product Screenshots
  /2-Corporate Documents
    - Certificate of Incorporation
    - Bylaws
    - EIN confirmation
    - Board Resolutions
  /3-Cap Table & Equity
    - Cap Table (current)
    - Founder Agreements
    - Advisor Agreements
    - SAFE Template
  /4-Financial Documents
    - Cash Flow Forecast
    - Revenue Projections
    - Use of Funds
    - Burn Rate Analysis
  /5-Team & HR
    - Org Chart
    - Founder Bios
    - Job Descriptions
    - IP Assignment Agreements
  /6-Product & Technology
    - Product Roadmap
    - Technical Architecture
    - Beta Metrics
    - App Store Listing Draft
  /7-Content & IP
    - Content Inventory Summary
    - Trademark Status
  /8-Legal & Compliance
    - Terms of Service
    - Privacy Policy
    - Pending Litigation (None)
  /9-Market & Customers
    - Market Analysis
    - Competitive Analysis
    - Customer Testimonials
  /10-Go-to-Market
    - GTM Strategy
    - Marketing Plan
    - Partnership Pipeline
```

### Access Control
- View-only access for investors (no download for sensitive docs)
- Track document views and time spent (DocSend)
- Watermark sensitive financial documents with investor name
- **NDA required before access?** Recommended: No for deck/summary, Yes for financials/cap table

---

## Preparation Timeline

| Milestone | Target Date | Status | Owner |
|-----------|-------------|--------|-------|
| Incorporation complete (Delaware C-Corp) | Feb 15, 2026 | ⬜ | YM |
| EIN obtained | Feb 15, 2026 | ⬜ | YM |
| Founder equity split agreed | Feb 1, 2026 | ⬜ | Team |
| Founder agreements executed | Feb 28, 2026 | ⬜ | YM/Legal |
| IP assignment agreements signed | Feb 28, 2026 | ⬜ | All/Legal |
| 83(b) elections filed | Within 30 days of stock grant | ⬜ | All |
| Cap table formalized (Pulley) | Mar 1, 2026 | ⬜ | YM |
| Cash flow forecast finalized (Feb session w/ Ben) | Feb 28, 2026 | 🟡 | YM |
| Executive summary drafted | Feb 15, 2026 | ⬜ | YM |
| Product demo video recorded | Mar 15, 2026 | ⬜ | TB/SP |
| Data room platform selected | Mar 1, 2026 | ⬜ | YM |
| Core documents uploaded | Mar 15, 2026 | ⬜ | YM |
| Internal test (team reviews data room) | Mar 20, 2026 | ⬜ | Team |
| **Data room ready for investors** | **Apr 1, 2026** | ⬜ | YM |

---

## Readiness Scorecard

| Category | Items | Complete | % Ready |
|----------|-------|----------|---------|
| Company Overview | 6 | 2 | 33% |
| Corporate Documents | 7 | 0 | 0% |
| Cap Table & Equity | 6 | 0 | 0% |
| Financial Documents | 8 | 2 | 25% |
| Team & HR | 7 | 3 | 43% |
| Product & Technology | 7 | 2 | 29% |
| Content & IP | 5 | 2 | 40% |
| Legal & Compliance | 6 | 1 | 17% |
| Market & Customers | 8 | 3 | 38% |
| Go-to-Market | 5 | 1 | 20% |
| **TOTAL** | **65** | **16** | **25%** |

**Target: 80%+ ready by April 1, 2026.** The remaining 75% is primarily: validation data (TestFlight metrics, ad audience results, user language), incorporation, legal agreements, financial finalization, and product documentation. Validation items are highest-impact — they transform the investor pitch from plan to proof.

---

## Critical Path (Must Complete Before Any Investor Meeting)

### Validation (New — Highest Impact)
1. ⬜ **Ship TestFlight MVP** (daily verse + one journey + Mixpanel + paywall screen)
2. ⬜ **Recruit up to 5,000 TestFlight users** (friends, family, spiritual communities, waitlist)
3. ⬜ **Collect traction data** (DAU, retention, session length, paywall tap-through)
4. ⬜ **Run micro-ad tests** ($50-100 on Pinterest/Instagram/Facebook — audience discovery)
5. ⬜ **Capture user language quotes** (how real users describe the app)

### Legal (Required — Cannot Accept Investment Without These)
6. ⬜ **Incorporate** (Delaware C-Corp)
7. ⬜ **Agree on equity split** (founder discussion)
8. ⬜ **Execute founder agreements** (stock purchase, vesting)
9. ⬜ **Sign IP assignment agreements** (all founders)
10. ⬜ **File 83(b) elections** (within 30 days — IRS hard deadline)
11. ⬜ **Finalize cap table** (in Pulley or Carta)
12. ⬜ **Prepare SAFE document** (YC template)

### Materials
13. 🟡 **Finalize cash flow forecast** (Feb session with Ben)
14. ⬜ **Record product demo** (2-3 minute screen recording — can use TestFlight MVP)
15. ⬜ **Write executive summary** (1-page)

**Without items 6-12, you cannot legally accept investment.** Without items 1-5, you walk into investor meetings with a plan instead of proof. The strongest position is both: legal readiness AND traction data.

---

## Notes

- Review all documents for consistency before sharing with investors
- Remove sensitive personal information (SSNs, home addresses)
- Ensure financial projections match across deck, cash flow, and sales forecast
- Update data room as new documents are created
- Assign one person (recommend: YM) as data room owner responsible for maintenance
