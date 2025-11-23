Markdown# CLASS-BCC v1.0

**Public Boltzmann solver for Balance-Condition Cosmology**  
Nicholas Ryan Christopher Jimison • 20 November 2025  
arXiv:2511.XXXXX • Zenodo DOI: 10.5281/zenodo.XXXXXXXX (replace with real DOI after release)

![BCC w(z)](https://raw.githubusercontent.com/nrcj1987/class_bcc/main/bcc_wz_final.png)
*Predicted dark-energy equation of state w(z) compared to ΛCDM (best-fit to DESI 2025 + Planck + SH0ES).*

### Overview

Balance-Condition Cosmology (BCC) is a three-parameter (H₀, Ωₘ, δ₀), string-embeddable geometric model for evolving dark energy based on a moving D3-brane in a warped throat with a minimal balance ansatz between vector flux and scalar gradient.

Key features:
- Rigid, non-monotonic phantom-crossing w(z)
- Future deceleration at z ≈ −0.45
- Naturally alleviates H₀ tension (best-fit H₀ ≃ 71.8 km s⁻¹ Mpc⁻¹)
- Correlated vector KK signatures in mid-ℓ CMB (detectable in mild-warping region)

### Quick start

```bash
git clone https://github.com/nrcj1987/class_bcc.git
cd class_bcc
make -j8
./class explanatory/explanatory.ini
Expected output includes:
textw_DE(a=1) = -1.1204
Future deceleration at z ≈ -0.45
Parameters



# CLASS-BCC v1.0

**Public Boltzmann solver for Balance-Condition Cosmology**  
Nicholas Ryan Christopher Jimison • 22 November 2025  
arXiv:2511.XXXXX • Zenodo DOI: 10.5281/zenodo.XXXXXXXX (replace after release)

![BCC w(z)](figures/bcc_wz_final.png)
*Predicted dark-energy equation of state w(z) compared to ΛCDM (best-fit to DESI 2025 + Planck + SH0ES).*

### Overview

Balance-Condition Cosmology (BCC) is a **three-parameter**, string-embeddable geometric model for evolving dark energy. Dark energy arises from the nearly light-speed motion of our 4D brane in a warped AdS₅ throat, stabilised by a minimal balance ansatz between bulk vector flux and scalar gradient.

Key predictions:
- Rigid non-monotonic w(z): phantom dip at z≈1.1, w₀≈−1.12, future deceleration at z≈−0.45
- Alleviates ∼50% of the H₀ tension (best-fit H₀ ≈ 71.9 km s⁻¹ Mpc⁻¹)
- Massive vector KK modes with definite helicity → **circularly polarised B-mode peak at ℓ ≈ 550–600**
- Detection forecast: **2–5 σ** (typical warping), **5.5–7.2 σ** (mild-warping region) with CMB-S4 + LiteBIRD

### Quick start

```bash
git clone https://github.com/nrcj1987/class_bcc.git
cd class_bcc
make -j8
./class explanatory/explanatory_proca.ini





















ParameterDescriptionBest-fit valuebcc_on = yesActivate BCC—delta_0_todayPresent-day deviation amplitude0.018kappa_bccO(1) coefficient (default 3.0)3.0
Citation
Please cite the code as:
bibtex@software{class_bcc_2025,
  author       = {Jimison, Nicholas Ryan Christopher},
  title        = {{CLASS-BCC: Public Boltzmann solver for Balance-Condition Cosmology}},
  year         = 2025,
  publisher    = {Zenodo},
  version      = {v1.0},
  doi          = {10.5281/zenodo.XXXXXXXX},
  url          = {https://doi.org/10.5281/zenodo.XXXXXXXX}
}
And the paper:
bibtex@article{jimison2025bcc,
  author        = {Jimison, Nicholas Ryan Christopher},
  title         = {{Balance-Condition Cosmology: A Predictive Moving-Brane Model with Minimal Balance Ansatz}},
  year          = 2025,
  archivePrefix = {arXiv},
  eprint        = {2511.XXXXX},
  primaryClass  = {astro-ph.CO}
}
Links

Paper I (theory): https://arxiv.org/abs/2511.XXXXX
Paper II (constraints): https://arxiv.org/abs/2511.YYYYY
MCMC chains & plots: https://github.com/nrcj1987/bcc_mcmc
Zenodo archive: https://doi.org/10.5281/zenodo.XXXXXXXX

License
MIT License (same as official CLASS)
Vector Proca modes and full perturbation implementation coming Q1 2026 (branch feature/vector_kk).
Issues, suggestions, and collaborations welcome!
