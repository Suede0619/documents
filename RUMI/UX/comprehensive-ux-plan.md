# Comprehensive UX Plan for The Rumi App
## Step-by-Step Implementation Guide

**Version:** 1.0
**Date:** January 12, 2026
**Prepared for:** Stuart Paul (Suede), John Wyrick, Todd Bowden, Yalor Moon
**Purpose:** End-to-end UX strategy from research through launch and optimization

---

## Table of Contents

1. [Executive Summary](#executive-summary)
2. [Phase 0: Foundation & Research](#phase-0-foundation--research)
3. [Phase 1: Information Architecture](#phase-1-information-architecture)
4. [Phase 2: Wireframing & User Flows](#phase-2-wireframing--user-flows)
5. [Phase 3: Visual Design System](#phase-3-visual-design-system)
6. [Phase 4: High-Fidelity Design](#phase-4-high-fidelity-design)
7. [Phase 5: Prototyping & Testing](#phase-5-prototyping--testing)
8. [Phase 6: Developer Handoff](#phase-6-developer-handoff)
9. [Phase 7: Post-Launch Optimization](#phase-7-post-launch-optimization)
10. [Appendix: Templates & Resources](#appendix-templates--resources)

---

## Executive Summary

### The Challenge
Design a spiritual companion app that treats Rumi as a living teacher, balancing authentic Sufi tradition with modern accessibility, scholarly depth with everyday usability, and conscious business principles with sustainable monetization.

### The Opportunity
- **Market Gap**: No competitor offers complete classical mystical text (25,000 verses) + structured spiritual teaching + modern retellings
- **Built-In Demand**: Rumi = world's most-read poet, #1 U.S. bestseller, 800 years of brand equity
- **Declining Incumbents**: Calm (-20% downloads), Headspace (-500K subscribers) create market share opportunity
- **Category Creation**: First true "Spiritual Companion App" per Play Bigger framework

### Success Criteria
1. **Activation**: 60%+ onboarding completion, <30 seconds to first verse
2. **Engagement**: 40% D1, 20% D7, 10% D30 retention (meditation app benchmarks)
3. **Monetization**: 5-10% free-to-paid conversion Year 1, 10-15% at scale
4. **Quality**: 4.5+ App Store rating, WCAG AA accessibility compliance
5. **Conscious Design**: No dark patterns, no gamification, "sanctuary not feed" principle maintained

### UX Philosophy
- **For Maya (Depth Seeker)**: Beauty + depth + contemplative design
- **For Robert (Poetry Lover)**: Text + scholarship + simple navigation
- **For Aisha (Spiritual Migrant)**: Authenticity + accessibility + BIPOC representation
- **For David (Knowledge Seeker)**: Search + sources + annotation tools
- **For Sarah (Life Navigator)**: Gentleness + solace + no pressure

**Design Principle**: Serve all five personas without compromising any.

---

## Phase 0: Foundation & Research

### Duration: 2-3 weeks (concurrent with fundraising deck completion)

### Step 0.1: Competitive UX Audit

**What to Do:**
1. Download and use all 5 competitors for 7-14 days:
   - Calm
   - Headspace
   - Insight Timer
   - Waking Up
   - Pattern (for comparison, different category)

2. For each app, document:
   - **Onboarding flow** (screenshots of every screen, time to complete)
   - **Information architecture** (sitemap, navigation structure)
   - **Core screens** (home, content detail, library/browse, settings)
   - **Paywall experience** (when shown, messaging, pricing, trial offers)
   - **Design patterns** (typography, color, spacing, motion)
   - **What works** (3-5 strengths)
   - **What doesn't** (3-5 weaknesses)

**Deliverable:** Competitive UX Audit Report (Figma file or PDF)
- Side-by-side screen comparisons
- Feature matrix
- Design pattern library
- Opportunities for differentiation

**Tools:**
- Figma (for organizing screenshots)
- Notion or Google Doc (for notes)
- Screen recording software (QuickTime on Mac, built-in on iOS)

---

### Step 0.2: Content Audit & Mapping

**What to Do:**
1. Work with John to inventory all Rumi content:
   - **Daily Verse Pool**: How many verses total? How are they curated/selected?
   - **Modern Retellings**: How many complete? How many in progress?
   - **Guided Journeys**: How many exist? What themes? What structure (5 steps confirmed)?
   - **Masnavi Structure**: 6 books, how many chapters per book? Tagging/metadata system?
   - **Shams of Tabriz**: What content is ready? When will it be integrated?

2. Create content inventory spreadsheet:

| Content Type | Quantity | Status | Length | Metadata/Tags | Notes |
|--------------|----------|--------|--------|---------------|-------|
| Daily Verses | 365? | Complete | 50-200 words | Theme, emotion, book/chapter | How selected? Random? Seasonal? |
| Modern Retellings | ? | ? | ? | Linked to verses | Who wrote? John? |
| Guided Journeys | 10? | ? | 5 minutes | Surrender, longing, grief, love, etc. | Audio or text only? |
| Masnavi Books | 6 | Complete | 25,000 verses total | Book, chapter, verse # | How searchable? |
| Shams Corpus | ? | Prepared | ? | ? | Launch timeline? |

**Deliverable:** Content Inventory & Metadata Map
- Spreadsheet with all content
- Tagging taxonomy (themes, emotions, life situations, book/chapter)
- Content prioritization (what's MVP, what's Phase 2)

**Why This Matters:** You can't design navigation/search without knowing what content exists and how it's organized.

---

### Step 0.3: User Research (If Budget Allows)

**What to Do:**
1. Recruit 10-15 participants matching persona profiles:
   - 3-4 Depth Seekers (Maya)
   - 2-3 Poetry Lovers (Robert)
   - 2-3 Spiritual Migrants (Aisha)
   - 1-2 Knowledge Seekers (David)
   - 1-2 Life Navigators (Sarah)

2. Conduct 30-45 minute interviews (remote via Zoom):
   - **Current behavior**: What apps do you use for spirituality/meditation? What frustrates you?
   - **Rumi relationship**: How do you engage with Rumi now? (Books? Instagram? Not at all?)
   - **Pain points**: What's missing in your spiritual practice?
   - **Feature validation**: Show paper sketches of key screens, get reactions
   - **Pricing sensitivity**: What would you pay for this app? What's too much?

3. Synthesize findings:
   - Affinity mapping (group similar pain points/needs)
   - Validate or refine personas
   - Identify must-have vs. nice-to-have features

**Deliverable:** User Research Report
- Interview transcripts (or key quotes)
- Affinity map (Miro or FigJam)
- Updated personas (if research reveals new insights)
- Feature prioritization matrix

**If No Budget:**
- Survey friends/family who read poetry or use meditation apps (10-15 people)
- Post in relevant subreddits (r/meditation, r/poetry, r/Sufism) asking for feedback
- Analyze App Store reviews of Calm, Headspace, Insight Timer for user complaints

---

### Step 0.4: Define Success Metrics & KPIs

**What to Do:**
1. Work with Yalor/John/Todd to align on measurable goals:

**Activation Metrics:**
- Onboarding completion rate: **Target 60%+**
- Time to first verse: **Target <30 seconds from app open**
- % users who read daily verse on Day 1: **Target 80%+**

**Engagement Metrics:**
- D1 (Day 1) retention: **Target 40%** (meditation app benchmark)
- D7 (Day 7) retention: **Target 20%**
- D30 (Day 30) retention: **Target 10%**
- Average session length: **Target 5-10 minutes** (contemplation, not scrolling)
- Daily Active Users (DAU): **Target [X]% of monthly users**
- Guided journey completion rate: **Target 60%+**

**Monetization Metrics:**
- Free-to-paid conversion: **Target 5-10% in Year 1, 10-15% at scale**
- Paywall conversion rate: **Target 15-25%** (users who see paywall who convert)
- Monthly vs. Annual subscription mix: **Target 70% annual** (better cash flow)
- LTV:CAC ratio: **Target 3:1 minimum**
- Monthly churn rate: **Target <5%**

**Quality Metrics:**
- App Store rating: **Target 4.5+ stars**
- Critical bugs/crashes: **<1% of sessions**
- Support ticket volume: **<5% of active users per month**
- Accessibility score: **WCAG AA compliance**

2. Create metrics dashboard plan:
   - What analytics tools? (Mixpanel, Amplitude, Firebase?)
   - What events to track? (app_open, verse_read, journey_started, paywall_shown, subscription_completed, etc.)
   - What cohorts to segment? (organic vs. paid, iOS vs. Android, persona type if self-identified)

**Deliverable:** Metrics & Analytics Plan
- KPI targets documented
- Event tracking specification for developers
- Dashboard wireframes (what reports do you need to see?)

---

## Phase 1: Information Architecture

### Duration: 1-2 weeks

### Step 1.1: Create User Flows

**What to Do:**
Map the critical user journeys from entry to goal completion.

**Primary User Flow: New User to First Verse**
```
1. App Store → Download → Install
2. App Open (first time)
3. Splash Screen (Rumi quote + loading)
4. Onboarding Screen 1: Welcome (value prop)
5. Onboarding Screen 2: How it works (daily verse, journeys, library)
6. Onboarding Screen 3: Notification permission request (optional)
7. Onboarding Screen 4: Account creation (email/Apple/Google)
8. Home Screen: Today's Verse (immediately visible)
9. User reads verse (Farsi, English, modern retelling)
10. Success! User has experienced core value.
```

**Decision Points to Map:**
- Skip onboarding? (Allow user to skip to verse?)
- Notification permission: When to ask? (iOS best practice: not on first screen)
- Account creation: Required or optional? (Can user browse first, then create account when hitting paywall?)

**Secondary User Flows to Map:**
- **Free User to Paid Subscriber**: App open → Daily verse (free) → Try Guided Journey → Paywall → See pricing → Trial or purchase → Success
- **Library Exploration**: Home → Library tab → Browse by book/chapter/theme → Search by keyword → Read verse in context → Bookmark → Save to collection
- **Guided Journey Experience**: Home → Journeys tab → Browse themes → Select journey → Step 1 (verse) → Step 2 (interpretation) → Step 3 (reflection) → Step 4 (breath/awareness) → Step 5 (integration) → Completion screen
- **Return User Daily Habit**: App open → Notification tap → Read today's verse → Contemplate → Close app (quick 3-5 min session)

**Tool:** Use Figjam, Miro, or Whimsical to create flowcharts.

**Deliverable:** User Flow Diagrams (PDF or Figma)
- 5-7 critical flows mapped
- Decision points identified
- Error states documented (what if server fails? what if no internet?)

---

### Step 1.2: Design Sitemap & Navigation Structure

**What to Do:**
Define the entire app's information architecture.

**MVP 1 Sitemap:**

```
ROOT (3 Bottom Tabs)
├── Home (Today's Verse)
│   ├── Daily Verse Detail
│   │   ├── Farsi (original text)
│   │   ├── English Translation (scholarly)
│   │   ├── Modern Retelling / Reimagining (first-person, accessible)
│   │   └── Contemplation Mode (fullscreen, distraction-free)
│   └── [Upsell card: Try a Guided Journey]
│
├── Journeys
│   ├── Journey Library (5-6 journeys at launch)
│   ├── Journey Detail/Preview
│   ├── Active Journey (5-step experience)
│   │   ├── Step 1: Verse
│   │   ├── Step 2: Interpretation
│   │   ├── Step 3: Reflection Prompt
│   │   ├── Step 4: Breath/Awareness Cue
│   │   └── Step 5: Integration/Closing
│   └── Completed Journeys (history)
│
└── Profile
    ├── Subscription (manage, cancel, restore purchases)
    ├── Settings
    │   ├── Notifications (daily verse time, preferences)
    │   ├── Appearance (dark mode)
    │   └── Account (email, password, delete account)
    ├── About (Rumi's story, Sufi tradition, credits)
    ├── Support/FAQ
    └── Privacy Policy / Terms

**Paywall Modal** (triggered contextually)
├── Feature Comparison (Free vs. Premium)
├── Pricing Plans (Monthly $8.88, Annual $84)
├── Free Trial (7 days)
└── Purchase/Subscribe
```

**Phase 2 Features (Post-MVP 1):**
```
├── Library (The Masnavi) - PHASE 2
│   ├── Browse by Book (Books 1-6)
│   ├── Browse by Chapter
│   ├── Browse by Theme
│   ├── Search (keyword, full-text)
│   └── Verse Detail with context
│
├── Save to Collections - PHASE 2
├── Chapter of Poetry (extended passages) - PHASE 2
└── Audio narration - PHASE 2
```

**Navigation Structure Decision:**

**Option A: Bottom Tab Navigation (Recommended for MVP 1)**
```
┌─────────────────────────────────┐
│                                 │
│         SCREEN CONTENT          │
│                                 │
├─────────────────────────────────┤
│   [Home] [Journeys] [Profile]   │
└─────────────────────────────────┘
```
- **Pros**: iOS/Android standard, familiar, easy thumb access, clean 3-tab structure
- **Cons**: None significant for MVP 1 scope

**Option B: Gesture-Based Navigation (Recommended for Robert, David)**
```
Swipe left/right between sections
Minimal chrome, text-first
```
- **Pros**: Immersive reading experience, mimics book-turning
- **Cons**: Discoverability issues for less tech-savvy users

**Recommendation:** Start with **Option A (Bottom Tabs)** for MVP, test gesture navigation in Phase 2.

**Deliverable:** Sitemap Diagram + Navigation Specification
- Full sitemap (every screen mapped)
- Navigation structure documented
- Rationale for tab labels and organization

---

### Step 1.3: Feature Prioritization (MVP vs. Phase 2)

**What to Do:**
Work with team to decide what ships at launch vs. what comes later.

**MVP (Must-Have for Launch):**
- ✅ Daily Verse (Farsi, English, Modern Retelling)
- ✅ Contemplation Mode (fullscreen reading)
- ✅ Save to Personal Collection
- ✅ Guided Journeys (10-15 journeys minimum)
- ✅ Complete Masnavi Library (25,000 verses)
- ✅ Browse by Book/Chapter
- ✅ Search by Keyword
- ✅ Freemium Paywall (one pricing screen, clear conversion path)
- ✅ Account Creation (email + Apple/Google Sign-In)
- ✅ Offline Mode (cached daily verses + downloaded library)
- ✅ Dark Mode
- ✅ Notifications (daily verse reminder, gentle)

**Phase 2 (Post-Launch, 3-6 months):**
- 🔲 Browse by Theme/Emotion (requires editorial tagging)
- 🔲 Audio Narration (requires recording 100+ hours of content)
- 🔲 Annotation/Note-Taking (requires backend for user-generated content)
- 🔲 Shams of Tabriz Content (separate section or integrated?)
- 🔲 Community Features (carefully designed, no social feed)
- 🔲 Apple Watch Companion (daily verse on wrist)
- 🔲 Widget (daily verse on iOS/Android home screen)
- 🔲 Premium+ Tier (if standard premium proves successful)

**Decision Criteria:**
1. **Does it serve core value prop?** (Rumi as living teacher, daily wisdom)
2. **Does it differentiate from competitors?** (Complete Masnavi = yes, generic meditation timer = no)
3. **Can it be built in 3-4 months?** (MVP timeline constraint)
4. **Does it support conscious business model?** (No dark patterns, no manipulation)

**Deliverable:** Feature Roadmap (Spreadsheet or Gantt chart)
- MVP features with priority ranking (P0, P1, P2)
- Phase 2 features with estimated timeline
- Dependencies mapped (e.g., audio requires content creation first)

---

## Phase 2: Wireframing & User Flows

### Duration: 2-3 weeks

### Step 2.1: Low-Fidelity Wireframes (Paper or Digital Sketches)

**What to Do:**
Sketch every screen in the sitemap at low fidelity to test structure before adding visual design.

**Screens to Wireframe (Minimum 30-40 screens for MVP):**

**Onboarding (4-5 screens):**
1. Splash Screen (Rumi quote while loading)
2. Welcome Screen (value prop, "A sanctuary, not a feed")
3. How It Works (Daily verse + Journeys + Library, 3 panels)
4. Notification Permission (iOS native prompt)
5. Account Creation (email/Apple/Google options)

**Home / Daily Verse (5-7 screens):**
1. Home Screen (Today's verse preview, tap to read)
2. Verse Detail - Farsi View
3. Verse Detail - English Translation View
4. Verse Detail - Modern Retelling View
5. Contemplation Mode (fullscreen, minimal UI)
6. Save to Collection (confirmation)
7. Upsell Card (Try Guided Journey) → links to Journeys tab

**Guided Journeys (6-8 screens):**
1. Journey Library (grid or list of themes)
2. Journey Detail/Preview (what to expect, 5 steps listed)
3. Journey Step 1 (Verse)
4. Journey Step 2 (Interpretation)
5. Journey Step 3 (Reflection Prompt)
6. Journey Step 4 (Breath/Awareness Cue)
7. Journey Step 5 (Integration/Closing)
8. Journey Completion Screen (gentle affirmation, no "streak" pressure)

**Library / Masnavi (8-10 screens):**
1. Library Home (tabs: Books, Chapters, Themes, Search)
2. Browse by Book (6 books listed)
3. Book Detail (chapters listed)
4. Chapter Detail (verses listed in reading order)
5. Browse by Theme (Love, Grief, Joy, Surrender, etc.)
6. Search Results (keyword search, relevance-ranked)
7. Verse Detail in Library (Farsi, English, Modern, with context)
8. Surrounding Verses (read in sequence, book-like pagination)
9. My Collections (saved verses organized by user)
10. Empty State (no saved verses yet, CTA to explore)

**Paywall (3-4 screens):**
1. Soft Paywall (triggered when user taps locked feature)
2. Feature Comparison (Free vs. Premium, clear value)
3. Pricing Plans (Monthly $9.99, Annual $69.99, trial highlighted)
4. Purchase/Subscription Confirmation (Apple/Google payment flow)

**Profile/Settings (5-6 screens):**
1. Profile Home (account info, subscription status)
2. Subscription Management (plan, billing, cancel)
3. Notification Settings (daily verse time picker, on/off toggles)
4. Language/Accessibility (font size, dark mode, Farsi UI toggle)
5. About/Credits (Rumi's story, team, translators, Sufi tradition context)
6. Support/FAQ (how to use app, troubleshooting)

**Tool:** Use Balsamiq, Whimsical, Figma (with wireframe kit), or literally pen and paper.

**Deliverable:** Low-Fidelity Wireframe Set (PDF or Figma file)
- 30-40 screens wireframed
- Annotations explaining interactions
- No color, no typography, just boxes and labels

---

### Step 2.2: User Flow Annotation & Interaction Design

**What to Do:**
Overlay interaction details onto wireframes.

**Annotations to Add:**
- **Tap targets**: What happens when user taps this button?
- **Swipe gestures**: Can user swipe between Farsi/English/Modern views?
- **Scrolling behavior**: Fixed header? Infinite scroll? Pagination?
- **Transitions**: Slide left? Fade? Modal overlay?
- **Error states**: No internet? Server error? Empty search results?
- **Loading states**: Spinner? Skeleton screens? "Loading verse..." message?
- **Success states**: "Verse saved!" toast notification? Checkmark animation?

**Example Annotation (Verse Detail Screen):**
```
┌───────────────────────────┐
│ [<Back]    Today's Verse  │  ← Fixed header, tap back to return to Home
├───────────────────────────┤
│                           │
│   Farsi text here         │  ← Default view on open
│   (beautiful serif font)  │  ← Tap to toggle English/Modern views (tabs? swipe?)
│                           │
│  [English] [Modern]       │  ← Tabs or swipe-able panels?
│                           │
├───────────────────────────┤
│ [Save]  [Contemplate]     │  ← Actions: Save to collection, enter fullscreen mode
└───────────────────────────┘

INTERACTIONS:
- Tap "English" → transition to English translation (0.3s fade)
- Tap "Modern" → transition to Modern retelling (0.3s fade)
- Swipe left/right → navigate between views (alternative to tabs)
- Tap "Contemplate" → enter fullscreen reading mode (hide nav, just text + close X)
- Tap "Save" → confirm with toast "Saved to collection" (2s auto-dismiss)
```

**Deliverable:** Annotated Wireframes (Figma file or PDF with notes)
- Every interaction documented
- Edge cases thought through
- Developer can understand what to build

---

### Step 2.3: Stakeholder Review & Iteration

**What to Do:**
Present wireframes to John, Todd, Yalor for feedback.

**Review Checklist:**
- [ ] Does this serve all 5 personas?
- [ ] Is the daily verse easy to access (Maya's priority)?
- [ ] Is the library navigable (Robert's priority)?
- [ ] Is the design gentle and non-manipulative (Sarah's need)?
- [ ] Is search powerful enough (David's need)?
- [ ] Does it feel authentic and non-corporate (Aisha's concern)?
- [ ] Is the paywall natural, not disruptive (conscious business principle)?
- [ ] Are there any dark patterns? (Remove immediately)

**Iteration:**
- Incorporate feedback
- Revise wireframes
- Re-present for final sign-off

**Deliverable:** Approved Wireframe Set v2.0
- Stakeholder feedback incorporated
- Ready for visual design

---

## Phase 3: Visual Design System

### Duration: 2-3 weeks

### Step 3.1: Define Visual Design Principles

**What to Do:**
Articulate the visual language before making design decisions.

**Visual Design Principles for The Rumi App:**

1. **Sanctuary Over Feed**
   - Generous white space (never cramped)
   - Calm, muted colors (no neon, no aggressive saturation)
   - Slow, gentle animations (no jarring transitions)
   - Silent and space are design elements

2. **Depth Without Overwhelm**
   - Progressive disclosure (don't show all 25,000 verses at once)
   - Clear hierarchy (daily verse is hero, library is secondary)
   - Breathing room around text (poetry needs space)

3. **Beauty Without Distraction**
   - Design serves content, never competes with it
   - Timeless aesthetic (no trendy gradients that will age poorly)
   - Elegant simplicity (less is more)

4. **Authenticity Without Appropriation**
   - Persian art-inspired patterns (subtle, not literal arabesques)
   - Islamic geometric patterns (respectfully adapted, not commodified)
   - Avoid Orientalist tropes (no "exotic" clichés)

5. **Accessibility as Baseline, Not Addition**
   - WCAG AA compliance minimum
   - Readable text (16pt+ body, high contrast)
   - Support for dynamic type (iOS/Android user text size preferences)
   - Dark mode as first-class experience (not afterthought)

**Deliverable:** Visual Design Principles Document (1-page PDF)
- Principles written clearly
- Example images showing "do" and "don't"

---

### Step 3.2: Color Palette

**What to Do:**
Develop a contemplative, spiritual color system.

**Recommended Color Strategy:**

**Primary Colors (Spiritual Foundation):**
- **Deep Blue (Night Sky)**: #1A2B4A - Trust, depth, contemplation, Islamic art association
- **Soft Gold (Sacred Light)**: #D4A574 - Illumination, wisdom, Persian miniature painting reference
- **Cream/Ivory (Parchment)**: #F5F1E8 - Warmth, readability, ancient manuscript feel

**Secondary Colors (Functional Accents):**
- **Teal (Water, Flow)**: #4A7C7E - Wayfinding, links, secondary actions
- **Warm Gray (Stone)**: #6B6560 - Secondary text, borders, subtle UI elements

**Semantic Colors (System Feedback):**
- **Success**: #5A8F7B - Muted green, not bright "app green"
- **Warning**: #C89B5E - Warm amber, not alarming orange
- **Error**: #A25B5B - Muted red, serious but not harsh

**Background Colors:**
- **Light Mode Background**: #FDFCFB (off-white, easier on eyes than pure white)
- **Dark Mode Background**: #0D1117 (very dark blue-gray, not pure black)

**Text Colors:**
- **Light Mode Text**: #1A1A1A (near-black, high contrast)
- **Light Mode Secondary Text**: #5A5A5A (medium gray)
- **Dark Mode Text**: #E8E6E3 (off-white)
- **Dark Mode Secondary Text**: #A0A0A0 (medium gray)

**Contrast Check:**
- All text/background combinations must pass WCAG AA (4.5:1 for body, 3:1 for large text)
- Use WebAIM Contrast Checker or Figma plugins

**Deliverable:** Color Palette Specification (Figma file + style guide)
- Named color tokens (for developers)
- Hex codes, RGB values
- Usage guidelines (when to use gold vs. teal)
- Accessibility contrast ratios documented

---

### Step 3.3: Typography System

**What to Do:**
Select fonts and create hierarchy.

**Font Selection Strategy:**

**For Rumi's Words (Serif, Poetic):**
- **Primary Choice**: Cormorant Garamond (free, elegant, literary)
- **Alternative**: Crimson Text, EB Garamond, Libre Baskerville
- **Reasoning**: Serif fonts convey dignity, timelessness, spiritual weight

**For UI Text (Sans-Serif, Clarity):**
- **iOS**: SF Pro (system font, optimized for iOS)
- **Android**: Roboto (system font, optimized for Android)
- **Cross-Platform**: Inter or Source Sans Pro (if you want consistency)
- **Reasoning**: Sans-serif for clarity, modern feel, UI chrome

**For Farsi Text:**
- **Farsi Font**: Nazanin, Geeza Pro, or IRANSans (readable, Persian-optimized)
- **Critical**: Test Farsi rendering early with John (right-to-left layout)

**Typography Scale (Mobile-Optimized):**

```
H1 (Screen Titles): 28pt, Semibold, Sans-Serif
H2 (Section Headers): 22pt, Semibold, Sans-Serif
H3 (Subsections): 18pt, Medium, Sans-Serif
Body Text (UI): 16pt, Regular, Sans-Serif
Caption (Metadata): 14pt, Regular, Sans-Serif

Rumi Quote (Large): 24pt, Regular, Serif, 1.6 line-height
Rumi Body (Verse Detail): 18pt, Regular, Serif, 1.8 line-height
Farsi Text: 20pt, Regular, Farsi Font, 2.0 line-height (needs more space)
```

**Line Height:**
- **UI Text**: 1.4-1.5 (comfortable reading)
- **Poetry**: 1.6-2.0 (breathing room, contemplative pacing)

**Letter Spacing:**
- **UI Text**: Default (0)
- **ALL CAPS (if used)**: +0.05em (increase tracking for legibility)

**Accessibility:**
- Support iOS Dynamic Type (user can increase font size system-wide)
- Support Android Accessibility settings (font scaling)
- Minimum 16pt for body text (accessibility guideline)

**Deliverable:** Typography System Specification (Figma + style guide)
- Font files (licensed or open-source)
- Type scale documented
- Line-height and letter-spacing rules
- Usage guidelines (when serif vs. sans-serif)

---

### Step 3.4: Iconography & Graphic Elements

**What to Do:**
Design or select icons for navigation and features.

**Icon Strategy:**

**Option A: Custom Iconography (Recommended)**
- Design simple, elegant icons that match brand tone
- Persian/Islamic art-inspired (geometric, not literal)
- Line-based (2px stroke weight, rounded corners)
- Monochrome (fill with brand colors contextually)

**Option B: Icon Library (Faster)**
- Use SF Symbols (iOS) or Material Icons (Android)
- Customize as needed (adjust stroke weight, corner radius)
- Cost-effective but less unique

**Icons Needed (Minimum Set):**
- **Navigation**: Home (house or book), Journeys (path or compass), Library (bookshelf or scroll), Profile (person or settings gear)
- **Actions**: Save (bookmark or heart), Contemplate (expand or zen circle), Share (if applicable), Search (magnifying glass)
- **Features**: Daily Wisdom (sun or calendar), Contemplation Mode (moon or fullscreen), Guided Journeys (map or path), Masnavi Library (book stack or scroll)
- **System**: Close (X), Back (arrow), More (three dots), Checkmark (success), Info (question mark)

**Graphic Elements:**
- **Persian Patterns**: Geometric tile patterns (subtle, background use only)
- **Dividers**: Simple lines or ornamental breaks between sections
- **Illustrations**: Rumi portrait (existing asset), possibly Shams, other mystic poets (future)
- **Gradients**: Avoid unless very subtle (e.g., cream to white background)

**Accessibility:**
- Icons must have text labels (don't rely on icon alone)
- Minimum 44x44pt tap targets (iOS guideline)

**Deliverable:** Icon Set & Graphic Elements Library (Figma)
- 20-30 icons designed or selected
- Persian pattern assets (subtle, not overpowering)
- Usage guidelines (size, color, placement)

---

### Step 3.5: Spacing & Layout Grid

**What to Do:**
Define a consistent spacing system and grid for layouts.

**Spacing Scale (8pt Grid System):**

```
4pt:  Micro (tight spacing between related elements)
8pt:  Small (padding inside buttons, gaps between text lines)
16pt: Medium (padding inside cards, space between sections)
24pt: Large (margins around screen edges, section breaks)
32pt: XLarge (major section dividers)
48pt: XXLarge (hero spacing, top of screen)
```

**Layout Grid (Mobile):**
- **Margins**: 16pt left/right (iPhone), 24pt (iPad)
- **Columns**: 12-column grid (flexible for responsive design)
- **Gutter**: 16pt (space between columns)

**Safe Areas:**
- Account for iPhone notch (top) and home indicator (bottom)
- Use iOS Safe Area guides or Android insets

**Responsive Breakpoints:**
- **Mobile**: 320px - 428px (iPhone SE to iPhone Pro Max)
- **Tablet**: 768px - 1024px (iPad, Android tablets)
- **Web (future)**: 1280px+ (if web app planned)

**Deliverable:** Spacing & Layout Specification (Figma)
- Grid system documented
- Spacing tokens named (for developers: spacing-xs, spacing-sm, spacing-md, etc.)
- Example layouts using grid

---

### Step 3.6: Component Library

**What to Do:**
Design reusable UI components in Figma.

**Core Components to Design:**

**Buttons:**
- Primary (filled, high emphasis): "Start Journey," "Subscribe"
- Secondary (outlined, medium emphasis): "Cancel," "Skip"
- Tertiary (text-only, low emphasis): "Learn More"
- States: Default, Hover (desktop), Active (pressed), Disabled

**Text Fields:**
- Input (email, search)
- States: Default, Focused, Error, Success

**Cards:**
- Verse Card (daily verse preview)
- Journey Card (theme thumbnail + title)
- Library Item (book/chapter/verse list item)

**Navigation:**
- Bottom Tab Bar (4 tabs: Home, Journeys, Library, Me)
- Header Bar (back button, title, actions)

**Modals & Overlays:**
- Paywall Modal (feature comparison + pricing)
- Confirmation Dialog ("Are you sure you want to delete?")
- Toast Notification ("Verse saved!")

**Lists:**
- Simple List (e.g., book chapters)
- Rich List (e.g., journey themes with thumbnails)
- Empty State (no content yet, CTA to create/explore)

**Switches & Toggles:**
- On/Off toggle (notifications, dark mode)
- Radio buttons (payment plan selection)
- Checkboxes (if needed)

**Progress Indicators:**
- Loading spinner (fetching content)
- Progress bar (onboarding: "Step 2 of 4")
- Skeleton screen (loading placeholder for text)

**Deliverable:** Component Library (Figma)
- All components designed with variants (default, hover, active, disabled, error, etc.)
- Auto-layout (Figma feature for responsive components)
- Components can be reused across all screens

---

## Phase 4: High-Fidelity Design

### Duration: 3-4 weeks

### Step 4.1: Apply Visual Design to Wireframes

**What to Do:**
Take low-fidelity wireframes and transform them into high-fidelity mockups using the design system.

**Process:**
1. Start with highest-priority screens (Home, Verse Detail, Paywall)
2. Apply color palette
3. Replace placeholder text with real Rumi verses (work with John for content)
4. Apply typography system
5. Add icons and graphic elements
6. Ensure spacing follows 8pt grid
7. Design dark mode variants for each screen

**Screen-by-Screen Priorities:**

**Week 1: Core Experience (Home + Daily Verse)**
- Splash Screen (Rumi quote + app icon)
- Welcome Screen (onboarding, value prop)
- Home Screen (today's verse preview)
- Verse Detail Screen (Farsi, English, Modern views)
- Contemplation Mode (fullscreen reading)

**Week 2: Monetization (Paywall + Journeys)**
- Paywall Modal (feature comparison + pricing)
- Journey Library (grid of themes)
- Journey Detail (what to expect)
- Journey Experience (all 5 steps)

**Week 3: Depth (Library + Settings)**
- Library Home (browse by book/chapter/theme)
- Verse Detail in Library (with context)
- Search Results
- Profile/Settings screens

**Week 4: Polish & Dark Mode**
- Review all screens for consistency
- Design dark mode variants
- Error states, empty states, loading states
- Accessibility review (contrast, tap targets, labels)

**Deliverable:** High-Fidelity Mockups (Figma)
- 30-40 screens fully designed
- Light mode + Dark mode
- All states (default, loading, error, empty)

---

### Step 4.2: Motion & Interaction Design

**What to Do:**
Define how screens transition and elements animate.

**Animation Principles (Calm, Gentle):**
- **Duration**: 250-350ms (not too fast, not sluggish)
- **Easing**: Ease-out (starts fast, slows down) for most transitions
- **Avoid**: Bouncy animations, aggressive parallax, anything "hyper" or "gamified"

**Key Animations:**
1. **Screen Transitions**: Slide left/right (navigation), Fade in (modals), Scale up (details)
2. **Button Press**: Subtle scale down (0.95) on tap, scale back up on release
3. **Loading**: Gentle fade-in for content, skeleton screen → real content
4. **Success**: Checkmark fade-in + subtle scale pulse (verse saved)
5. **Contemplation Mode Enter**: Fade out UI chrome, fade in verse (2-3 second transition)

**Prototype Key Flows:**
- Onboarding flow (all 4-5 screens linked)
- Daily verse → Contemplate → Save flow
- Guided journey (all 5 steps linked)
- Paywall → Purchase flow

**Tool:** Use Figma's prototyping feature (Smart Animate for smooth transitions)

**Deliverable:** Interactive Prototype (Figma)
- 3-5 critical user flows prototyped
- Transitions and animations defined
- Clickable prototype ready for user testing

---

### Step 4.3: Accessibility Review & Refinement

**What to Do:**
Audit designs for accessibility compliance.

**Accessibility Checklist:**

**Color Contrast:**
- [ ] All text/background combos pass WCAG AA (4.5:1 for body, 3:1 for large)
- [ ] Use Figma plugins: Stark, Contrast, or A11y - Color Contrast Checker

**Touch Targets:**
- [ ] All buttons/taps are minimum 44x44pt (iOS guideline)
- [ ] Adequate spacing between tappable elements (8pt+ gap)

**Text Readability:**
- [ ] Body text is minimum 16pt
- [ ] Line height is 1.4+ for UI, 1.6+ for poetry
- [ ] No light gray text on white backgrounds (contrast fail)

**Screen Reader Support (Design for Implementation):**
- [ ] Every icon has a text label (for VoiceOver/TalkBack)
- [ ] Meaningful headings (H1, H2, H3) for navigation
- [ ] Alt text for images (Rumi illustration, etc.)

**Dynamic Type:**
- [ ] Designs accommodate iOS Dynamic Type (text can scale up to 200%+)
- [ ] Layouts don't break when text size increases

**Dark Mode:**
- [ ] Dark mode is not just inverted colors (intentionally designed)
- [ ] Contrast still passes WCAG AA in dark mode

**Reduced Motion:**
- [ ] Plan for users who disable animations (accessibility setting)
- [ ] Core functionality works without motion (no animation-dependent UX)

**Deliverable:** Accessibility Audit Report (PDF or Notion doc)
- All issues documented
- Fixes applied to Figma designs
- Developer notes for implementation (VoiceOver labels, etc.)

---

## Phase 5: Prototyping & Testing

### Duration: 2-3 weeks

### Step 5.1: Build Interactive Prototype

**What to Do:**
Create a clickable prototype in Figma that simulates the app experience.

**Flows to Prototype:**
1. **Onboarding → First Verse**: New user experience, from splash screen to reading first verse
2. **Daily Verse Habit**: Return user opens app, reads verse, contemplates, saves
3. **Guided Journey**: Browse journeys → select theme → complete 5 steps
4. **Library Exploration**: Search by keyword → read verse in context → bookmark
5. **Paywall → Purchase**: Hit paywall → see pricing → trial or purchase

**Prototype Features:**
- Clickable buttons (linked to next screen)
- Smart Animate transitions (smooth, realistic)
- Realistic content (real Rumi verses, not "Lorem ipsum")
- Dark mode toggle (show both themes)

**Tool:** Figma Prototyping (or ProtoPie, Principle for advanced micro-interactions)

**Deliverable:** Clickable Prototype (Figma link)
- 5 user flows fully interactive
- Shareable link (for user testing, stakeholder review)

---

### Step 5.2: Usability Testing (Internal or External)

**What to Do:**
Test prototype with real users to validate design decisions.

**Recruit Participants (5-10 people):**
- Match persona profiles (1-2 from each persona: Maya, Robert, Aisha, David, Sarah)
- Mix of tech-savvy and non-tech-savvy
- Include at least 2 people unfamiliar with Rumi (test accessibility for newcomers)

**Testing Protocol (30-45 min per participant):**

**Introduction (5 min):**
- Explain purpose: "We're testing a new app, not testing you."
- Emphasize thinking aloud: "Tell me what you're thinking as you use the app."

**Tasks (20-30 min):**
1. **Onboarding**: "Walk me through signing up and reading your first verse."
   - Observe: Do they complete onboarding? Any confusion? How long does it take?

2. **Daily Verse**: "Read today's verse. What do you think?"
   - Observe: Do they toggle between Farsi/English/Modern? Do they use Contemplate mode?

3. **Guided Journey**: "Find and complete a guided journey on 'Letting Go.'"
   - Observe: Can they find Journeys tab? Do they understand the 5-step structure?

4. **Library Search**: "Search for verses about 'grief' in the Masnavi library."
   - Observe: Do they find the search feature? Are results clear? Can they read verses in context?

5. **Paywall**: "You've hit a paywall. What would you do?"
   - Observe: Is the value clear? Is pricing understandable? Would they subscribe?

**Questions (10 min):**
- What did you like most?
- What was confusing or frustrating?
- Would you pay $69.99/year for this? Why or why not?
- How does this compare to Calm/Headspace? (if they use those apps)

**Testing Format:**
- **Remote**: Zoom screen-share with Figma prototype
- **In-Person**: iPad with prototype loaded (via Figma app or exported to InVision)

**Deliverable:** Usability Testing Report
- Key findings (3-5 insights)
- Quotes from participants
- Prioritized list of issues (critical, medium, minor)
- Recommendations for iteration

---

### Step 5.3: Iterate Based on Testing Feedback

**What to Do:**
Fix usability issues identified in testing.

**Example Issues & Fixes:**

**Issue**: "I couldn't find how to switch between English and Modern retelling."
- **Fix**: Make tabs more prominent, or add swipe gesture hint

**Issue**: "The paywall felt aggressive — it appeared too soon."
- **Fix**: Delay paywall until after 3 daily verses (build trust first)

**Issue**: "I wanted to save multiple verses, but couldn't find my collection."
- **Fix**: Add "My Collection" to Library tab, make it easier to access

**Issue**: "Dark mode colors hurt my eyes — text is too bright."
- **Fix**: Lower dark mode text from pure white to off-white (reduce glare)

**Process:**
1. Categorize feedback (onboarding issues, navigation issues, content issues, paywall issues)
2. Prioritize (must-fix vs. nice-to-fix)
3. Revise designs in Figma
4. Update prototype
5. Test again with 2-3 users (validate fixes)

**Deliverable:** Design Iteration v2.0 (Figma)
- All critical issues fixed
- Validated with users
- Ready for developer handoff

---

## Phase 6: Developer Handoff

### Duration: 1-2 weeks

### Step 6.1: Design Specification Document

**What to Do:**
Create a developer-friendly guide to implement designs.

**Specification Sections:**

**1. Design System Tokens** (for developers to code):
```
/* Colors */
--color-primary-blue: #1A2B4A;
--color-accent-gold: #D4A574;
--color-background-light: #FDFCFB;
--color-text-primary: #1A1A1A;
/* ...all colors documented */

/* Typography */
--font-family-serif: 'Cormorant Garamond', serif;
--font-family-sans: 'SF Pro', -apple-system, sans-serif;
--font-size-h1: 28pt;
--font-size-body: 16pt;
/* ...all type specs */

/* Spacing */
--spacing-xs: 4pt;
--spacing-sm: 8pt;
--spacing-md: 16pt;
--spacing-lg: 24pt;
/* ...all spacing values */
```

**2. Screen Redlines:**
- Annotate Figma designs with measurements (padding, margins, font sizes)
- Use Figma's "Inspect" panel (developers can extract CSS/Swift/Kotlin code)

**3. Interaction Specifications:**
- Document every button tap, swipe, transition
- Example: "Tapping 'Contemplate' fades out nav bar (300ms ease-out) and scales verse text to 20pt"

**4. Asset Exports:**
- Export all icons at @1x, @2x, @3x (iOS) or mdpi, hdpi, xhdpi, xxhdpi, xxxhdpi (Android)
- Export images as PNG (with transparency) or SVG (scalable)
- Organize in folders: `icons/`, `images/`, `illustrations/`

**5. Animation Specifications:**
- Document animation duration, easing, and trigger
- Example: "Loading spinner: 2s rotation loop, linear easing"

**Deliverable:** Developer Handoff Package
- Figma file with "Inspect Mode" enabled (developers can extract values)
- Design Spec Document (Notion or PDF) with tokens, interactions, assets
- Asset export folder (all icons, images ready for implementation)

---

### Step 6.2: Design QA During Development

**What to Do:**
Stay involved during development to ensure pixel-perfect implementation.

**QA Process:**
1. **Weekly Design Reviews**: Todd shares builds (via TestFlight for iOS, APK for Android)
2. **Compare Build to Designs**: Screenshot build next to Figma mockup, identify discrepancies
3. **Document Issues**: Create bug tickets (font size wrong, color off, spacing incorrect, animation too fast)
4. **Prioritize Fixes**: Critical (breaks UX) vs. minor (nice-to-have polish)
5. **Re-test**: Verify fixes in next build

**Common QA Issues:**
- Font sizes don't match (developer used 14pt instead of 16pt)
- Colors are slightly off (hex code typo)
- Spacing is inconsistent (8pt instead of 16pt)
- Animations are too fast/slow (wrong duration)
- Dark mode looks wrong (colors not properly inverted)

**Tool:** Use Figma's "Pixel Perfect" plugin or Zeplin for side-by-side comparison

**Deliverable:** Design QA Checklist (Spreadsheet or Notion)
- All screens reviewed
- Issues logged and tracked
- Build quality meets design standards before launch

---

## Phase 7: Post-Launch Optimization

### Duration: Ongoing (3-6 months post-launch)

### Step 7.1: Analytics Setup & Monitoring

**What to Do:**
Track user behavior to validate design decisions and identify issues.

**Key Events to Track:**
- **Onboarding**: onboarding_start, onboarding_step_1_complete, onboarding_complete
- **Daily Verse**: verse_viewed, verse_farsi_toggled, verse_english_toggled, verse_modern_toggled, contemplate_mode_entered, verse_saved
- **Guided Journeys**: journey_library_viewed, journey_started, journey_step_completed, journey_finished
- **Library**: library_opened, search_performed, book_browsed, verse_bookmarked
- **Paywall**: paywall_shown, paywall_pricing_viewed, paywall_dismissed, trial_started, subscription_purchased
- **Retention**: app_opened (daily), session_length, days_active_last_7

**Analytics Tools:**
- Mixpanel (event tracking, cohort analysis)
- Amplitude (user journeys, retention funnels)
- Firebase Analytics (free, basic tracking)
- App Store Connect (downloads, crashes, revenue)

**Dashboard to Build:**
- **Activation**: Onboarding completion rate, time to first verse
- **Engagement**: DAU/MAU, session length, feature adoption (% using Journeys, Library)
- **Retention**: D1/D7/D30 retention curves by cohort
- **Monetization**: Paywall conversion, trial-to-paid, churn rate, LTV

**Deliverable:** Analytics Dashboard (live, updating)
- Key metrics visible at a glance
- Alerts for anomalies (sudden drop in retention, spike in crashes)

---

### Step 7.2: A/B Testing Roadmap (Per User Testing Logic Doc)

**What to Do:**
Run systematic experiments to optimize key metrics.

**Month 1-2: Onboarding Optimization**
- **Test 1: Login Options**
  - Variant A: Email only
  - Variant B: Email + Apple/Google Sign-In
  - Metric: Onboarding completion rate
  - Hypothesis: Social login increases completion (less friction)

- **Test 2: Onboarding Length**
  - Variant A: 4-screen onboarding (current)
  - Variant B: 2-screen minimal onboarding (skip straight to verse)
  - Metric: Completion rate, D1 retention
  - Hypothesis: Shorter onboarding gets users to value faster

**Month 3-4: Paywall Optimization**
- **Test 3: Paywall Timing**
  - Variant A: Show paywall on Day 1 (after first journey attempt)
  - Variant B: Show paywall on Day 3 (after 3 daily verses, build trust first)
  - Metric: Paywall conversion rate, D7 retention
  - Hypothesis: Delayed paywall converts better (users see value first)

- **Test 4: Pricing Display**
  - Variant A: Monthly $9.99, Annual $69.99 (equal prominence)
  - Variant B: Annual $69.99 highlighted as "Most Popular" with "Save 42%" badge
  - Metric: Plan mix, ARPU
  - Hypothesis: Highlighting annual increases annual subscriptions (better LTV)

**Month 5-6: Engagement Optimization**
- **Test 5: Push Notification Copy**
  - Variant A: "Your daily verse is ready"
  - Variant B: "Rumi is waiting — your moment of stillness awaits"
  - Metric: Push open rate, app opens
  - Hypothesis: Poetic, personalized copy increases engagement

- **Test 6: Contemplation Mode Entry**
  - Variant A: Button labeled "Contemplate"
  - Variant B: Button labeled "Enter Stillness" or icon-only (zen circle)
  - Metric: Contemplate mode usage rate, session length
  - Hypothesis: Clearer CTA increases feature adoption

**Process:**
1. Define hypothesis
2. Design variants
3. Implement with feature flags (developers can toggle A/B remotely)
4. Run test for 2-4 weeks (until statistical significance)
5. Analyze results
6. Ship winner to 100% of users
7. Document learnings

**Deliverable:** A/B Testing Log (Spreadsheet)
- Test name, date, variants, metrics, winner, learnings

---

### Step 7.3: User Feedback Loop

**What to Do:**
Continuously collect and act on user feedback.

**Feedback Channels:**
1. **App Store Reviews**: Monitor daily, respond to critiques
2. **In-App Feedback**: Add "Send Feedback" button in Settings
3. **User Surveys**: Email survey to 30-day actives (NPS, feature requests)
4. **Support Tickets**: Track common complaints/requests
5. **Social Media**: Monitor mentions of app (Twitter, Instagram, Reddit)

**Feedback Triage:**
- **Critical Bugs**: Fix immediately (app crashes, paywall broken)
- **Usability Issues**: Prioritize by frequency (many users report same issue)
- **Feature Requests**: Log in backlog, prioritize by strategic value
- **Positive Feedback**: Celebrate with team, extract testimonials for marketing

**Quarterly User Interviews (5-10 power users):**
- What do you love?
- What's frustrating?
- What features are you missing?
- Would you recommend to a friend? Why or why not?

**Deliverable:** Feedback Dashboard (Notion or Airtable)
- All feedback categorized (bugs, features, usability, praise)
- Prioritized roadmap based on user needs
- Closed loop (tell users when you ship their requested feature)

---

### Step 7.4: Continuous Design Iteration

**What to Do:**
Treat design as ongoing, not "done at launch."

**Monthly Design Reviews:**
- Analyze analytics (what screens have high drop-off?)
- Review user feedback (what's confusing?)
- Competitive landscape (what are Calm/Headspace shipping?)
- Propose design improvements

**Example Iterations:**

**Month 1**: "Onboarding completion is 45% (below 60% target)"
- Redesign onboarding to be shorter (2 screens instead of 4)
- Ship, measure, hit 62% completion

**Month 2**: "Only 15% of users try Guided Journeys"
- Add prominent Journeys CTA on Home screen
- Redesign Journeys tab with better visual hierarchy
- Ship, measure, increase to 28% adoption

**Month 3**: "Dark mode text is too bright (user complaints)"
- Lower text brightness from #FFFFFF to #E8E6E3
- Ship, complaints drop

**Continuous Improvement Cadence:**
- **Weekly**: Review analytics, log issues
- **Bi-weekly**: Design sprints (fix 2-3 issues)
- **Monthly**: Ship design updates
- **Quarterly**: Major feature additions (new journeys, Shams content, etc.)

**Deliverable:** Design Iteration Roadmap (updated monthly)
- Prioritized list of design improvements
- Shipped, in progress, backlog

---

## Appendix: Templates & Resources

### Template A: Screen Design Checklist

Use this checklist for every screen you design:

**Content & Hierarchy:**
- [ ] Clear headline (H1) that explains screen purpose
- [ ] Primary action is obvious (largest, highest contrast button)
- [ ] Secondary actions are visually de-emphasized
- [ ] Content is scannable (headings, bullet points, short paragraphs)

**Visual Design:**
- [ ] Colors match design system (no random hex codes)
- [ ] Typography follows type scale (no arbitrary font sizes)
- [ ] Spacing follows 8pt grid (no pixel-pushing)
- [ ] Icons have consistent style (all line icons or all filled, not mixed)

**Accessibility:**
- [ ] Text contrast passes WCAG AA (4.5:1 minimum)
- [ ] Touch targets are 44x44pt minimum
- [ ] Every icon has a text label (for screen readers)
- [ ] Layout supports dynamic type (text can scale up)

**Interaction:**
- [ ] All tap targets are documented (what happens when user taps?)
- [ ] Loading state is designed (spinner, skeleton, or message)
- [ ] Error state is designed (what if API fails?)
- [ ] Empty state is designed (what if no content yet?)

**Platform:**
- [ ] Design respects iOS/Android conventions (back button, navigation patterns)
- [ ] Safe area accounted for (iPhone notch, Android navigation bar)
- [ ] Dark mode variant designed (not just inverted)

---

### Template B: Feature Prioritization Matrix

Use this to decide what to build first:

| Feature | User Value (1-5) | Business Impact (1-5) | Effort (1-5) | Priority Score | Status |
|---------|------------------|----------------------|--------------|----------------|--------|
| Daily Verse | 5 | 5 | 2 | 12.5 | MVP |
| Guided Journeys | 4 | 4 | 3 | 8 | MVP |
| Complete Masnavi | 5 | 5 | 4 | 10 | MVP |
| Audio Narration | 3 | 3 | 5 | 3 | Phase 2 |
| Annotation/Notes | 3 | 2 | 4 | 2.5 | Phase 2 |
| Community Features | 2 | 3 | 5 | 2 | Phase 3 |

**Priority Score** = (User Value + Business Impact) / Effort
- Higher score = build first
- "Effort" is 1 (easy) to 5 (very hard)

---

### Template C: Design Critique Framework

Use this to give/receive feedback on designs:

**What's Working Well?** (Start with positives)
- Example: "The typography hierarchy is clear — I immediately know what's important."

**What's Unclear or Confusing?** (Usability issues)
- Example: "I don't understand what the heart icon does. Is it 'like' or 'save'?"

**What Could Be Stronger?** (Constructive suggestions)
- Example: "The paywall feels aggressive. Could we delay it until Day 3?"

**What Would You Test?** (Hypotheses to validate)
- Example: "I'd test whether users prefer tabs or swipe gestures for switching between Farsi/English views."

---

### Resource D: Recommended Tools

**Design:**
- **Figma**: UI design, prototyping, collaboration (primary tool)
- **Sketch**: Alternative to Figma (Mac-only)
- **Adobe XD**: Alternative to Figma (deprecated by Adobe, not recommended)

**Wireframing:**
- **Balsamiq**: Low-fidelity wireframes (sketch-like)
- **Whimsical**: Flowcharts, wireframes, mind maps
- **FigJam**: Whiteboarding, brainstorming (built into Figma)

**Prototyping:**
- **Figma Prototype**: Built-in, good for most use cases
- **ProtoPie**: Advanced micro-interactions
- **Principle**: Animation prototyping (Mac-only)

**User Testing:**
- **Zoom**: Remote screen-sharing for interviews
- **Lookback.io**: User testing platform (records sessions)
- **Maze**: Automated usability testing (clickable prototypes with metrics)

**Analytics:**
- **Mixpanel**: Event tracking, funnels, cohorts
- **Amplitude**: User journey analysis
- **Firebase Analytics**: Free, basic tracking
- **Hotjar**: Heatmaps, session recordings (web-focused)

**Accessibility:**
- **Stark** (Figma plugin): Color contrast checker
- **A11y - Color Contrast Checker** (Figma plugin)
- **WebAIM Contrast Checker**: Online tool

**Collaboration:**
- **Notion**: Documentation, wikis, roadmaps
- **Miro**: Whiteboarding, affinity mapping
- **Slack**: Team communication
- **ClickUp**: Project management (already in use)

---

### Resource E: UX Reading List

**Books:**
- **The Design of Everyday Things** by Don Norman (UX fundamentals)
- **Don't Make Me Think** by Steve Krug (usability principles)
- **Hooked** by Nir Eyal (habit-forming products) — *Read critically, avoid dark patterns*
- **Sprint** by Jake Knapp (design sprints, rapid prototyping)
- **The Mom Test** by Rob Fitzpatrick (user research, asking good questions)

**Articles/Blogs:**
- **Nielsen Norman Group** (NNG.com) — UX research and guidelines
- **UX Collective** (Medium) — UX case studies
- **Humane by Design** (humanebydesign.com) — Ethical design patterns

**Podcasts:**
- **Design Details** — Design process, interviews
- **UI Breakfast** — UX/UI design topics
- **The Honest Designers Show** — Design critiques

---

## Final Notes: Making This Plan Actionable

### How to Use This Plan

**If You're Working Solo (Suede):**
- Follow phases sequentially (don't skip ahead)
- Budget 12-16 weeks total (3-4 months) for full UX design
- Prioritize MVP features (don't get stuck in Phase 2 feature creep)

**If You Have a Team:**
- Assign owners to each phase (Suede = design, Todd = implementation, Yalor = user research, John = content)
- Run phases in parallel where possible (e.g., visual design while Todd builds backend)
- Weekly check-ins to align progress

**If Budget is Tight:**
- Skip Step 0.3 (User Research) and rely on personas + competitive analysis
- Use free tools (Figma free tier, Google Forms for surveys, Zoom for interviews)
- DIY user testing with friends/family instead of recruiting participants

**If Timeline is Tight:**
- Reduce MVP scope (ship with 5 guided journeys instead of 15, add more later)
- Use design system templates (iOS/Android design kits) instead of designing from scratch
- Parallel design and development (risky but faster: Todd starts building while Suede designs)

---

### Success Metrics for This UX Plan

**You'll know this plan is working if:**
- ✅ Onboarding completion rate is 60%+ (users finish setup, reach first verse)
- ✅ D1 retention is 40%+ (users come back the next day)
- ✅ Paywall conversion is 5-10% (free users upgrade to premium)
- ✅ App Store rating is 4.5+ (users love the design)
- ✅ No dark patterns complaints (conscious business integrity maintained)
- ✅ All 5 personas are served (Maya, Robert, Aisha, David, Sarah all find value)

---

### Next Steps (Immediate)

1. **This Week**: Present this plan to John, Todd, Yalor for feedback and alignment
2. **Next Week**: Begin Phase 0 (Competitive audit + content mapping)
3. **Week 3-4**: Complete Phase 1 (Information architecture + wireframes)
4. **Month 2**: Complete Phases 2-3 (Visual design system)
5. **Month 3**: Complete Phase 4 (High-fidelity mockups)
6. **Month 4**: Complete Phases 5-6 (Prototyping, testing, developer handoff)
7. **Month 5+**: Todd builds, Suede does design QA
8. **Launch**: Phase 7 begins (analytics, A/B testing, continuous iteration)

---

**This plan is comprehensive, but flexible.** Adapt it to your team's needs, timeline, and budget. The goal is not perfection, but **a beautiful, usable, conscious spiritual companion app that serves Rumi's wisdom with integrity and depth.**

**Go build something sacred.**

---

**Document created by:** Claude (AI Assistant for Suede)
**Date:** January 12, 2026
**Version:** 1.0
**Status:** Ready for team review and execution
