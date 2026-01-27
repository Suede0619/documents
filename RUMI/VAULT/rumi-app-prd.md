# Product Requirements Document (PRD)
## The Rumi App: A Spiritual Wisdom Companion

**Version:** 2.0
**Date:** January 26, 2026
**Stakeholders:** John Wyrick (Co-Founder & CEO / Spiritual Director), Todd Bowden PhD (Co-Founder & CTO), Yalor Mewn (Co-Founder & COO / IPO), Stuart Paul (Co-Founder & CDO / IML)

---

## EXECUTIVE SUMMARY

### Project Overview
The Rumi App transforms the world's most-read poet into a living spiritual teacher through a mobile application that delivers daily wisdom, guided contemplative journeys, and complete access to the Masnavi's 25,000 verses. Unlike existing quote apps or meditation platforms, this product creates a structured spiritual path grounded in authentic source texts.

### Vision
A sanctuary, not a feed. A digital platform where ancient mystical poetry becomes accessible daily practice without dilution or commercialization.

### Current Status (January 2026)
- **Content:** Complete Masnavi (25,000 verses in Farsi + English), modern retellings, Shams of Tabriz corpus prepared
- **Product:** App architecture in progress for iOS (primary) and Android (secondary)
- **Strategy:** Validation-first — ship minimum TestFlight build, gather traction data, then raise and build full product (per advisor guidance, Jan 2026)
- **Fundraising:** $250K pre-seed via YC Post-Money SAFE at $4M post-money valuation cap
- **Phase 1 (Pitch Deck):** Complete — 16-slide investor-ready deck delivered
- **Entity:** [DECISION NEEDED — Delaware C-Corp recommended]
- **Advisor:** Ben Rewis — monthly strategic sessions through 2027 (no equity, no pay)

### Success Criteria
1. **Validation:** Ship TestFlight MVP, recruit up to 5,000 users, gather traction data (target: Feb-Mar 2026)
2. **Audience Discovery:** Run $50-100 micro-ad tests on Pinterest/Instagram/Facebook to define actual audience (target: Feb-Mar 2026)
3. **Fundraising:** Close $250K SAFE with traction data in hand (target: April-May 2026)
4. **iOS Launch:** Public release (target: September-October 2026)
5. **Android Launch:** Public release (target: Q4 2026-Q1 2027)
6. **Year 1 ARR:** $150K (Q4 2026), scaling to $800K+ (Q3 2027)
7. **Platform Expansion:** Proven model repeatable for Hafez, Shams of Tabriz, and other mystical poets

---

## TEAM

| Name | Role | Domain |
|------|------|--------|
| John Wyrick (Sheikh Firdousi) | Co-Founder & CEO / Spiritual Director | Vision, content, spiritual integrity |
| Todd Bowden, PhD | Co-Founder & CTO | App architecture, development, infrastructure |
| Yalor Mewn | Co-Founder & COO / IPO | Operations, fundraising, product priorities |
| Stuart Paul | Co-Founder & CDO / IML | Brand, UI/UX design, marketing, investor materials |
| Ben Rewis | Advisor | Strategic guidance, financial planning (monthly sessions) |

**Detailed role definitions:** See Doc 05 (Job Descriptions)
**RACI matrix:** See Doc 03
**Org chart:** See Doc 04

---

## BUSINESS MODEL

### Pricing

| Tier | Price | Annual Equivalent |
|------|-------|-------------------|
| Monthly | $9.99/month | $119.88/year |
| Annual | $96/year (20% discount) | $96/year |
| **Blended Average** | **~$100/year (~$8.33/month)** | Assumes 60% annual / 40% monthly mix |

### Freemium Strategy

**Free Tier:**
- Daily verse (Farsi + English translation + modern retelling)
- Basic contemplation mode
- [DECISION NEEDED — additional free features]

**Premium Tier ($9.99/month or $96/year):**
- All guided journeys
- Full Masnavi library access (25,000 verses)
- Shams of Tabriz teachings
- Offline mode
- [DECISION NEEDED — additional premium features]

### Revenue Projections (Moderate Scenario)

| Quarter | Total Users | Paid Subscribers | Conversion | Gross ARR |
|---------|-------------|------------------|------------|-----------|
| Q4 2026 | 300,000 | 1,500 | 0.5% | $150,000 |
| Q1 2027 | 412,500 | 2,681 | 0.65% | $268,100 |
| Q2 2027 | 520,000 | 4,420 | 0.85% | $442,000 |
| Q3 2027 | 691,000 | 8,016 | 1.16% | $801,600 |

**Detailed projections:** See Doc 01 (Cash Flow Forecast) and Doc 02 (Weighted Sales Forecast)

### Use of Funds ($250K)

| Category | Amount | % |
|----------|--------|---|
| Product Development | $75,000 | 30% |
| Marketing & User Acquisition | $100,000 | 40% |
| Team (New Hires) | $50,000 | 20% |
| Operations | $25,000 | 10% |

**Runway:** 14-16 months at moderate burn ($25,589/month)
**Break-even:** April-May 2027 (~500K users, ~4,000 paid subscribers)

---

## PHASE 0: VALIDATION (Before Full Build)

Per advisor feedback (Former Head of Product at Twitter, Jan 2026): "Don't build anything substantial till you can validate the market." The following phase precedes all product development described in this PRD.

### Validation Build (TestFlight MVP)

Ship the simplest possible version of the app to TestFlight:

1. **Daily verse** — Farsi original + English translation + modern retelling
2. **One guided journey** — A single complete journey experience
3. **Basic analytics** — Mixpanel integration tracking DAU, session length, screen time, return rate
4. **Paywall screen** — Feature comparison and subscription prompt (even without payment processing — measure tap intent)

This is not a beta. It is a learning tool. The goal is data, not polish.

### TestFlight Distribution

- **Target:** Up to 5,000 users
- **Sources:** Friends and family, spiritual communities, John's existing network, waitlist signups, public Rumi/poetry communities
- **Timeline:** Ship within weeks of CTO beginning focused build, not months

### Tracking and Metrics

Track everything from day one:

| Metric | What It Tells Us |
|--------|-----------------|
| DAU / MAU | Is anyone coming back? |
| Session length | Are they reading or bouncing? |
| Return rate (D1, D7, D30) | Is this a habit or a novelty? |
| Screen time per feature | What do people actually use? |
| Paywall tap-through rate | Will people pay for this? |
| Daily verse engagement (open, read time, save) | Is the core experience working? |
| Guided journey start rate / completion rate | Is the deeper content compelling? |

### Micro-Ad Audience Discovery

- **Spend:** $50-100 total across Pinterest, Instagram, and Facebook
- **Purpose:** Define the actual audience — demographics, interests, which platform converts
- **What to measure:** CPM, click-through rate, audience demographics of engaged users
- **Outcome:** Real audience data replaces founder assumptions about who the user is

### User Language Capture

- Collect how real users describe the app in their own words
- These descriptions become marketing copy, App Store text, and investor pitch language
- "The best slogans are ones that your users give you" (advisor)

### Validation Success Criteria

Before committing to full build and fundraising, the team should have answers to:

| Question | Minimum Signal |
|----------|---------------|
| Do users return after day 1? | D1 retention > 30% |
| Do users return after a week? | D7 retention > 15% |
| Will users pay? | Paywall tap-through > 5% |
| What features matter? | Screen time data shows clear preferences |
| Who is the audience? | Ad data defines demographics and platform |
| How do users describe the app? | 10+ organic user quotes collected |

These thresholds are starting points, not hard gates. The point is to have real data before spending $250K.

### What Validation Changes

Validation findings feed directly into:
- **Feature priorities** — Build what users actually engage with, cut what they ignore
- **Marketing language** — Use user words, not founder words
- **Audience targeting** — Spend $100K marketing budget on proven demographics, not assumptions
- **Investor pitch** — Walk into meetings with traction data ("X thousand users, Y% return daily, Z% tapped to pay")
- **Pricing confidence** — Real willingness-to-pay data vs. competitor benchmarking

---

## PRODUCT REQUIREMENTS

### Core Screens

**1. Onboarding Flow**
- Welcome / intro screens
- Account creation
- Personalization setup (interests, daily notification time)
- First verse experience

**2. Daily Wisdom (Primary Experience)**
- Home screen: today's verse
- Farsi original display
- English translation view
- Modern retelling (first-person narrative)
- Contemplation mode (distraction-free reading)
- Save to personal collection

**3. Guided Journeys**
- Journey library (browse by theme)
- Journey detail / preview
- Active journey experience (5 steps: verse, interpretation, reflection, breath, integration)
- Journey completion / reflection
- Journey history
- [DECISION NEEDED — number of journeys at launch]
- [DECISION NEEDED — text-only or audio narration? If audio, whose voice?]

**4. The Masnavi Library**
- Browse by book (6 books), chapter, or theme
- Search by keyword, emotion, or life situation
- Long-form reading view
- Bookmarking and highlighted passages
- Personal notes / reflections (premium)

**5. Settings & Profile**
- Notification preferences
- Language settings (English / Farsi toggle)
- Subscription management
- About / credits
- Support / FAQ

**6. Premium / Paywall Screens**
- Feature comparison (Free vs. Premium)
- Subscription tiers
- Payment flow (Apple / Google in-app purchase)
- Restore purchases

**7. Future Features**
- Shams of Tabriz section
- Hafez expansion
- Sharing (designed to avoid "feed" feeling)
- Offline mode indicator
- Apple Watch widget (daily verse)

### Daily Verse Curation
- [DECISION NEEDED — selection method: random (avoiding repetition), thematic calendar, or user personalization?]
- Decision owner: John (Spiritual Director)

### Content at Launch
- 25,000 Masnavi verses (Farsi + English + modern retellings)
- [DECISION NEEDED — number of guided journeys at launch]
- [DECISION NEEDED — Shams of Tabriz content at launch or post-launch?]

---

## USER FLOWS

### Primary Flow: Daily Verse
1. User opens app (or taps notification)
2. Sees today's verse (English translation)
3. Taps to read Farsi original
4. Taps to read modern retelling
5. Enters contemplation mode (optional)
6. Saves to personal collection (optional)
7. Returns tomorrow

### Secondary Flow: Guided Journey
1. User browses journey library
2. Selects journey by theme (e.g., "Surrender")
3. Previews journey structure
4. Begins journey
5. Progresses through 5 steps (verse, interpretation, reflection, breath, integration)
6. Completes journey
7. Optional: journal reflection

### Tertiary Flow: Masnavi Exploration
1. User searches for keyword (e.g., "love")
2. Views search results
3. Selects a verse
4. Reads in context (surrounding verses)
5. Bookmarks for later
6. Returns to search or browses by chapter

### Conversion Flow: Free to Premium
1. Free user encounters paywall (e.g., accessing a Guided Journey)
2. Sees feature comparison
3. Reviews subscription options
4. Subscribes (in-app purchase)
5. Unlocks premium content

---

## DESIGN SYSTEM

### Typography
- **Farsi text:** Proper Persian font (RTL support required)
- **Rumi quotes:** Elegant serif (Cormorant, Crimson, or EB Garamond)
- **Modern retellings:** Readable serif
- **UI text:** SF Pro (iOS), Roboto (Android)
- Clear hierarchy between spiritual content and UI chrome

### Color Palette
- Contemplative, calming tones
- Deep blues, soft golds, cream/ivory backgrounds
- Full dark mode support (essential for contemplative use)
- Avoid bright, aggressive, or overly saturated colors

### Iconography
- Custom icons for core features (Daily Wisdom, Journeys, Library)
- Simple, elegant, culturally appropriate
- Avoid overly decorative Islamic patterns (cultural sensitivity)

### Spacing & Layout
- Generous white space — "sanctuary, not a feed"
- Breathing room around text
- No clutter or noise

### Motion & Transitions
- Gentle, slow animations
- No jarring transitions
- Respect reduced motion accessibility setting

### Imagery
- Minimal photography
- Abstract / geometric patterns inspired by Persian art
- Consistent illustration style for Rumi
- No stock photos

---

## DESIGN PRINCIPLES: SANCTUARY

### 1. Depth Without Overwhelm
- Progressive disclosure of 25,000 verses
- Daily verse as curated entry point
- Guided journeys provide structure

### 2. Wisdom Without Dogma
- Rumi speaks for himself
- App facilitates, doesn't preach
- Respect user's own spiritual path

### 3. Beauty Without Distraction
- Design serves content, never competes
- No flashy effects or trendy gradients
- Silence and space are design elements

### 4. Guidance Without Gamification
- No streaks, badges, or points
- No social comparison or leaderboards
- No manipulative notifications
- Gentle nudges, never nagging

### 5. Authenticity Without Appropriation
- Respect Islamic and Sufi traditions
- Scholarly translations alongside modern retellings
- Avoid Orientalist tropes

### 6. Technology as Vessel
- AI supports, doesn't replace teaching
- Features enable contemplation, not consumption
- Offline-first where possible
- Privacy-respecting

---

## TECHNICAL REQUIREMENTS

### Platform Support
- **iOS:** Minimum iOS 15+ (primary platform, launch Q3 2026)
- **Android:** Minimum Android 10+ (secondary, launch Q4 2026)
- **Tablets:** iPad and Android tablet layouts (post-launch)

### Performance Targets
- App size: < 100MB initial download
- Launch time: < 2 seconds to usable state (cold start < 3 seconds)
- Scroll performance: 60fps
- Search latency: < 500ms across 25,000 verses
- Crash-free rate: 99.5%+

### Accessibility
- Full VoiceOver (iOS) and TalkBack (Android) support
- Dynamic Type support
- WCAG AA minimum (AAA for body text)
- Reduced motion support
- RTL support for Farsi

### Data & Privacy
- Minimal data collection — no surveillance analytics
- Offline-first: core content available without internet
- No social features at launch (no profiles, following, likes)
- Clear, honest privacy policy

### Content Management
- 25,000+ verse database (Farsi + English + retellings)
- [DECISION NEEDED — number of guided journeys at launch]
- Server-side journey updates (no app update required)
- Localization: English and Farsi minimum

---

## COMPETITIVE LANDSCAPE

### Direct Competitors

| App | Strength | Weakness |
|-----|----------|----------|
| Calm | Beautiful, minimal design | Generic, lacks depth |
| Headspace | Approachable, friendly | Too clinical, no spiritual dimension |
| Insight Timer | Massive library, powerful search | Overwhelming, no curation |
| Waking Up | Intellectual depth | Western philosophy focus |
| Pattern | Strong habit design | No spiritual tradition |
| Daily Rumi apps | Rumi-specific | Fragmented quotes, no context, ad-heavy |

### Our Differentiation
- **Only app with complete Masnavi** (25,000 verses)
- **Only app with scholarly + modern retellings**
- **Only app treating Rumi as teacher, not quote source**
- **Non-denominational** yet authentically rooted in Sufi tradition
- **John Wyrick's 40+ years** as spiritual teacher — moat no competitor can replicate

### Design Target
- Match Calm's beauty while exceeding its depth
- Match Bible app structure while remaining non-dogmatic
- Exceed Insight Timer's content while maintaining curation

---

## GO-TO-MARKET

### Phase 0: Audience Discovery (Feb-Mar 2026)

Before spending the $100K marketing budget, define the audience with real data:

- **Micro-ad tests:** $50-100 across Pinterest, Instagram, Facebook
- **Purpose:** Learn who clicks, who engages, which platform converts, what creative resonates
- **Output:** Audience demographics, platform preference, cost benchmarks — all inputs to the $100K plan
- **User language:** Capture how TestFlight users describe the app in their own words for marketing copy

### Phase 1: Full Acquisition (Post-Funding)

#### User Acquisition Channels

**Organic:**
- App Store Optimization (ASO): "Rumi," "Rumi poetry," "Masnavi," "spiritual companion"
- Content marketing and social sharing
- Word of mouth from TestFlight users (up to 5,000 by launch)

**Paid ($100K budget, informed by Phase 0 audience data, front-loaded around launches):**
- Social ads (Meta, TikTok) — allocate to platforms proven in micro-ad tests
- Apple Search Ads, Google UAC
- Podcast sponsorships

**PR:**
- Target publications: Well+Good, Psychology Today, Lion's Roar, Mindful Magazine, Tricycle
- Cultural moments: Sheb-i Arus (Dec 17), Nowruz (Mar 21), World Poetry Day (Mar 21)

**Partnerships:**
- Meditation centers, yoga studios, retreat centers
- Spiritual/poetry influencers
- Rumi book communities (Goodreads, Reddit)

### Growth Loops
- **Habit loop:** Daily verse → contemplation → return tomorrow
- **Depth loop:** Free verse → desire for journeys → subscribe
- **Platform loop:** Rumi → Hafez → Shams → ecosystem

### Retention Strategy
- Daily verse notification (gentle, not aggressive)
- Progressive depth discovery over time
- Continuous new guided journeys
- No churn tactics — genuine value only

**Detailed marketing plan:** See Doc 01 (marketing spend ramp) and Doc 02 (acquisition targets)

---

## SUCCESS METRICS

### Product KPIs

| Metric | Target | Frequency |
|--------|--------|-----------|
| Time to first verse | < 30 seconds from app open | Per release |
| App Store rating | 4.5+ stars | Weekly |
| Crash-free rate | 99.5%+ | Weekly |
| App load time | < 3 seconds cold start | Per release |
| Release cadence | Weekly Thursday releases, 80%+ on-time | Weekly |

### Growth KPIs

| Metric | Target | Frequency |
|--------|--------|-----------|
| D1 retention | 40% | Monthly |
| D7 retention | 20% | Monthly |
| D30 retention | 10% | Monthly |
| DAU growth | 5% week-over-week post-launch | Weekly |
| Session length | 5-10 minutes average | Weekly |
| NPS | 40+ (good), 50+ (excellent) | Quarterly |

### Revenue KPIs

| Metric | Target | Frequency |
|--------|--------|-----------|
| Free-to-paid conversion | 0.5% at launch → 1% at 12 months | Monthly |
| Blended CAC | $30-$50 | Monthly |
| LTV:CAC ratio | 4:1+ | Quarterly |
| Monthly subscriber churn | < 10% | Monthly |
| Annual subscriber retention | 65%+ | Annually |
| Guided Journey completion rate | 70%+ | Monthly |

**Detailed forecasts:** See Doc 02 (Weighted Sales Forecast)

---

## RISKS & MITIGATION

| Risk | Probability | Impact | Mitigation |
|------|------------|--------|------------|
| Content overwhelm (25,000 verses) | Medium | High | Curated daily verse as entry point; guided journeys for structure; progressive disclosure |
| Cultural appropriation perception | Low | High | John's 40+ year Sufi lineage; scholarly translations; Islamic/Sufi context preserved |
| Spiritual bypass (entertainment not transformation) | Medium | Medium | No gamification; design for contemplation not consumption; "sanctuary not feed" |
| Paywall disrupts contemplative experience | Medium | Medium | Generous free tier; premium as "going deeper" not "unlocking basics" |
| App Store approval delays | Low | Medium | Submit 6-8 weeks early; TestFlight beta as fallback |
| Marketing channel underperformance | Medium | Medium | Diversify channels early; monthly CAC ceiling; reallocate to best performers |
| Competitive response from Calm/Headspace | Low | Medium | First-mover with complete Masnavi; depth is the moat |
| Higher-than-expected churn | Medium | Medium | Focus on annual subscriptions; push notifications for daily engagement; guided journeys for retention |
| Platform dependency (Apple/Google) | Low | Medium | Build web-based subscription option as alternative; monitor policy changes |

---

## TIMELINE

```
VALIDATE             TRACTION DATA       SAFE CLOSE          BUILD & LAUNCH
(Feb-Mar 2026)       (~Mar-Apr 2026)     (~Apr-May 2026)     (~Jun-Oct 2026)
    |                    |                    |                    |
    ├─ TestFlight MVP    ├─ Usage metrics     ├─ Hire UI/UX       ├─ Full UI design
    ├─ Micro-ad tests    ├─ Audience data     ├─ Hire Marketing   ├─ Full build
    ├─ Recruit 5K users  ├─ User quotes       ├─ Todd full-time   ├─ Release train
    ├─ Mixpanel setup    ├─ Investor mtgs     ├─ Build begins     ├─ Beta groups
    ├─ Incorporation     |   (with data)      |                   ├─ App Store live
    ├─ Founder agmts     |                    |                   ├─ Marketing push
```

### Key Milestones

| Milestone | Target | Status |
|-----------|--------|--------|
| Pitch deck complete | Jan 2026 | Done |
| VAULT docs complete (Pass 1) | Jan 2026 | Done |
| **TestFlight MVP shipped** | **Feb 2026** | **Not started** |
| **Mixpanel analytics integrated** | **Feb 2026** | **Not started** |
| **Micro-ad audience tests ($50-100)** | **Feb-Mar 2026** | **Not started** |
| **Up to 5,000 TestFlight users recruited** | **Feb-Mar 2026** | **Not started** |
| Incorporation (Delaware C-Corp) | Feb 2026 | Not started |
| Founder agreements signed | Feb-Mar 2026 | Not started |
| **Validation data collected (DAU, retention, paywall intent)** | **Mar 2026** | **Not started** |
| Wireframes + hero mockups | Mar 2026 | Not started |
| Data room 80% ready (including traction data) | Mar-Apr 2026 | In progress |
| Investor meetings begin (with traction data) | Apr 2026 | Not started |
| SAFE closes ($250K) | Apr-May 2026 | Not started |
| Hire UI/UX Designer + Marketing Specialist | May-Jun 2026 | Not started |
| Full UI design system complete | Jun-Jul 2026 | Not started |
| Release train starts | ~Jun 2026 | Not started |
| iOS public launch | Sep-Oct 2026 | Not started |
| Android launch | Q4 2026-Q1 2027 | Not started |

---

## RELEASE TRAIN (Two Phases)

### Phase 0: Validation Cadence (Feb-Mar 2026)

Lightweight weekly builds focused on learning, not features. Ship TestFlight MVP, then iterate based on analytics and user behavior. No formal QA process — speed matters more than polish.

| Day | Activity | Owner |
|-----|----------|-------|
| Thursday | Weekly TestFlight build | Todd (CTO) |
| Monday | Review Mixpanel data + user feedback (30 min) | Yalor (PO) + Todd |

### Phase 1: Full Release Train (Starting ~Jun 2026)

| Day | Activity | Owner |
|-----|----------|-------|
| Thursday | Weekly release (MVP n+1) on TestFlight | Todd (CTO) |
| Friday | Beta testing (up to 5,000 users) | Yalor (PO) |
| Monday | Feedback integration (45 min) | Yalor (PO) |
| Tuesday | Product release discussion (1 hr, full team) | Yalor (PO) |
| Wednesday | Team QA (3 hrs) | Full team |

**Detailed schedule:** See Doc 06 (Release Train Schedule)
**PO authority:** See Doc 07 (Product Owner Charter)

---

## PLANNED HIRES (Post $250K Funding)

| Priority | Role | Reports To | Salary | Equity | Timeline |
|----------|------|-----------|--------|--------|----------|
| 1 | UI/UX Designer | Stuart (CDO) | $30K-$45K | 0.50-1.00% | Q3 2026 |
| 2 | Marketing Specialist | Yalor (COO) | $30K-$42K | 0.50-1.00% | Q3 2026 |
| 3 | Android Developer | Todd (CTO) | $90K-$130K | 0.75-1.50% | Q4 2026 (Series A) |

**Detailed descriptions:** See Doc 05 (Job Descriptions)
**Org structure:** See Doc 04 (Organizational Chart)

---

## OPEN DECISIONS

### Critical (Resolve Before Investor Meetings)

| # | Decision | Owner | Recommendation |
|---|----------|-------|----------------|
| 1 | Entity type: C-Corp or LLC? | Team | C-Corp (required for SAFE) |
| 2 | State of incorporation | Team | Delaware |
| 3 | Founder equity split (JW, TB, YM, SP %) | All | See Doc 09 for benchmark patterns |
| 4 | Employee option pool size | Team | 15% |
| 5 | Cash on hand (current bank balance) | YM | Required for cash flow forecast |
| 6 | Monthly founder stipends | Team | $8K-$16K/month total |

### High (Resolve Before Launch)

| # | Decision | Owner | Recommendation |
|---|----------|-------|----------------|
| 7 | Vesting start dates | Team | Date of incorporation or work start |
| 8 | Acceleration terms | Team | Double trigger (25% single, 100% double) |
| 9 | Ben Rewis advisor equity | Team | 0.50-1.00% with 2yr vesting |
| 10 | SAFE discount | YM | 20% standard or cap-only |
| 11 | Time commitment per founder | Each | Full-time / part-time / hrs per week |
| 12 | John's content IP: assign or license? | JW/Team | Assign (investors require company ownership) |
| 13 | Number of guided journeys at launch | JW/SP | [NO RECOMMENDATION YET] |
| 14 | Free vs. premium feature breakdown | Team | [NO RECOMMENDATION YET] |
| 15 | Daily verse selection method | JW | Random, calendar, or personalization? |
| 16 | Audio narration for journeys? | JW | If yes, whose voice? |

### Medium (Resolve Before Launch)

| # | Decision | Owner |
|---|----------|-------|
| 17 | Release train start date | Team |
| 18 | Meeting times (PT) | Team |
| 19 | Slack channel names | Team |
| 20 | Beta group recruitment source | YM |
| 21 | Non-compete terms | Team |
| 22 | Board composition | Team |
| 23 | Data room platform | YM |
| 24 | Trademark filing ("Rumi App" / "Rumi Sanctuary") | YM |

**Full decision tracker:** See Doc 00 (Data Needed Summary)

---

## RELATED VAULT DOCUMENTS

| Doc | Title | Purpose |
|-----|-------|---------|
| 00 | Data Needed Summary | Master list of all remaining decisions |
| 01 | Cash Flow Forecast | 24-month financial projections |
| 02 | Weighted Sales Forecast | Revenue projections by scenario |
| 03 | RACI Matrix | Responsibility assignments |
| 04 | Organizational Chart | Team structure (current + projected) |
| 05 | Job Descriptions | All role definitions and planned hires |
| 06 | Release Train Schedule | Weekly development cadence |
| 07 | Product Owner Charter | PO authority and decision-making |
| 08 | Investor Data Room Checklist | Due diligence readiness (63 items) |
| 09 | Cap Table | Equity structure and SAFE terms |
| 10 | Team Governance | Founder agreement framework |

---

## BRAND IDENTITY

### Positioning
"The only spiritual companion that treats Rumi as a teacher, not a quote database."

### Brand Attributes
- **Authentic** — Scholarly source texts, not watered-down interpretations
- **Contemplative** — Designed for stillness, not scrolling
- **Deep** — 25,000 verses, not 100 quotes
- **Accessible** — Modern retellings make ancient wisdom relatable
- **Respectful** — Honors tradition without dogma

### Tone of Voice

**In the App:**
- Gentle, not pushy
- Poetic, not flowery
- Invitational, not prescriptive
- Wise, not preachy

**In Marketing:**
- Confident, not apologetic
- Clear, not vague
- Substantive, not shallow
- Inspirational, not manipulative

### Examples
- "A verse waits for you when you're ready." (not "Unlock your best self with Rumi!")
- "Rumi as a living teacher — daily, authentic, deeply human." (not "Join 10,000 users on their journey!")

**Note:** These are starting positions. Per validation-first strategy, brand language should be tested against real user language captured during Phase 0. The best slogans come from users, not founders.

---

## DOCUMENT HISTORY

| Version | Date | Changes |
|---------|------|---------|
| 1.0 | December 29, 2024 | Initial PRD — Phase 1 (deck) and Phase 2 (app) scoped |
| 2.0 | January 26, 2026 | Major revision: aligned with VAULT system, updated team titles (all Co-Founder), filled in confirmed decisions (pricing, funding, timeline, forecasts), removed completed Phase 1 workflow, added release train and hire plan, updated competitive landscape, consolidated open decisions with Doc 00 |
| 2.1 | January 27, 2026 | Validation-first strategy: added Phase 0 (TestFlight MVP, micro-ad audience discovery, user language capture), shifted timeline (validate → traction data → raise → build), updated go-to-market with audience discovery phase, updated release train to two phases, updated success criteria and milestones |

---

## SIGN-OFF

| Name | Role | Signature | Date |
|------|------|-----------|------|
| John Wyrick | Co-Founder & CEO | _____________ | _____ |
| Todd Bowden | Co-Founder & CTO | _____________ | _____ |
| Yalor Mewn | Co-Founder & COO | _____________ | _____ |
| Stuart Paul | Co-Founder & CDO | _____________ | _____ |
