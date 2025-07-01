# Project Charter: Job Tracker App

**Document Version:** 1.0<br/>
**Date:** June 30, 2025

### 1. Vision

To create a streamlined, personal tool that helps a job seeker to effectively manage and track their application process.

### 2. Mission & Problem Statement

**Mission:** To develop, launch, and manage a simple web application that allows a user to manually add job postings and visualize their application pipeline, all within a one-week initial development sprint (Phase 1).

**Problem Statement:** The process of applying for multiple jobs is chaotic. While comprehensive job tracking platforms exist, they are often overly complex, require subscriptions, or are cluttered with features unnecessary for a user who simply wants a lightweight, visual, and personal Kanban board for their job search. As a result, many job seekers revert to spreadsheets, lacking a purpose-built tool that is both simple and effective.

### 3. Goals & Objectives

- **Objective 1: Initial MVP Launch (Phase 1):** Deploy a minimum viable product (MVP) of the web application to a public-facing platform within 1 week. The application must be functional and meet the "In-Scope" criteria.
- **Objective 2: Core Functionality (Phase 1):** Implement the ability to manually add, view, update, and delete job applications (full CRUD) within the 1-week MVP sprint.

### 4. Scope

### In Scope (Phase 1 - MVP):

- A single-page web application.
- Manual entry of job information (Company, Role Title, Date Applied, Status, URL to posting, Other Info).
- A Kanban-style board view to drag-and-drop jobs between statuses.
- Data persistence using Google Firestore.
- Clean, simple, and mobile-responsive user interface.

### Out of Scope (for Phase 1 - MVP):

- User accounts or authentication.
- Automated web scraping of job boards.
- Email or calendar integrations.

### 5. Key Assumptions & Constraints

- **Assumptions:**
    - The user has access to a modern web browser.
    - The functionality of third-party services (GitHub, Firestore, hosting platform) will remain stable.
    - The primary user is technically proficient enough to manually input job data.
- **Constraints:**
    - **Schedule:** The project has a 1-week deadline for the MVP.
    - **Resources:**  This project is executed without a financial budget; all technologies must be available at no cost.
    - **Technology:** The project must be built using web technologies (HTML, CSS, JS) and Google Firestore.
    - **Scope:** The features are strictly limited to those defined as "In Scope" for Phase 1.

### 6. Timeline & Milestones

- **Timeline:**
    - **Day 1:** Project Setup & Planning, & **UI/UX Wireframing**.
    - **Days 2-5:** **Parallel Development**:
        - *Backend:* Firestore database setup and CRUD API development.
        - *Frontend:* UI implementation based on wireframes.
    - **Day 6:** Integration & Testing (Connecting frontend to backend, bug fixing).
    - **Day 7:** Deployment & Project Wrap-up.
- **Key Deliverables & Milestones:**
    - **Deliverable:** A finalized Project Charter.
    - **Deliverable:** A complete product backlog in GitHub Issues.
    - **Milestone:** Backend API for job management is functional.
    - **Milestone:** Frontend UI is complete and interactive.
    - **Final Deliverable:** The MVP application is deployed and publicly accessible.
    - **Final Deliverable:** A written Project Retrospective is published.

### 7. Future Roadmap (Potential Phase 2)

- **Feature:** Automated Job Ingestion.
- **Feature:** User Accounts.

### 8. Success Metrics

1. **Project Milestone:** The Phase 1 MVP is successfully deployed by the end of week one.
2. **Functionality:** The application allows for full CRUD operations on job postings without critical bugs.
3. **Project Governance:** Key project artifacts (this charter, backlog, retrospective) are created.

### 9. Stakeholders

- **Project Lead / Backend Developer:** Haritha Ravi
- **Frontend Developer:** Abhijith Kalayil Shaji
