# PROJECT_CONTEXT.md

# Project Name

CloudNest - Personal Cloud Storage & File Management System

---

## Tagline

Your Personal Cloud. Your Files. Anywhere.

---

# Version

v1.0

---

# Project Type

Full Stack Web Application

---

# Project Category

Cloud Storage / File Management Platform

---

# Problem Statement

Users often store files across multiple devices such as laptops, desktops, and mobile phones, making file organization and accessibility difficult. Existing cloud storage solutions may not always meet the needs of students or individuals looking for a lightweight personal cloud solution.

CloudNest provides a secure web-based platform where users can upload, organize, preview, search, and manage their personal files from anywhere using a browser.

---

# Vision

To build a production-ready cloud storage platform using Java Full Stack technologies that demonstrates industry-standard software architecture, security, scalability, and modern UI/UX.

---

# Objectives

• Learn enterprise-level Java Full Stack development.
• Build a portfolio-quality project.
• Implement secure authentication.
• Practice REST API development.
• Understand cloud file storage.
• Gain experience with deployment.
• Learn clean architecture and documentation.

---

# Target Users

• Students
• Developers
• Freelancers
• Small Businesses
• Individuals

---

# User Roles

1. Guest
2. Registered User
3. Administrator

---

# Technology Stack

## Frontend

- React
- TypeScript
- Vite
- Tailwind CSS
- React Router
- Axios
- Framer Motion
- React Hook Form

---

## Backend

- Java 21
- Spring Boot
- Spring Security
- Spring Data JPA
- Hibernate
- JWT Authentication
- Bean Validation
- Swagger

---

## Database

MySQL

---

## Cloud Storage

Supabase Storage

---

## Version Control

Git
GitHub

---

## API Testing

Postman

---

## Build Tool

Maven

---

## Deployment

Frontend
- Vercel

Backend
- Render

Database
- MySQL

Storage
- Supabase Storage

---

# High Level Architecture

React Frontend

↓

Spring Boot REST API

↓

Spring Security + JWT

↓

Business Layer

↓

JPA/Hibernate

↓

MySQL Database

↓

Supabase Storage

---

# Application Layers

Presentation Layer

↓

Controller Layer

↓

Service Layer

↓

Repository Layer

↓

Database

---

# Project Modules

Authentication Module

User Management Module

Dashboard Module

Folder Management Module

File Management Module

Search Module

Sharing Module

Favorites Module

Trash Module

Profile Module

Notification Module

Admin Dashboard

Activity Logs

---

# Coding Standards

• Layered Architecture
• SOLID Principles
• DTO Pattern
• Repository Pattern
• Constructor Injection
• Global Exception Handler
• Validation
• Swagger Documentation
• Meaningful Logging
• REST Naming Standards

---

# Folder Structure

cloudnest/

docs/

frontend/

backend/

database/

docker/

postman/

.github/

README.md

---

# Git Branching Strategy

main

develop

feature/authentication

feature/file-upload

feature/folder-management

feature/search

feature/admin

feature/sharing

feature/profile

---

# Git Commit Standard

feat:

fix:

docs:

refactor:

style:

test:

chore:

---

# Daily Development Workflow

1. Read documentation
2. Select task
3. Create feature branch
4. Develop one module
5. Test locally
6. Commit changes
7. Push GitHub
8. Update documentation

---

# Deployment Strategy

Frontend

Vercel

Backend

Render

Database

MySQL

Cloud Storage

Supabase Storage

---

# Security Standards

JWT Authentication

BCrypt Password Encoding

Role-Based Access Control

Input Validation

File Ownership Verification

Global Exception Handling

Secure REST APIs

---

# Non Functional Goals

High Performance

Responsive Design

Scalable Architecture

Maintainable Code

Reusable Components

Secure APIs

Fast Loading

Production Ready

---

# Expected Project Outcome

CloudNest will be a production-ready personal cloud platform that enables users to securely store, organize, manage, preview, search, and share files from anywhere using a browser.

The project will demonstrate modern Java Full Stack development practices and serve as a portfolio-ready application suitable for technical interviews and placements.