# Welcome to my GitHub 👋

*Astrophysics · data analysis*

Physicist (MSc Astrophysics, Universitat de Barcelona) working at the intersection
of statistical modelling and data analysis. My background is in extracting robust
signal from noisy, messy real-world data — neutron star oscillations, gravitational
lensing, and multi-survey astronomical photometry — and I'm now applying that same
rigor to data analysis more broadly. Along the way I also pick up side-projects that allow me to grow
while being fun and actually useful, from browser-based hardware tests to visualising the cosmos.

**What I work with:**
- 🐍 Python (UltraNest, NumPy, PyCBC) for statistical modelling, data cleaning, and Bayesian inference
- 📊 SQL, Excel and Matplotlib for data analysis and reporting
- 🔬 Validating every result against independent benchmarks before trusting it

## My big projects

**TFM** — *Trabajo Final de Máster (Master's Thesis)*
Core topic: neutron star oscillations & asteroseismology (Julia/Mathematica). Multiple EOS models (APR, BBS1, BSk22, FPS, GM1, MPA1, RMF2, SLy4, SLy9), TOV solver implementations, Cowling approximation convergence studies, built on the [`NeutronStarOscillations.jl`](https://github.com/lennoxkeeble/NeutronStarOscillations.jl) package by Keeble. Supervised by Dr. Yago Bea Besade and Dr. Jorge Casalderrey Solana.

**TFG** — *Treball de Fi de Grau (Bachelor's Thesis)*
Core topic: gravitational microlensing and limb darkening of supermagnified stars. Fit a 6-parameter statistical model (later extended to 8 parameters) to 131 real HST photometric measurements across 2 filters, using Bayesian nested sampling (`UltraNest`). Supervised by Dr. Jordi Miralda-Escudé. Published in ASP Conference Proceedings, Vol. 543 (Habitable Worlds Observatory: Mission Framework, Technology, and Broader Contributions); also available as a [preprint on arXiv](https://arxiv.org/abs/2607.14034). Currently ongoing extension.

**SPHEREx/Gaia** — *Stellar Classification from Multi-Survey Photometry*
Core topic: infrared excess and binarity/accretion classification of Gaia-selected stellar sources. Adapted an existing data-cleaning and cross-catalogue matching pipeline for 32 sources across 7 survey catalogues, applying SNR ≥ 3 cuts, automated contaminant detection, and outlier rejection (MAD filtering). Fit photospheric blackbody models to each source's spectral energy distribution, classifying infrared excess above 3σ significance in 30 of 32 sources. Supervised by Dr. Nadejda Blagorodnova.

I'm currently looking for **Data Analyst / Junior Data Scientist / PhD** opportunities.

---

## 📂 Other Projects

### 🔭 Astrophysics

| Sub-project | Description |
|---|---|
| **ALBA** | Synchrotron beamline emittance measurements & fitting (Python/UltraNest). |
| **CAFOS** | Calar Alto Observatory instrument calibration. |
| **Chandra** | X-ray imaging and spectral analysis of the oxygen-rich supernova remnant G292.0+1.8 using CIAO; extracted region spectra (soft, hard, bright, filament, pulsar wind nebula) and fit NEI/power-law models in Sherpa. |
| **FermiLAT** | Reduced ~6 months of Fermi-LAT data (>40,000 events) on the Vela pulsar with the Fermi ScienceTools pipeline; produced a barycentre-corrected, exposure-corrected light curve, and outlined the methodology for a binned likelihood spectral fit. |
| **GammaRay** | 1D spectral and time-resolved light curve analysis of the flaring blazar PKS 2155−304 using Gammapy on 15 H.E.S.S. DL3 observations; fit a power-law spectral model and extracted flux points via the reflected-background method. |
| **Log-Likelihood fitting comparison** | Statistical fitting hands-on: RooFit, UltraNest, corner plots, multi-Gaussian fits to HEP data (B_s → φγ). |
| **GW** | Gravitational-wave data analysis with PyCBC: waveform generation across mass/spin/distance, GWTC-4.0 catalog and parameter extraction, strain data processing (PSD, whitening, Q-transform), and matched filtering/SNR detection on real LIGO events. |
| **Muon** | Muon lifetime experiment: data acquisition and exponential lifetime fitting (UltraNest). |
| **Final Project** | SPHEREx/Gaia cross-match, extinction mapping, and spectral fitting pipeline for stellar classification. |
| **Binary classification problem** | ML event selection for particle physics: Keras/PyTorch/XGBoost classifiers applied to LHCb data (B → K*μμ). |
| **Orbit integration** | galpy orbit-integration covering spherical and axisymmetric galactic potentials, orbital families and action-angle variables. Also included distribution functions and Schwarzschild modelling. |
| **ALMA OT mock proposal** | Proposal preparation: scientific justification, technical setup, sensitivity calculations and document reviewal. |
| **CASSIS/RADEX** | CASSIS line analysis & RADEX non-LTE modelling hands-on: CO excitation, collisional rates and parameter estimation. |
| **MESA** | MESA lab: 1 M☉ (pre-MS to He-burning) and 20 M☉ full evolution runs; HR diagrams, nuclear profiles, mass-loss. |
| **YSO** | SED fitting & classification of Young Stellar Objects using Gaia EDR3 + WISE/IRAS photometry; YSO evolutionary stage classification. |

### 🌐 Web

- **[MousePress](https://github.com/gtorralba4/MouseBench)** — [site](https://mousebench.fyi)
  I've seen that most mouse-test and similar sites often require extra non-test related cookies or even sign-ups, so I've been developing my own website to help people resolve mouse-related issues (and maybe keyboard-related down the line).
  Browser-based tests for your mouse: click speed, DPI, polling rate, latency. Runs
  entirely locally — no tracking, no accounts — plus editorial articles in EN/DE/ES.
---

<details>
<summary>🇪🇸 Español</summary>

# Bienvenido/a mi GitHub 👋

*Astrofísica · análisis de datos*

Físico (Máster en Astrofísica, Universitat de Barcelona) que trabaja en la
intersección entre la modelización estadística y el análisis de datos. Mi
trayectoria se centra en extraer señal fiable a partir de datos reales,
ruidosos y complejos — oscilaciones de estrellas de neutrones, lente
gravitatoria y fotometría astronómica multi-survey — y ahora aplico ese
mismo rigor al análisis de datos en un sentido más amplio. Por el camino,
también voy aprendiendo y construyendo herramientas divertidas y realmente útiles, desde tests
de hardware en el navegador hasta visualizaciones del cosmos.

**Con qué trabajo:**
- 🐍 Python (UltraNest, NumPy, PyCBC) para modelización estadística, limpieza de datos e inferencia bayesiana
- 📊 SQL, Excel y Matplotlib para análisis de datos e informes
- 🔬 Validando cada resultado frente a referencias independientes antes de darlo por bueno

## Mis grandes proyectos

**TFM** — *Trabajo Final de Máster*
Tema principal: oscilaciones de estrellas de neutrones y astrosismología (Julia/Mathematica). Usando múltiples modelos de ecuación de estado (APR, BBS1, BSk22, FPS, GM1, MPA1, RMF2, SLy4, SLy9), implementaciones del solucionador de las ecuaciones TOV, estudios de convergencia de la aproximación de Cowling, construido sobre el paquete [`NeutronStarOscillations.jl`](https://github.com/lennoxkeeble/NeutronStarOscillations.jl) de Keeble. Dirigido por el Dr. Yago Bea Besade y el Dr. Jorge Casalderrey Solana.

**TFG** — *Treball de Fi de Grau*
Tema principal: microlente gravitatoria y oscurecimiento de limbo (limb darkening) en estrellas supermagnificadas. Ajuste de un modelo estadístico de 6 parámetros (ampliado posteriormente a 8) a 131 medidas fotométricas reales del HST en 2 filtros, mediante muestreo anidado bayesiano (`UltraNest`). Dirigido por el Dr. Jordi Miralda-Escudé. Publicado en ASP Conference Proceedings, Vol. 543 (Habitable Worlds Observatory: Mission Framework, Technology, and Broader Contributions); disponible también como [preprint en arXiv](https://arxiv.org/abs/2607.14034). Actualmente en proceso de ampliación.

**SPHEREx/Gaia** — *Clasificación Estelar a partir de Fotometría Multi-Survey*
Tema principal: clasificación de exceso infrarrojo y de señales de binaridad/acreción en fuentes estelares seleccionadas de Gaia. Adapté un pipeline existente de limpieza de datos y cruce de catálogos para 32 fuentes en 7 catálogos de sondeos, aplicando cortes de SNR ≥ 3, detección automática de contaminantes y rechazo de valores atípicos (filtrado MAD). Ajusté modelos de cuerpo negro fotosférico a la distribución espectral de energía de cada fuente, clasificando el exceso infrarrojo por encima de 3σ de significancia en 30 de las 32 fuentes. Dirigido por la Dra. Nadejda Blagorodnova.

Actualmente busco oportunidades como **Analista de Datos / Científico de Datos Júnior / Doctorado (PhD)**.

---

## 📂 Otros Proyectos

| Subproyecto | Descripción |
|---|---|
| **ALBA** | Medición y ajuste de la emitancia del haz en el sincrotrón (Python/UltraNest). |
| **CAFOS** | Calibración de instrumentación en el Observatorio de Calar Alto. |
| **Chandra** | Análisis de imagen y espectral en rayos X del remanente de supernova rico en oxígeno G292.0+1.8 usando CIAO; extracción de espectros por región (suave, dura, brillante, filamento, nebulosa del viento del púlsar) y ajuste de modelos NEI/ley de potencias en Sherpa. |
| **FermiLAT** | Reducción de ~6 meses de datos de Fermi-LAT (>40.000 eventos) del púlsar de Vela con el pipeline de Fermi ScienceTools; producción de una curva de luz corregida por baricentro y por exposición, y descripción de la metodología para un ajuste espectral de verosimilitud binned. |
| **GammaRay** | Análisis espectral 1D y curva de luz resuelta en tiempo del blazar en erupción PKS 2155−304 usando Gammapy sobre 15 observaciones DL3 de H.E.S.S.; ajuste de un modelo espectral de ley de potencias y extracción de puntos de flujo mediante el método de fondo por regiones reflejadas. |
| **Comparación de ajuste por log-verosimilitud** | Prácticas de ajuste estadístico: RooFit, UltraNest, corner plots, ajustes multi-gaussianos a datos de física de partículas (B_s → φγ). |
| **GW** | Análisis de datos de ondas gravitacionales con PyCBC: generación de formas de onda variando masa/espín/distancia, exploración del catálogo GWTC-4.0 y extracción de parámetros, procesado de datos de deformación (PSD, whitening), y detección mediante filtrado adaptado/SNR en eventos reales de LIGO. |
| **Muon** | Experimento de vida media del muón: adquisición de datos y ajuste exponencial de la vida media (UltraNest). |
| **Proyecto Final** | Cruce de catálogos SPHEREx/Gaia, mapeo de extinción y pipeline de ajuste espectral para clasificación estelar. |
| **Problema de clasificación binaria** | Selección de eventos mediante ML en física de partículas: clasificadores Keras/PyTorch/XGBoost aplicados a datos de LHCb (B → K*μμ). |
| **Integración de órbitas** | Integración de órbitas con galpy en potenciales galácticos esféricos y axisimétricos, familias orbitales y variables de ángulo-acción. Incluye también funciones de distribución y modelización de Schwarzschild. |
| **Propuesta simulada ALMA OT** | Preparación de propuesta: justificación científica, configuración técnica, cálculos de sensibilidad y revisión del documento. |
| **CASSIS/RADEX** | Prácticas de análisis de líneas con CASSIS y modelización no-LTE con RADEX: excitación de CO, tasas colisionales y estimación de parámetros. |
| **MESA** | Prácticas con MESA: evolución completa de modelos de 1 M☉ (pre-secuencia principal hasta combustión de helio) y 20 M☉; diagramas HR, perfiles nucleares, pérdida de masa. |
| **YSO** | Ajuste de SED y clasificación de Objetos Estelares Jóvenes usando fotometría de Gaia EDR3 + WISE/IRAS; clasificación por etapa evolutiva. |

### 🌐 Web

- **[MousePress](https://github.com/gtorralba4/MouseBench)** — [sitio web](https://mousebench.fyi)
  He visto que la mayoría de webs de test de ratón y similares suelen requerir cookies adicionales no relacionadas con el test, o incluso un registro, así que he estado desarrollando mi propia web para ayudar a la gente a resolver problemas relacionados con el ratón (y quizás con el teclado más adelante).
  Tests de ratón en el navegador: velocidad de clic, DPI, tasa de sondeo (polling rate), latencia. Funciona
  completamente en local — sin rastreo, sin cuentas — además de artículos editoriales en EN/DE/ES.

---
</details>
