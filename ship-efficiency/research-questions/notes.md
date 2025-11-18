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

Slide 1
Fleet is still 98% fossil-powered. Median age 20 years. Alternative fuels are being introduced but energy density, still carbon-based.



**White-Box Models (WBMs)** are based on physics-driven approaches utilizing naval architecture principles, hydrodynamic theory, and thermodynamic equations. While these models provide interpretability and require minimal training data, they struggle with accuracy in complex real-world conditions due to simplified assumptions and difficulty incorporating all relevant factors.

**Black-Box Models (BBMs)** employ pure data-driven machine learning approaches without explicit physical equations. These models have demonstrated superior predictive accuracy when sufficient training data is available, with studies reporting R² values exceeding 0.95. However, they face challenges including limited interpretability, high data requirements, and poor generalization to unseen operational conditions.

**Grey-Box Models (GBMs)** represent hybrid approaches that integrate physics-based principles with data-driven learning. Recent research demonstrates that GBMs can achieve performance comparable to BBMs while requiring less historical data and offering better extrapolation capabilities beyond training datasets. Lang et al. (2024) developed a physics-informed grey-box model combining PINNs for calm water speed estimation with XGBoost for speed reduction prediction, achieving approximately 30% improvement over traditional black-box models.

**LSTM (Long Short-Term Memory) Networks** have become the predominant architecture for ship fuel consumption prediction due to their ability to capture long-term temporal dependencies. Wang et al. (2023) developed a GA-LSTM model optimized using genetic algorithms, demonstrating prediction errors as low as 0.29% and improving accuracy by up to 15.6% compared to unoptimized LSTM networks. Yuan et al. (2020) constructed LSTM-based models for real-time fuel consumption rate prediction, outperforming regression-based and traditional RNN models.​

**Bidirectional LSTM (Bi-LSTM)** with attention mechanisms represents a significant advancement. Zhang et al. (2024) developed an attention-based Bi-LSTM framework utilizing 266 variables from sensors, voyage reporting, and hydrometeorological data on a Kamsarmax bulk carrier. The attention mechanism allows the model to focus on specific parts of data streams and assign varying degrees of importance, achieving superior performance with high-frequency data compared to existing methods.

**Hybrid Temporal Architectures** are emerging as powerful approaches. Recent work by Song et al. (2025) proposed a parallel TCN-BiGRU architecture with dynamic attention mechanisms combining Squeeze-and-Excitation (SE) and Global Attention (GA) modules for enhanced spatiotemporal feature learning under variable navigation conditions.​

**Transformer architectures** are gaining traction for maritime applications. Chen et al. (2025) developed the Crossformer model for ship trajectory prediction, demonstrating 60-70% error reduction compared to GRU, LSTM, and TGCN models. The model's Dimension-Segment-Wise embedding, Two-Stage Attention layers, and Hierarchical Encoder-Decoder structure efficiently capture spatiotemporal dependencies.​

A ship fuel consumption prediction model combining local attention mechanisms with Transformer architecture has shown promise for high-precision predictions by effectively modeling long-range dependencies in operational data.

**Physics Informed Neural Networks** represent a paradigm shift by incorporating physical constraints directly into neural network training. Alam et al. (2025) proposed PINN frameworks leveraging first-order and second-order finite-difference physics loss functions for vessel trajectory prediction, reducing average displacement errors by up to 32% while maintaining physical consistency. These approaches enforce fidelity to kinematic principles through discretized loss functions using forward Euler and Heun's methods.​

Bourchas et al. (2025) developed physics-informed neural networks for vessel main engine performance prediction, focusing on optimization procedures to reduce fuel consumption and emissions. The integration of domain knowledge enables PINNs to generalize better with limited data compared to pure data-driven approaches.

Tree-Based Ensemble Methods: Random Forest (RF) and XGBoost consistently rank among top performers. Yang et al. (2023) conducted experiments with 14 popular ML models, finding that Extra Trees, Random Forest, XGBoost, and LightGBM achieved excellent fitting and generalization performance, with R² values reaching 0.9317 when incorporating comprehensive meteorological data. The study demonstrated 1.97% accuracy improvement over models using only voyage reports when including meteorological features.​

Stacking and Meta-Ensemble Approaches: Li et al. (2024) constructed an integrated model combining Random Forest, Extra Random Trees, AdaBoost, GBDT, and Decision Trees using Stacking ensemble techniques, achieving superior performance compared to individual models.​

Gradient Boosting Variants: Abdella Mohamed et al. (2024) investigated data fusion with machine learning for bulk carriers, revealing that simpler models (Ridge Regression, SVR) often outperform complex nonlinear models in baseline scenarios, but Random Forest emerged as the best performer (R² = 0.9021) when incorporating environmental variables.​

