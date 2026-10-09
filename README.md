# CampusOS Frontend

A responsive web application for college management, built using React, Vite, TypeScript, and Tailwind CSS.

---

## Overview

This is the client-side user interface for the CampusOS college management project. It provides distinct views and tools for three user roles:
- **Admin**: Manage departments, courses, faculty allocations, and post campus notices.
- **Faculty**: Take lecture attendance, check low attendance alerts, and enter test marks.
- **Student**: View personal attendance percentage, check class timetables, view marks, and pay pending fees.

---

## Tech Stack

- **Framework**: React 18 with TypeScript
- **Build Tool**: Vite
- **Styling**: Tailwind CSS
- **Routing**: React Router v6
- **Server State & Caching**: TanStack React Query
- **Client State**: Zustand
- **Charts**: Recharts
- **Icons**: Phosphor Icons and Lucide React
- **HTTP Client**: Axios (configured with JWT token interceptors)

---

## Getting Started

### Prerequisites

- Node.js (version 18 or higher)
- npm

### Installation & Running Locally

1. Install dependencies:
   ```bash
   npm install
   ```

2. Run the development server:
   ```bash
   npm run dev
   ```

3. Open your browser and navigate to `http://localhost:5173`.

---

## Key Pages & Modules

- `/login`: Secure login page with demo account shortcuts.
- `/`: Role-tailored dashboard for Admin, Faculty, or Student.
- `/academics/courses`: View and add curriculum courses.
- `/academics/departments`: View academic departments.
- `/academics/timetable`: Weekly class timetable and schedule view.
- `/attendance/mark`: Faculty attendance entry for lectures.
- `/attendance/me`: Student attendance records and overall percentage.
- `/attendance/shortage`: List of students whose attendance is below 75%.
- `/exams/schedule`: Exam dates and schedule.
- `/exams/marks`: Marks entry page for teachers.
- `/exams/marksheets`: Student marks summary and PDF download.
- `/fees/structures`: Fee categories and assignments (Admin).
- `/fees/my`: Student fee dues with a simulated payment checkout.
- `/notices`: College circulars and announcements.

---

## Demo Accounts

- **Admin**: `admin@campusos.edu` (Password: `Admin@123`)
- **Faculty**: `faculty1@campusos.edu` (Password: `Faculty@123`)
- **Student**: `student00001@campusos.edu` (Password: `Student@123`)
