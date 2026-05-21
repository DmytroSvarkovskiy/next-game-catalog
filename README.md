# 🎮 Game Hub 

A modern, high-performance web application for exploring video games, tracking system requirements, and managing a personal wishlist. Built with a focus on Server-Side Rendering (SSR) and seamless user experience.

🔗 **Live Demo:** [Deploy Link Here]

---

## 🚀 Tech Stack

- **Framework:** Next.js (App Router)
- **Language:** TypeScript
- **Database & Auth:** Supabase (PostgreSQL)
- **State & Fetching:** SWR (with Pre-rendering / Fallback data)
- **Styling:** Tailwind CSS & Shadcn UI
- **Forms:** React Hook Form + Zod
- **API Source:** RAWG Video Games Database API

---

## ✨ Key Features

- **Blazing Fast Catalog:** Game lists are pre-rendered on the server for instant loading and perfect SEO, then hydrated on the client via SWR.
- **Advanced Filtering & Search:** Search games on-the-fly using a debounced search input, with instant filtering by genres, platforms, and release dates.
- **Dynamic Routing:** Individual page for each game showcasing details, Metacritic scores, and interactive screenshot carousels.
- **PC Hardware Section:** Automatically parses and displays minimum and recommended PC system requirements for each game.
- **User Authentication:** Secure social and credentials login powered by Supabase Auth.
- **Personal Dashboard:** A private workspace where users can update their bio, showcase their PC specs, and manage their favorite games list.

---

## 🛠️ Architecture & Optimization Highlights

- **API Protection:** The RAWG API key is securely hidden in environmental variables on the server. Client-side components query data via Next.js Route Handlers (Proxy API).
- **URL-Driven State:** Filter and search settings are preserved inside URL Search Params, making links completely shareable and resilient to page refreshes.
- **Data Validation:** Strict end-to-end type safety with TypeScript and runtime schema validation with Zod.

---

## 📦 Getting Started

1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/repo-name.git](https://github.com/DmytroSvarkovskiy/next-game-catalog.git)
