# Aether Core

Build a production-ready, ultra-immersive, sci-fi cyberpunk desktop and mobile web application titled "THORKAN OS // BOOTLOADER_v1.000" (also styled as AETHER_OS / THORKAN-33). The app must feature a high-end hacker/terminal aesthetic with a dark charcoal/black background (#050808), crisp neon cyan/teal accents (#00FFC4, #10B981), glassmorphism borders, monospaced tech typography, and live data telemetry counters.

### 1. Global Layout & Navigation System

- **Top Command Bar:** Displays system status (`THORKAN OS // BOOTLOADER_v1.000`), health index (`HEALTH_INDEX: 0.9984_NOMINAL`), global search query input (`QUERY_MATRIX...`), live UTC clock, system status indicators (CPU, RAM, network ticks), and an interactive **Desktop / Mobile View Switcher** button.

- **Left Sidebar Navigation (Collapsible/Responsive):** Cyber-themed menu with active states, icons, and text labels for all 10 core modules:

  01. Home / Dashboard Hub

  02. Cybersecurity Grid (Sec. Network Core)

  03. Research Matrix (Lab. Intel & Research)

  04. AI News & Metrics (Feed. AI Creation)

  05. Vehicle Telemetry (Diag. Smart Vehicle)

  06. Analytics Hub (Metric. SaaS Finance)

  07. Home Automation (Sys. Home Automation)

  08. Game Center (Tel. Esports Hub)

  09. Personal Updates (Core. Personal Updates)

  10. Habit Tracker (Sys. Habit Tracker)

  11. Rule Engine Builder (Rule Engine Builder)

- **Footer Ticker:** Bottom status marquee showing active sector links (`GOOGLE`, `GEMINI`, `WIKIPEDIA`, `SCREENER`, `HACKER_GPT`, `CLAUDE`, `N8N`, `PYWARE`) and live geolocation coordinates (`LAT: 40.7128`, `LNG: -74.0060`).

---

### 2. Detailed Module Specifications (From Figma Screens 1 to 13)

#### Module 1: Boot Sequence & System Initiation (Screens 1 & 2)

- **Initiate System View:** Features a massive central interactive circular radar/portal button (`INITIATE SYSTEM`), system daemon status diagnostic logs (`SYS.LINK_OK`, `FIREWALL_ARMED`, `KERNEL_LOAD_100%`, `MEMORY_FLUSH_COMPLETE`), and a right-side crypto sequence and hardware resource monitor widget (Uplink stability, Encryption buffer, Entropy collector, RAM, GPU, NPU, CPU, Swap bars).

- **Bootloader Logs:** Expandable boot sequence terminal logs with real-time percentage meters and security warning notices.

#### Module 2: The 10-Grid Command Central Hub (Screen 3)

- An interactive 2x5 grid dashboard of modular cards, each with a cyberpunk icon, subtitle, and live metric badge:

  - `01 // SEC.NETWORK_CORE` (ENCR_SHA256)

  - `02 // LAB.INTEL_RESEARCH` (DOC_VECTOR_DB)

  - `03 // FEED.AI_CREATION` (GEN_LAYER_4)

  - `04 // DIAG.SMART_VEHICLE` (EV_STATE: 82%)

  - `05 // METRIC.SAAS_FINANCE` (MRR: $42.5K)

  - `06 // SYS.HOME_AUTOMATION` (LOC_01)

  - `07 // TEL.ESPORTS_HUB` (LIVE_PONG)

  - `08 // CORE.PERSONAL_UPDATES` (SYNC_GSHEETS)

  - `09 // SYS.HABIT_TRACKER` (LOC_01)

  - `10 // RULE.ENGINE_BUILDER` (LOC_01)

#### Module 3: Cybersecurity Grid & Terminal (Screens 4 & 5)

- **Network Recon Dashboard:** Top stats showing DEFCON level, network latency (ms), active packet counts, and bandwidth throughput.

- **Interactive Terminal Emulator:** Fully functional pseudo-terminal where users can type/run simulated commands like `nmap -sV 192.168.1.1` with scrolling output logs (`[+] Scanning... Port 22 open SSH`).

- **Research Document Reader:** Markdown reader interface for tactical communication protocols, abstract summaries, and inline code blocks with citation checkboxes.

#### Module 4: AI Creation Feed & Analytics (Screen 6)

- **Trending Models Leaderboard:** Live bar metrics for models (GPT-5, Claude-3.5-Opus, Gemini-2-Pro) with version numbers and status indicators.

- **Scraper Health & Pipeline Logs:** Real-time data pipeline status feed monitoring vector ingestion rates and API bridge synchronization.

#### Module 5: Vehicle Telemetry & Diagnostics (Screen 7)

- **Smart Vehicle Dashboard:** 3D rendered/styled wireframe vehicle visualizer, live tire pressure monitors (PSI), battery status, G-force meters, and live map coordinates tracking telemetry packets in real-time.

#### Module 6: Financial Matrix & Analytics Hub (Screen 8)

- **Commodities & Crypto Tickers:** Live tracking cards for GOLD_AU, SILVER_AG, and BITCOIN_BTC with percentage changes.

- **Equity Performance Matrix:** Interactive SVG area charts for tech and retail sectors with high-profit trackers and volatility indices.

- **Freelance Delivery Milestones:** Horizontal milestone progression bar tracking `UI_REDACT` (Completed), `CORE_BACKEND` (Completed), `API_BRIDGE` (Processing), `STRESS_TEST` (Queued), and `DEPLOY_MAIN` (Standby).

#### Module 7: Smart Home Automation & Security (Screen 9)

- **Power Grid Status:** Live energy consumption graphs (`842.4 kW`).

- **Security Perimeter Toggles:** Interactive switches for Main Access, Motion Sensors, and Perimeter Cameras with a live CCTV feed container and a red panic protocol trigger button.

- **Climate Control & Lighting:** Ambient temperature sliders (`22°C`, `45%` humidity) and fine-grained smart bulb brightness sliders.

#### Module 8: Esports Telemetry & Gaming Hub (Screen 10)

- **Squad Performance Vector:** Cross-platform engagement metrics for games like *Minecraft* and *Free Fire MAX*, displaying active server tps, active players, player matrix K/D ratios (`Viper_09`, `Ghost_Specter`), and live patch log feeds.

#### Module 9: Personal Updates & Habit Tracker (Screens 11 & 12)

- **Intelligence Briefing & Mission Command:** Strategic goals checklist (`Advanced Cert. Mastery`, `Research Publication v1.0`, `Neural Net Optimization`) with dynamic progress rings.

- **Habit Matrix Grid:** GitHub-style contribution and habit habit-completion heatmaps across days of the week for operational tasks, physical calibration, and data synthesis.

- **Pomodoro Focus Timer:** Built-in cyberpunk timer widget (`25:00`) with start/pause/reset controls for deep work sessions.

#### Module 10: Rule Engine Builder & System Node Graph (Screen 13)

- **Visual Node Workflow Editor:** Interactive canvas where users can drag, view, and connect automation nodes (`Trigger`, `Filter`, `Action`, `Database Storage`) with glowing connection paths, memory stack monitoring, and event orchestration logs.

---

### 3. Technical & Functional Requirements

- **Tech Stack:** React, Tailwind CSS, Lucide React icons, Recharts (for telemetry and financial graphs), and canvas/SVG elements for the node builder and radar views.

- **State Persistence:** Use `localStorage` so user tasks, habits, terminal inputs, and rule engine configurations persist across page reloads.

- **Interactivity:** Every button, tab switcher, toggle switch, and modal must be fully interactive with smooth animations and responsive feedback.

This project was built with [Lovable](https://lovable.dev).

## Build with Lovable

Continue developing this project in the [Lovable editor](https://lovable.dev/projects/579cbb02-7c41-4583-bc46-ea595c5e163d).

- **Ship faster**: describe what you want to build and Lovable handles the code.
- **Stay in sync**: every change made in Lovable is committed straight to this repository.
- **Full ownership**: this code is yours. Push to `main` on GitHub and your changes sync back into Lovable, ready for your next prompt.

## Development

Prefer working locally? You need Node.js and npm — [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating).

```sh
git clone <this-repository-url>
cd <repository-name>
npm i
npm run dev
```
