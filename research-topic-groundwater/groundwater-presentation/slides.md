---
marp: true
paginate: true
class:
  - invert
style: |
    section {font-size: 1.7em}
---
![bg right:60%](./mottisfont.jpg)
# Improving Groundwater Behaviour Prediction<br> with AI

James Carlyle
10 November 2025
AI for Sustainability<br> PhD CDT

---
![bg right:30%](./yorkshire-river.jpg)
## Motivation
* Water companies struggle to provide clean water in the UK & globally.
* Rainfall is not in short supply but may become seasonally concentrated.
* When groundwater abstraction is too high, river levels fall and fish die.
* Groundwater is difficult to model physically, and aquifers contain unknown geological discontinuities.
* Good water supplies promote health; poor water leads to disease and reduced life expectancy.
* AI processor cooling will drive further demand for water.
<sub>These points are also true outside the UK</sub>

---
![bg right:30%](./sciml-case-study-maria-image1.png)
## Existing Research
* Groundwater has traditionally been modelled physically.
* The global standard is MODFLOW, developed over 40 years in Fortran.
* Groundwater aquifers have been modelled with ML since 2020 with a mixture of techniques. Examples include:
    * Feedforward Neural Networks
    * Recurrent Neural Networks (e.g. LSTM)
    * Hybrid models (e.g. CNN-LSTM)
    * Spatial-Temporal Graph Neural Networks (ST-GNN)
    * Physics-Informed Neural Networks (PINNs)
<sup>These are research efforts and are not available across the water industry.</sup>

---
![bg left:25%](./borehole-monitoring.jpg)
## Research Opportunities in 2025
* Improve the models used to model groundwater, possibly by further combining previous approaches, e.g. Physics-Informed Spatial-Temporal Graph Neural Networks (PISTGNN). 
<sup>It's not clear whether ever-increasing sophistication is impactful.</sup>
* Add underground geological discontinuities, rivers, abstraction points and rainfall catchments to graphs. Increase scale to regional / national.
* Combine long-range rainfall forecasts, to permit present-day abstraction based on future replenishment.
* Provide an interpretable "grey-box" decision-support capability.
* Produce open-source software which is accessible to end users in the water industry.

---

## Thank you

I have access to water data and hydrogeology experts in the UK.

**I'm looking for research supervision within Southampton University, and validation of the research gaps identified.**

James Carlyle
james.carlyle@soton.ac.uk
SustAI CDT
School of Electronics and Computer Science
University of Southampton