# Release Train Schedule

Rumi App - Weekly Development Cadence  
Last Updated: January 26, 2026

---

## Overview

A predictable weekly rhythm for product development, testing, and release. Creates accountability and ensures regular customer feedback integration. Per Ben Rewis (Jan 21, 2026): Implement a release train methodology with Thursday releases, Friday beta testing, and weekly feedback loops.

**Two-phase approach:** Phase 0 (validation cadence) starts immediately with the TestFlight MVP. Phase 1 (full release train) starts ~4 weeks before iOS public launch.

---

## Phase 0: Validation Cadence (Starting Feb 2026)

A lightweight weekly build cycle focused on learning, not features. Per advisor feedback (Former Head of Product at Twitter, Jan 2026): "Don't build anything substantial till you can validate the market."

### Purpose
- Ship the simplest version to TestFlight as fast as possible
- Track user behavior with Mixpanel from day one
- Iterate based on what the data shows, not what the team assumes
- Generate traction data for investor meetings

### Weekly Cycle

| Day | Activity | Time (PT) | Owner | Duration | Output |
|-----|----------|-----------|-------|----------|--------|
| **Thursday** | TestFlight build | 2:00 PM | Todd (CTO) | — | Updated build on TestFlight |
| **Monday** | Data review + user feedback | 10:00 AM | Yalor (PO) + Todd | 30 min | What the data says, what to change |

### What Ships in Phase 0
- Daily verse (Farsi + English + modern retelling)
- One guided journey
- Mixpanel analytics (DAU, session length, screen time, return rate)
- Paywall screen (measure tap intent — no payment processing required)

### What Does NOT Ship in Phase 0
- Full Masnavi library
- Search functionality
- Bookmarking / personal collections
- Multiple guided journeys
- Polished design system
- Any feature not needed to measure core engagement

### Phase 0 Metrics Dashboard

Track weekly from the first TestFlight build:

| Metric | Target | Week 1 | Week 2 | Week 3 | Week 4 |
|--------|--------|--------|--------|--------|--------|
| TestFlight installs | 500+ first week | — | — | — | — |
| DAU | Growing week-over-week | — | — | — | — |
| D1 retention | > 30% | — | — | — | — |
| D7 retention | > 15% | — | — | — | — |
| Avg session length | > 3 min | — | — | — | — |
| Paywall tap-through | > 5% | — | — | — | — |
| Journey completion rate | > 50% | — | — | — | — |

### Phase 0 Exit Criteria

Move to Phase 1 (full release train) when:
1. Validation data collected from 500+ users minimum
2. Core engagement metrics (retention, session length) are within target range
3. SAFE has closed and full build resources are available
4. Team is ready for formal weekly cadence with QA

If metrics are below targets, iterate in Phase 0 until the core experience works. Do not scale what does not retain.

---

## Phase 1: Full Release Train (Starting ~Jun 2026)

### Weekly Schedule

| Day | Activity | Time (PT) | Owner (A) | Participants | Duration | Output |
|-----|----------|-----------|-----------|-------------|----------|--------|
| **Thursday** | Weekly Release (MVP n+1) | 2:00 PM | Todd (CTO) | TB, SP reviews | — | New build on TestFlight |
| **Friday** | Beta Testing | All day | Yalor (COO/PO) | Up to 5,000 TestFlight users | Async | Feedback collected |
| **Monday** | Feedback Integration | 10:00 AM | Yalor (PO) | TB, SP, JW (optional) | 45 min | Prioritized issue list |
| **Tuesday** | Product Release Discussion | 10:00 AM | Yalor (PO) | Full team | 1 hour | Sprint scope confirmed |
| **Wednesday** | Team QA | 10:00 AM - 1:00 PM | Full Team | All | 3 hours | QA sign-off for Thursday |

**Cadence start date:** ~June 2026 (4 weeks before target iOS launch), or upon Phase 0 exit criteria being met.

---

## Thursday: Weekly Release

**Time:** 2:00 PM PT  
**Owner:** Todd Bowden (Accountable)  
**Notification:** Post in #release-train Slack channel  

### Pre-Release Checklist
- [ ] All committed features for this sprint are complete
- [ ] Code review completed (self-review minimum; peer review when available)
- [ ] Unit tests passing
- [ ] Build successfully compiles for iOS (and Android when applicable)
- [ ] No P0 bugs outstanding
- [ ] Release notes drafted (what's new, what's fixed, known issues)

### Release Process
1. TB creates build in Xcode
2. TB uploads to TestFlight
3. TB posts release notes in #release-train
4. TestFlight auto-notifies beta testers
5. TB tags the release in Git (e.g., `v0.3.1-beta.42`)

### Deliverables
- New build available on TestFlight
- Release notes shared in #release-train
- Known issues documented in ClickUp
- Git tag created

### If Release Cannot Ship
1. TB notifies team by Wednesday 5:00 PM PT
2. YM decides: delay to Friday, partial release, or skip week
3. Communicate to beta testers (if partial/skip)
4. Document reason in ClickUp and discuss at Tuesday retro

---

## Friday: Beta Testing

**Time:** All day (async)  
**Owner:** Yalor Mewn (Accountable)  
**Channel:** #beta-feedback Slack channel (or dedicated feedback tool)  

### Beta Groups

**Phase 0 (Validation):** All TestFlight users (up to 5,000) receive every build. No group segmentation — maximize data volume.

**Phase 1 (Full Release Train):** Segment into groups for targeted feedback:

| Group | Size | Profile | Focus | Rotation |
|-------|------|---------|-------|----------|
| **Group A** | 100-200 users | Power users, early adopters, Rumi enthusiasts | Deep feature testing, edge cases | Stable core group |
| **Group B** | 300-500 users | Target demographic (spiritual seekers, 25-55) | UX flow, emotional response, daily habit | Rotate 20% monthly |
| **Group C** | 1,000-4,000 users | Broader audience from validation recruitment | First impressions, onboarding, retention | Rotate 50% monthly |
| **Total** | **Up to 5,000 users** | Carried over from Phase 0 TestFlight recruitment | | |

**Recruitment sources for beta testers:**
- Existing waitlist / landing page signups
- Social media followers
- Rumi book communities (Goodreads, Reddit r/Rumi)
- Meditation / spiritual practice communities
- John's existing spiritual community

### Feedback Collection Methods

| Method | Tool | When | Owner |
|--------|------|------|-------|
| In-app feedback button | Custom build or Instabug | Ongoing | TB builds, YM monitors |
| Weekly structured survey | Typeform | Friday PM (auto-sent) | YM |
| Direct messages | Slack DM or email | As needed | YM triages |
| Usage analytics | Mixpanel | Continuous | TB configures, YM reviews |
| Video recordings | Loom (user-submitted) | Optional | YM requests for specific flows |

### Friday Survey Template (5 questions max)
1. What did you use the app for today? (open text)
2. Rate today's daily verse (1-5 stars)
3. Did anything confuse or frustrate you? (open text)
4. What would make you come back tomorrow? (open text)
5. Would you recommend this app to a friend? (NPS: 0-10 scale)

### Deliverables
- Raw feedback compiled in ClickUp or Notion
- Critical bugs flagged immediately in #release-train (tag @todd)
- User quotes captured for marketing and investor materials
- Weekly NPS score tracked

---

## Monday: Feedback Integration

**Time:** 10:00 AM PT  
**Owner:** Yalor Mewn (Accountable)  
**Duration:** 45 minutes  
**Attendees:** YM, TB, SP (JW optional — invited for content-related feedback)  
**Location:** Zoom / Google Meet (or Slack huddle)  

### Agenda
1. **Weekend feedback review** (15 min) — YM presents top themes and quotes
2. **Bug triage** (10 min) — TB classifies by severity
3. **Feature request patterns** (10 min) — YM highlights recurring requests
4. **Sprint impact assessment** (10 min) — Team decides what enters this week's work

### Prioritization Framework

| Priority | Definition | Response Time | Example |
|----------|------------|---------------|---------|
| **P0 - Critical** | App crash, data loss, security issue | Fix within 24 hours | App won't launch; user data exposed |
| **P1 - High** | Major feature broken, blocks core flow | Fix this sprint | Daily verse not loading; payment fails |
| **P2 - Medium** | Minor bug, UX confusion, cosmetic | Next sprint | Misaligned text; slow animation |
| **P3 - Low** | Enhancement, nice-to-have, polish | Backlog | "Would be nice if..." requests |

### Deliverables
- Prioritized issue list updated in ClickUp
- Sprint backlog adjusted if P0/P1 items found
- Assignments clear for the week

---

## Tuesday: Product Release Discussion

**Time:** 10:00 AM PT  
**Owner:** Yalor Mewn (Accountable)  
**Duration:** 1 hour  
**Attendees:** Full team (JW, TB, YM, SP)  
**Location:** Zoom / Google Meet  

### Agenda
1. **Demo of current build** (10 min) — TB or SP screen-shares latest
2. **Metrics review** (10 min) — YM shares DAU, retention, NPS, feedback themes
3. **Sprint scope discussion** (20 min) — What ships Thursday? What gets deferred?
4. **Trade-off decisions** (15 min) — PO makes calls with team input
5. **Confirm Thursday release scope** (5 min) — Clear, written list of what ships

### Key Questions to Answer Every Tuesday
- What ships this Thursday? (specific feature list)
- What gets cut or deferred? (and why)
- What moves to next sprint? (documented in backlog)
- Any blockers that need resolution before Wednesday?
- Is there a content/spiritual integrity question for John?

### Deliverables
- Sprint scope confirmed and posted in #release-train
- Trade-off decisions documented in ClickUp
- Team aligned on Thursday delivery
- Any design work needed identified (SP begins immediately)

---

## Wednesday: Team QA

**Time:** 10:00 AM - 1:00 PM PT  
**Owner:** Full Team (YM accountable for sign-off)  
**Duration:** 3 hours (can be shorter if build is clean)  
**Attendees:** All team members test independently, then sync  

### QA Assignment by Role

| Team Member | QA Focus Area |
|-------------|---------------|
| **Todd (CTO)** | Technical: crashes, performance, API calls, data integrity, offline mode |
| **Yalor (PO)** | Flows: onboarding, daily verse, guided journeys, subscription, navigation |
| **Stuart (CDO)** | Design QA: fonts, colors, spacing, animations, transitions, visual consistency, brand adherence |
| **John (CEO)** | Content: verse accuracy, tone, spiritual integrity, Farsi rendering |

### QA Checklist

#### Core Flows
- [ ] App launch and onboarding (first-time user experience)
- [ ] Daily verse display (Farsi, English translation, Modern retelling)
- [ ] Contemplation mode (enter and exit)
- [ ] Guided journey (start to finish — at least one journey)
- [ ] Masnavi library navigation (browse, search, filter)
- [ ] Search functionality (keyword, emotion, theme)
- [ ] Save/bookmark feature
- [ ] Share functionality (Instagram, WhatsApp, copy text)
- [ ] Settings and preferences
- [ ] Subscription/paywall flow (free → premium prompt)
- [ ] Push notification (receive and tap-to-open)

#### Technical
- [ ] No crashes on main flows (crash-free rate target: 99.5%+)
- [ ] Performance acceptable (app load < 3 seconds, screens < 1 second)
- [ ] Offline mode works (cached daily verse, saved content)
- [ ] Push notifications working correctly
- [ ] Analytics events firing (check Mixpanel debug)
- [ ] Dark mode rendering (if supported)
- [ ] Multiple device sizes (iPhone SE, iPhone 15, iPad)

#### Design
- [ ] Fonts rendering correctly (serif for Rumi, sans-serif for UI)
- [ ] Colors match design system tokens
- [ ] Spacing and alignment per design specs
- [ ] Transitions and animations smooth (no jank)
- [ ] No visual glitches (overlapping text, clipped images)
- [ ] Farsi/Arabic text renders right-to-left correctly

#### Content
- [ ] Daily verse is correct for today's date
- [ ] Farsi text is accurate (John verifies)
- [ ] English translation matches source
- [ ] Modern retelling reads naturally
- [ ] No typos or formatting errors

### QA Sync (12:30 PM PT — 30 minutes)
- Each person reports: pass, pass with notes, or blocker
- Todd resolves any P0/P1 issues before 2:00 PM Thursday
- YM makes go/no-go call for Thursday release

### Deliverables
- QA sign-off (or blocker list) posted in #release-train
- Last-minute fixes identified and assigned
- Go/no-go decision documented

---

## Sprint Metrics Dashboard

Track weekly in ClickUp or a shared spreadsheet:

| Metric | Target | Week 1 | Week 2 | Week 3 | Week 4 |
|--------|--------|--------|--------|--------|--------|
| Features shipped | 2-4 per sprint | — | — | — | — |
| Bugs fixed | 5-10 per sprint | — | — | — | — |
| P0/P1 bugs open | 0 at release | — | — | — | — |
| Beta feedback items addressed | 3-5 per sprint | — | — | — | — |
| Build stability (crash-free %) | 99.5%+ | — | — | — | — |
| Release on time (Thursday) | Yes | — | — | — | — |
| Sprint completion rate | 80%+ | — | — | — | — |

---

## Release Versioning

| Version Format | Example | Use |
|----------------|---------|-----|
| Major.Minor.Patch | 1.2.3 | Public App Store releases |
| Build number | 1.2.3 (456) | Internal/TestFlight tracking |

### Version Increment Rules
- **Major (1.x.x):** Breaking changes, major new features (e.g., Shams content launch, platform redesign)
- **Minor (x.1.x):** New features, significant improvements (e.g., new guided journey, library filters)
- **Patch (x.x.1):** Bug fixes, small improvements (e.g., typo fix, performance improvement)

### Pre-Launch Versioning
- Use `0.x.x` during beta (e.g., 0.1.0, 0.2.0, etc.)
- Version 1.0.0 = App Store public launch

---

## Communication Channels

### Internal
| Channel | Purpose | Who Posts |
|---------|---------|-----------|
| **#release-train** (Slack) | Release notes, go/no-go, sprint scope | TB (releases), YM (scope) |
| **#beta-feedback** (Slack) | User feedback, quotes, issues | YM |
| **#bugs** (Slack) | Bug reports with screenshots/videos | All |
| **ClickUp Board** | Sprint backlog, task assignment, progress | All |

### External (Beta Testers)
| Channel | Purpose | Frequency |
|---------|---------|-----------|
| TestFlight release notes | What's new in each build | Weekly (Thursday) |
| Email update | Major milestones, new features | Monthly |
| In-app changelog | Visible to users in settings | Per release |

---

## Exceptions & Holiday Coverage

### If release cannot ship Thursday:
1. TB notifies team by Wednesday 5:00 PM PT
2. YM decides: delay to Friday, partial release, or skip week
3. Post decision in #release-train with reason
4. Document in ClickUp for retrospective

### Holiday / Vacation weeks:
- Designate backup for each role (see below)
- Minimum: 1 person available for P0 bug response
- Skip formal release if team capacity < 50%

| Role | Primary | Backup |
|------|---------|--------|
| Release (Thursday) | Todd | Yalor (if technically capable) or skip |
| Beta coordination (Friday) | Yalor | Stuart |
| Feedback integration (Monday) | Yalor | Stuart |
| Release discussion (Tuesday) | Yalor | John |
| QA (Wednesday) | All | Minimum 2 of 4 |

---

## Cadence Review

Review the release train process monthly:
- Is the weekly cadence sustainable?
- Are meetings the right length?
- Is beta feedback being acted on quickly enough?
- Do we need to adjust meeting times?
- Any bottlenecks to address?

---

## Notes

- **Phase 0 (validation cadence) begins as soon as the TestFlight MVP is ready — target Feb 2026**
- Phase 0 is lightweight: Thursday builds + Monday data reviews only
- Phase 0 goal: traction data for investor meetings, not product polish
- **Phase 1 (full release train) begins ~June 2026**, 4 weeks before iOS launch, or upon Phase 0 exit criteria
- Phase 1 first 2 weeks: practice full cadence with internal + Group A testing
- Phase 1 weeks 3-4: bring in all beta groups
- Post-launch: full cadence with all groups (up to 5,000 TestFlight users)
- Adjust timing based on team availability and time zones
- The cadence is a commitment — consistency is what makes it work
