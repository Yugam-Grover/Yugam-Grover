# Yugam Grover

Frontend engineer building performant, type-safe React applications.

> 🟢 Open to frontend engineering roles — [yugamgrover13@gmail.com](mailto:yugamgrover13@gmail.com)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/yugam-grover)
[![Wellfound](https://img.shields.io/badge/Wellfound-000000?style=flat-square&logo=wellfound&logoColor=white)](https://wellfound.com/u/yugam-grover)
[![Foundit](https://img.shields.io/badge/Foundit-6F2DBD?style=flat-square&logo=monster&logoColor=white)](YOUR_FOUNDIT_PROFILE_LINK)

---

### Stack

[![Skills](https://skillicons.dev/icons?i=react,ts,js,tailwind,supabase,postgres,vite)](https://skillicons.dev)

**Languages & Frameworks** — React.js, TypeScript, JavaScript (ES6+)  
**State & Data** — TanStack Query, TanStack Table, Zustand  
**UI & Styling** — Tailwind CSS, Shadcn/UI, Styled Components  
**Backend** — Supabase, PostgreSQL, REST APIs  
**Tooling** — Zod, React Hook Form, Leaflet, Vite

---

### Projects

#### [Clavis — Hotel Management Dashboard](https://github.com/Yugam-Grover/clavis)

Full-stack hotel dashboard using Supabase for JWT auth, PostgreSQL operations, and image storage. Remote state via TanStack Query with server-side filtering and pagination prefetching, compound components built on React Context, CRUD forms wired with React Hook Form, and sales analytics with Recharts. Route-based code splitting improved Lighthouse Performance from 74 to 90.

`React` `Supabase` `TanStack Query` `Recharts` `React Hook Form` `Styled Components`

[Live Demo ↗](YOUR_CLAVIS_LIVE_LINK) · [README + Screenshots →](https://github.com/Yugam-Grover/clavis#readme)

---

#### [Nimbus — Real-Time Weather App](https://github.com/Yugam-Grover/Weather_App)

Fetches weather, geocoding, and air pollution data from OpenWeatherMap via TanStack Query with shared query keys. Includes a custom AQI utility built on EPA breakpoint formulas, an interactive Leaflet + MapTiler map, and per-section Error Boundaries for isolated failure handling.

`React` `TypeScript` `TanStack Query` `Zod` `Leaflet` `Shadcn/UI` `Tailwind CSS`

[Live Demo ↗](YOUR_NIMBUS_LIVE_LINK) · [README + Screenshots →](https://github.com/Yugam-Grover/Weather_App#readme)

---

### Currently Building With

**Next.js** — App Router, Server Components, SSR/SSG patterns

---

### GitHub Stats

<div align="center">
  <img height="170em" src="https://github-readme-stats.vercel.app/api?username=Yugam-Grover&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
  <img height="170em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Yugam-Grover&layout=compact&theme=tokyonight&hide_border=true" />
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=Yugam-Grover&theme=tokyonight&hide_border=true" />
</div>

---

### How I approach frontend work

TypeScript types are compile-time only — they don't exist when the app runs. I validate all API responses with Zod schemas at runtime so an unexpected shape from a real API doesn't cause silent failures in component state. Combined with TanStack Query's request deduplication and caching, and Error Boundaries scoped to individual sections, the result is a UI that holds up when things go wrong.
