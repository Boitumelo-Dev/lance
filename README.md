
[![Coverage Status](https://coveralls.io/repos/github/Thuthu-KII/Lance/badge.svg?branch=lance)](https://coveralls.io/github/Thuthu-KII/Lance?branch=lance)

# Freelancer Management Platform (Lance)

A comprehensive web application connecting clients with freelancers, enabling job posting, application, management, and payments with admin oversight.

## Table of Contents
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Installation](#installation)
- [Database Structure](#database-structure)
- [Security Features](#security-features)
- [Usage & Demo](#usage--demo)
- [Project Artifacts](#project-artifacts)
- [License](#license)

## Features

### Clients
- Register and create profile
- Post jobs with budget and details
- View and manage freelancer applications
- Hire freelancers and mark jobs complete
- Generate invoices

### Freelancers
- Register, upload documents (CV, certificates)
- Browse and apply for jobs
- Manage assigned jobs and mark complete
- Track earnings

### Admins
- Approve freelancer registrations
- Manage users and monitor jobs/applications
- Handle reported issues
- Process payments to freelancers
- View system statistics/dashboard

## Technology Stack
- **Backend:** Node.js with Express.js
- **Database:** PostgreSQL
- **Authentication:** Passport.js (Local & Google OAuth)
- **File Upload:** Multer
- **Payment:** Yoco API
- **Frontend:** EJS templates with CSS
- **Security:** Helmet, bcrypt, express-session

## Installation

1. Clone the repo:
   ```bash
   git clone https://github.com/Thuthu-KII/Lance.git
   cd Lance


2. Install dependencies:
   ```bash
   npm install
   ```

3. Create `.env` from `.env.example` and configure environment variables.

4. Setup PostgreSQL and update `DATABASE_URL` in `.env`.

5. Start server:
   ```bash
   npm start
   ```

   For development with auto-reload:
   ```bash
   npm run dev
   ```

6. Access the app at: [http://localhost:3000](http://localhost:3000)

## Database Structure

- `users` — user authentication and core info
- `clients` — client profiles
- `freelancers` — freelancer profiles, including approval status
- `admins` — admin profiles
- `jobs` — job listings with statuses and payment data
- `job_applications` — freelancer applications to jobs
- `payments` — records of payments made
- `reports` — user issue reports
- `job_completions` — tracking job completion status

## Security Features

- Password hashing with bcrypt
- Session management via express-session
- HTTP header protection with Helmet
- CSRF protection
- Input validation with express-validator
- Role-based access control (clients, freelancers, admins)

## Usage & Demo

- [Screen Recording Demo Video](SCREEN_RECORDING_VIDEO_LINK)
- [Publicly Hosted Application](DEPLOYED_APP_LINK)
- **Access Instructions:**
  - Credentials or any special instructions to login/use the app: `<INSTRUCTIONS OR TEST ACCOUNTS HERE>`

## Project Artifacts

- [GitHub Repository](https://github.com/Thuthu-KII/Lance) (public, with full code and commit history)
- **Scrum Artifacts:**
  - [Product Backlog](PRODUCT_BACKLOG_LINK)
  - [Sprint Backlogs](SPRINT_BACKLOGS_LINK)
  - [Sprint Burndown Charts](BURNDOWN_CHARTS_LINK)
  - [Sprint Retrospective Reports](RETROSPECTIVE_REPORTS_LINK)
  - [Daily Stand-Up Summaries](DAILY_STANDUP_SUMMARIES_LINK)
  - [Sprint Review Demonstrations](SPRINT_REVIEW_LINKS_OR_VIDEOS)
- **Additional Design Documents:**
  - [Project Plan](PROJECT_PLAN_LINK)
  - [Architecture Diagram](ARCHITECTURE_DIAGRAM_LINK)
  - [Design Documents (class diagrams, wireframes, etc.)](DESIGN_DOCS_LINK)
  - [Test Plan and Results (including automated test screenshots/logs)](TEST_PLAN_AND_RESULTS_LINK)

## License

This project is licensed under the MIT License.

---

*This README serves as the main navigation document for the Freelancer Management Platform project submission. Replace placeholders with actual links before final submission.*
```

---
