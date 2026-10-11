---
layout: page
title: Airflow-Pathogen Spread Dynamics
description: A CFD-ABS approach to optimizing ventilation and filtration strategies to reduce airborne infection risk in a cardiopulmonary rehabilitation gym. The study examines mixing versus displacement ventilation and MERV-13 filtration under superspreader conditions.
img: assets/img/sigradi-cover.png
importance: 1
category: work
related_publications: false
published: true
cv_pdf: SIGraDi_2025.pdf
---

## Project Information

Building ventilation systems are crucial in airborne transmission, yet current ASHRAE standards, while meeting indoor air quality requirements, fall short in high-intensity environments like gyms due to high occupancy, prolonged interactions, and elevated respiratory rates. This SIGraDi 2025 study examines airborne pathogen risks in a cardiopulmonary rehabilitation gym, addressing aerosol dispersion from equipment-induced forced convection and occupant thermal plumes, as well as the effectiveness of MERV-13 filtration.

An integrated framework synthesizes computational fluid dynamics (CFD) and agent-based simulation (ABS) to compare mixing versus displacement ventilation and to evaluate MERV-13 filtration for reducing pathogen exposure. The CFD model simulates equipment- and thermally-induced airflow with HVAC boundary conditions including air change rates, stratification, and filtration. Results, validated using the Wells-Riley model and contaminant removal effectiveness (CRE), indicate that induced convection increases horizontal pathogen dissemination, while MERV-13 filtration significantly reduces concentration despite superspreader impact.

**Authors:** Sharmista Debnath, Amy Yang, Matthew Swarts, Marcelo Alvarez, Paula Gomez  
**Affiliation:** Georgia Institute of Technology and Georgia Tech Research Institute  
**Publication:** SIGraDi 2025 | Meta - Responsive Approaches

<div class="image-row-3">
<img src="{{ 'assets/img/sigradi-cfd-setup.png' | relative_url }}" alt="CFD gym setup">
<img src="{{ 'assets/img/sigradi-mixing.jpg' | relative_url }}" alt="Mixing ventilation airflow">
<img src="{{ 'assets/img/sigradi-displacement.jpg' | relative_url }}" alt="Displacement ventilation airflow">
</div>

---

## Methodology

The case study focuses on a cardiopulmonary rehabilitation gym, chosen for its high occupancy, diverse activities, and immunocompromised population. CFD simulations are executed through the Eddy3D plugin in Grasshopper using OpenFOAM’s buoyantBoussinesqSimpleFoam solver with k-ε RANS turbulence modeling. Boundary conditions include variable air change rates (6–12 ACH), supply air temperatures, metabolic heat sources (400–600 W per occupant), and equipment-induced airflow from treadmills and stationary bicycles.

The ABS model, created in AnyLogic, includes waiting areas, locker rooms, the main gym, rest areas, and observation rooms. Twenty agents are simulated over a 4-hour morning session (6:00 AM to 10:00 AM): 12 patients, including 3 superspreaders, and 8 staff. A sequential one-way coupling approach uses ABS peak-exposure locations as occupant and equipment positions in the CFD setup. Results are validated with the Wells-Riley infection risk model and contaminant removal effectiveness (CRE).

<img src="{{ 'assets/img/sigradi-abs.png' | relative_url }}" alt="Agent-based simulation paths and gym layout" class="img-fluid">

---

## Results

Equipment-induced forced convection increases aerosol dispersion distances by 65% (1.8 m to 3.0 m) and elevates exposure risks by 40% compared to static occupant scenarios. Displacement ventilation achieved superior CRE values of 1.8–2.4 in occupant breathing zones, compared with mixing ventilation at an average CRE of 1.7. Under superspreader scenarios emitting pathogens at five times the baseline rate, displacement ventilation showed better thermal stratification and contaminant capture than mixing, particularly when paired with MERV-13 filtration.

<img src="{{ 'assets/img/sigradi-superspreader.jpg' | relative_url }}" alt="Superspreader temperature contours" class="img-fluid">

Spatiotemporal exposure maps show high-density zones in the cardio equipment area, main corridor, and rest areas. Overall exposure rose from 2,757 at 7:52 AM to 14,151 at 8:58 AM as patients completed cardio and staff circulated for disinfection. MERV-13 filtration reduced infection probability by 75–80% in non-superspreader scenarios, though superspreaders reduced this efficacy to 40–60%.

<div class="iecc-image-pair">
<div class="iecc-image-pair__item">
<img src="{{ 'assets/img/sigradi-exposure-early.jpg' | relative_url }}" alt="Exposure at peak cardio initiation">
</div>
<div class="iecc-image-pair__item">
<img src="{{ 'assets/img/sigradi-exposure-late.jpg' | relative_url }}" alt="Exposure at post-cardio dispersal">
</div>
</div>

---

<div class="mt-4 mb-4">
  <a href="{{ 'assets/pdf/SIGraDi_2025.pdf' | relative_url }}" target="_blank" class="btn btn-primary">
    <i class="fas fa-file-pdf"></i> View Full Report (PDF)
  </a>
</div>
