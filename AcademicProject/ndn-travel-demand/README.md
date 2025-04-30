# Travel Demand Modeling Project (4-Step Model)

### Project Title: **Urban Travel Behavior Simulation using Nguyen-Dupuis Network**

### Overview
This project applied the 4-step travel demand model to simulate long-term travel behavior in a simplified urban network (Nguyen-Dupuis) over a 30-year period. The network consists of 4 zones (A, B, C, D), incorporating three travel modes: automobile, transit, and bicycle. The analysis focuses on user responses to population growth, travel cost evolution, and infrastructure constraints using iterative loop feedback under user equilibrium conditions.

---

### Key Objectives
- Model travel demand and distribution across four zones for a 30-year planning horizon.
- Evaluate the role of travel time, population growth, and friction factors in trip generation and assignment.
- Use modal split and user equilibrium to reflect travel choice and traffic patterns realistically.

---

### Methodology

**1. Network Design**
- Zones: A, B, C, D
- Modes: Automobile, Transit, Bicycle
- Simulated network: Nguyen-Dupuis grid with designated transit corridors and zone-specific infrastructure.

**2. 4-Step Model Process**
- **Trip Generation**: Based on population, students, and employee growth with calibrated regression equations.
- **Trip Distribution**: Applied gravity model with friction factors calibrated using hybrid functions and travel time frequencies.
- **Modal Split**: Used utility-based logit model considering time and cost; parameters estimated using Maximum Likelihood Estimation.
- **Trip Assignment**: User Equilibrium using BPR Function and iterative loop feedback to simulate route switching behavior.

---

### Scenario Parameters
- Growth Rate:
    - Population: 1.50% / year
    - Student: 1.00% / year
    - Employee: 1.40% / year
- Travel time updated every 5 years using UE loop adjustments
- No cross-zone bicycle trips or observed transit use during the 30-year period

---

### Results Summary
- **Mode Dominance**: Car travel remained dominant throughout the simulation due to perceived convenience and speed.
- **Bike Usage**: Confined to intra-zone trips, demonstrating effectiveness in localized travel.
- **Transit**: No significant adoption observed; linked to absence of facilities or service performance.
- **Route Adjustment**: UE-based feedback shifted users to alternative paths every 5 years in response to congestion growth.
- **Network Insight**: Zone A emerged as the trip attraction hub, influencing flow intensity in surrounding OD pairs.

---

### Tools & Techniques
- Spreadsheet-based modeling (manual computation and matrix analysis)
- Gravity model with calibrated Friction Factors
- Utility-based Multinomial Logit Model
- User Equilibrium via BPR function with capacity-based delay adjustments

---

### Insights
- Infrastructure gaps lead to modal dominance (private vehicles).
- Loop feedback from user equilibrium reflects realistic shifts in network performance and user behavior over time.
- Modal shift requires not only infrastructure but also service reliability and behavioral incentives.

---

### Disclaimer
This project was conducted for academic simulation purposes. No real-world data or policy was used or implied. Model, data, and assumptions are educational and illustrative in nature only.
