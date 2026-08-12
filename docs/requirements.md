# Functional & Usability Requirements — Campus Lost & Found App

*Derived from `docs/user-flows-and-navigation.md` (screen inventory, flows A–E) and the two personas in `docs/personas.md`.*

## 1. Functional Requirements

### 1.1 Authentication

| ID | Requirement | Persona need | Screen(s) |
|---|---|---|---|
| FR-1.1 | User can log in with email/password or Google sign-in | Fast entry for both personas, especially Amina when stressed | Login |

### 1.2 Home & Navigation

| ID | Requirement | Persona need | Screen(s) |
|---|---|---|---|
| FR-2.1 | Home screen provides a search bar and quick entry points: Report Lost, Report Found, Browse Items, My Reports | Both personas need to reach their goal in one tap from entry | Home / Dashboard |
| FR-2.2 | Bottom navigation (Home, Search, Claims, Profile) is present and consistent across core screens | Both personas need a reliable way back to Home | All core screens |

### 1.3 Reporting

| ID | Requirement | Persona need | Screen(s) |
|---|---|---|---|
| FR-3.1 | User can report a lost item with name, description, location lost, date, and category | Amina needs a fast, low-friction form while details are fresh | Report Lost Item |
| FR-3.2 | User can report a found item with photo upload, identifier tags (colour, brand), and contact preference | David needs this to feel quick and low-effort, not a chore | Report Found Item |
| FR-3.3 | Submitting either report produces a confirmation with a report ID and submission date, linking to My Reports or Home | Amina needs concrete proof the report "went somewhere" | Confirmation |

### 1.4 Browsing & Search

| ID | Requirement | Persona need | Screen(s) |
|---|---|---|---|
| FR-4.1 | User can browse a feed of found items showing photo, name, date, and location | Supports casual browsing for a lost item | Found Items feed |
| FR-4.2 | User can search and filter found items by category/location | Narrows results for users with a specific item in mind | Search & Filter |
| FR-4.3 | User can view full item details, including a Claim Item action | Bridges browsing to the claim flow | Item Details |

### 1.5 Claiming

| ID | Requirement | Persona need | Screen(s) |
|---|---|---|---|
| FR-5.1 | User can submit a claim with reason, location lost, name, and contact details | Amina needs to formally assert ownership | Claim This Item |
| FR-5.2 | System compares the finder's description against the claimant's submitted description | Directly addresses Amina's "false claim" trust concern | Verifying Your Claim |
| FR-5.3 | User can track claim status through defined stages: Submitted → Verification → Under Review → Decision | Reduces anxiety via visible progress, no need to chase anyone | Claim Status Tracker |
| FR-5.4 | User can view drop-off/collection location details: campus map, landmark, contact | Closes the loop for both personas — where does the item physically go | Drop-off Location |

### 1.6 Profile

| ID | Requirement | Persona need | Screen(s) |
|---|---|---|---|
| FR-6.1 | User can view stats, claim history, account settings, and log out | Both personas want a record of past activity | Profile |

## 2. Non-Functional / Usability Requirements

| ID | Requirement | HCI Principle | Relevant Screens |
|---|---|---|---|
| NFR-1 | Report Lost/Found forms must be completable in under a minute for a typical case | Efficiency of use | Report Lost Item, Report Found Item |
| NFR-2 | Every submission (report, claim) must give immediate, clear confirmation that it was received | Visibility of system status | Confirmation, Claim Status Tracker |
| NFR-3 | The Verifying Your Claim step must clearly communicate what is being compared and why, without requiring the user to guess | Visibility of system status / user trust | Verifying Your Claim |
| NFR-4 | Claim Status Tracker must show all stages at once (not just the current one), so users understand what's ahead as well as what's done | Visibility of system status, reduce anxiety | Claim Status Tracker |
| NFR-5 | Bottom navigation must remain identical and present across all core screens | Consistency, recognition over recall | Home, Found Items feed, Search & Filter, Item Details, Profile |
| NFR-6 | Found Items feed and Search & Filter must both lead to the same Item Details screen without divergent behavior | Consistency & standards | Found Items feed, Search & Filter, Item Details |
| NFR-7 | Report Found Item's photo upload must not block submission if a photo can't be taken (e.g. allow text-only identifier tags as fallback) | Error prevention / flexibility | Report Found Item |
| NFR-8 | Drop-off Location must be understandable without requiring the user to already know campus landmarks | Learnability | Drop-off Location |
| NFR-9 | All touch targets must be sized appropriately for mobile use | Mobile usability / error prevention | All screens |
| NFR-10 | Claim form fields must validate input and show specific, actionable error messages | Error prevention & recovery | Claim This Item |

## 3. Traceability Note

If usability testing (see `usability-testing-plan.md`) surfaces problems with Task 7 (comprehension of the Verifying Your Claim step) or Task 3/9 (Report Found Item effort, Drop-off clarity), those findings map directly to NFR-3, NFR-7, and NFR-8 respectively — cite this mapping directly in the final report as evidence of a traceable, principle-driven design process rather than ad hoc fixes.