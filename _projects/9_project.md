---
layout: page
title: Micro-Grid Feasibility
description: This project investigates the microgrid feasibility for St. Mary’s and Darien, Georgia, focusing on resilience, solar energy potential, and sustainable community infrastructure. Conducted as a collaborative class effort between the Urban Design Studio and the High Performance Building Lab, the work combines site-specific solar potential assessment, energy demand analysis, cost modeling, and climate adaptation scenarios—including rainfall, outdoor comfort, and stormwater management. The integrated approach provides comprehensive recommendations for efficient microgrid design, renewable energy adoption, and climate-resilient urban planning tailored to the needs of these Georgia communities.
img: assets/img/microgrid-solar.jpg
importance: 1
category: work
related_publications: false
published: true
cv_pdf: SolarMSUD.pdf
---

## Project Information

**Location:** St. Mary’s and Darien, Georgia  
**Studio:** Urban Design Studio with the High Performance Building Lab  
**Software:** Rhino, Climate Consultant, Ladybug and Honeybee

This project investigates the microgrid feasibility for St. Mary’s and Darien, Georgia, focusing on resilience, solar energy potential, and sustainable community infrastructure. Conducted as a collaborative class effort between the Urban Design Studio and the High Performance Building Lab, the work combines site-specific solar potential assessment, energy demand analysis, cost modeling, and climate adaptation scenarios—including rainfall, outdoor comfort, and stormwater management. The integrated approach provides comprehensive recommendations for efficient microgrid design, renewable energy adoption, and climate-resilient urban planning tailored to the needs of these Georgia communities.

<img src="{{ 'assets/img/microgrid-massing.jpg' | relative_url }}" alt="Urban massing options for the microgrid study" class="img-fluid">

---

## Solar Energy - St. Marys

The Osborne Street corridor is treated as a high-resilience microgrid. Roof-mounted PV is sized from measured roof area and local radiation rather than a generic per-house kit.

Annual solar radiation on the site is 1,819 kWh/m²·yr. Available roof area is 15,897.64 m². With 80% panel coverage, 18% module efficiency, and 96% inverter efficiency, the array generates about 3,997,600 kWh per year. Site EUI is 148 kWh/m²·yr across 35,744.54 m² of floor area, so projected annual use is 12,546,334 kWh. On-site PV covers 31.86% of that load. The remainder has to come from storage, a sized backup generator, and demand management — which is why the cost and climate work sit next to the solar map rather than after it.

<img src="{{ 'assets/img/microgrid-solar.jpg' | relative_url }}" alt="St. Marys solar potential map and site radiation" class="img-fluid">

---

## Climate Analysis

The monthly solar-exposure plot is the climate driver for the St. Marys array. Annual radiation is 1,819 kWh/m²·yr, but it is not spread evenly: output climbs through spring, peaks from May to August, and drops sharply in November and December. That summer-heavy profile is why storage and an 800 kW backup are sized to critical loads rather than to a flat year-round yield.

The same coastal climate also sets the rainfall and comfort work. Extreme-rainfall projections for 2035 and 2060 span Hot/Dry, Central, and Warm/Wet storylines, and rainwater catchment on the study blocks can harvest about 988,415 gallons per year. The monthly radiation curve and those wetter futures have to be read together: generation is highest in the months when outdoor heat and stormwater are also at their most demanding.

<img src="{{ 'assets/img/microgrid-climate.gif' | relative_url }}" alt="Monthly solar exposure and climate resource for St. Marys" class="img-fluid">

---

## Cost Analysis

A 1,471 kW PV array at $2/W is about $2.94 million. Critical loads are taken as 15% of the 34,374 kWh daily use, or roughly 5,000 kWh/day, which sets a 5,000 kWh lithium-ion battery at $2 million. Peak demand, spread over a 10-hour window, is about 3,437 kW; sizing backup to 25% of that peak gives an 800 kW natural-gas generator at $540,000. Underground cabling, switchgear, and building interfaces add $1.34 million. Soft costs and contingency bring the package to about $7.95 million.

The 30% federal ITC on PV plus storage knocks $1.48 million off that total, to about $6.46 million — roughly $1,539 per resident across 4,200 people. That is a community infrastructure number, not a rooftop-solar sticker: it buys generation, a day of critical-load storage, and a generator that can ride through a coastal outage.

<img src="{{ 'assets/img/microgrid-cost.png' | relative_url }}" alt="Microgrid cost breakdown for St. Marys" class="img-fluid">

---

## Context-Sensitive Outdoor Thermal Comfort

Outdoor comfort is tested as an iterative urban-form problem, not a single shade canopy. Hours run annually from 06:00 to 20:00.

The base case puts 442 kWh/m²·yr on exposed surfaces. The south façades take more than they can use and need shading or trees at the fenestration. A 30 ft, medium-density tree line on the centre, shedding in fall, drops that to 426 kWh/m²·yr.

Under a warm filter (outdoor temperature above 25°C), annual radiation on the comfort surfaces falls to 209 kWh/m²·yr and sits in a comfortable range once shading is in place. Cool hours below 15°C behave differently: with trees, radiation is only 48 kWh/m²·yr and winter sun is short; without trees in fall it rises to 52 kWh/m²·yr and is the better indoor-comfort alternative. The rule that comes out of the iterations is seasonal: shade and trees for the hot months, a thinner canopy when the same streets need winter radiation.

<img src="{{ 'assets/img/microgrid-comfort.gif' | relative_url }}" alt="Context-sensitive outdoor thermal comfort iterative case" class="img-fluid">

---

## Conclusion

St. Marys can host a rooftop microgrid that covers about a third of annual community energy use, stores a critical-load day, and keeps an 800 kW backup for peak outages, at a net cost near $6.5 million after tax credit. That only holds if the same plan treats climate as infrastructure: future rainfall is not one number, soils and slope decide how much water the site can take, and street trees have to be tuned so summer shade does not steal winter sun. The recommendation is a paired energy-and-ground project — PV and storage on the roofs, cisterns and infiltration on the blocks — sized to Osborne Street and transferable to Darien’s similar coastal fabric.

---

<div class="mt-4 mb-4">
  <a href="{{ 'assets/pdf/SolarMSUD.pdf' | relative_url }}" target="_blank" class="btn btn-primary">
    <i class="fas fa-file-pdf"></i> View Full Report (PDF)
  </a>
</div>
