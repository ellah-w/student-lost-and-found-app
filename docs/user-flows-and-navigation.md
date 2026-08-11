# User Flows and Navigation Hierarchy
 
**Prepared by:** Member 4 (Information Architect)

**Based on:** the Balsamiq screens already built by the Scenario A, B, and C design teams.

**Purpose:** documents how the app's screens connect, so the structure is traceable before usability testing.
 
---
 
## 1. Screen inventory
 
The prototype currently has screens across login, reporting, browsing/claiming, and profile.
 
| # | Screen | What it does |
|---|--------|---------------|
| 1 | Login | Student signs in with email/password or Google |
| 2 | Home / Dashboard | Entry hub — search bar, Report Lost, Report Found, Browse Items, My Reports |
| 3 | Report Lost Item | Item name, description, location lost, date, category |
| 4 | Report Found Item | Photo upload, identifier tags (colour, brand), contact preference |
| 5 | Confirmation | Shows report ID and submission date; links to My Reports or Home |
| 6 | Found Items feed | Grid of found items with photo, name, date, location |
| 7 | Search & Filter | Search bar plus category/location filters, results list |
| 8 | Item Details | Full item info with a Claim Item button |
| 9 | Claim This Item | Claim form — reason, location lost, name, contact |
| 10 | Verifying Your Claim | Compares finder's description to the claimant's, shows pickup point |
| 11 | Claim Status Tracker | Step tracker: Submitted → Verification → Under Review → Decision |
| 12 | Drop-off Location | Campus map, collection point, landmark, directions, contact |
| 13 | Profile | Stats, claim history list, account settings, logout |
 
---
 
## 2. User flows
 
### Flow A — Report a lost item
Login → Home → Report Lost Item → Confirmation → Return Home / View My Reports
 
### Flow B — Report a found item
Login → Home → Report Found Item → Confirmation → Return Home / View My Reports
 
### Flow C — Browse and search found items
Login → Home → Found Items feed **or** Search & Filter → Item Details
 
### Flow D — Claim an item
Item Details → Claim This Item → Verifying Your Claim → Claim Status Tracker → Drop-off Location
 
### Flow E — View profile
Home (bottom nav) → Profile

<img width="406" height="308" alt="image" src="https://github.com/user-attachments/assets/d9a91e10-c1b8-4719-8f64-fed854991f8e" />

 
---
 
## 3. Navigation hierarchy
 
```
Login
└── Home / Dashboard
    ├── Report Lost Item
    │   └── Confirmation
    ├── Report Found Item
    │   └── Confirmation
    ├── Found Items feed
    │   └── Item Details
    │       ├── Claim This Item
    │       │   └── Verifying Your Claim
    │       │       └── Claim Status Tracker
    │       │           └── Drop-off Location
    ├── Search & Filter
    │   └── Item Details (same as above)
    └── Profile (bottom nav tab)
```
 
Bottom navigation is consistent across the core screens (Home, Search, Claims, Profile), which is good for orientation — a user should always have a way back to Home.
 
---
 
## 5. Paper sketches
 
Low-fidelity paper sketches for each screen are stored separately in `wireframes/sketches/`.
