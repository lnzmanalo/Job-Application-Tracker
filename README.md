# Job Application Tracker

## 📋 Project Description

### Overview
The **Job Application Tracker** is a lightweight, browser-based web application designed to help job seekers organize and monitor their job search process. It provides a clean, intuitive interface for logging every application, tracking its progress through the hiring pipeline, and staying on top of follow-ups — all without needing an account, server, or internet connection.

### Purpose
Job hunting often involves sending out dozens of applications across different companies and platforms. Without a system, it's easy to lose track of:
- Which companies you've applied to
- What stage each application is in (Applied, Interview, Offer, Rejected)
- When you applied and what follow-up is needed

This tool solves that problem by offering a single, visual dashboard where every opportunity is recorded and its status is always visible at a glance.

---

## ✨ Key Features

### 1. Add New Applications
A simple form at the top lets you log a new job application with:
- **Company name**
- **Position title**
- **Date applied** (defaults to today)
- **Current status** (Applied, Interview, Offer, or Rejected)

### 2. Interactive Application Table
All applications are displayed in a clean, sortable table showing company, position, date, and a color-coded status badge:
- 🔵 **Applied** — blue
- 🟡 **Interview** — yellow
- 🟢 **Offer** — green
- 🔴 **Rejected** — red

### 3. Inline Editing
Each row has an **edit** button that turns the row into editable fields directly in the table. You can update the company, position, date, or status and save without leaving the page. A **cancel** option reverts any unsaved changes.

### 4. Delete with Confirmation
A trash icon removes an application, with a confirmation prompt to prevent accidental data loss.

### 5. Filtering
A status filter dropdown lets you quickly narrow the view to only applications in a specific stage — useful when you want to focus on, for example, just your active interviews.

### 6. Live Statistics
A stats bar at the top displays:
- **Total applications** submitted
- **Active applications** (Applied + Interview — i.e., not yet rejected or offered)

These update instantly as you add, edit, or delete entries.

### 7. Automatic Data Persistence
All data is saved to your browser's **localStorage**. There's no signup, no server, and no internet requirement — your list is preserved even after closing the tab or restarting your computer.

### 8. User Feedback
A toast notification appears briefly at the bottom of the screen to confirm actions like "Application added," "Application updated," or "Application deleted."

---

## 🛠️ Technical Highlights
- **Pure HTML, CSS, and JavaScript** — no frameworks, no build step, no dependencies
- **Single file** — the entire app runs from one `.html` file, making it easy to host or share
- **Responsive design** — adapts to smaller screens with a mobile-friendly layout
- **XSS-safe rendering** — user input is escaped before being inserted into the DOM
- **Event delegation** — efficient click handling for all table actions
- **Seed data** — includes two sample applications on first launch so the interface isn't empty

---

## 👥 Ideal Users
- **Active job seekers** managing multiple applications at once
- **Career changers** tracking a long or complex search
- **Students and new graduates** applying to internships and entry-level roles
- **Recruiters or career coaches** demonstrating how to organize a job hunt

---

## 📝 Summary
The Job Application Tracker is a self-contained, privacy-friendly productivity tool that turns a chaotic job search into a clear, manageable pipeline. It requires zero setup, works offline, and gives users full control over their job hunt data — all from a single HTML file.

---

## 🚀 Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/inzmanalo/Job-Application-Tracker.git
