# StrategyOS

**What can we actually do?** StrategyOS is an actionable strategy dashboard that bridges the gap between understanding the problems (ClimateOS, TransitionOS, GovernanceOS) and taking action. It ranks personal, organizational, and policy strategies by real-world impact and connects each action to the metrics it moves across the ecosystem.

## Live Dashboard

🔗 **[StrategyOS Dashboard](https://strategy-os-pearl.vercel.app/)**

## Features

### 📊 Overview
Strategy Readiness Score with six domain grades (Climate Action, Economic Transition, Governance Quality, Social Equity, Individual Agency, Systemic Readiness). Four scenario projections (Aggressive Action → Active Regression) with aggregate impact charts for emissions, temperature, biodiversity, and equity. Radar visualization of domain balance.

### 👤 Personal Actions
10 individual-level strategies ranked by impact score, with CO₂ savings estimates, cost ratings, difficulty levels, and detailed descriptions. Filterable by category (Energy, Food, Transport, Finance, Waste, Civic, Career, Social). Each action links to the ecosystem dashboard it moves.

### 🏢 Organization Strategies
8 business-level strategies from Science-Based Targets to Just Transition Investment. Ranked by systemic leverage with CO₂ reduction estimates. Includes horizontal bar chart comparing reduction potential across strategies.

### 🏛️ Policy Interventions
8 government/institutional levers ranked by cost-effectiveness. From carbon pricing (#1) to AI governance frameworks. Each includes evidence-based descriptions, difficulty ratings, and the specific metrics it moves across the ecosystem.

### 🧪 Impact Simulator
Interactive "What if everyone did this?" calculator. Select any combination of 10 major strategies and see the aggregate CO₂ reduction in real time. Visual breakdown by strategy type (personal, org, policy) with narrative assessment of what the selected combination would achieve.

## Ecosystem

StrategyOS is part of the Civilization Futures Ecosystem:

| App | Focus | Link |
|-----|-------|------|
| 🌍 ClimateOS | Climate scenarios & projections | [climate-os.vercel.app](https://climate-os.vercel.app/) |
| 🛠️ TransitionOS | Workforce transition & reskilling | [transition-os-beta.vercel.app](https://transition-os-beta.vercel.app/) |
| 🏛️ GovernanceOS | Civic governance & AI oversight | [civilization-os-ashy.vercel.app](https://civilization-os-ashy.vercel.app/) |
| 🌐 CivilizationOS | Aggregate civilization health | [civilization-os-ashy.vercel.app](https://civilization-os-ashy.vercel.app/) |
| 🔬 Simulation | Macro civilizational simulation | [simulation-brown.vercel.app](https://simulation-brown.vercel.app/) |
| ⚙️ StrategyOS | Actionable strategies | [strategy-os-pearl.vercel.app](https://strategy-os-pearl.vercel.app/) |

## Tech Stack

- **Next.js 14** (App Router)
- **React 18** + TypeScript
- **Tailwind CSS 3**
- **Recharts** for data visualization
- Dark glass-card UI theme consistent with the ecosystem

## Development

```bash
npm install
npm run dev    # http://localhost:3000
npm run build  # production build
```

## Repository Layout

- `app/` — Next.js dashboard (layout, styles, page)
- `docs/` — concept notes, method primers, glossary
- `playbooks/` — decision frameworks and facilitation scripts
- `packages/analysis/` — reusable model + simulation code (planned)
- `services/api/` — scoring API interfaces (planned)
- `infrastructure/` — deployment notes and datasets
