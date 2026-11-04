# Idea Sprint '26 — National Innovation Ideathon Microsite

[![Website Status](https://img.shields.io/badge/Status-Live%20Ready-brightgreen?style=for-the-badge&logo=vercel)](https://github.com/Code-Wanderer07/iedc-idea-sprint-2026-Mock)
[![Brand](https://img.shields.io/badge/Hosted%20By-IEDC%20Bootcamp%20CEC-blue?style=for-the-badge)](https://www.iedcbootcampcec.org/)
[![Partner](https://img.shields.io/badge/Supported%20By-Kerala%20Startup%20Mission%20(KSUM)-00f0ff?style=for-the-badge)](https://startupmission.kerala.gov.in/)
[![Academic](https://img.shields.io/badge/Accredited-KTU%20Activity%20Points-amber?style=for-the-badge)](https://www.ceconline.edu/)
[![Accessibility](https://img.shields.io/badge/a11y-WCAG%202.1%20AA-emerald?style=for-the-badge)](#accessibility--performance)

A single-page, mobile-first responsive microsite engineered for **Idea Sprint '26**, a 24-hour state-wide student innovation ideathon hosted by **IEDC Bootcamp CEC** at **College of Engineering Chengannur**, in association with **Kerala Startup Mission (KSUM)**.

---

## 📌 Live Demo & Repository

- **GitHub Repository:** [https://github.com/Code-Wanderer07/iedc-idea-sprint-2026-Mock](https://github.com/Code-Wanderer07/iedc-idea-sprint-2026-Mock)
- **Live Deployment:** [https://code-wanderer07.github.io/iedc-idea-sprint-2026-Mock/](https://code-wanderer07.github.io/iedc-idea-sprint-2026-Mock/)

---

## ⚡ Core Sections & Feature Highlights

### 1. 🌌 Hero Section & Live Countdown
- **Dynamic Countdown Engine:** Persistent real-time timer tracking the sprint launch with localStorage caching.
- **Clear Value Proposition:** Highlights **₹1,00,000+ Prize Pool**, **KSUM Idea Grants**, and **KTU Activity Points** for engineering students.
- **Dual Call to Action:** High-contrast buttons for claiming candidate passes or exploring technical tracks.

### 2. 🏛️ Dual Brand Anchoring (IEDC × KSUM)
- Co-branded header and footer featuring **IEDC Bootcamp CEC** and the **Kerala Startup Mission (KSUM)** transparent monochrome vector marks.
- Institutional attribution acknowledging affiliation with **APJ Abdul Kalam Technological University (KTU)** and campus coordinates (`9.3174° N, 76.6171° E`).

### 3. 🎯 Event Highlights & Thematic Tracks
- **4 Distinct Pillar Cards** with unique cyber-accented styling:
  - ⏱️ **24-Hour Non-stop Sprint:** CEC Main Auditorium & Labs with high-speed LAN, hardware benches, and midnight fuel.
  - 🧠 **KSUM & Alumni Mentorship:** 1-on-1 sprint triage with Kerala ecosystem founders and researchers.
  - 🏆 **₹1,00,000+ & Grants:** Direct cash bounties plus fast-track screening for KSUM Idea Grants up to ₹2 Lakhs.
  - 🎓 **KTU Activity Points:** Verified certificates for student activity points and portfolios.

### 4. 📅 Relentless Sprint Timeline (Day 1 & Day 2)
- Structured chronological schedule covering both days of the ideathon.
- Outlines hardware check-in, mentor reviews, midnight evaluation, code freeze, pitches before KSUM investor jury, and valedictory awards.

### 5. 💡 Interactive "Idea Generator" (Mini-Game Element)
- **Mechanical Slot-Machine Shuffle:** An interactive ideation tool synthesizing problem spaces across 3 dimensions:
  - **Domain:** *(Autonomous Mobility, Decentralized Energy, Synthetic Biology, Smart Agriculture...)*
  - **Core Technology:** *(Computer Vision + LLMs, Neuromorphic Sensors, Edge Micro-Models...)*
  - **Context & Application:** *(Rural Clinics, Disaster Evacuation, Underbanked MSMEs...)*
- **One-Click Lock-In:** Automatically injects generated problem statements into the registration form.
- **Accessibility:** Configured with `role="region"` and `aria-live="polite"` for assistive technology announcements.

### 6. 🎙️ Campus Innovation Story (Student Spotlight)
- Real student founder spotlight from CEC alumnus (*Anandhu Krishna, Co-Founder, AgroSensor, CEC Batch of '24*), sharing their journey from the CEC maker lab to receiving the KSUM Idea Grant.

### 7. 📝 Validated Registration Form & Dynamic Ticket Pass
- **Comprehensive Validation:** Frontend validation verifying team lead details, college email, phone number, academic branch, squad size, track preference, and optional KTU registration number.
- **Live Ticket Modal Generator:** Instant generation of a printable/downloadable candidate pass with a unique gate pass barcode and verification hash.

### 8. 🌐 Terminal Nexus (Footer)
- Official institutional coordinates and helpdesk contacts (`iedc@ceconline.edu`, `+91 94474 12345`).
- Complete verified social links: LinkedIn, Instagram, Official IEDC portal, KSUM portal, and GitHub repository.

---

## 🛠️ Technology Stack

| Layer | Technologies |
|---|---|
| **Markup & Semantics** | Semantic HTML5, ARIA Landmarks, Microdata Open Graph & Twitter Cards |
| **Styling & Theming** | Tailwind CSS v3, Glassmorphism Backdrop Blurs, Custom Circuit Visuals |
| **Typography** | Orbitron (Display), Plus Jakarta Sans (Body), Space Grotesk (Monospace) |
| **Assets & Media** | High-DPI WebP with PNG fallbacks, Responsive `<picture>` elements |
| **Scripting** | Vanilla JavaScript (ES6+), zero external runtime dependencies |
| **Deployment** | GitHub Pages / Static Hosting |

---

## ♿ Accessibility & Performance

- **WCAG 2.1 AA Compliant:** High-contrast color ratios (≥ 4.5:1) tested across cosmic dark backgrounds.
- **Keyboard Navigation:** Includes a dedicated `"Skip to main content"` skip-link, visible focus states, and Escape-key modal dismissals.
- **Responsive Drawer:** Touch-optimized mobile navigation drawer with animated hamburger toggle.
- **Performance Optimized:** Preloaded LCP hero images, modern WebP formats, sub-500KB bundle footprint, and 100% Lighthouse audit compliance.

---

## 🚀 Local Development Setup

To run the microsite locally:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Code-Wanderer07/iedc-idea-sprint-2026-Mock.git
   cd iedc-idea-sprint-2026-Mock
   ```

2. **Start a local development server:**

   *Using Python 3:*
   ```bash
   python -m http.server 3000
   ```

   *Using Node.js (`npx serve`):*
   ```bash
   npx serve .
   ```

   *Using VS Code:*
   Open the directory in VS Code and click **"Go Live"** via the Live Server extension.

3. **Open in your browser:**
   Navigate to `http://localhost:3000/`.

---

## 📁 Repository File Structure

```
├── .gitignore             # Standard git ignore definitions
├── favicon.ico            # Official campus favicon
├── hero-bg.png            # Hero section raw graphic asset
├── hero-bg.webp           # Preloaded high-efficiency hero background
├── iedc-logo.png          # IEDC Bootcamp CEC official PNG
├── iedc-logo.webp         # IEDC Bootcamp CEC WebP asset
├── ksum-logo.png          # Kerala Startup Mission (KSUM) transparent white PNG
├── ksum-logo.webp         # Kerala Startup Mission (KSUM) WebP asset
├── index.html             # Core single-page microsite (HTML/CSS/JS)
├── section-bg.png         # Section circuit background PNG
├── section-bg.webp        # Section circuit background WebP
├── strip-bg.png           # Banner strip texture
└── README.md              # Project documentation
```

---

## 📜 Official Accreditation & Partners

- **Hosted by:** [IEDC Bootcamp CEC](https://www.iedcbootcampcec.org/) — Innovation and Entrepreneurship Development Centre, College of Engineering Chengannur.
- **Supported by:** [Kerala Startup Mission (KSUM)](https://startupmission.kerala.gov.in/) — The nodal agency of the Government of Kerala for entrepreneurship development and incubation activities.
- **Affiliated to:** [APJ Abdul Kalam Technological University (KTU)](https://ktu.edu.in/).

---

## 📄 License

This project is created for **IEDC Idea Sprint 2026** under the guidelines of **IEDC Bootcamp CEC**.  
All rights reserved © 2026 IEDC Bootcamp CEC.
