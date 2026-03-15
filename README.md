# Concrete-Penetration-Failure-Response-Dataset
The Data of concrete Penetration depth with detailed references
Comprehensive Dataset for ML-Based Concrete Penetration Prediction

**📖 Overview**

Existing datasets for machine learning (ML)-based penetration prediction often suffer from limited data sources, narrow parameter ranges, and insufficient feature evaluation. To build broadly applicable and highly generalizable predictive models, we have compiled a comprehensive, large-scale global experimental dataset.

By balancing physical comprehensiveness with model training feasibility, this repository provides a rigorously homogenized foundational dataset for evaluating and predicting the penetration failure response of concrete under high-velocity impacts.

**🎯 Feature Space Definition**

To capture the governing physical mechanisms of concrete penetration, we selected data acquisition metrics based on three core dimensions: projectile characteristics, target properties, and impact conditions. After eliminating redundant parameters, we finalized a robust 12-dimensional feature vector as the model input:

1. Projectile Parameters

M: Mass (kg)

d: Diameter (mm)

L: Length (mm)

CRH: Caliber-Radius-Head

rho_p: Density (kg/m³)

sigma_y: Yield strength (MPa)

sigma_u: Ultimate tensile strength (MPa)

2. Target Properties

rho_c: Concrete density (kg/m³)

f_c: Compressive strength (MPa)

T: Thickness (mm)

A_t: Area (m²)

3. Impact Conditions

V: Striking velocity (m/s)

**🛡️ Data Curation Protocol**

To mitigate systematic bias and ensure data reliability, the global experimental data was strictly screened based on the following criteria:

Projectile Shape: Restricted to ogive-nosed projectiles.

Target Boundary: Restricted to semi-infinite targets.

Impact Trajectory: Restricted to normal, non-perforating impacts.

Rigorous data processing and homogenization were applied to unify disparate data formats, ultimately yielding a highly robust dataset for subsequent analysis and ML model training.
