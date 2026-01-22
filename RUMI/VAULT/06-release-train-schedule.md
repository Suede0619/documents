# Release Train Schedule

Rumi App - Weekly Development Cadence  
Last Updated: January 21, 2026

---

## Overview

A predictable weekly rhythm for product development, testing, and release. Creates accountability and ensures regular customer feedback integration.

---

## Weekly Schedule

| Day | Activity | Owner | Participants | Output |
|-----|----------|-------|--------------|--------|
| **Thursday** | Weekly Release (MVP n+1) | Todd Bowden | Dev team | New build deployed to beta |
| **Friday** | Beta Testing | Yalor Mewn | Beta groups A/B/C | Testing feedback collected |
| **Monday** | Feedback Integration | Todd Bowden | YM, SP | Prioritized bug/feedback list |
| **Tuesday** | Product Release Discussion | Yalor Mewn | Full team | Next sprint scope decided |
| **Wednesday** | Team QA | Full Team | All | Final QA before Thursday |

---

## Thursday: Weekly Release

**Time:** [RELEASE TIME - e.g., 2:00 PM PT]  
**Owner:** Todd Bowden (Accountable)  

### Checklist
- [ ] All committed features complete
- [ ] Code review completed
- [ ] Unit tests passing
- [ ] Build successfully compiles
- [ ] Deploy to TestFlight/beta channel
- [ ] Release notes drafted
- [ ] Beta testers notified

### Deliverables
- New build available on TestFlight
- Release notes shared with team
- Known issues documented

---

## Friday: Beta Testing

**Time:** All day  
**Owner:** Yalor Mewn (Accountable)  

### Beta Groups

| Group | Size | Profile | Focus |
|-------|------|---------|-------|
| Group A | [SIZE] | Power users, early adopters | Deep feature testing |
| Group B | [SIZE] | Target demographic match | UX and flow testing |
| Group C | [SIZE] | General audience | First impressions, onboarding |

### Feedback Collection
- In-app feedback mechanism
- Structured survey (weekly)
- Direct messages/emails
- Analytics review

### Deliverables
- Raw feedback compiled
- Critical bugs flagged immediately
- User quotes captured

---

## Monday: Feedback Integration

**Time:** [MEETING TIME - e.g., 10:00 AM PT]  
**Owner:** Todd Bowden (Accountable)  
**Duration:** 1 hour  

### Agenda
1. Review weekend feedback (15 min)
2. Triage bugs by severity (15 min)
3. Prioritize feature requests (15 min)
4. Assign items for current sprint (15 min)

### Prioritization Framework

| Priority | Definition | Response |
|----------|------------|----------|
| P0 - Critical | App crash, data loss, security | Fix immediately |
| P1 - High | Major feature broken | Fix this sprint |
| P2 - Medium | Minor bug, UX issue | Next sprint |
| P3 - Low | Enhancement, nice-to-have | Backlog |

### Deliverables
- Prioritized issue list
- Sprint backlog updated
- Assignments clear

---

## Tuesday: Product Release Discussion

**Time:** [MEETING TIME - e.g., 10:00 AM PT]  
**Owner:** Yalor Mewn (Accountable)  
**Duration:** 1 hour  
**Attendees:** Full team  

### Agenda
1. Demo of current build (10 min)
2. Review metrics and feedback (10 min)
3. Discuss next sprint scope (20 min)
4. Trade-off decisions (15 min)
5. Confirm Thursday release scope (5 min)

### Key Questions
- What ships Thursday?
- What gets cut?
- What moves to next sprint?
- Any blockers?

### Deliverables
- Sprint scope confirmed
- Trade-off decisions documented
- Team aligned on priorities

---

## Wednesday: Team QA

**Time:** [QA WINDOW - e.g., 9:00 AM - 12:00 PM PT]  
**Owner:** Full Team  
**Duration:** 3 hours  

### QA Checklist

#### Core Flows
- [ ] App launch and onboarding
- [ ] Daily quote display (Farsi, English, Retelling)
- [ ] Contemplation mode
- [ ] Guided journey (start to finish)
- [ ] Masnavi library navigation
- [ ] Search functionality
- [ ] Save/bookmark feature
- [ ] Share functionality
- [ ] Settings and preferences
- [ ] Subscription/paywall flow

#### Technical
- [ ] No crashes on main flows
- [ ] Performance acceptable
- [ ] Offline mode works
- [ ] Push notifications working
- [ ] Analytics tracking correctly

#### Design
- [ ] Fonts rendering correctly
- [ ] Colors match design system
- [ ] Spacing and alignment
- [ ] Transitions smooth
- [ ] No visual glitches

### Deliverables
- QA sign-off (or blocker list)
- Last-minute fixes identified
- Go/no-go decision for Thursday

---

## Sprint Metrics

Track weekly:

| Metric | Target | Actual |
|--------|--------|--------|
| Features shipped | [TARGET] | [ACTUAL] |
| Bugs fixed | [TARGET] | [ACTUAL] |
| Beta feedback items addressed | [TARGET] | [ACTUAL] |
| Build stability (crash-free rate) | 99%+ | [ACTUAL] |
| Release on time | Yes | [YES/NO] |

---

## Release Versioning

| Version Format | Example | Use |
|----------------|---------|-----|
| Major.Minor.Patch | 1.2.3 | Public releases |
| Build number | 1.2.3 (456) | Internal tracking |

### Version Increment Rules
- **Major:** Breaking changes, major new features
- **Minor:** New features, significant improvements
- **Patch:** Bug fixes, small improvements

---

## Communication

### Internal
- Slack channel: [#RELEASE-TRAIN CHANNEL]
- Release notes: [LOCATION - e.g., Notion, ClickUp]
- Sprint board: ClickUp

### External (Beta Testers)
- TestFlight release notes
- Email updates (major releases)
- In-app changelog

---

## Exceptions Process

If release cannot happen Thursday:

1. Todd notifies team by Wednesday EOD
2. Yalor decides: delay vs. partial release
3. Communicate to beta testers
4. Document reason and prevention plan

---

## Notes

- This cadence starts [START DATE]
- Adjust timing based on team availability
- Review process monthly for improvements
- Holiday/vacation coverage plan needed
