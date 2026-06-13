# Collegium

**Collegium** is a dedicated collegiate esports management platform built specifically for the Philippine collegiate circuit. It serves as an institutionally verified ecosystem restricted to users with valid `.edu.ph` email domains, bridging the gap between informal gaming communities and formal varsity athletics.

## The Product

Collegium addresses the current lack of unified, secure, and data-driven digital infrastructure in Philippine collegiate esports by providing a structured, data-centric management Progressive Web App (PWA). It features:

* **Peer-to-Peer Scrim Board:** Structured request-and-approval workflow for practice matches.
* **Integrated Tournament Module:** A bracketing system for official events with real-time result propagation.
* **War Room:** Automatically generated, role-restricted private chatrooms for secure match logistics coordination.
* **Dual-Layer Athlete Portfolio:** Profiles tracking Practice Reliability and Peak Performance metrics.

### Technical & Ranking Innovations

* **Hybrid Match-Logging System:** Direct Riot Games REST API integration for PC titles, and a two-step peer-confirmation protocol for Mobile titles (MLBB, CODM).
* **Advanced Ranking Engine:** Utilizes the Glicko-2 Algorithm combined with a custom Varsity Contribution Score (VCS) for highly accurate performance tracking and dynamic university rankings.

## Technology Stack

The platform operates on a modern, high-performance full-stack architecture:

* **Frontend:** Next.js, React, TypeScript, Tailwind CSS
* **Backend:** NestJS, TypeScript
* **Database & ORM:** PostgreSQL, Prisma
* **Caching:** Redis

## Repositories

The project is structured into the following main repositories:

* **`collegium-web`**: The client-side Progressive Web App (PWA) built with Next.js. This repository contains all the user-facing interfaces, including the scrim board, tournament brackets, and athlete portfolios.
* **`collegium-server`**: The backend application built with NestJS. It handles API routing, secure authentication, database interactions via Prisma, and runs the core logic for the Glicko-2 and VCS ranking engines.
