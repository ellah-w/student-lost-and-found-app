# User flows and navigation hierarchy

**Prepared by:** Member 4 (Information Architect)
**Purpose:** Maps out how users move through the app for each of the three core scenarios, and how all screens fit together in one navigation structure. This is the blueprint the Week 2 design teams (Scenario A, B, C) build their Balsamiq screens from.

---

## 1. User flows

Each flow below matches the screens already assigned to the design teams in the task allocation.

### Scenario A — Report a lost item
**Team:** Member 1 & Member 5

Home → Report lost item form → Category/photo upload → Confirmation

A student opens the app from the home screen, fills in a form describing the item they lost, adds a category and photo, and receives a confirmation that their report was submitted.

### Scenario B — Search and filter found items
**Team:** Member 6 & Member 7

Found feed → Search & filter modal → Item details → Drop-off location map

A student browses the feed of found items, narrows results using search and filters, opens an item's details, and views where it can be picked up.

### Scenario C — Submit and track a claim
**Team:** Member 8 & Member 2

Claim request form → Verification step → Claim status tracker → User profile/history

After finding a matching item, a student submits a claim, verifies ownership, and tracks the claim status until it's resolved. Past claims and reports appear in their profile.

---

## 2. Navigation hierarchy

This shows how the ~12 screens sit together as one app — not just the linear paths above, but what's a home-level screen versus what's nested inside another flow.

```
Home
├── Report section
│   ├── Report lost item form
│   │   └── Category/photo upload
│   │       └── Confirmation
├── Found section
│   ├── Found feed
│   │   └── Search & filter modal
│   │       └── Item details
│   │           ├── Drop-off location map
│   │           └── Claim request form (enters claim flow)
├── Claim section
│   ├── Verification step
│   │   └── Claim status tracker
│   │       └── User profile/history
```

**Notes for the design teams:**
- Home is the single entry point; Report and Found are the two main paths a user chooses between.
- The claim flow is reached *from* item details (Found section), not from Home directly — it's the natural next step after finding a match.
- Confirmation, claim status, and profile screens are end-states or persistent references, not dead ends — they should always offer a way back to Home.

---

## 3. Diagrams

See the attached flow diagram and navigation hierarchy diagram (screenshots) in this folder for the visual versions of the above.

## 4. Paper sketches

Low-fidelity paper sketches of each of the 12+ screens are stored separately in `wireframes/sketches/`.
