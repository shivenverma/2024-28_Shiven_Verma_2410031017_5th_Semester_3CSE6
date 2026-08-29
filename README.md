Full Stack Development Internship — Thiranex

Internship: Full Stack Development
Organization: Thiranex
Duration: 30 July 2026 – 29 August 2026
Mode: Remote / Project-Based
Intern ID: THX-JUL3026-475

Overview

This repository documents my Full Stack Development Internship at Thiranex, where I built four independent, production-style web applications from end to end.

The internship focused on applying full-stack engineering concepts repeatedly across different domains — from database modelling and REST API development to authentication, responsive frontend development, testing, and deployment-oriented project structure.

Applications Built

Project

Description

Primary Stack

Full-Stack Portfolio Website

Dynamic portfolio with database-backed project showcase

React, Vite, Tailwind CSS, Express, MySQL

TaskFlow

Authenticated task management application with dashboard analytics

React, Vite, Tailwind CSS, Express, Prisma, SQLite

E-Commerce Application

Online store with cart, checkout, orders, and admin management

React, Tailwind CSS, Express, Prisma, PostgreSQL

InkFlow

Full-stack blogging platform with comments, search, filtering, and creator dashboard

React 19, Vite, Tailwind CSS v4, Express 5, Prisma, PostgreSQL

Internship Objectives

The primary objectives of the internship were to:

Build a full-stack personal portfolio with a dynamic project showcase.

Develop an authenticated task management application with complete CRUD functionality.

Build an e-commerce platform covering products, cart, checkout, orders, and role-based access.

Develop a blogging platform with post CRUD, comments, search, filtering, and a creator dashboard.

Apply production-style practices such as JWT authentication, password hashing, validation, error handling, and REST API design.

Gain practical experience with Prisma ORM and multiple relational databases.

Tech Stack

Frontend

React

Vite

Tailwind CSS

React Router

Context API

React Hot Toast

Lucide React

Backend

Node.js

Express.js

REST APIs

JWT Authentication

bcrypt / bcryptjs

Zod

express-validator

Database & ORM

PostgreSQL

MySQL

SQLite

Prisma ORM

Testing

Jest

Supertest

API integration testing

Deployment

Vercel

Render

Development Practices

RESTful API architecture

Protected routes

Role-based authorization

Per-user data isolation

Input validation

Error handling

Database seeding

Automated integration testing

Responsive UI development

Projects

1. Full-Stack Portfolio Website

A full-stack personal portfolio where project information is stored in a MySQL database rather than being completely hardcoded into the frontend.

Key Features

Dynamic project showcase

REST API for project data

MySQL-backed project storage

Database seed script

Responsive React interface

Graceful fallback to static project data when the backend is unavailable

Tech

React Vite Tailwind CSS Node.js Express MySQL

Repository

View Project →

2. TaskFlow — Task Management Application

A production-style task management application focused on authenticated, per-user task management and database-driven dashboard functionality.

Key Features

User registration and login

bcrypt password hashing

JWT-based authorization

Per-user data isolation

Complete task CRUD

Task priority and status

Due dates

Search and filtering

Sorting

Dynamic overdue detection

Optimistic UI status updates

Dashboard statistics

Automated backend integration tests

The backend includes a 17-test integration suite covering authentication and task-management logic.

Tech

React Vite Tailwind CSS Express Prisma SQLite JWT Jest Supertest

Repository

View Project →

3. E-Commerce Web Application

A full-stack e-commerce application implementing a complete product-to-order flow with separate user and admin functionality.

Key Features

Product catalogue

Product detail pages

User authentication

Profile management

Shopping cart

Checkout flow

Order history

Order details

Admin product management

Admin order management

JWT authentication

API input validation

Data Models

The application works with relational entities including:

User → Product → Cart → CartItem → Order → OrderItem

Tech

React Tailwind CSS Express Prisma PostgreSQL JWT express-validator

Repository

View Project →

4. InkFlow — Blog Platform

A full-stack blogging platform designed around content creation, ownership-based authorization, comments, search, and creator analytics.

Key Features

User registration and login

JWT + bcrypt authentication

Full post CRUD

Draft mode

Categories and tags

Live side-by-side writing preview

Interactive commenting system

Comment ownership controls

Comment moderation for post owners

Full-text search

Category and tag filtering

Sorting

Creator dashboard

Post and comment metrics

Rate limiting on authentication endpoints

Automated integration testing

The project uses a Supabase-hosted PostgreSQL database through Prisma.

Tech

React 19 Vite Tailwind CSS v4 Express 5 Prisma PostgreSQL Supabase JWT

Repository

View Project →

Architecture

The four applications followed a common full-stack architecture:

┌──────────────────────────────┐
│        React Frontend        │
│       Vite + Tailwind CSS    │
└──────────────┬───────────────┘
               │
          REST / JSON
               │
               ▼
┌──────────────────────────────┐
│      Node.js + Express       │
│       REST API + JWT         │
│      Validation + Logic      │
└──────────────┬───────────────┘
               │
            Prisma
               │
               ▼
┌──────────────────────────────┐
│       Relational Database    │
│ PostgreSQL / MySQL / SQLite  │
└──────────────────────────────┘

Authentication tokens are verified through backend middleware, while validation and authorization are applied at the API layer.

Development Methodology

For each project, I followed a consistent development workflow:

1. Requirements & Feature Planning
              ↓
2. Database / Data Model Design
              ↓
3. REST API Development
              ↓
4. API Testing
              ↓
5. React Frontend Development
              ↓
6. Authentication & Authorization
              ↓
7. Validation & Error Handling
              ↓
8. Integration Testing
              ↓
9. Deployment Preparation

This approach allowed the same engineering patterns to be applied across four different domains while adapting the data models and business logic to each application.

Internship Milestones

Milestone

Application

Due Date

Status

01

Full-Stack Portfolio Website

06 Aug 2026

✅ Completed

02

TaskFlow

13 Aug 2026

✅ Completed

03

E-Commerce Application

20 Aug 2026

✅ Completed

04

InkFlow

27 Aug 2026

✅ Completed

All four applications were completed and submitted within the internship window.

Key Outcomes

By the end of the internship, I gained practical experience in:

Building complete full-stack applications from scratch

Designing relational database schemas

Working with Prisma ORM

Using PostgreSQL, MySQL, and SQLite

Building and consuming REST APIs

Implementing JWT authentication

Implementing password hashing

Building protected routes

Implementing role-based authorization

Designing responsive React interfaces

Managing frontend application state

Writing automated API integration tests

Handling validation and API errors

Structuring applications for deployment

Working across multiple project domains

Repository Structure

This internship work is organized across four independent repositories:

Full-Stack Development Internship
│
├── Full-Stack-Portfolio-Website
├── Task-Management-WebApp
├── E-Commerce-Application
└── Blog-Platform

Each project contains its own source code, configuration, database setup, and documentation.

Internship Proof

The internship was completed at Thiranex as an Intern – Full Stack Development.

Supporting documents include:

Internship Offer Letter

Certificate of Achievement

Internship project repositories

Project milestone submissions

Intern ID: THX-JUL3026-475

What I Learned

The biggest takeaway from this internship was learning to build the same full-stack fundamentals across different real-world problem domains.

Instead of implementing authentication, APIs, databases, and frontend integration only once, I repeatedly applied those concepts across portfolio management, task management, e-commerce, and blogging.

This helped me move from building isolated classroom assignments toward thinking about applications as complete systems — from database design and backend security to frontend state, testing, and deployment.

Projects

🖥️ Full-Stack Portfolio Website

✅ TaskFlow — Task Management WebApp

🛒 E-Commerce Application

✍️ InkFlow — Blog Platform

Author

Shiven Verma
B.Tech CSE · IILM University
Batch: 2024–2028

Internship: Full Stack Development @ Thiranex
Duration: July–August 2026
Focus: Full-Stack Web Development
