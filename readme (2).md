# 🤖 RCE Eluru — Academic X-Ray Analytics Console

[Institution](https://www.google.com/search?q=https://www.rcee.ac.in/)
[Accreditation](https://www.google.com/search?q=https://www.rcee.ac.in/information/iqac)
[NBA](https://www.google.com/search?q=https://admissions.rcee.ac.in/)
[Stack](https://www.google.com/search?q=https://vitejs.dev/)
[](#developer-credits)

> **How does an Autonomous Engineering Campus really work?**  
> **RCE Xray** puts **[Ramachandra College of Engineering (Autonomous), Eluru](https://www.google.com/search?q=https://www.rcee.ac.in/)** under an interactive visual X-ray—allowing management, faculty, students, and accreditation peer teams to explore every department, R23 curriculum track, student lifecycle stage, NAAC A+ / NBA audit metric, and placement drive in one unified map.

**Designed, Re-Engineered & Developed by:** **Maneesha L.L.S.**

---

## ✨ Key Features & AI-to-Campus Architecture Mapping

This repository forks and re-engineers the visual `agent-xray` simulation paradigm into a domain-specific institutional telemetry platform for **RCE Eluru**:

| Ray's Anatomical Organ | Source Modules | Original AI Agent Layer | RCE Eluru Institutional Mapping |
| :--- | :--- | :--- | :--- |
| **🧠 Neural Core (`Brain`)** | `src/data/brain.ts`<br>`src/scenes/brain.tsx` | **LLM (Large Language Model)** — Context windows, reasoning & system prompts | **6 Engineering Departments (`CSE`, `AI & ML / IoT / CS`, `ECE`, `EEE`, `MECH`, `CIVIL`)**, 70+ laboratories, R23 OBE curricula & [Department Faculty](https://www.google.com/search?q=https://www.rcee.ac.in/Faculty). |
| **💾 Memory Vault (`Memory`)** | `src/data/memory.ts`<br>`src/components/Ray.tsx` | **RAG (Retrieval-Augmented Generation)** — Vector databases & embeddings | **Central Library (27,300+ Volumes)**, 640+ Scopus/IEEE publications & Autonomous Digital Exam ERP. |
| **🌳 Spinal Bus (`Tree`)** | `src/data/tree.ts`<br>`src/scenes/tree.tsx` | **Planning DAG** — Chain-of-Thought (CoT) & Tree-of-Thoughts (ToT) | **Student Academic Lifecycle**: EAPCET Admissions & `Parichay` in the [Freshmen Engineering Department](https://www.google.com/search?q=https://fed.rcee.ac.in/) → Mid-I/II Exams → Lab Externals → Graduation. |
| **💓 Heart Monitor (`Checkup`)** | `src/data/checkup.ts`<br>`src/scenes/checkup.tsx` | **Guardrails, Evals & Observability** — Benchmark scoring & verification | **[RCE IQAC](https://www.google.com/search?q=https://www.rcee.ac.in/information/iqac) Institutional Audit**: NAAC A+ Grade (CGPA > 3.26), 5 NBA-accredited branches, 155 patents & ₹4.34 Cr R&D grants. |
| **🚀 Propulsion (`Trips`)** | `src/data/trips.ts`<br>`src/scenes/trips.tsx` | **Tool Calling & Action Loops (MCP / APIs)** | **[RCE Training \& Placements Cell](https://www.google.com/search?q=https://www.rcee.ac.in/placements)**: 610+ annual offers across 50+ MNCs (Accenture, TCS, Infosys, Wipro, Enzen, Formonic Tech). |

---

## 🗂️ Repository File Structure

```text
rce-eluru-academic-xray-console/
├── README.md                         # Project documentation & architecture guide
├── LICENSE                           # MIT License (Copyright © 2026 Maneesha L.L.S.)
├── package.json                      # Scripts, dependencies & author metadata
├── index.html                        # App entry HTML with RCE Eluru branding
├── vite.config.ts                    # Vite bundler configuration
├── tsconfig.json                     # TypeScript compiler configuration
├── tailwind.config.js                # Tailwind CSS theme & RCE color tokens
├── postcss.config.js                 # PostCSS configuration
├── src/
│   ├── main.tsx                      # React DOM root mount
│   ├── App.tsx                       # Unified interactive RCE Xray Console application
│   ├── styles.css                    # Global styles, RCE Navy/Gold variables & TopBar/Footer
│   ├── scenes.css                    # Vector node glow, X-ray scanner & inspector card styles
│   ├── components/
│   │   ├── TopBar.tsx                # Header with 1/135 counter, ⚡ X-ray toggle & Maneesha L.L.S. pill
│   │   ├── Footer.tsx                # Persistent institutional & developer credit bar
│   │   └── Ray.tsx                   # Animated cubic Bezier X-ray telemetry beam component
│   ├── utils/
│   │   └── geometry.ts               # Polar-to-Cartesian orbital math & Bezier curve generator
│   ├── data/
│   │   ├── brain.ts                  # CSE, AIML/IoT/CS, ECE, EEE, MECH, CIVIL & R23 courses
│   │   ├── tree.ts                   # 5-stage Student Academic Lifecycle DAG
│   │   ├── checkup.ts                # NAAC A+, NBA 5-branch, 155 Patents & IQAC metrics
│   │   ├── memory.ts                 # 27,300+ Library Volumes & Autonomous ERP telemetry
│   │   └── trips.ts                  # 610+ Placement Drives & branch eligibility matrices
│   └── scenes/
│       ├── brain.tsx                 # Radial Department & Curriculum X-Ray Explorer
│       ├── tree.tsx                  # Student Academic Lifecycle Progression View
│       ├── checkup.tsx               # Institutional NAAC A+ / NBA Audit Dashboard
│       └── trips.tsx                 # Training & Placement Cell Drives Filter View
├── scripts/
│   └── tour.mjs                      # Headless Playwright automated scene walkthrough capture
└── video/
    └── make.mjs                      # FFmpeg 1080p MP4 compositor with Maneesha L.L.S. watermark
```

---

## 🚀 Quick Start (Local Development)

### 1. Clone & Install Dependencies

```bash
git clone https://github.com/<your-username>/rce-eluru-academic-xray-console.git
cd rce-eluru-academic-xray-console
npm install
```

### 2. Start the Interactive Development Server

```bash
npm run dev
```

Open `http://localhost:5173` in your browser:
- **Hover over Ray** to peek inside with the live circular X-ray scanner lens.
- Click **`⚡ Turn on the X-ray`** (or toggle the top-bar `⚡ X-ray` switch) to expose all internal organs.
- Click **`🗺️ Whole map`** to inspect all 135 mapped parts and 327 tools across RCE Eluru.
- Click **`⭐ Maneesha L.L.S.`** or **`💻 Code Blueprint`** to view developer credits and architecture snippets.

### 3. Build for Production (GitHub Pages / Vercel / Netlify)

```bash
npm run build
npm run preview
```

### 4. Generate Automated Management Briefing Video (`MP4`)

With the dev server running on port `5173` and `ffmpeg` installed:

```bash
npm run report:generate
```

This runs `scripts/tour.mjs` (Playwright) followed by `video/make.mjs` (FFmpeg) to produce a watermarked 1080p management briefing video at `video/output/rce_eluru_management_review.mp4`.

---

## 👩‍💻 Developer Credits

- **Lead Architect & Developer:** **Maneesha L.L.S.**
- **Institution:** [Ramachandra College of Engineering (Autonomous), Eluru](https://www.google.com/search?q=https://www.rcee.ac.in/), NH-16 Bypass Road, Vatluru (V), Eluru – 534007, West Godavari District, Andhra Pradesh, India.
