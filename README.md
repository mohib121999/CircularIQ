# CircularIQ 🌿

> AI-powered platform that transforms agrifood wastewater into certified circular revenue streams.

CircularIQ helps Mediterranean agrifood operators (dairy, olive, aquaculture) turn wastewater from a disposal cost (€15–40/m³) into a certified circular revenue stream. Built as part of the **Master in Open Innovation & Youth Entrepreneurship** at **CIHEAM Bari × LUM University**, in partnership with **Giovanni Putignano & Figli S.r.l.** (Massafra, Puglia, Italy).

---

## The Problem

Mediterranean agrifood producers pay €15–40 per m³ to dispose of nutrient-rich wastewater — while simultaneously buying fishmeal at €1,200–1,800/tonne to feed their fish. No intelligence tool exists to help them identify, compare, and prioritise the most profitable valorisation pathway for their specific waste streams.

CircularIQ solves this.

---

## How It Works

```
Your Waste → BioLink Unit → CircularIQ Engine → Best Pathway → Recovered Product → Circular Passport → WasteMap Sale
5 streams     IoT sensors     AI scoring          Ranked         Algae/Struvite/      QR certified        B2B marketplace
60 m³/day     every 15 min    & ranking           recommendations Biogas/Water         EU ESPR ready       prices feed back
```

---

## Key Features

### 🧠 AI Scoring Engine
Scores 6 circular valorisation pathways across 4 weighted dimensions in under 10 minutes:
- **Economic** (40%) — revenue + savings − capex − opex = net annual value
- **Technical** (30%) — feasibility given waste stream composition
- **Regulatory** (20%) — EU/national compliance gates (e.g. NaCl > 10 g/L blocks biological pathways)
- **Logistics** (10%) — proximity to buyers, transport cost

**Scored pathways:**
| Pathway | Example output | Potential value |
|---|---|---|
| Microalgae production | Fish feed, cosmetics | +€52K/yr |
| Struvite crystallisation | Organic fertiliser | +€28K/yr |
| Anaerobic digestion | Biogas / biomethane | +€18K/yr |
| Treated water reuse | Irrigation | €12K saved/yr |
| Halophyte cultivation | Salt-tolerant crops | +€9K/yr |
| Brine concentration | Industrial salt | Context-dependent |

### ⚗️ BioLink Unit
On-site IoT sensor layer monitoring 5 waste streams every 15 minutes:
- Conductivity, BOD, COD, nitrogen, phosphorus, pH, salinity
- Real-time alerts for regulatory threshold breaches
- Data feeds directly into the scoring engine

### 📊 Admin Dashboard
Real-time command centre for operators:
- Live pathway scores and rankings
- Economic waterfall: net annual value projection
- Regulatory compliance status per stream
- Batch management and history
- Alert system for hard gates (e.g. NaCl threshold)

### 🏷️ Circular Passport
QR-coded digital certificates for every certified output batch — 4 certification layers:
1. **Regulatory** — EU FPR 2019/1009, ARPA Puglia ISO 17025 compliance
2. **Process audit** — production method and traceability
3. **Circular claim** — origin from valorised wastewater
4. **On-chain traceability** *(roadmap)* — immutable batch record

EU ESPR Digital Product Passport-ready.

### 🛒 WasteMap Marketplace
B2B platform connecting certified circular output producers with local buyers:
- Farmers, municipalities, energy users, cosmetic manufacturers
- Real market prices feed back into pathway scoring
- Target: Puglia producers → Mediterranean MENA expansion

---

## Pilot: Giovanni Putignano & Figli S.r.l.

**Location:** Massafra, Puglia, Italy  
**Sector:** Agrifood wastewater treatment  
**Streams monitored:** 5 (dairy whey, brine, RAS effluent, olive mill, treated water)  
**Volume:** 60 m³/day  
**Projected net annual value:** +€217K  
**Disposal cost avoided:** €120K/yr  
**Payback period:** 3–5 years  

---

## Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML5, CSS3, JavaScript, Chart.js, Recharts |
| Backend | PHP Laravel, RESTful APIs |
| Database | MySQL |
| IoT | ESP32, sensor integration, real-time data pipeline |
| DevOps | Docker, CI/CD (GitHub Actions) |
| Compliance | EU FPR 2019/1009, ARPA Puglia ISO 17025, EU ESPR DPP |

---

## Project Structure

```
circulariq/
├── frontend/
│   ├── landing/          # CircularIQ landing page
│   ├── dashboard/        # Admin operator dashboard
│   └── customer/         # Customer-facing portal
├── backend/
│   ├── api/              # Laravel REST API
│   ├── scoring/          # AI pathway scoring engine
│   └── passport/         # Circular Passport generator
├── iot/
│   └── biolink/          # BioLink Unit sensor firmware (ESP32)
├── marketplace/
│   └── wastemap/         # WasteMap B2B marketplace
└── docs/
    ├── architecture.md
    ├── scoring-model.md
    └── regulatory-framework.md
```

---

## Roadmap

| Phase | Timeline | Scope |
|---|---|---|
| Phase 1 — Pilot | Oct 2025 – Jun 2026 | Massafra single operator, MVP validation |
| Phase 2 — Puglia | Q3 2026 | 3–5 Puglia agrifood operators |
| Phase 3 — Italy | 2027 | National rollout, SaaS model |
| Phase 4 — Mediterranean | 2028 | MENA expansion: Tunisia, Morocco, Algeria — PRIMA/Horizon funding |

---

## Academic Context

This project was developed within the  
**Master in Open Innovation & Youth Entrepreneurship in the Mediterranean Agrifood Sector**  
📍 CIHEAM Bari × LUM University — Puglia, Italy (Oct 2025 – Jun 2026)

---

## Author

**Mohib Bekalti**  
Industrial Computing Engineer | Agrifood Innovation | Circular Economy  
🔗 [linkedin.com/in/mohib-bekalti](https://www.linkedin.com/in/mohib-bekalti)  
📧 bekalti.mohib@gmail.com

---

## License

This project is currently under academic development. Licensing terms will be defined upon commercial release.

---

*Built with the belief that waste is just a resource in the wrong place.*
