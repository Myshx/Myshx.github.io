---
layout: page
title: Design Space Exploration for High Efficiency Buildings
description: The project focuses on designing an exploration for retrofitting 792 Donald Lee Hollowell Parkway NW, Atlanta, Georgia, USA. The project is located in Climate Zone 3, with an area of 1,680 sqf. The aim is to design exploration for building renovation to understand the tradeoff between occupancy (density), comfort and energy use intensity while balancing operational energy, reducing the overall carbon emission, and maintaining daylight performance (UDI/ASE). Additionally, explore rainwater harvesting potential.
img: assets/img/A.jpg
importance: 1
category: work
related_publications: true
cv_pdf: BSDP1.pdf
---

## Project Information

**Location:** 792 Donald Lee Hollowell Parkway NW, Atlanta, Georgia, USA  
**Climate Zone:** 3  
**Building Area:** 1,680 sq ft

The project focuses on designing an exploration for retrofitting 792 Donald Lee Hollowell Parkway NW, Atlanta, Georgia, USA. The project is located in Climate Zone 3, with an area of 1,680 sqf. The aim is to design exploration for building renovation to understand the tradeoff between occupancy (density), comfort and energy use intensity while balancing operational energy, reducing the overall carbon emission, and maintaining daylight performance (UDI/ASE). Additionally, explore rainwater harvesting potential.

---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/design-exploration.gif" title="Design exploration 3D model" class="img-fluid rounded" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/design-exploration-2.gif" title="Building analysis with occupancy" class="img-fluid rounded" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/design-exploration-3.gif" title="Daylight performance analysis" class="img-fluid rounded" %}
    </div>
</div>
<div class="caption">
    Design space exploration showing 3D building models with envelope analysis, occupancy density studies, and daylight performance optimization.
</div>

---

## Retrofitting Strategy

Preserve the shell. Reline the core. Retrofit from inside out. The building is leaky, glare-prone, and energy-hungry, but the façade is sound, daylight is already sufficient, and occupancy can rise. Because it is historic, the street face stays; insulation, systems, and interior shades do the work from the inside, cutting infiltration and radiation without rewriting the envelope.

<div class="row mt-4">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/retrofitting-table.png" title="Retrofitting components and upgrades" class="img-fluid rounded" %}
    </div>
</div>

---

## Methodology

<div class="row mt-4">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/methodology-workflow.png" title="Design exploration methodology workflow" class="img-fluid rounded" %}
    </div>
</div>
<div class="caption">
    Computational workflow for design space exploration: (1) Read database parameters, (2) Construct building geometry, (3) Configure simulation settings, (4) Generate geometry energy model, and (5) Run simulation to evaluate performance metrics.
</div>

---

## Assumptions

Simulations run on the current Atlanta-Fulton TMY and a 2050 morphed file. Zone loads follow ASHRAE 90.1, with an equipment power density of 8.1 W/m² and a cooling set point of 24–27°C. Envelope, infiltration, shading, and HVAC COP ranges are the variables; level count, floor fraction, and extension set how the shell grows.

### Weather Files

<div class="row mt-4">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/weather-files.png" title="Current and future weather files comparison" class="img-fluid rounded" %}
    </div>
</div>

<div class="image-row-3">
<img src="{{ 'assets/img/assumption-layer-1.gif' | relative_url }}" alt="Envelope layer assembly 1">
<img src="{{ 'assets/img/assumption-layer-2.gif' | relative_url }}" alt="Envelope layer assembly 2">
<img src="{{ 'assets/img/assumption-layer-3.gif' | relative_url }}" alt="Envelope layer assembly 3">
</div>

<div class="row mt-4">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/assumption-geometry.png" title="Building geometry settings" class="img-fluid rounded" %}
    </div>
</div>

---

## Design Space Construction

Wall, roof, glazing, shading, infiltration, and HVAC options combine into 7,077,888 solutions. A 128-run fractional factorial samples that space so EUI, CO₂, cost, daylight (UDI), and glare can be compared without simulating every combination.

<div class="row mt-4">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/design-space-construction.png" title="Design space construction parameters" class="img-fluid rounded" %}
    </div>
</div>

---

## Results

A weighted score (EUI 27.5%, UDI and DGP 17.5% each, area 15%, CO₂ 12.5%, cost 10%) ranks the runs. Cooling load, then roof and wall insulation, move EUI the most; adding floors changes area and glare. Best current-weather cases cut site EUI by about 61% from the 283.91 baseline.

<div class="results-hero-image">
<img src="{{ 'assets/img/results-performance.jpg' | relative_url }}" alt="Performance results">
</div>

<div class="row mt-4">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/results-sensitivity.png" title="Sensitivity analysis results" class="img-fluid rounded" %}
    </div>
</div>

---

<div class="mt-4 mb-4">
  <a href="{{ 'assets/pdf/BSDP1.pdf' | relative_url }}" target="_blank" class="btn btn-primary">
    <i class="fas fa-file-pdf"></i> View Full Report (PDF)
  </a>
</div>
