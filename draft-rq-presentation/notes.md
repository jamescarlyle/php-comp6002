---

## Slide 1: The Challenge
### Global Shipping at a Crossroads

**Context:**
- International shipping carries **80%+ of global cargo** – essential to global trade
- Sector contributes **~3% of global GHG emissions** – a major environmental concern
- IMO regulatory pressure: EEXI and CII mandates demand decarbonisation

**The Opportunity:**
- Operational strategies (speed regulation, route optimisation, trim adjustment) are the **most cost-effective solutions**
- These strategies depend on **accurate Ship Fuel Consumption (SFC) prediction**
- An interpretable, causal SFC framework could transform maritime energy management

**Motivating Question:**
*How can we build AI models that are not only accurate, but also transparent and causally grounded to guide real decarbonisation decisions?*

---

## Slide 2: The Three Core Challenges

### Challenge 1: The Homogeneity Assumption
Current models treat ship operations as a **single homogeneous system**, ignoring operational diversity:
- Cruising in rough seas vs. calm waters vs. port manoeuvring involve **distinct physical dynamics**
- Single global models **fail under non-standard conditions**
- Results: Poor generalisability and unreliable condition-specific predictions

### Challenge 2: The Black Box Problem
Advanced ML models achieve high accuracy but lack transparency:
- Feature importance rankings reveal **correlations, not causal mechanisms**
- Missing crucial insights: non-linear relationships, thresholds, inflection points
- **Critical distinction:** Energy policies must be grounded in causality, not correlation alone
- Safety-critical maritime operations demand **trustworthy, interpretable systems**

### Challenge 3: Methodological Fragmentation
Research silos limit progress:
- Predictive modelling, XAI, and causal inference remain **disconnected**
- Multi-source data fusion (noon reports, AIS, environmental) introduces multicollinearity and the **curse of dimensionality**
- Feature selection and hyperparameter optimisation are often **single-model-based** or computationally intensive

---

## Slide 3: Research Question 1
### RQ1: Operational Heterogeneity & Interpretability

**The Question:**
*How can the intrinsic heterogeneity of ship operational states be systematically identified, modelled, and interpreted to develop more accurate, robust, and physically meaningful SFC prediction frameworks?*

**What We're After:**
- Move beyond "one model fits all" to **state-aware, condition-specific models**
- Identify and characterise distinct operational regimes (cruising, maneuvering, weather-affected, etc.)
- Develop **interpretable representations** of how different conditions drive energy consumption
- Create physically meaningful models that engineers and operators can trust

**Impact:**
Enables targeted, condition-specific energy optimisation strategies grounded in operational reality

---

## Slide 4: Research Questions 2 & 3
### RQ2: From Correlation to Causation

**The Question:**
*How can we move beyond correlation to establish and quantify the true causal relationships between key operational, navigational, and environmental factors and SFC to inform effective and reliable intervention strategies?*

**What We're After:**
- Apply causal inference methods to distinguish correlation from causation
- Quantify **true causal drivers** of fuel consumption
- Build policy-relevant understanding: what interventions actually work?
- Create a scientific foundation for IMO regulations and operational guidelines

---

### RQ3: Unified Analytical Framework

**The Question:**
*How can a unified analytical framework be developed to integrate advanced data fusion, robust feature selection, efficient model optimisation, and deep interpretability—ultimately creating transparent, trustworthy, and actionable decision-support tools for ship energy management?*

**What We're After:**
- Bridge predictive accuracy, scientific understanding, and practical applicability
- Solve high-dimensional complexity through intelligent feature selection
- Create an **integrated pipeline**: data fusion → feature engineering → interpretable models → causal analysis
- Deliver **trustworthy decision-support systems** that maritime stakeholders can rely on

**Impact:**
Transforms research outputs into actionable tools for industry adoption and net-zero alignment

---

## Slide 5: The Vision Forward

### Bridging Theory, Transparency, and Practice

**Research Vision:**
Develop an **AI-aided, interpretable, and causally informed framework** for ship fuel consumption prediction that simultaneously achieves:

1. **Accuracy** – Robust predictions across diverse operational conditions
2. **Interpretability** – Clear understanding of causal mechanisms driving consumption
3. **Applicability** – Trustworthy, actionable insights for maritime stakeholders

**Why It Matters:**
- **Scientific advance:** Extends maritime AI methodology beyond black-box prediction
- **Environmental impact:** Enables evidence-based decarbonisation strategies
- **Industry adoption:** Trustworthy systems operators will actually use
- **Regulatory alignment:** Supports IMO net-zero objectives with sound science

**The Outcome:**
A framework that transforms shipping from data-driven prediction toward **knowledge-driven, causally grounded, and operationally intelligent energy management**

---

## Presentation Tips (7-minute delivery)

**Timing Breakdown:**
- **Slide 1 (Context):** 1 minute – Set the stage
- **Slide 2 (Challenges):** 2 minutes – Problem definition (pace carefully, let challenges sink in)
- **Slides 3-4 (RQs):** 3 minutes – 1 minute per research question, emphasise the "what we're after"
- **Slide 5 (Vision):** 1 minute – Strong conclusion linking all threads

**Delivery Notes:**
- Lead with the motivation: global shipping's role vs. climate impact
- Use Slide 2 as your "pain points" narrative – these drive home why RQs matter
- RQs (Slides 3-4) should feel like natural responses to the challenges
- Finish with the vision: accuracy + interpretability + applicability
- Be prepared for questions on causality methods and data sources