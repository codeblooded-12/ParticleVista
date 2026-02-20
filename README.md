# ParticleVista
ParticleVista is a physics-informed ML surrogate that accelerates Monte Carlo particle simulations while preserving physical correctness and uncertainty awareness.


## Day 1 – Data Understanding & Surrogate Framing

### Objective
Defined the surrogate modeling task:
Predict `DER_mass_MMC` using only `PRI_*` detector-level variables.

### Work Completed
- Inspected dataset structure
- Identified PRI (primary) and DER (derived) features


### Key Insight
The mapping:
Primary Detector Variables → Derived Observable  
resembles a simplified surrogate modeling pipeline.
