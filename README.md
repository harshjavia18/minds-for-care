# 🧠 Minds for Care — UX Pivot Project

**Global Concern for Mental Health Across Countries (2020–2024)**  

**Original Viz:** Ananya Dikshit (Tableau VOTD, B2VB2025 Week 20)  
**Pivot Tool:** Datawrapper  
**Live Chart:** [datawrapper.de/_/CNmJB](https://www.datawrapper.de/_/CNmJB/)

---

## 📌 Project Overview

This project deconstructs a Tableau Viz of the Day (VOTD) — *Minds for Care* — and rebuilds it as a focused, persona-driven editorial chart using Datawrapper.

The original dashboard visualises mental health concern across 31 countries from 2020 to 2024 using a purple gradient heatmap. While visually impressive, it was designed for data exploration, not quick decision-making.

The pivot reframes the same data around a single, actionable question:

> **"Where does Australia stand in global mental health concern — and why does it matter?"**

---

## 🗂️ Repository Structure

```
minds-for-care/
│
├── README.md                  ← You are here
│
├── docs/
│   ├── Project_Report.pdf     ← Full UX Pivot Report (Phase 1–3 analysis)
│   ├── Visual_Pitch.pdf       ← Cognitive Load Audit + Before/After comparison
│   └── Live_URL.pdf           ← Datawrapper live chart link
│
├── assets/
│   └── Mental_Health_Viz.png  ← Original Tableau dashboard screenshot
│
└── charts/                    ← (for any exported chart images added later)
```

---

## 🔍 Three-Phase Methodology

### Phase 1 — WHAT? (Deconstruction)
- Audited the original dashboard's data structure: 31 countries × 5 years × concern %
- Identified the viz's strengths (custom heatmap, memorable icons) and limitations
- Source: Ipsos Health Service Report 2024

### Phase 2 — SO WHAT? (Narrative Pivot)
Identified **6 friction points** blocking the target persona:

| Zone | Issue | Impact |
|------|-------|--------|
| 🔴 Red | Dense prose block | No headline or key number visible |
| 🔴 Red | 31-country unsortable table | Cannot sort, filter, or search |
| 🔴 Red | No interactivity | Fully static — no hover, no year selector |
| 🟡 Yellow | 5 years at equal visual weight | 2024 (most critical) gets no emphasis |
| 🟡 Yellow | Decorative icon bar chart | No axis, no scale, no precise value |
| 🟢 Green | **Golden Thread — 2024 concern %** | Australia at 60% vs global avg 45% |

**Persona:** Australian Health Policy Advisor  
**User Story:** *"I need to immediately see where Australia ranks globally so I can justify budget allocation to government stakeholders."*

### Phase 3 — WHAT NEXT? (The Pivot)
Rebuilt in Datawrapper as a ranked horizontal bar chart:
- ✅ 8 countries ranked highest → lowest by 2024 concern %
- ✅ Australia highlighted in **bold blue** — instant focal point
- ✅ Dashed reference line at **45%** (global average)
- ✅ Global Average bar in **amber** as a visual anchor
- ✅ Title answers the question before the chart is even read
- ✅ Mobile-friendly, live URL, under 5 seconds to insight

---

## 📊 Key Finding

> Australia ranks **3rd globally** at **60% concern**, sitting **15 percentage points above** the global average of 45% — above comparable peers including the United States (52%), Canada (57%), and Great Britain (54%).

---

## 🔗 Links

| Resource | Link |
|----------|------|
| 📊 Live Pivot Chart | [datawrapper.de/_/CNmJB](https://www.datawrapper.de/_/CNmJB/) |
| 📄 Original Tableau VOTD | B2VB2025 Week 20 — Minds for Care by Ananya Dikshit |
| 📰 Data Source | Ipsos Health Service Report 2024 |

---

## 📁 Documents Guide

| File | What's Inside |
|------|---------------|
| `Project_Report.pdf` | Full written report covering all 3 phases — data audit, persona analysis, pivot rationale (~950 words) |
| `Visual_Pitch.pdf` | Visual slide deck — Cognitive Load Audit with numbered friction zones + Before/After comparison table |
| `Live_URL.pdf` | One-page document with the published Datawrapper chart URL |

---

*Data Viz Assignment | Ipsos Health Service Report 2024 | Tool: Datawrapper*
