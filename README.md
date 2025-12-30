# ResuMatch (ATS + Resume Matching System)

A production-oriented Job Portal and Applicant Tracking System (ATS) built to simulate real-world hiring workflows.

The platform supports three primary user roles:

1. **Candidate** – Create a profile, upload resumes, apply to job openings, and track application status.
2. **Company (Recruiter)** – Register an organization, post job openings, and review candidate applications.
3. **Admin** – Platform-level role responsible for moderation and system management.

---

## Overview

This project is a full-stack job platform inspired by systems like LinkedIn and Glassdoor.  
It focuses on backend-driven business logic, including role-based access control, secure authentication, and a resume-to-job matching mechanism based on skill overlap and experience weighting.

The goal of this project is to demonstrate real-world system design, database modeling, and backend ownership rather than UI-heavy features.

---

## Core Features

- JWT-based authentication and role-based access control (RBAC)
- Candidate profile and resume management
- Company onboarding and job posting workflow
- Job application lifecycle management (Applied, Shortlisted, Rejected, Hired)
- Resume-to-job matching using skill and experience-based scoring
- Pagination, filtering, and secure API validation

---

## Tech Stack

This application is built as a **pnpm + Turborepo monorepo** with shared types and schemas.

- **TypeScript**
- **Next.js** (Frontend & API routes)
- **Express.js** (Optional backend services)
- **PostgreSQL**
- **Prisma ORM**
- **Zod** (Validation)
- **JWT Authentication**

---

_This README will be updated as the project evolves._
