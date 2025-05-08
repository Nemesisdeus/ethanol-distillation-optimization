## Ethanol-Water Distillation Simulation using DWSIM
## Project Overview
This project simulates a binary distillation column for separating ethanol and water using DWSIM, an open-source chemical process simulator. The simulation aims to optimize key parameters such as reflux ratio and number of stages to maximize ethanol purity while minimizing energy consumption.
## Objectives
- Simulate a continuous binary distillation column for an ethanol-water mixture.
- Study the effect of reflux ratio on separation efficiency.
- Analyze trade-offs between purity and energy consumption.
- Practice chemical process modeling and technical documentation.
## Process Description
- **Feed Composition**: 50 mol% Ethanol, 50 mol% Water  
- **Feed Flow Rate**: 100 kmol/h  
- **Feed Temperature**: 78°C (approx.)  
- **Operating Pressure**: 1 atm  
- Distillation Setup  
  - Total condenser  
  - Partial reboiler  
  - Initial number of stages: 10  
  - Feed enters at stage 5  
  - Thermodynamic Model: NRTL
## Tools Used
- [DWSIM](https://dwsim.org/) – process simulation  
- Microsoft Excel – graph plotting  
- GitHub – documentation and sharing
## Optimization Studies
### 1. **Reflux Ratio Variation**  
- **Range**: 1.5 to 5 (step = 0.5)  
- **Output Observed**:  
  - Ethanol purity in distillate  
  - Reboiler and condenser duty
## Key Learnings

- Increasing reflux ratio improves separation but increases energy cost.
- There exists an optimal reflux ratio (~2.5) for balance between purity and energy.

