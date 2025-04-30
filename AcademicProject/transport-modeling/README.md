# Transportation Modeling Project

### Project Title: **Multimodal Travel Demand and Infrastructure Impact Analysis on Sioux Falls Network**

### Overview
This academic project investigates the long-term impacts of implementing Light Rail Transit (LRT) and Bike infrastructure on the Sioux Falls transportation network using a 4-step travel demand modeling approach. The analysis simulates population growth and its effects on congestion, mode choice, and system-wide travel time over a 30-year horizon.

---

### Key Objectives
- Analyze the effect of LRT and Bike lane introduction on urban mobility.
- Simulate multimodal user behavior using utility-based modal split.
- Optimize traffic distribution with User Equilibrium assignment.
- Quantify benefits using economic evaluation: NPV, IRR, and B/C Ratio.

---

### Methodology
**1. Network & Demand Setup**
- Study area: Sioux Falls Network (24 nodes, 76 links)
- Input: OD Matrix with 1.8% annual demand growth
- Modes: Automobile, LRT, Bike

**2. 4-Step Travel Demand Modeling**
- **Trip Generation & Distribution**: Based on socio-economic data
- **Modal Split**: Multinomial Logit model using utility functions (based on time & cost)
- **Assignment**: 
    - Shortest Path for free-flow time analysis
    - Frank-Wolfe-based User Equilibrium to simulate realistic traffic flow

**3. Scenario Design**
- Compare "Do Nothing" vs. "With Project" (includes 74 km LRT and 144 km bike lanes)
- Introduce LRT/Bike on high-attraction nodes (e.g. schools, transport terminals)

**4. Economic Evaluation**
- Time Value: 100 THB/hour
- Construction Costs: LRT = 800M THB/km, Bike = 5M THB/km
- Indicators: 
    - Net Present Value (NPV)
    - Internal Rate of Return (IRR)
    - Benefit/Cost Ratio (B/C)

---

### Results Summary
- **Traffic Flow**: Congestion was significantly reduced in major links after project implementation.
- **Mode Shift**: Despite availability, LRT had low adoption due to longer travel time and fare; bicycles showed moderate shift in short trips.
- **Travel Time**: Network-wide travel time decreased, especially in years 15–30.
- **Economic Feasibility**: Positive NPV and B/C > 1 indicated the project is economically viable.

---

### Tools & Techniques
- Excel-based modeling and simulation
- Mathematical algorithms:
    - Dijkstra's Algorithm (Shortest Path)
    - Frank-Wolfe Algorithm (User Equilibrium)
    - BPR Function for travel time estimation
- Cost-benefit computation using present value techniques

---

### Insights
- Infrastructure improvement tailored to trip-attraction nodes can significantly reduce congestion.
- Bicycles are a feasible alternative for intra-zone trips; LRT requires service improvement to be competitive.
- Feedback loops in user equilibrium modeling reflect realistic travel behavior and network evolution.

---

### Disclaimer
This project was completed for academic purposes as part of a graduate-level transportation modeling course. Full model files and data are not publicly shared.
