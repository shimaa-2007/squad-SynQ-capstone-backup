## Squad Roster & Role Matrix

| Member Name | Assigned Role | Primary Module / Ownership |
| :--- | :--- | :--- |
| Shimaa | Git & QA Release Lead | Branch protection, PR release checks, testing & bug triage |
| Jana | Frontend State & Logic Lead | Client state management, BOM/localStorage logic, core UI interactions |
| Sohaila | Product & UI/UX Lead | Wireframes, design system, responsive layouts, user flows |
| Rahma | Backend & Data Lead | REST API endpoints, database schema, authentication & CRUD logic |
## 2. Problem Statement & Target Users

### Problem Statement

University students often face challenges when working on group projects, including unclear task responsibilities, unequal workload distribution, missed deadlines, scattered project files, and difficulties tracking individual contributions.

Instructors also struggle to monitor team progress and evaluate each student's actual contribution fairly.

TeamUp aims to solve these problems by providing a centralized platform for university project management, task assignment, progress tracking, evidence-based submissions, and contribution reporting.

Unlike general-purpose project management tools, TeamUp focuses on academic teamwork, accountability, and documented student contributions.

### Target Users

| User | Needs |
|---|---|
| University Students | Manage assigned tasks, track deadlines, submit work, and document their contributions. |
| Team Leaders | Organize projects, assign tasks, monitor progress, review submissions, and identify workload imbalances. |
| Instructors / Teaching Assistants | Monitor project progress, review documented contributions, and support fair student evaluation. |

### Project Objective

To improve collaboration, transparency, and accountability in university group projects by providing a structured environment where tasks, responsibilities, submissions, and individual contributions can be tracked and reviewed.
## 3. Core MVP Features (Weeks 5–24 Roadmap)
1. **Responsive Event Directory (Frontend UI):** Grid layout displaying campus events with category tags.
2. **Saved Bookmarks & Preferences (Client State/BOM):** Using `localStorage` to save bookmarked events and theme settings across reloads.
3. **Event Management (CRUD / REST API):** Creating, reading, updating, and deleting events via backend API calls.
4. **Role-Based Access (Authentication):** Separate login flows for students and club organizers.
