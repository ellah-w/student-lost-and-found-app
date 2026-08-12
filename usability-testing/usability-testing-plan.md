# Usability Testing Plan — Campus Lost & Found App

*Prepared for Member 7 (Testing Lead), Phase 3. Testing plan built from the screen inventory, user flows, and navigation hierarchy documented in `docs/user-flows-and-navigation.md` (Member 4).*

## Purpose

To evaluate whether real students can successfully complete the core lost-and-found tasks using the Balsamiq prototype built by the three Scenario teams (A: Report Lost, B: Search & Filter Found, C: Submit & Track Claim), and to surface specific usability problems before final iteration and submission.

## Participants

- Minimum 5 students, per the assignment's usability testing requirement.
- Ideally a mix of students who've actually lost/found something on campus before and those who haven't — the app needs to work for both a stressed first-time user and a casual browser.

## Method

- **Format:** Moderated walkthrough using the Balsamiq prototype's linked screens (click-through mode).
- **Task delivery:** One task at a time, read aloud, without explaining the navigation path in advance.
- **Recording:** Completion (Y/N/Partial), approximate time, wrong taps/backtracks, hesitation points, and think-aloud comments.
- **Think-aloud:** Participants narrate what they expect to happen as they navigate — this is especially useful for the claim-verification flow (Screens 9–11), which is the most novel/unfamiliar interaction in the app.
- **Assistance:** Only when a participant is fully stuck; log when and why it was given.

## Tasks

Each task is mapped to the flow letter and screens it exercises, per `docs/user-flows-and-navigation.md`.

| # | Task given to participant | Flow / Screens | Success Criteria |
|---|---|---|---|
| 1 | "Log in to the app." | Login (Screen 1) | Participant completes login without confusion about email/password vs. Google sign-in |
| 2 | "You lost your water bottle near the library yesterday. Report it as lost." | Flow A — Screens 2, 3, 5 | Participant reaches Report Lost Item, fills key fields, and reaches Confirmation |
| 3 | "You found a student ID card in the cafeteria. Report it as found." | Flow B — Screens 2, 4, 5 | Participant reaches Report Found Item, uploads/attempts photo, reaches Confirmation |
| 4 | "Without submitting anything — browse the found items feed and find anything that looks like a water bottle." | Flow C — Screens 2, 6 | Participant reaches Found Items feed and visually scans/identifies an item |
| 5 | "Use search or filters to narrow the found items down to a specific location or category." | Flow C — Screens 2, 7 | Participant finds and correctly uses Search & Filter, gets a narrowed results list |
| 6 | "Open an item's details page and start a claim for it." | Flow D — Screens 8, 9 | Participant reaches Item Details, finds Claim Item button, reaches the claim form |
| 7 | "Without me explaining it — what do you think happens at this 'Verifying Your Claim' step?" | Flow D — Screen 10 | Participant correctly infers this step compares their description to the finder's, unprompted |
| 8 | "Check the current status of a claim you've submitted." | Flow D — Screen 11 | Participant finds and correctly reads the Claim Status Tracker (Submitted → Verification → Under Review → Decision) |
| 9 | "Find out where to actually pick up an item once your claim is approved." | Flow D — Screen 12 | Participant reaches Drop-off Location and can describe where/how to collect the item |
| 10 | "Check your claim history and account settings." | Flow E — Screen 13 | Participant finds Profile via bottom nav and locates claim history |

## Recording Template

| Participant # | Task # | Completed? (Y/N/Partial) | Time / attempts | Wrong turns or hesitation | Notable comment (think-aloud) |
|---|---|---|---|---|---|
| | | | | | |

*(Duplicate per participant, or keep one long table across all 5 participants × 10 tasks — whichever your group finds easier to manage.)*

## Post-Task Questions

1. Which task felt hardest, and why?
2. At the "Verifying Your Claim" step — did it feel trustworthy, or unclear what was being checked?
3. Was there any point where you weren't sure what to do next?
4. Did the bottom navigation (Home, Search, Claims, Profile) make it easy to find your way back?
5. On a scale of 1–5, how confident would you feel using this for a real lost item?

## Severity Rating

- **Critical** — task could not be completed at all
- **Major** — task completed but only with significant confusion/backtracking
- **Minor** — task completed smoothly but participant commented on friction or confusion
- **Cosmetic** — no functional impact, purely a visual/wording suggestion

## Notes on Likely Risk Areas

Worth paying particular attention to during testing, based on the navigation structure alone:

- **Screens 9–11 (Claim → Verification → Status Tracker)** form the longest, most unfamiliar chain in the app — this is where Task 7's comprehension check matters most. If participants don't understand *why* verification happens, trust in the whole claim process suffers.
- **Search & Filter (Screen 7) vs. the plain Found Items feed (Screen 6)** are two ways to reach the same destination (Item Details) — worth watching whether participants naturally discover both paths or only ever use one.
- **Report Found Item (Screen 4)** asks for a photo upload plus identifier tags — this is more effortful than Report Lost Item (Screen 3); if participants stall here, it may indicate the found-item reporting flow needs to feel more worthwhile/rewarded to complete.

## Next Step

Once testing is complete, findings go into `usability-testing/` (severity-rated issue list per the template above), feeding directly into `iterations/` — where Member 8 documents the specific before/after change made for each Major or Critical issue.# Usability Testing Plan — Campus Lost & Found App

*Prepared for Member 7 (Testing Lead), Phase 3. Testing plan built from the screen inventory, user flows, and navigation hierarchy documented in `docs/user-flows-and-navigation.md` (Member 4).*

## Purpose

To evaluate whether real students can successfully complete the core lost-and-found tasks using the Balsamiq prototype built by the three Scenario teams (A: Report Lost, B: Search & Filter Found, C: Submit & Track Claim), and to surface specific usability problems before final iteration and submission.

## Participants

- Minimum 5 students, per the assignment's usability testing requirement.
- Ideally a mix of students who've actually lost/found something on campus before and those who haven't — the app needs to work for both a stressed first-time user and a casual browser.

## Method

- **Format:** Moderated walkthrough using the Balsamiq prototype's linked screens (click-through mode).
- **Task delivery:** One task at a time, read aloud, without explaining the navigation path in advance.
- **Recording:** Completion (Y/N/Partial), approximate time, wrong taps/backtracks, hesitation points, and think-aloud comments.
- **Think-aloud:** Participants narrate what they expect to happen as they navigate — this is especially useful for the claim-verification flow (Screens 9–11), which is the most novel/unfamiliar interaction in the app.
- **Assistance:** Only when a participant is fully stuck; log when and why it was given.

## Tasks

Each task is mapped to the flow letter and screens it exercises, per `docs/user-flows-and-navigation.md`.

| # | Task given to participant | Flow / Screens | Success Criteria |
|---|---|---|---|
| 1 | "Log in to the app." | Login (Screen 1) | Participant completes login without confusion about email/password vs. Google sign-in |
| 2 | "You lost your water bottle near the library yesterday. Report it as lost." | Flow A — Screens 2, 3, 5 | Participant reaches Report Lost Item, fills key fields, and reaches Confirmation |
| 3 | "You found a student ID card in the cafeteria. Report it as found." | Flow B — Screens 2, 4, 5 | Participant reaches Report Found Item, uploads/attempts photo, reaches Confirmation |
| 4 | "Without submitting anything — browse the found items feed and find anything that looks like a water bottle." | Flow C — Screens 2, 6 | Participant reaches Found Items feed and visually scans/identifies an item |
| 5 | "Use search or filters to narrow the found items down to a specific location or category." | Flow C — Screens 2, 7 | Participant finds and correctly uses Search & Filter, gets a narrowed results list |
| 6 | "Open an item's details page and start a claim for it." | Flow D — Screens 8, 9 | Participant reaches Item Details, finds Claim Item button, reaches the claim form |
| 7 | "Without me explaining it — what do you think happens at this 'Verifying Your Claim' step?" | Flow D — Screen 10 | Participant correctly infers this step compares their description to the finder's, unprompted |
| 8 | "Check the current status of a claim you've submitted." | Flow D — Screen 11 | Participant finds and correctly reads the Claim Status Tracker (Submitted → Verification → Under Review → Decision) |
| 9 | "Find out where to actually pick up an item once your claim is approved." | Flow D — Screen 12 | Participant reaches Drop-off Location and can describe where/how to collect the item |
| 10 | "Check your claim history and account settings." | Flow E — Screen 13 | Participant finds Profile via bottom nav and locates claim history |

## Recording Template

| Participant # | Task # | Completed? (Y/N/Partial) | Time / attempts | Wrong turns or hesitation | Notable comment (think-aloud) |
|---|---|---|---|---|---|
| | | | | | |

*(Duplicate per participant, or keep one long table across all 5 participants × 10 tasks — whichever your group finds easier to manage.)*

## Post-Task Questions

1. Which task felt hardest, and why?
2. At the "Verifying Your Claim" step — did it feel trustworthy, or unclear what was being checked?
3. Was there any point where you weren't sure what to do next?
4. Did the bottom navigation (Home, Search, Claims, Profile) make it easy to find your way back?
5. On a scale of 1–5, how confident would you feel using this for a real lost item?

## Severity Rating

- **Critical** — task could not be completed at all
- **Major** — task completed but only with significant confusion/backtracking
- **Minor** — task completed smoothly but participant commented on friction or confusion
- **Cosmetic** — no functional impact, purely a visual/wording suggestion

## Notes on Likely Risk Areas

Worth paying particular attention to during testing, based on the navigation structure alone:

- **Screens 9–11 (Claim → Verification → Status Tracker)** form the longest, most unfamiliar chain in the app — this is where Task 7's comprehension check matters most. If participants don't understand *why* verification happens, trust in the whole claim process suffers.
- **Search & Filter (Screen 7) vs. the plain Found Items feed (Screen 6)** are two ways to reach the same destination (Item Details) — worth watching whether participants naturally discover both paths or only ever use one.
- **Report Found Item (Screen 4)** asks for a photo upload plus identifier tags — this is more effortful than Report Lost Item (Screen 3); if participants stall here, it may indicate the found-item reporting flow needs to feel more worthwhile/rewarded to complete.

## Next Step

Once testing is complete, findings go into `usability-testing/` (severity-rated issue list per the template above), feeding directly into `iterations/` — where Member 8 documents the specific before/after change made for each Major or Critical issue.