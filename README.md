# Hi, I'm Lewan Hassan 👋

**Full-Stack Developer** (ASP.NET Core · Next.js · PostgreSQL) from Qaladze, Kurdistan Region of Iraq.
I build complete products on my own — database, REST API, interface, automated tests and deployment — and I run them in the real world.

🌐 **Portfolio:** [portfolio-ruddy-one-25.vercel.app](https://portfolio-ruddy-one-25.vercel.app/) · 📄 **CV:** [Download PDF](https://portfolio-ruddy-one-25.vercel.app/Lewan_Hassan_CV.pdf)
💼 [LinkedIn](https://www.linkedin.com/in/lewan-hassan-298087396) · 📫 lewanhassan641@gmail.com
🎓 B.Sc. Computer Science & IT — Salahaddin University, Erbil (2026)
🟢 Open to full-stack & backend developer roles (Kurdistan or remote)

> Most of my work lives in private repositories because it runs real businesses.
> Screenshots and details are on my [portfolio](https://portfolio-ruddy-one-25.vercel.app/).

---

## 🛒 KOGA — Retail ERP & Point-of-Sale System
The system that runs **Abdulla Barza Store** in Qaladze every day: **2 branches, 10+ staff**. I designed and built all of it, solo.

| | |
|---|---|
| **Scale** | 47 API controllers · ~110k lines of C# & TypeScript · 290+ database migrations |
| **Workflow** | 1,100+ commits · 340+ merged pull requests · CI on every PR · automatic deploys |
| **Quality** | 53 API integration test suites (real PostgreSQL, no mocks) + 52 Playwright E2E suites |

- **Offline-first POS.** Sales are queued in IndexedDB and synced with idempotency keys, so nothing is lost or duplicated when the internet drops. Supports barcode scanners, label and receipt printing.
- **Real retail rules:** multi-branch stock, carton › pack › piece units, weighted goods, price tiers, purchase orders, supplier invoices & claims, expiry tracking, daily cash close.
- **Field-sales app** for sales reps: visits, route maps, returns, customer statements, commission & pay, and Telegram alerts.
- **Audit log and stock ledger** through EF Core interceptors, plus a background worker for stock processing.
- **Analytics:** revenue vs. profit, margins, customer insights and reorder suggestions, with Excel/PDF export.
- Fully **right-to-left Sorani Kurdish** UI.

`ASP.NET Core 8` `EF Core` `PostgreSQL` `Next.js 16` `React 19` `TypeScript` `Zustand` `Dexie` `TailwindCSS` `Playwright` `GitHub Actions` `Docker` `Render` `Cloudflare Pages`

## 🎟️ Xanchy — Online Ticket Booking Platform
University research project at Salahaddin University. Ticketing for concerts, events and sports.
- Interactive SVG seat map with timed seat holds; a background service releases expired holds, so seats are never double-sold
- Organizer finance dashboard, promo codes, JWT auth, Web Push notifications and scheduled reminders

`ASP.NET Core 8` `EF Core` `PostgreSQL` `Next.js 16` `React 19` `TailwindCSS` `GSAP` `Docker`

## 🍕 Fast Pizza Qaladze — QR Table Ordering *(freelance)*
Started as a digital menu, then grew into a full ordering system. Customers scan the QR code on their table and order with no app or account, and orders appear live on the kitchen screen. Delivered in under a week.
`Supabase` `PostgreSQL` `Row-Level Security` `Realtime` `JavaScript` `PWA`

## 💱 Exchange Rate Board *(freelance)* · [live](https://creative-fenglisu-045c0d.netlify.app/)
A price board for a currency exchange office. Staff edit currency, gold and silver rates from a phone and export a ready-to-post image in one tap.
`React` `HTML/CSS`

## 🏪 Ashty Market *(freelance)*
A supplier and transaction tracker for a local market: ASP.NET Core API with Identity/JWT, and a Next.js PWA with photo upload.

---

## 🛠️ Tech Stack

**Backend:** C# · ASP.NET Core 8 · EF Core · REST APIs · JWT / role-based auth · background services
**Frontend:** TypeScript · React 19 · Next.js 16 · Zustand · TailwindCSS · DaisyUI · PWA & offline-first · RTL UIs
**Data:** PostgreSQL (Neon, Supabase) · SQL Server · MySQL · SQLite · IndexedDB
**Quality & DevOps:** Playwright · integration testing · GitHub Actions · Docker · Render · Vercel · Cloudflare Pages · Netlify

🗣️ Kurdish (native) · English (professional working) · Arabic (basic)
🌱 Currently learning: AI / LLM integration, Python
