# Target User Description & User Research Summary

**Project:** Student Lost-and-Found Mobile App **Prepared by:** Member 2 – User Researcher **Folder:** `research/`

## 1. Target User Description

The app is for university students who lose or find personal items on campus — most commonly **student/school IDs**, but also other belongings (e.g. pencil cases). Right now, students rely entirely on informal channels: **class WhatsApp groups** and the **security office**. These work sometimes, but are slow, unstructured, and easy to miss. Trust is a major concern for this user group — several participants raised fears about fraudulent claims, scams, or even extortion during the recovery process, so the app needs to make ownership verification and safe handover a core part of the experience, not an afterthought.

## 2. Research Method

Since live interviews weren't feasible on everyone's schedule, research was conducted via **structured written responses collected from a class WhatsApp group** (9 members, 5 responded), using the same 5 questions for each participant. This is a valid substitute for live interviews — it still reflects real users answering real questions, just asynchronously.

## 3. Findings Summary

| Participant | Experience | Current method used | Key desired feature | Data comfortable sharing | Main concern |
| - | - | - | - | - | - |
| P1 | Lost a pencil case; recovered via class group chat | Asked in class WhatsApp group | Notification when a lost item is recovered | Photo (if available), description, name/contact | Too much personal data required + charging a fee |
| P2 | Found a national ID; connected to owner via a contact who posted it | Sent photo to someone who posted it, then linked to owner | A "found item" posting flow: finder posts photo + contact, owner reaches out — saves time for everyone | Photo, contact info | Scams — false claimants guessing descriptions, or luring people to unsafe meetups |
| P3 | Lost student ID; found it later at security office | Asked friends, WhatsApp groups, visited security office | Instant notification if someone reports finding a matching item | Photo, brief description, location lost, contact info | Personal info security; risk of fake reports |
| P4 | Found a school ID | Asked in WhatsApp groups | Ability to match the report to the correct (real) owner | Photo, description | Wrong/dishonest people accepting items that aren't theirs |
| P5 | Lost school ID | Asked in WhatsApp groups + security office | A dedicated platform to post lost/found items for owners to collect | Description, contact info | Financial extortion by the person who found the item |



## 4. Key Themes

1. **Current behavior is informal and channel-fragmented.** 4 of 5 participants rely on class WhatsApp groups, and several also mentioned the security office as a fallback — but neither is searchable, filterable, or reliable long-term.

2. **IDs are the most commonly lost/found item mentioned.** 4 of 5 stories involved a student/national ID specifically — worth highlighting in personas and maybe as a default "item category" in the reporting form.

3. **Notifications matter.** Multiple participants (P1, P3) specifically want to be notified automatically when a matching item is found, rather than having to keep checking manually.

4. **Trust and safety is the dominant concern, not usability.** Every single participant raised some version of a fraud/security worry: fake claims (P3, P4), fee-charging (P1), scams around descriptions (P2), or extortion (P5). This is the strongest and most consistent signal from the research.

## 5. Design Implications (feeds directly into Scenario C: Submit & Track Claim)

- **Verification Step is essential, not optional.** Since trust/fraud was the \#1 concern across all 5 participants, the Claim flow (Screens 9-12) should require the claimant to confirm specific details (e.g. unique markings, exact location lost) before contact info is exchanged — rather than a simple "I claim this" button.

- **Avoid requiring excessive personal data.** P1 explicitly flagged over-collection of personal data as a deterrent — the claim form should ask only for what's needed to verify ownership (photo/description match, basic contact), not more.

- **No fees, ever.** P1's concern about being charged to recover a lost item should be treated as a hard design constraint — make clear in the UI that reporting/claiming is free.

- **Build in notifications.** Supports Member 4's user flow and the app's core loop — a "notify me if found" toggle on lost reports directly answers P1 and P3.

- **Safety around handover.** P2 and P5's concerns about unsafe meetups/extortion suggest the Claim Status Tracker (Screen 11-12) should recommend safe pickup locations (e.g. security office) rather than open-ended private meetups.
