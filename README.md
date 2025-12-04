# AI and the Future of Now — Conference Website

A single-page static website for the **AI and the Future of Now** conference, co-hosted by Canarias Eco-Education Centre (CEEC) and AI4Edu.

[![Astro](https://img.shields.io/badge/Astro-5.16.4-purple?logo=astro)](https://astro.build/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-4.1.17-38B2AC?logo=tailwindcss)](https://tailwindcss.com/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

---

## About the Conference

| Attribute | Details |
|-----------|---------|
| **Date** | 20 December 2025 |
| **Time** | 10:00 – 15:00 |
| **Venue** | Gran Hotel Arrecife, Lanzarote |
| **Format** | In-person + Hybrid (Google Meet, Zoom) |
| **Organisers** | CEEC (Lanzarote) & AI4Edu (Dublin, Erasmus+ KA2, European Project) |

### Purpose

Exploring how AI tools (TeacherMate, StudyBuddy) can transform education for:

- Migrants and newly arrived immigrants
- Minority groups
- People with functional diversity
- Adults in vocational education and training (VET)

### Expected Outcome

A joint policy proposal document for the Cabildo de Lanzarote and Arrecife Town Council under the Erasmus+ 2025–2027 framework.

### Participating Projects

- AI4EDU
- AIEDTECH
- AIOT

---

## Agenda

| Time | Activity |
|------|----------|
| 10:00 | Registration and welcome coffee |
| 10:20 | Official welcome (Nabil Afkir, CEO CEEC) |
| 10:30 | Keynote: Dr. Daithí Ó Murchú — "AI for EDU, Migration & the Future of Human-Centred Integration" |
| 11:30 | Q&A with speaker |
| 11:45 | Coffee break |
| 12:00 | Panel discussion: "AI Literacy, Migration & New Pathways to European Citizenship" |
| 13:00 | Breakout groups: School Education, Adult & Community Education, VET Education |
| 14:00 | Lunch and networking |
| 14:30 | Consolidation session — drafting policy document |
| 14:50 | Closing and next steps |

---

## Tech Stack

| Technology | Version |
|------------|---------|
| [Astro](https://astro.build/) | 5.16.4 |
| [Tailwind CSS](https://tailwindcss.com/) | 4.1.17 |

---

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) v18.x or higher
- [npm](https://www.npmjs.com/) v9.x or higher (included with Node.js)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/ai-future-now-conference.git
   cd ai-future-now-conference
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open in browser**
   Navigate to `http://localhost:4321/`

---

## Available Commands

| Command | Description |
|---------|-------------|
| `npm run dev` | Start development server at `localhost:4321` |
| `npm run build` | Build production site to `./dist/` |
| `npm run preview` | Preview production build locally |

---

## Project Structure

```
ai-conference-2025/
├── src/
│   ├── pages/
│   │   └── index.astro      # Main page (12 sections)
│   └── styles/
│       └── global.css       # Custom styles
├── public/                   # Static assets
├── astro.config.mjs          # Astro configuration
├── package.json
└── tsconfig.json
```

### Website Sections

1. Hero
2. About
3. Organisers
4. Agenda
5. Keynote Speaker
6. Panel Discussion
7. Breakout Groups
8. Registration
9. Hybrid Access
10. Venue
11. Contact
12. Footer

---

## Adding Tailwind CSS to an Astro Project

If starting from scratch, follow these steps:

1. **Create a new Astro project**
   ```bash
   npm create astro@latest
   ```

2. **Install Tailwind CSS and its Vite plugin**
   ```bash
   npm install tailwindcss @tailwindcss/vite
   ```

3. **Configure Vite plugin in `astro.config.mjs`**
   ```javascript
   import { defineConfig } from 'astro/config';
   import tailwindcss from '@tailwindcss/vite';

   export default defineConfig({
     vite: {
       plugins: [tailwindcss()],
     },
   });
   ```

4. **Import Tailwind in your CSS file (e.g., `src/styles/global.css`)**
   ```css
   @import "tailwindcss";
   ```

5. **Import the CSS in your layout or page**
   ```astro
   ---
   import '../styles/global.css';
   ---
   ```

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Contact

- **Organisation**: Canarias Eco-Education Centre Ltd. (CEEC)
- **Location**: Lanzarote, Canary Islands
- **Email**: canariaseec@gmail.com
- **Email**: afkirslimaninabil@gmail.com
- **Phone**: +34 651 32 64 62
