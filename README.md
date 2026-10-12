# Hi, I'm Bendegúz 👋

**Junior Full-Stack Developer** focused on **React, TypeScript, NestJS and PostgreSQL**.

I enjoy building web applications where the interesting part is not just writing code, but deciding **how the system should be structured**: how data is shaped, where responsibilities belong, how authorization is enforced, and how to keep the result maintainable.

I use AI coding tools as part of my development workflow, but I treat generated code as a proposal, not as the source of truth. I still own the architecture, data flow, correctness and trade-offs.

## Featured project

### [SupportFlow](https://github.com/bakosbendeguz/supportflow)

A full-stack helpdesk / ticketing application built with:

**React · TypeScript · NestJS · PostgreSQL · Prisma · TanStack Query · JWT/RBAC · Jest · Vitest · Docker**

Highlights:

* JWT authentication with Admin, Agent and Customer roles
* backend-enforced role-based access control and ticket visibility
* ticket assignment and status workflows
* comments and transactional status history
* search, filtering, pagination and sorting
* dashboard statistics
* Swagger / OpenAPI documentation
* backend unit tests and frontend component tests
* Dockerized PostgreSQL development environment

One design decision I particularly care about is keeping authorization and data-visibility rules centralized instead of duplicating role checks across the application. Status changes and their audit history are also handled transactionally so the system cannot end up in a partially updated state.

## Other work

### Dimensionless

Independent e-commerce web application built with **PHP, JavaScript, SQL and AJAX**.

Worked on authentication, cart and ordering flows, account features, relational data and frontend-backend integration.

## Background

Before focusing on software development, I worked in **application operations and IT operations**.

That experience shaped how I approach development today:

* reproduce issues before guessing
* understand the full system, not only one layer
* treat reliability and maintainability as engineering concerns
* communicate technical problems clearly

## Tech

**Frontend:** React, TypeScript, JavaScript, HTML, CSS, Tailwind CSS, TanStack Query, React Hook Form, Zod  
**Backend:** NestJS, Node.js, REST APIs, JWT/RBAC  
**Data:** PostgreSQL, Prisma, SQL  
**Testing \& Tooling:** Jest, Vitest, React Testing Library, Docker Compose, Swagger/OpenAPI, Git/GitHub

## Contact

📫 **Email:** <bakos.bendeguz@gmail.com>
