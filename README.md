# student-lost-and-found-app
HCI Group Project: Student Lost-and-Found Mobile Application prototype designed using Balsamiq and managed with GitHub.
# 📱 Campus Student Lost-and-Found Mobile App

An interactive mobile application prototype designed to streamline reporting, searching, and claiming lost items within the university campus. Built as part of the Human–Computer Interaction (HCI) module.



##  Project Overview
Navigating lost belongings on campus is often fragmented and slow, relying on physical bulletin boards or unorganized social media groups. This project addresses the issue by introducing a centralized, mobile-first platform designed with clear touch interactions, minimal friction forms, and real-time claim status tracking.

- Design Tool: Balsamiq
- Target Platform: Mobile Application (Smartphone)
- Target Users: Students, Teaching & Non-Teaching Staff, Campus Security/Administration



##  Screen Directory & Workflow

### Scenario A: Report a Lost Item
- Screen 1: Home / Dashboard - Central hub featuring search, main action triggers (Report Lost, Report Found), and recent campus listings.
- Screen 2: Basic Information (Form Step 1/2) - Captures basic details including item name, primary category dropdown, date/time lost, and estimated campus location.
- Screen 3: Category & Media Upload (Form Step 2/2) - Handles photo uploads, categorized visual identifier tags (Colour & Brand/Model), and preferred contact methods (Email, Phone Call / SMS, In-App Message).
- Screen 4: Submission Confirmation - Displays reference ID (#LF-2026-089), submission summary, and direct links back to Home or Listing View.

### Scenario B: Search & Filter Found Items
- Screen 5: Search Feed & Filters - Filterable feed sorted by category, building/location, and date range.
- Screen 6: Detailed Item View - Complete item breakdown with founder notes, photo gallery, and claim trigger.
- Screen 7: Search Results & Empty States - Filtered listing results display and user guidance for empty search query states.

### Scenario C: Submit & Track a Claim
- Screen 8: Claim Verification Form (Step 1) - Proof-of-ownership details form (serial numbers, distinguishing marks).
- Screen 9: Claim Proof Upload (Step 2) - Supporting document, receipt, or matching image proof submission.
- Screen 10: Claim Status Tracker - Real-time tracking pipeline from review to campus security pickup approval.

### Supplemental / Navigation Screens
- Screen 11: My Claims / Activity Log - History of reported items and claim submissions.
- Screen 12: Profile & Security Settings - Student identity verification details, privacy controls, and preferences.

---

 Team Members & Responsibilities

| Name | Role | Primary Responsibilities |
| :--- | :--- | :--- |
| Member 1 (Lead) | Project Lead & Co-Designer | Repo administration, README management, and Scenario A Balsamiq wireframes (Screen 3: Media Upload, Screen 4: Confirmation). |
| Member 2 | User Researcher | Field research with 5 campus users, survey design, and Scenario B wireframes (Screen 5: Search Feed, Screen 6: Item View). |
| Member 3 | UX Analyst | Development of Personas, Usability Requirements, and Scenario B wireframes (Screen 7: Search Results & Empty States). |
| Member 4 | Information Architect | User journeys, task flows, low-fi sketches, and Scenario C wireframes (Screen 8: Claim Form, Screen 9: Claim Upload). |
| Member 5 | Lead Balsamiq Designer | Scenario A wireframing (Screen 1: Home Dashboard, Screen 2: Basic Info Form) and global mobile UI layout standards. |
| Member 6 | Assistant Balsamiq Designer | Scenario C wireframing (Screen 10: Claim Status Tracker Pipeline). |
| Member 7 | Usability Testing Lead | Usability test execution with 5 participants, error logging, and Supplemental UI (Screen 11: My Claims Log). |
| Member 8 | Iteration & Deck Lead | Wireframe revisions based on test data, slides, and Supplemental UI (Screen 12: Profile & Settings). |
| Member 9 | Interactive Prototyping Lead | Configured clickthrough links, screen transitions, and interactive flows across all 12 screens in Balsamiq. |

---

Key Application Features & User Scenarios

1. Scenario A: Report a Lost Item
   - Fast form submission with automated item categorization, loss location tagging, visual tags (Colour & Brand), and image uploads.
2. Scenario B: Search & Filter Found Items
   - Search feed with filtering by item category, location, and date found.
3. Scenario C: Submit & Track a Claim
   - Ownership verification process and real-time status updates on claim requests.

---

 Design Guidelines & Conventions

- Color Palette (Wireframe Accents):
  - Primary Action / Active State: #007BFF (Blue)
  - Background / Fill Accents: #CCE5FF (Light Blue)
  - Secondary Text / Placeholders: #6C757D (Gray)
- Interactive Linking: Navigation links (Submit Listing → Confirmation, Return to Home → Dashboard) are mapped directly within the Balsamiq project canvas.



 Repository Structure

├── docs/                 # Problem statement, personas, requirements, and task flows
├── research/             # User research tools, interview scripts, and summaries
├── wireframes/           # Low-fi sketches, Balsamiq project files, and screen exports
├── usability-testing/   # Testing plans, task scenarios, user logs, and evaluation reports
├── iterations/          # Before-and-after screen comparisons following user feedback
└── final/               # Final presentation slides and prototype walkthrough video links
