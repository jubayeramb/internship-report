# Internship Context & Knowledge Base

This document summarizes the details of **Jubaer Al Mamun's** industrial training at **Tanbel Inc.** (Parent of WeCycle/ArrayQ), extracted from the internship report. It is intended to serve as a context source for updating the report or generating future documentation.

## 1. Intern Profile

- **Name:** Jubaer Al Mamun
- **Student ID:** 221902013
- **University:** Green University of Bangladesh (Dept. of CSE)
- **Role:** Full-Stack Web Development
- **Internship Period:** October 13, 2025 – December 5, 2025 (8 Weeks)
- ** Supervisors:**
  - _Academic:_ Md. Parvez Hossain (Lecturer, Dept. of CSE)
  - _Industrial:_ MD Tanvir Ahmed (Tanbel Inc.)

## 2. Organization Profile

- **Company:** Tanbel Inc. (US-based remote tech startup).
- **Products:**
  1.  **WeCycle (B2C):** On-demand junk removal platform for homeowners/businesses. "Uber for junk."
  2.  **ArrayQ (B2B):** SaaS CRM and dashboard for haulers to manage dumpsters/inventory.
- **Work Culture:** Remote, Agile/Scrum (Jira), Fast-paced startup environment.

## 3. Technology Stack

The intern worked as a **Full-Stack Developer**, covering frontend, backend, mobile, and devops.

- **Languages:** TypeScript, JavaScript (ES6+).
- **Frontend:** React.js, Next.js (App Router), Tailwind CSS, shadcn/ui.
- **Mobile:** Capacitor.js (Cross-platform), React Native.
- **Backend:** Node.js, Express.js.
- **Database:** MongoDB, PostgreSQL.
- **DevOps/Infra:** Docker, Nginx, DigitalOcean (Droplets), GitHub Actions (CI/CD), Nx Monorepo.
- **Tools:** Jira (Project Management), Git/GitHub, Stripe (Payments), Ring Central (SMS integration), Listmonk (Email), AI Chat SDKs.

## 4. Key Projects & Responsibilities

### A. WeCycle Dashboard & Platform (Maintenance & Features)

- **UI Migration:** Migrated legacy **Ant Design** components to a custom internal UI library.
- **Responsive Design:** Fixed critical layout issues for **iPad/Tablet** devices (15+ components).
- **Features:**
  - Implemented "Job Completion" flow directly from dashboard.
  - Refactored Invoice and Booking IDs to be human-readable.
  - Added CSV Export for junk removal items.
  - Implemented mandatory OTP phone verification.
  - Integrated Trustpilot review requests in emails.

### B. ArrayQ Platform (New Brand Launch)

- **Launch:** Developed and deployed the **ArrayQ landing page** and configured the domain.
- **Branding:** Implemented multi-tenant branding (dynamic logos/themes) to separate WeCycle and ArrayQ identities within the same codebase.
- **Mobile:** Updated mobile app assets (splash screens, build IDs) for ArrayQ Store submission.
- **Support:** Created support and privacy policy pages.

### C. Financial Infrastructure

- **Stripe Connect:** Implemented Stripe Connected Accounts to allow haulers to receive payouts directly.
- **Invoicing:** Modernized the invoice system with dynamic logos, hauler contact info, and payment links.
- **Pricing Display:** Logic to hide individual item prices on mobile (showing subtotal only) to simplify UX.

### D. DevOps & AI

- **Chatbot:** Deployed a production AI chatbot service on a DigitalOcean droplet (Dockerized, Nginx, SSL).
- **CI/CD:** Optimized build times and configured GitHub Actions.
- **Environments:** Set up Staging and Pre-Production environments for safer testing.

## 5. Timeline & Weekly Highlights

- **Week 1:** Environment setup (Capacitor), mobile nav fixes.
- **Week 2:** Chatbot deployment, Docker setup, Staging DB sync.
- **Week 3:** CSV exports, ArrayQ project init, GDPR account deletion.
- **Week 4:** Branding/Theming for ArrayQ, Invoice logic updates.
- **Week 5:** RBAC (Blog Manager), Mobile Store prep, Discounts debugging.
- **Week 6:** App Store compliance/reviews, Blog caching/performance fixes.
- **Week 7:** Security (OTP), Pre-prod setup, SMTP fixes.
- **Week 8:** Stripe Connect implementation, Next.js/React version upgrades, HO.

## 6. Skills & Outcomes (Mapped to POs/SDGs)

- **Technical:** Advanced Next.js (SSR), Type-Safe Data Fetching, automated CI/CD pipelines, accessible mobile UI design.
- **Soft Skills:** Remote communication, Jira ticket management, breaking down complex barriers, agile velocity.
- **SDG Impact:** Contributed to **Sustainable Cities (SDG 11)** and **Responsible Consumption (SDG 12)** by digitizing waste management.
