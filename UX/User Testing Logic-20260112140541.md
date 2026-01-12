# User Testing Logic

The most impactful A/B tests in mobile products focus on onboarding, paywalls/pricing, navigation, and messaging, all tied directly to activation, revenue, or retention. Below are concrete patterns you can copy and adapt.
**Onboarding flow tests**
Improving onboarding is often the highest‑leverage mobile A/B testing area because it hits activation and early retention. Examples:
• Login options
• Variant A: Email/phone only.
• Variant B: Email + Apple/Google/Facebook social login.
• Primary metric: Onboarding completion rate; secondary: day‑1 retention.
• Number of onboarding steps
• Variant A: Minimal 1–2 screens explaining value prop.
• Variant B: Rich multi‑step flow that asks intent, goals, or level (Duolingo‑style).
• Metrics: Completion rate, time‑to‑first‑value, support tickets from new users.
• Progress indicators and checklists
• Variant A: Multi‑screen onboarding, no progress bar.
• Variant B: Same flow with a progress bar and checklist of key actions to complete.
• Metrics: Completion rate, percentage of users hitting “aha” feature.
Paywall and pricing tests
Subscription and IAP apps get outsized gains from systematic paywall experiments.
• Paywall layout and copy
• Variant A: Simple single‑plan paywall, generic headline.
• Variant B: Highlighted “Most popular” plan, social proof, money‑back copy, clearer benefits.
• Metrics: Paywall conversion rate, ARPU, refund rate.
• Price‑point testing
• Variant A: Monthly at 7.99.
• Variant B: Monthly at 9.99.
• Metrics: Conversion to paid, ARPU/LTV, churn; don’t judge by conversion alone.
• Trial length and offer framing
• Variant A: 3‑day free trial, then full price.
• Variant B: 7‑day free trial, or “50% off first 3 months” intro offer.
• Metrics: Trial start rate, trial‑to‑paid conversion, 60–90 day retention.
• Plan structure
• Variant A: Monthly only.
• Variant B: Monthly + discounted annual, or bundled features vs unbundled.
• Metrics: Revenue per install, plan mix, churn by plan.
Navigation and in‑app UX tests
These tests remove friction to reach the core action and are usually easy to implement.
• Primary navigation structure
• Variant A: Bottom nav with 3 core tabs.
• Variant B: Bottom nav with 5 tabs, or different labeling/ordering.
• Metrics: Time to first key event, feature adoption rate, session length.
• CTA position and prominence
• Variant A: Primary CTA below the fold or in secondary color.
• Variant B: Above‑the‑fold, high‑contrast CTA, clearer verb (“Start workout” vs “Continue”).
• Metrics: Click‑through to next step, task completion rate.
• Empty states and helper UI
• Variant A: Blank screens when no data yet (e.g., no saved items).
• Variant B: Guided empty states with example content, tips, and CTA to create/import.
• Metrics: Creation of first item/project, bounce rate from empty screens.
Messaging, nudges, and push tests
Push and in‑app messaging tests are fast, iterative, and directly tied to engagement.
• Push notification copy
• Variant A: Generic “Reminder” message.
• Variant B: Personalized copy with user name, last activity, or streak (“Ben, your 3‑day streak is on the line”).
• Metrics: Push open rate, app opens per user, target event completion.
• Send time and trigger rules
• Variant A: Fixed time (e.g., 9am local) for all users.
• Variant B: Time based on last active or behavior triggers (e.g., 24 hours after cart add but no purchase).
• Metrics: Open rate, conversion from notification to purchase/feature use.
• In‑app upsell prompts
• Variant A: One generic upsell modal after signup.
• Variant B: Contextual prompts when user hits a specific threshold (e.g., 3rd session, feature limit).
• Metrics: Click‑through on upsell, conversion to paid, user complaints.
Key metrics and guardrails
Measuring the right outcomes is as important as the variant design.
• Core metrics to watch
• Activation: Onboarding completion, first key action, time‑to‑value.
• Engagement: Session frequency, feature adoption, push open rate.
• Monetization: Paywall conversion, ARPU, LTV, refund rate.
• Retention: Day‑1 / day‑7 / day‑30 retention; churn by variant.
• Guardrails
• Always segment by platform (iOS/Android), channel (organic vs paid), and cohort date when possible.
• Avoid shipping winners that only improve vanity metrics (e.g., more trials but worse churn) by pairing conversion with retention/revenue.
If you share what kind of mobile product you are running (content, utility, subscription, marketplace, etc.), a short list of 3–5 high‑impact test ideas can be tailored specifically to that context.