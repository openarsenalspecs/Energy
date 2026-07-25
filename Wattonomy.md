# Wattonomy

**Precision for real-world power.**

Wattonomy is an open-source (AGPL-3.0+) AI-driven energy and utility decision intelligence platform that models real-world home systems, evaluates full lifecycle costs, applies verified incentives, and provides transparent, source-backed financial recommendations.

It is designed to help users make informed decisions about heating, cooling, and energy systems based on **location, utility rates, incentives, installation costs, and long-term performance.**

---

## License & Notice Requirements

Wattonomy is released under the **GNU Affero General Public License v3.0 or later (AGPL-3.0+)**.  
By contributing to this project, you agree that your contributions will also be released under this license.

Please note the following:

- All contributions must comply with the **AGPL-3.0+** terms.  
- Under **Section 7** of the license, all redistributions, forks, and derivative works must preserve attribution to:  
  **Roxanne Ardary** and **[roxanneardary.com](https://www.roxanneardary.com/)**.  
- Wattonomy specifications are free to use with attribution. A Specification Branding License can be negotiated upon request.
- The project's `notice.md` file tracks attribution requirements and contributor acknowledgments.  
  Any update that adds new contributors or modifies attribution should also update `notice.md`.
- When submitting a pull request, ensure that any new files maintain attribution headers where applicable.
- Network-deployed versions of this software must also remain fully AGPL-3.0+ compliant, including exposure of source code modifications when applicable under the license.

For full legal details, please refer to the AGPL-3.0+ license and the project's `notice.md` file.

---

## What Wattonomy Does

Wattonomy analyzes home energy systems using real-world data to answer one key question:

> **What is the true long-term cost of this system in my location, after incentives and real utility rates?**

It evaluates:
- Heating systems (gas, electric, heat pumps, geothermal)
- Cooling systems
- Energy efficiency options
- Incentives (federal, state, utility)
- Installation + maintenance + replacement cycles
- Monthly and lifetime energy costs

---

## Core Features

### 🧠 Energy System Modeling
- Simulates HVAC system performance based on:
  - Home size
  - Insulation quality
  - Climate zone
  - Efficiency ratings (SEER, AFUE, COP)
- Converts heating and cooling demand into real energy usage estimates

---

### 💰 Financial Analysis Engine
- Upfront installation cost estimation
- Monthly utility cost projection
- Lifetime cost modeling (10–30 year range)
- Maintenance and replacement cycle cost integration
- Inflation and utility rate scaling support

---

### 💸 Incentives Engine (Federal + State + Utility)
- Automatically detects applicable incentives based on location and system type
- Supports:
  - Tax credits
  - Rebates
  - Utility-specific programs
- Calculates:
  - Upfront savings (rebates)
  - Delayed savings (tax credits)
- Applies stackability rules and eligibility filtering

---

### 🔍 Verified Source Transparency
Every incentive includes:
- Official program source links
- Legal references (where applicable)
- Verification timestamps

Primary data sources include:
- :contentReference[oaicite:0]{index=0}  
- :contentReference[oaicite:1]{index=1}  
- :contentReference[oaicite:2]{index=2}  

---

### 🤖 AI Explanation Layer (Explainable Intelligence)
Wattonomy includes an AI layer that:
- Explains incentives in plain language
- Clarifies tax credits vs rebates
- Calculates real usable value based on tax liability
- Identifies whether incentives help upfront affordability or only long-term savings
- Flags limitations, exclusions, and assumptions
- Always references official sources

---

### 📊 System Comparison Engine
- Normalizes all systems into comparable financial outputs
- Ranks options based on:
  - Total lifetime cost
  - Monthly cost
  - Incentive-adjusted net cost
  - Budget fit
- Produces clear ranked recommendations

---

### 🧩 Modular Plugin Architecture
Wattonomy is fully extensible:

- Region plugins (state/country-specific logic)
- Utility provider plugins
- HVAC/system plugins
- Incentive program plugins

New data sources or systems can be added without modifying core logic.

---

### 📄 Reporting System
Generates structured outputs:
- Cost breakdown reports
- Incentive summaries
- System comparison tables
- AI explanations with citations
- Budget feasibility analysis

---

## Example Output

| System        | Install Cost | Incentives | Net Cost | Monthly | Lifetime Cost | Rank |
|--------------|-------------|------------|----------|--------|---------------|------|
| Heat Pump    | $15,000     | $7,000     | $8,000   | $120   | $45,000       | #1   |
| Gas Furnace  | $8,000      | $1,000     | $7,000   | $160   | $52,000       | #2   |
| Geothermal   | $30,000     | $10,000    | $20,000  | $60    | $40,000       | #3   |

---

## Design Philosophy

Wattonomy is built on three principles:

- **Transparency** — every number is explainable and traceable  
- **Accuracy** — based on real-world data, not assumptions  
- **Modularity** — every component is replaceable and extensible  

---

## Roadmap (Planned)

- Multi-state incentive expansion
- Utility rate API integrations
- Solar + battery system modeling
- Real-time rate updates
- Advanced climate modeling
- User-specific tax optimization profiles

---

## Contributing

Contributions are welcome under AGPL-3.0+.

Please ensure:
- All modules follow the plugin structure
- All external data sources are documented
- Incentive logic includes source references
- `notice.md` is updated for attribution changes

---

## Specification Branding License (SBL)

### Standard
- Fully AGPL-3.0+ compliant system
- Copyleft enforced for network deployments
- Required attribution:
  - Roxanne Ardary
  - https://www.roxanneardary.com/

### Optional

- **Specification Branding License (SBL)**
  - Attribution-free commercial deployment
  - Pricing based on scale, usage, and deployment scope
  - [https://roxanneardary.com/wattonomy/](https://roxanneardary.com/wattonomy/)  

---
