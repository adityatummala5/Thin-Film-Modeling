This repository aims to lower barriers to precision modeling of anisotropic deposition and thin-film transport. By keeping the methods transparent and the code reproducible (including all figure pipelines), we hope it serves as a common foundation for MEMS and bio-MEMS researchers to design predictable, tunable conductive pathways on curved substrates.

## Overview
This repository provides an **open-access framework** for modeling anisotropic physical vapor deposition (PVD) on cylindrical and wire-like substrates and predicting the resulting electrical resistance. It includes:

- **First-principles geometric model** for anisotropic flux: generalized pseudo-Lambertian emission  cos^n(psi)
  mapped to cylindrical coordinates.

- **Closed-form resistance model** integrating **Fuchs–Sondheimer** (surface scattering) and **Mayadas–Shatzkes** (grain-boundary scattering) corrections.

- **3D Monte Carlo simulator** for validating deposition profiles.

- **Reproducible code** for every figure reported in the manuscript.

The intent is to keep these tools **transparent, reusable, and extensible**, enabling the community to build modeling pipelines for **deposition, transport, optimization, and MEMS/bio-MEMS design**.

See the manuscript for more details and contact the authors for questions.
