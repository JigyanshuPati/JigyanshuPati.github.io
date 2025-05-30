---
title: "Physics-Informed Neural Networks for Falkner–Skan Flow"
excerpt: "Implemented a PINN-based solver to learn boundary layer velocity profiles governed by the RANS equations<br/><img src='/images/Screenshot 2025-05-29 at 4.54.49 PM.png'>"
collection: portfolio
---

This project implements a Physics-Informed Neural Network (PINN) to solve the Falkner–Skan boundary layer problem—a classical fluid dynamics case governed by Reynolds-Averaged Navier–Stokes (RANS) equations.

**Key Features:**
- Neural network model incorporates physical laws as soft constraints
- Learned velocity and pressure profiles in boundary layers with high accuracy
- Achieved errors: U = 0.082%, V = 0.147%, P = 0.021%
- Compared results with OpenFOAM to validate PINN predictions
- Eliminated the need for mesh refinement, reducing computational overhead

🔗 [View on GitHub](https://github.com/JigyanshuPati/Physics-Informed-Neural-Networks-PINNs-for-Falkner-Skan-Flow)