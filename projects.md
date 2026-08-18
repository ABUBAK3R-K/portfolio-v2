# Project Portfolio Data

This file contains structured project information for use in a portfolio website.

> **Instruction for the code editor:** Use this file as the source of truth for project content. Replace only the project information and the `LIVE_DEMO_URL` / `GITHUB_REPO_URL` placeholders when real links are provided. Do not invent links, metrics, technologies, or achievements that are not present here. Keep the existing portfolio design unchanged unless explicitly instructed otherwise.

---

## 1. PersonaArena

**Category:** AI / LLM / Multi-Agent Simulation

**Description:** A multi-agent LLM persona simulation and debate platform where users create structured AI personas from descriptions of their friends, run controlled multi-round debates using the same underlying model configuration, and evaluate the debate with an independent AI judge.

### Key Highlights
- Converts natural-language personality descriptions into structured, Pydantic-validated persona profiles.
- Uses the same model, model version, temperature, token limits, and generation settings for all participants so persona instructions are the primary differentiator.
- Runs debates through a deterministic backend state machine covering positioning, opening statements, rebuttals, counterarguments, closing statements, and judging.
- Streams debate responses to the React frontend using Server-Sent Events.
- Uses an independent judge and separate persona-consistency evaluator to score logic, evidence, rebuttal, persuasion, consistency, originality, and overall performance.
- Stores personas, debate configuration, transcripts, evaluations, and prompt versions for future experimentation.

### Tech Stack
React, Vite, Tailwind CSS, FastAPI, Python, Pydantic, SQLAlchemy, Alembic, PostgreSQL, SSE, LLM APIs

### Links
- **Live Demo:** `LIVE_DEMO_URL`
- **GitHub:** `GITHUB_REPO_URL`

---

## 2. AuraFit

**Category:** AI / Computer Vision / E-commerce

**Description:** A full-stack AI-powered e-commerce platform for five cultural communities, combining product recommendations with an AI Virtual Try-On Studio.

### Key Highlights
- Built a multi-stage virtual try-on pipeline using background removal, pose estimation, garment classification, category-aware sizing, and vectorized alpha blending.
- Used rembg/U²-Net for garment background removal and MediaPipe PoseLandmarker for 33 body landmarks.
- Used CLIP zero-shot classification to recognize traditional garments such as sarees, hijabs, sherwanis, and lehengas.
- Estimated body measurements from pose landmarks to recommend clothing sizes.
- Built a content-based recommendation engine using TF-IDF and cosine similarity over a 56-product catalog, incorporating budget and ratings.
- Designed five community storefronts with an integrated AI recommendations experience.

### Tech Stack
React, FastAPI, Python, OpenCV, MediaPipe, rembg, CLIP, Transformers, scikit-learn, NumPy

### Links
- **Live Demo:** `LIVE_DEMO_URL`
- **GitHub:** `GITHUB_REPO_URL`

---

## 3. TrackWise AI

**Category:** AI / Full-Stack / Personal Finance

**Description:** An AI-powered personal finance and expense tracking platform with account management, budgeting, analytics, and automated receipt scanning.

### Key Highlights
- Implemented secure email/password authentication with NextAuth.js.
- Built multi-account support for bank accounts, wallets, and credit cards with live balances.
- Implemented full expense CRUD with categories, payment methods, and automatic account balance updates.
- Built an AI receipt scanner using Google Cloud Vision OCR to extract merchant names, dates, totals, and categories from receipt images.
- Added interactive spending analytics with 30-day trends and category breakdowns.
- Added category-based budgets, responsive layouts, dark mode, and Framer Motion page transitions.

### Tech Stack
Next.js, TypeScript, Tailwind CSS, Prisma, SQLite, NextAuth.js, Google Cloud Vision, Recharts, Framer Motion

### Links
- **Live Demo:** `LIVE_DEMO_URL`
- **GitHub:** `GITHUB_REPO_URL`

---

## 4. World Cup Draft XI

**Category:** Full-Stack / Data / Interactive Simulation

**Description:** An interactive cricket experience where users build an ultimate Cricket World Cup XI, set a batting order, and simulate a tournament against historic World Cup teams.

### Key Highlights
- Built a country/year drafting system for selecting players from historical World Cup data.
- Created a drag-and-drop team builder for organizing players into batting-order roles.
- Implemented tournament simulation across group stage, quarter-final, semi-final, and final.
- Created dynamic trading-card-style player profiles with statistics and attributes.
- Added result and team-seed sharing functionality.
- Used pre-seeded historical data in embedded SQLite for a lightweight, serverless deployment model.

### Tech Stack
Next.js, Tailwind CSS, Prisma, SQLite, Framer Motion, dnd-kit

### Links
- **Live Demo:** `LIVE_DEMO_URL`
- **GitHub:** `GITHUB_REPO_URL`

---

## 5. ArenaX Event Manager

**Category:** Full-Stack / Real-Time Web Application

**Description:** A full-stack event management platform built to operate the ArenaX multi-game competition, including player registration, game control, admin management, and a live leaderboard.

### Key Highlights
- Built an admin dashboard with authentication and match/result management.
- Implemented player registration, profiles, statistics, and game assignment.
- Built a real-time leaderboard using Socket.io for live score updates.
- Implemented a coin-based game economy and point-based scoring system across 10 mini-games.
- Created public-facing pages for rules, game information, and leaderboard viewing.
- Designed and deployed the platform for a college event with 200+ participants.

### Tech Stack
React, Tailwind CSS, Node.js, Express.js, MongoDB, Mongoose, Socket.io, JWT, Bcrypt, Axios

### Links
- **Live Demo:** `LIVE_DEMO_URL`
- **GitHub:** `GITHUB_REPO_URL`

---

## 6. CityGuide

**Category:** Mobile / Recommendation System / Civic Tech

**Description:** A community-curated city guide Android application that maps local businesses, shops, and public/religious places, with similar-place recommendations and photo-based civic problem reporting.

### Key Highlights
- Built the recommendation microservice that analyzes interaction history and geographical data to recommend similar places.
- Implemented the recommendation service as a Python FastAPI microservice connected directly to Supabase PostgreSQL.
- Integrated OpenStreetMap through flutter_map without paid map APIs or keys.
- Used Supabase PostgreSQL, PostGIS, Auth, and Storage for backend data and geospatial functionality.
- Included a Streamlit admin dashboard for authorities to review, categorize, and resolve reported civic problems.
- Structured the project as a monorepo with separate mobile, recommendation, admin, backend/database, and documentation components.

### Tech Stack
Flutter, Dart, OpenStreetMap, flutter_map, Supabase, PostgreSQL, PostGIS, Python, FastAPI, Streamlit

### Links
- **Live Demo:** `LIVE_DEMO_URL`
- **GitHub:** `GITHUB_REPO_URL`

---

## 7. Palk Watch

**Category:** Systems / Real-Time Data / Geospatial

**Description:** A real-time maritime dark-vessel detection system that ingests high-volume AIS position messages and raises alerts for zone violations, position spoofing, and vessels that stop transmitting, with intercept geometry for patrol response.

### Key Highlights
- Implemented a single Go binary for high-throughput AIS ingestion and real-time alert processing.
- Designed detection for zone violations, position spoofing, and dark events where vessels stop transmitting.
- Added patrol intercept geometry and dead-reckoning visualization for response planning.
- Built a React + MapLibre GL dashboard with vessel positions, alert feeds, zones, metrics, and latency panels.
- Included synthetic firehose and benchmark modes for sustained throughput and latency testing.
- Supports a live AIS feed through aisstream.io while keeping the high-throughput benchmark independent of the live regional feed.

### Tech Stack
Go, React, MapLibre GL, WebSockets, GeoJSON, AISStream, geospatial processing

### Links
- **Live Demo:** `LIVE_DEMO_URL`
- **GitHub:** `GITHUB_REPO_URL`

---

## Link Placeholder Format

When I provide actual links later, replace only:

- `LIVE_DEMO_URL` → actual deployed project URL
- `GITHUB_REPO_URL` → actual GitHub repository URL

If a project has no live demo, keep the Live Demo field as `NOT_AVAILABLE` rather than inventing one.

## Portfolio Selection Guidance

For an AI Engineer-focused portfolio, prioritize these projects visually:

1. **AuraFit** — strongest Computer Vision + AI application
2. **PersonaArena** — strongest LLM / AI-agent-style project
3. **TrackWise AI** — strongest AI + full-stack product
4. **CityGuide** — strongest recommendation/geospatial project
5. **World Cup Draft XI** — strong interactive/data-driven project
6. **ArenaX Event Manager** — strong real-time full-stack project
7. **Palk Watch** — strong systems/geospatial project

The descriptions can be shortened for project cards, while the full highlights can be used on individual project detail pages.
