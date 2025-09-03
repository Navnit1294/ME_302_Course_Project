# Turbomachine Component Scaling Analysis in a Closed-Loop High-Pressure Facility


This project, completed as part of ME302 (Mechanical Engineering Course Project, IIT Kanpur, 2024-25), focuses on determining the maximum feasible scale for testing a turbomachine component in a laboratory closed-loop high-pressure flow facility.

The objective is to achieve Mach (0.55) and Reynolds number (3×10⁶) similarity with the prototype, while ensuring compliance with facility constraints (maximum pressure ≤ 250 kPa and closed-loop condition p₀₅ ≥ p₀₁).

🎯 Objectives

Determine the maximum geometric scaling factor for the turbomachine model.

Ensure dynamic similarity (Mach and Reynolds number) with the prototype.

Validate feasibility under facility constraints and compressor performance limits.

🛠️ Methodology

Flow Analysis

Applied compressible flow relations to compute stagnation and static conditions across compressor–diffuser stages.

Incorporated facility constraints and similarity requirements.

Computational Validation

Used compressor performance map (p₀ ratio vs. ṁref) for operating point identification.

Verified closed-loop feasibility and validated against Reynolds number and mass flow conditions.

Tools Used

Python for computational analysis and plotting.

LaTeX for report documentation.

Reference compressor data provided in .txt and .xlsx formats.

📊 Key Results

Maximum feasible scale factor: 0.6179 (~61.8% of prototype length).

Operating conditions:

Inlet stagnation pressure = 204.7 kPa

Compressor exit stagnation pressure = 247.8 kPa (within 250 kPa limit)

Outcome: Closed-loop condition satisfied (p₀₅ ≥ p₀₁), ensuring stable and dynamically similar testing of scaled models.
