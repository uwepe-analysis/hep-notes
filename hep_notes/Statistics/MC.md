# MC Event Generation

Monte Carlo (MC) event generators are software libraries that simulate high-energy particle physics events.

## Parton Showers
**Definition**:
The perturbative evolution of high-energy partons through successive splittings, governed by Quantum Chromodynamics (QCD), producing a cascade of quarks and gluons.

**Approaches**:
- **$p_T$-ordered parton shower**:
  Splittings are ordered based on transverse momentum ($p_T$) of emissions.
- **Angular-ordered parton shower**:
  Emissions are ordered by angles to account for QCD coherence and interference effects.
- **Dipole parton shower**:
  Emissions are modeled as radiation off color-connected dipoles, improving soft and collinear emission descriptions.

---

## Hadronization
**Definition**:
The non-perturbative process where partons transition into color-neutral hadrons, ensuring confinement as required by QCD.

**Approaches**:
- **String-based hadronization**:
  Color-connected partons are treated as strings that fragment into hadrons based on string tension.
- **Cluster-based hadronization**:
  Color-singlet partons are grouped into clusters, which decay into hadrons based on their mass and phase space.
