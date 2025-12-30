# Clueso.io – Full-Stack Product Feedback Platform (Clone)

## Overview

This project is a full-stack functional clone of Clueso.io**, built as a technical assignment to demonstrate product thinking, system design, and clean engineering practices**.

The objective of this implementation is to closely replicate **Clueso’s core workflows and user experience**, focusing on **feature parity, data flow, and architectural clarity** rather than pixel-perfect UI replication.

---

## Product Understanding

Clueso is a product feedback and insights platform that helps teams:
- Collect structured user feedback
- Organize and manage feedback efficiently
- Generate AI-powered summaries and insights
- View and act on feedback from a centralized dashboard

This clone recreates those flows end-to-end, including authentication, dashboard interaction, feedback collection, backend processing, and AI-assisted insight generation.

---

## Architecture Overview

The application follows a **modular and scalable architecture** with clear separation of concerns.


### Architectural Principles
- Clear separation between UI, business logic, and data access
- RESTful API communication
- Stateless backend with JWT-based authentication
- AI layer abstracted to allow easy integration of real AI providers

---

## Tech Stack

### Frontend
- React / Next.js
- Tailwind CSS
- Axios / Fetch API
- JWT authentication handling

### Backend
- Node.js
- Express.js
- REST APIs
- Middleware-based request validation

### Database
- PostgreSQL (via Supabase)
- Relational schema design
- Secure data access patterns

### AI Integration
- Mock AI summarization service
- Interface designed for OpenAI / Claude / Gemini integration
- AI logic isolated from core business logic

---

## Core Features

### User Authentication & Onboarding
- User registration and login
- Secure session handling using JWT
- Protected routes and role-based access

### Dashboard Experience
- Central dashboard for authenticated users
- Feedback overview and navigation
- Clean layout inspired by Clueso’s workflow

### Feedback Collection
- Create and submit product feedback
- Store feedback with metadata
- Backend validation and structured storage

### AI-Powered Insights
- Automatic feedback summarization
- Insight generation (mocked implementation)
- Clearly documented AI abstraction layer

### Data Management
- CRUD operations for feedback
- Consistent API responses
- Robust error handling and edge-case management

---

## Folder Structure

/frontend
├── components
├── pages
├── services
└── utils

/backend
├── routes
├── controllers
├── middleware
├── services
└── models

/ai
└── insightService.js

# Application Flow

User signs up or logs in

User accesses the dashboard

Feedback is submitted through the UI

Feedback is stored and displayed

AI insights are generated and shown

# Error Handling & Best Practices

Input validation on backend APIs

User-friendly frontend error messages

Authentication and authorization checks

Graceful handling of empty or invalid data

Clean and readable codebase with modular structure

# Assumptions & Limitations

AI functionality is mocked due to API cost and access constraints

Browser extension layer is optional and not included

Focus is on functionality and workflow accuracy over UI perfection

