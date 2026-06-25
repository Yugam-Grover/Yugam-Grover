# Yugam Grover

Frontend engineer. React, TypeScript — and the parts that only break in production.

> 🟢 Based in Delhi · Open to frontend engineering roles — [yugamgrover13@gmail.com](mailto:yugamgrover13@gmail.com)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/yugam-grover)
[![Wellfound](https://img.shields.io/badge/Wellfound-000000?style=flat-square&logo=wellfound&logoColor=white)](https://wellfound.com/u/yugam-grover)

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

#### [Clavis — Hotel Management Dashboard](https://github.com/Yugam-Grover/Hotel-Dashboard)

Full-stack hotel dashboard using Supabase for JWT auth, PostgreSQL operations, and image storage. Remote state via TanStack Query with server-side filtering and pagination prefetching, compound components built on React Context, CRUD forms wired with React Hook Form, and sales analytics with Recharts. Route-based code splitting improved Lighthouse Performance from 74 to 90.

`React` `Supabase` `TanStack Query` `Recharts` `React Hook Form` `Styled Components`

[Live Demo ↗](https://clavis-dashboard.vercel.app/) · [README + Screenshots →](https://github.com/Yugam-Grover/Hotel-Dashboard#readme)

---

#### [Nimbus — Real-Time Weather App](https://github.com/Yugam-Grover/Weather_App)

Fetches weather, geocoding, and air pollution data from OpenWeatherMap via TanStack Query with shared query keys. Includes a custom AQI utility built on EPA breakpoint formulas, an interactive Leaflet + MapTiler map, and per-section Error Boundaries for isolated failure handling.

`React` `TypeScript` `TanStack Query` `Zod` `Leaflet` `Shadcn/UI` `Tailwind CSS`

[Live Demo ↗](https://nimbus-weatherapp.vercel.app/) · [README + Screenshots →](https://github.com/Yugam-Grover/Weather_App#readme)

---

### Currently Building With

**Next.js** — App Router, Server Components, SSR/SSG patterns

---

### Most Used Languages


  <img height="170em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Yugam-Grover&layout=compact&theme=tokyonight&hide_border=true" />

---

### How I approach frontend work

TypeScript covers compile time — at runtime, I validate every API response through **Zod** schemas at the network boundary so unexpected shapes are caught before they reach component state. **Error Boundaries** scoped per section contain failures without cascading; **TanStack Query** deduplicates requests across components so the same endpoint never fires twice. On the component side, **compound components** via React Context keep internal state hidden from the consumer — clean API, no prop threading.

