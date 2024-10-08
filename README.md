﻿# PlanIt - Weekly Goal Management App

Project developed through RocketSeat - Focused on Full Stack Development.

Technologies used:

- Backend: Node.js, Fastify, Docker, PostgreSQL
- Frontend: React, TypeScript, Vite, Tailwind CSS

# Summary

- [Project Objectives](#project-objectives);

## Project Objectives

- Backend Development: Set up a server using Fastify and Node.js to create routes. Implement features to:

  - Register new goals.
  - Mark goals as completed.
  - Retrieve weekly data (weekly summary).
  - Display goals that have been completed and those that are still pending.

- Database Setup:

  - Use Docker and PostgreSQL to create and manage the database.
  - Develop functions that interact with the routes to update the database.

- Data Validation:

  - Use the ZOD library to validate environment variables and HTTP request data.

- User Interface:

  - Display a welcome screen when no data is registered.
  - Create a user-friendly dialog box for adding new goals.
  - Show pending goals.
  - Display completed goals, organized by date and time.
  - Include a progress bar to visually track goal completion.
  - Disable the option to mark goals as completed once the desired weekly frequency is reached.
