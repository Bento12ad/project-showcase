# Talkative AI — AI-Powered Speaking Coach

An independently developed full-stack web application designed to help users improve their communication and speaking skills through AI-powered practice, performance analysis, and personalized feedback.

**Live Demo:** https://talkativeai-frontend.vercel.app/

## Overview

Talkative AI provides an interactive environment where users can practice speaking and receive AI-generated feedback to understand their performance and identify areas for improvement.

The application combines a modern frontend, backend APIs, database management, and Google Gemini API integration.

## Key Features

- **AI Speaking Practice:** Interactive speaking practice powered by AI.
- **Personalized Feedback:** AI-generated feedback and recommendations based on speaking performance.
- **Speaking Analytics:** Tracks Words Per Minute (WPM), pause frequency, and filler word usage.
- **User Authentication:** Server-side session authentication with secure HttpOnly cookies.
- **Feedback Validation:** Validates AI-generated feedback before presenting results to users.

## Technology Stack

| Category | Technologies |
|---|---|
| Frontend | Next.js, React, TypeScript |
| Backend | Fastify, Node.js |
| Database | PostgreSQL |
| ORM | Prisma |
| AI Integration | Google Gemini API |
| Authentication | Server-side sessions, bcrypt, HttpOnly Cookies |
| Containerization | Docker |
| Testing | Vitest, Playwright |

## System Architecture

The application follows a full-stack architecture:

1. **Frontend:** Handles user interaction and speaking practice workflows.
2. **Backend API:** Processes application requests and coordinates business logic.
3. **AI Integration:** Sends relevant input to Google Gemini API and processes generated feedback.
4. **Database:** Uses PostgreSQL and Prisma to manage application data.
5. **Authentication:** Manages secure user sessions.

## Development Highlights

- Independently developed the frontend and backend.
- Integrated an external LLM API into a practical application.
- Implemented authentication and session management.
- Designed speaking performance metrics and feedback workflows.
- Used automated testing tools to support application quality.

## Live Application

Try the application:

https://talkativeai-frontend.vercel.app/

## Developer

**Jakapan Ploensup**

- GitHub: https://github.com/Bento12ad
- LinkedIn: https://www.linkedin.com/in/jakapan-ploensup/

---

*This case study describes the project's functionality and technical implementation. Source code is maintained separately.*
