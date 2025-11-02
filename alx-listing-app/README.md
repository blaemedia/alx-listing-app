Project Description and Goals

This project is a web application built with Next.js aimed at recreating an Airbnb-style listing page. The goal is to allow users to browse, view, and interact with property listings in a modern, responsive interface. The project emphasizes performance, component reusability, and scalable folder structure — key strengths of the Next.js framework.

Project Structure Overview
1. components/

Contains reusable UI components used across the project.

Examples: Navbar.tsx, ListingCard.tsx, Footer.tsx.

Purpose: Keeps the code modular, clean, and maintainable by separating UI building blocks.

2. interfaces/

Holds TypeScript interface definitions and types for data models.

Examples: Listing.ts, User.ts.

Purpose: Provides strong typing for props and data, reducing bugs and improving development consistency.

3. constants/

Stores static configuration values or reusable constants.

Examples: API endpoints, routes, default images, or status values.

Purpose: Centralizes key values to make updates easy and prevent repetition throughout the codebase.

4. public/assets/

Contains static files such as images, icons, fonts, and logos.

Examples: /assets/logo.png, /assets/banner.jpg.

Purpose: Files here are publicly accessible and can be referenced directly (e.g., /assets/logo.png).