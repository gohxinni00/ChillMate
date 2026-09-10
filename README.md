# ChillMate by One More Fix

### Your AI Buddy for Stress-Free Student Life

**Team:** One More Fix<br>
**Team Members:** Goh Xin Ni, Goh Yi Jun, Cheryl Goh Wen Si<br>
**Problem Statement:** Stress & Workload Manager<br>
**Video Presentation:** [Insert Unlisted YouTube Link]<br>
**Presentation Slides:** [Insert Public Slide Link]

---

# 1. Project Overview

## The Problem

University students face increasing levels of stress due to the combination of academic responsibilities, extracurricular commitments, part-time work, personal obligations, and social commitments. While numerous productivity tools exist, they primarily focus on managing tasks rather than understanding whether students have the capacity to realistically handle their workload.

Our team identified four major root causes:

- Fragmented tools requiring students to manually combine information across multiple platforms
- Multiple commitments competing for limited time, energy, and mental capacity
- Overcommitment caused by underestimating actual workload
- Competing priorities that make decision-making difficult

As a result, students often experience:

- Increased stress
- Reduced productivity
- Burnout risk
- Poor visibility of future workload
- Difficulty balancing academics and personal life


---

## Stakeholders & User Personas

ChillMate is designed for students managing academics, commitments, and wellbeing throughout their educational journey.

### Target Users

- 🎒 Pre-University Students
- 📚 Undergraduate Students
- 🎓 Postgraduate Students

### Representative User Personas

![Representative User Personas](images/representative-user-personas.png)

---

## Existing Solutions & Market Gap

Although many productivity tools support students, most only address part of the problem.

| Feature | MyStudyLife | Todoist | Mood Tracker | Studwy | ChillMate |
|----------|------------|----------|-------------|---------|----------|
| Academic Planning | ✅ | ❌ | ❌ | ✅ | ✅ |
| Task Management | ✅ | ✅ | ❌ | ✅ | ✅ |
| AI Task Breakdown | ❌ | ❌ | ❌ | ✅ | ✅ |
| Workload Capacity Score | ❌ | ❌ | ❌ | ❌ | ✅ |
| Stress Monitoring | ❌ | ❌ | ✅ | ❌ | ✅ |
| Wellbeing & Life Balance | ❌ | ❌ | ✅ | Limited | ✅ |
| Weekly Workload Analysis | ❌ | ❌ | ❌ | ❌ | ✅ |

### Market Gap

Most existing applications answer:

> “What tasks do I need to do?”

ChillMate answers:

> “Can I realistically handle these tasks without becoming overwhelmed?”

---

## Our Solution

ChillMate is an AI-powered student capacity management platform that helps university students balance their workload, wellbeing, and personal commitments. Unlike traditional productivity tools that focus heavily on task completion, ChillMate evaluates workload, available time, energy levels, and wellbeing indicators to help students make better decisions before stress becomes burnout.

The platform combines planning, wellbeing support, workload analysis, and AI-powered recommendations into a single ecosystem.

### Core Features

### 🤖 AI Planning Assistant
- AI Task Breakdown
- AI Smart Scheduling
- AI Assistant

**Purpose:** Transform tasks into actionable plans.

---

### 📅 Academic & Life Management
- Classes
- Assignments
- Exams
- Activities
- Part-Time Work
- Travel
- Emergency Events
- Personal Commitments

**Purpose:** Centralize all commitments in one platform.

---

### 📊 Smart Dashboard
- Daily Overview
- Upcoming Deadlines
- Progress Tracking
- Weekly Reports

**Purpose:** Provide a unified view of workload and progress.

---

### ⚡ Capacity & Stress Monitoring
- Workload Capacity Score
- Early Overload Detection

**Purpose:** Identify overload risks before burnout occurs.

---

### 🌱 Wellbeing & Motivation System
- Wellness Coach
- Recovery Suggestions
- Mood Check-ins
- Rewards & Encouragement

**Purpose:** Support healthy study habits and wellbeing.

---

### 🚨 AI Insights & Recommendations
Examples:
- “You have been studying for 3 hours. Consider taking a short break.”
- “Move revision to Friday to reduce Thursday's workload.”
- “Your average sleep duration is below 6 hours. Consider taking a short nap.”

**Purpose:** Provide personalized recommendations based on workload, stress, sleep, and progress.

---

# 2. Ideation & Process

## 2.1 Ideas We Considered

| Idea | Why It Was Kept / Dropped |
|--------|--------------------------|
| AI Task Breakdown ✅ | Reduces planning burden and makes large assignments manageable |
| AI Smart Scheduling ✅ | Prevents overload by distributing workload realistically |
| Workload Capacity Score ✅ | Core differentiator; focuses on capacity rather than productivity |
| Mood Check-ins ✅ | Helps track wellbeing in a non-intrusive way |
| Full Mental Health Diagnosis ❌ | Too complex and outside project scope |
| Meditation App ❌ | Existing solutions already address this problem |
| Habit Tracker ⚠️ | Useful but not directly related to workload management |

---

## 2.2 Ideation Boards

### User Personas

images/representative-user-personas.png

This diagram illustrates the primary target users and the common workload-related challenges experienced by different student groups.

---

### User Journey

![User Journey](images/user-journey.png)

This journey map illustrates how students interact with ChillMate, from task input and AI analysis to personalized scheduling, execution, wellbeing support, and achievement tracking.

---

### Development Roadmap

![Development Roadmap](images/development-roadmap.png)

This roadmap outlines the project's phases, MVP scope, future enhancements, and expected deliverables.

---

## 2.3 Mentor Consultation

| Date | Mentor | Feedback Received | What Was Changed |
|--------|--------|--------------------|------------------|
| TBD | TBD | TBD | TBD |
| TBD | TBD | TBD | TBD |

---

# 3. Design & Prototype

### UI Prototype

[Figma Prototype Link]

Below are selected screens from the prototype.

## Dashboard

images/dashboard.png

Provides:
- Weekly workload overview
- Capacity score
- Upcoming deadlines
- Progress tracking
- Reward points
- Weekly report summary

---

## Calendar

images/calendar.png

Provides:
- Day, week, and month views
- Task scheduling
- Deadline management
- Capacity visualization

---

## AI Assistant

images/ai-assistant.png

Allows students to:
- Describe assignments naturally
- Obtain workload analysis
- Generate personalized schedules
- Receive recommendations

---

Demonstrates the entire interaction flow from onboarding to task completion.

---

# 4. What Makes It Different

## Traditional Productivity Apps

Most applications focus on:

- Task tracking
- Time blocking
- Productivity optimization

They answer:

> “What tasks do I have?”

---

## ChillMate

ChillMate focuses on:

- Capacity Management
- Wellbeing
- Early Burnout Prevention
- Smarter Workload Decisions

ChillMate answers:

> “Can I realistically handle this workload without becoming overwhelmed?”

### Key Differentiators

✅ Workload Capacity Score

✅ Early Overload Detection

✅ AI Smart Scheduling

✅ AI Wellness Coach

✅ Wellbeing Integration

✅ Capacity-Based Planning

---

# 5. Technical Architecture & Feasibility

## Tech Stack

| Layer | Technology | Reason |
|---------|------------|----------|
| Frontend | HTML5, CSS3, JavaScript | Lightweight and accessible |
| Backend | Firebase Cloud Functions | Serverless architecture |
| Database | Firebase Firestore | Real-time cloud database |
| Authentication | Firebase Authentication | User management |
| AI | Gemini API | Task breakdown and scheduling |
| Visualization | Chart.js | Workload analysis and charts |
| Hosting | Firebase Hosting | Fast and scalable deployment |

---

## Technical Architecture

![Tech Stack](images/tech-stack.png)

The system consists of:

- Responsive Web Application
- Firebase Backend
- Gemini AI Integration
- Cloud-Based Deployment

---

## Build Plan & Scope

### MVP Scope

Features planned during development:

✅ AI Task Breakdown

✅ AI Smart Scheduling

✅ Smart Dashboard

✅ Capacity Score

✅ Weekly Report

✅ Academic & Life Management

✅ Wellbeing System

---

### Future Enhancements

- Sleep Tracking & Wellness Suggestions
- Automatic Timetable Import
- Advanced AI Recommendations
- Mobile Quick Capture Companion App
- Gamification Features
- Collaborative Planning

---

## Scalability

### Current Target

🎓 University Students

### Future Expansion

➡ Secondary School Students

➡ Interns

➡ Young Professionals

➡ Capacity Management Beyond Education

The same capacity-management framework can be adapted beyond university settings, enabling broader societal impact.

---
