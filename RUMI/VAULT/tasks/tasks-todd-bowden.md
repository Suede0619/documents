# Task List: Todd Bowden, PhD (CTO)

Rumi App — Documents and Deliverables Needed from Todd  
Generated: January 26, 2026

---

## BLOCKING (Must Complete Before Investor Meetings)

### 1. Ship TestFlight MVP — THE #1 PRIORITY
- **What:** Build and ship the simplest possible version of the app to TestFlight
- **Why blocking:** Per advisor (Former Head of Product at Twitter): "Don't build anything substantial till you can validate the market." Traction data from real users is the strongest asset for investor meetings. Without it, the team walks in with a plan. With it, the team walks in with proof.
- **Scope — ONLY these features:**
  - Daily verse (Farsi + English + modern retelling)
  - One guided journey (complete 5-step experience)
  - Mixpanel analytics (DAU, session length, screen time per feature, return rate)
  - Paywall screen (feature comparison + subscription prompt — no payment processing needed, just measure tap intent)
- **What NOT to build:** Full Masnavi library, search, bookmarking, multiple journeys, polished design system, offline mode. None of these are needed to validate.
- **Target:** Ship within weeks, not months
- **Deliverable:** Working build on TestFlight with Mixpanel tracking live
- **Reference:** PRD Phase 0, VAULT/06-release-train-schedule.md (Phase 0)

### 2. Integrate Mixpanel Analytics
- **What:** Set up Mixpanel (free tier) and instrument the TestFlight MVP to track all key events
- **Why blocking:** Without analytics, the TestFlight build generates no data. The data IS the point.
- **Events to track:**
  - App open / session start / session end
  - Daily verse viewed / time on verse / verse saved
  - Guided journey started / each step completed / journey completed
  - Paywall screen viewed / subscription button tapped
  - Screen transitions (time on each screen)
- **Deliverable:** Mixpanel dashboard showing real-time user behavior
- **Reference:** PRD Phase 0

### 3. Founder Equity Discussion
- **What:** Participate in equity split negotiation with all founders
- **Why blocking:** Investors will ask about the cap table.
- **Deliverable:** Agreement on equity percentages
- **Reference:** VAULT/09-cap-table.md, VAULT/analysis/equity-fairness-analysis.md

### 4. Technical Architecture Document
- **What:** Write a 1-2 page high-level technical architecture overview for investors
- **Why blocking:** Investors need to see the technology choices are sound and the CTO has a plan
- **Deliverable:** Document covering:
  - Platform choices (iOS/Swift, Android/Kotlin)
  - Backend architecture (cloud provider, database, API)
  - AI integration approach
  - Content delivery system
  - Offline capability
  - Security & privacy approach
  - Scalability plan
  - Simple architecture diagram
- **Reference:** VAULT/08-investor-data-room-checklist.md (Section 6: Technical Architecture)

### 5. IP Assignment — Technical Work
- **What:** Inventory any prior technical work (prototypes, code, architecture docs) AND sign IP assignment
- **Why blocking:** All pre-incorporation work must be assigned to the company
- **Deliverable:**
  - Written inventory of technical deliverables to date
  - Signed IP assignment (after incorporation)
- **Reference:** VAULT/08-investor-data-room-checklist.md (Section 5: IP Assignment Agreements)

### 6. Prior IP Disclosure
- **What:** Disclose any prior intellectual property you want to EXCLUDE from the company assignment
- **Deliverable:** Written list of excluded prior IP (or "none")
- **Reference:** VAULT/10-team-governance.md

---

## HIGH PRIORITY (Before Investor Meetings)

### 7. Professional Bio (150 words)
- **What:** Write a 150-word professional bio for the data room and pitch deck
- **Deliverable:** Text document
- **Reference:** VAULT/08-investor-data-room-checklist.md (Section 5: Founder Bios)

### 8. Headshot Photo
- **What:** Professional-quality headshot for pitch deck and data room
- **Deliverable:** High-resolution JPG/PNG

### 9. Infrastructure Cost Estimate
- **What:** Confirm estimated monthly costs for hosting, Apple Developer account, third-party services, tools
- **Why important:** Needed for cash flow forecast accuracy
- **Deliverable:** Itemized monthly cost estimate
- **Reference:** VAULT/01-cash-flow-forecast.md

### 10. Privacy Policy Technical Input
- **What:** Specify all data the app will collect and all third-party SDKs used (Mixpanel, Firebase, etc.)
- **Why important:** Required for privacy policy and App Store submission
- **Deliverable:** Written list of data collected + third-party integrations
- **Reference:** VAULT/08-investor-data-room-checklist.md (Section 8: Privacy Policy)

### 11. Product Demo Video
- **What:** Record screen recording of TestFlight MVP (2-3 minutes) for investor data room
- **Deliverable:** MP4 video file
- **Reference:** VAULT/08-investor-data-room-checklist.md (Section 1: Product Demo Video)

### 12. LinkedIn Profile Update
- **What:** Update LinkedIn profile to reflect Rumi App Co-Founder & CTO role
- **Deliverable:** Updated LinkedIn profile URL
- **Reference:** VAULT/08-investor-data-room-checklist.md (Section 5: LinkedIn Profiles)

### 13. TestFlight Metrics Report for Investors
- **What:** Compile Mixpanel data from TestFlight MVP into investor-ready summary: DAU, retention curves (D1/D7/D30), session length, paywall tap-through, feature engagement
- **Why important:** This is the traction proof investors want. "Here's what X thousand users did on our app."
- **Deliverable:** Metrics dashboard or summary document with charts
- **Reference:** VAULT/08-investor-data-room-checklist.md (Section 6: TestFlight Usage Metrics)

### 14. GDPR/CCPA Technical Implementation
- **What:** Implement GDPR consent flows, data deletion capability, CCPA notice if serving CA/EU users
- **Deliverable:** Technical compliance implementation
- **Reference:** VAULT/08-investor-data-room-checklist.md (Section 8: GDPR/CCPA)

---

## TEAM DECISIONS (Requires All Founders)

### 15. Hours & Commitment Clarification
Answer the following questions (from VAULT/analysis/hours-commitment-questions.md):
1. Breakdown of ~1,000 hours by category
2. Specific technical deliverables from those hours (working prototype? codebase? architecture docs?)
3. Were you employed elsewhere during the 2-year period?
4. Current hours per week commitment
5. Going-forward commitment — when do you plan to go full-time?
6. Will you track hours going forward?

### 16. Incorporation Decision
- **What:** Agree on entity type (Delaware C-Corp recommended), company legal name
- **Reference:** VAULT/09-cap-table.md

### 17. Founder Agreement Review & Sign
- **What:** Review and sign founder agreement once drafted
- **Reference:** VAULT/10-team-governance.md

### 18. 83(b) Election
- **What:** File 83(b) election with IRS within 30 days of stock grant — HARD DEADLINE
- **Reference:** VAULT/09-cap-table.md

### 19. App Name Decision
- **What:** Participate in finalizing app name ("Rumi Sanctuary" recommended)
- **Reference:** documents/RUMI/consciousBiz/app-naming-analysis.md

### 20. Outside Activities Disclosure
- **What:** Disclose all outside activities per founder agreement
- **Deliverable:** Written disclosure
- **Reference:** VAULT/10-team-governance.md

### 21. Founder Join Date
- **What:** Provide official join date for documentation
- **Deliverable:** Date provided
- **Reference:** VAULT/10-team-governance.md

---

## MEDIUM PRIORITY (Before Launch)

### 22. App Store Technical Submission
- **What:** Handle technical requirements for App Store submission (provisioning, signing, build upload)
- **Reference:** VAULT/08-investor-data-room-checklist.md (Section 6: App Store Listing Draft)

### 23. QA Process
- **What:** Own Thursday release builds and Wednesday QA per release train schedule (Phase 1)
- **Reference:** VAULT/06-release-train-schedule.md (Phase 1)

### 24. Validation Cadence Builds
- **What:** Own weekly Thursday TestFlight builds during Phase 0 validation cadence
- **Reference:** VAULT/06-release-train-schedule.md (Phase 0)
