# Memristors for Edge AI

## Abstract

## Introduction
Power requirements for datacentres housing machine learning (ML) and AI are doubling every 6 months[[]] and AI deployment and usage is likely to be rate-limited by power availability rather than by computing technology by 2030[[]]. GPT-5 includes around 5 trillion parameters and consumes 18Wh for a single mid-sized query[[]], and up to 45GWh when scaled to 700M queries/day[[]]. Recent estimates suggest inference can account for up to 90% of a model’s total lifecycle energy use [14, 15].
It is likely that the total power consumption of AI will reach  by 2030[[]]. Indeed, some researchers argue that Artificial Super Intelligence (ASI) is out of reach simply because the energy required would be greater than all global energy supply[[4]].

AI has relied on cloud-based datacentres rather than personal or small-scale devices. Obviously, datacentres require data to be transmitted to and from them to work, and data transmission itself requires power and leads to latency. As a result, the availability of ML and AI is currently very restricted on small, low power, disconnected and possibly autonomous devices[[]]. Unfortunately, many of the devices required for enviromental monitoring and protection fall into this category.

A newer field of research, Neuromorphic Computing, takes inspiration from the incredibly efficient human brain. By comparison with earlier datacentre data, the brain provides up to 150 trillion synapses (neural connections) and consumes around 20W[[]].

We propose a field of research looking at one particular architecture for neuromorphic computing, Memristors, and how this technology can be used to create a new type of AI suitable for low-power and disconnected devices. Memristors themselves where predicted by Memristor-based neural networkss have several unique features; they have only been created in the last 5 years[[]], they can respond to events and use no power between events, they rely on analog computation, and they resist radiation and very low temperatures well. These characteristics also lend memristors to the application of AI in space, for example on environmental sensing satellites.


## Background
The memristor was first proposed as the missing device linking flux and current by Chua in 1971 [[5]] and instantiated by Strukov et al. in 2007[[6]].


"Using memristor-based in-memory compute could potentially reduce annually GPU based Al data center power 84% from 300 TWh to 48 TWh in 2030, saving upto 232 TWh or the equivalent of 32 nuclear reactors of new power generation or allowing data center compute density to increase by a factor of 5."

### Literature Review



Group papers into different categories of approaches. Visualise differences and commonalities between groups using,
e.g., graphs, tables, figures.
• For each group, provide a concise summary of the underpinning concept.
• Highlight key papers in each group, e.g., papers that changed how people think about the problem.
• What makes these papers stand out?
• Provide an objective discussion of the benefits and disadvantages of each approach:
• Consider aspects such as performance of the algorithm regarding evaluation metrics common in the related work, computational
cost, and resilience against uncertainties.
• What types of data was the work tested on?
• Do you foresee challenges when applying the work to data that is specific to your problem?
• Is the approach feasible in practice? What aspects of the problem can and cannot be addressed?
• What sort of date they used? What data do researchers in the field normally use?
### Synthesis:
• What has the state-of-the-art achieved?
• What are the outstanding challenges?

### Research Questions
Bold and explicit: The main questions that you are aiming to address
• [For a PhD thesis, you would usually] identify 3-4 sub-questions and map them to techniques
you see fit for addressing them [justify using literature]
• It is recommended that you follow the “FINER” framework to ensure that research questions
are Feasible, Interesting, Novel, Ethical, and Relevant (FINER)
• Research questions should be well formulated. For example, the PICO framework may help
you to construct your research questions by identifying the Problem, Issue / Improvement,
Comparison, and targeted Outcome (PICO).
• As a rule-of-thumb, for a PhD, each objective should correspond to one thesis chapter. Each
thesis chapter corresponds to a journal article / high-impact conference paper
• Elaborate on each RQ. Do not just list a few bullet points.

## Concluding Remarks
This is not just to repeat and summarise
• Potential impact
• Ethical considerations
• Limitations
• Future Work



...the **go to** statement should be abolished..." [[1]](#1).

## References
<a id="1">[1]</a> 
Dijkstra, E. W. (1968). 
Go to statement considered harmful. 
Communications of the ACM, 11(3), 147-148.

<a id''></a>[Optoelectronic memristor for neuromorphic computing](https://cpb.iphy.ac.cn/article/2020/2027/cpb_29_4_048401.html)
<a id=''></a>[Neurotransmission: The Synapse](https://dana.org/resources/neurotransmission-the-synapse/)
[How Hungry is AI? Benchmarking Energy, Water, and Carbon Footprint of LLM Inference](https://arxiv.org/html/2505.09598v5)
4. [The energy challenges of artificial superintelligence](https://pmc.ncbi.nlm.nih.gov/articles/PMC10629395/)
5. [Chua L 1971 IEEE Trans. Circuit Theory 18 507](https://dx.doi.org/10.1109/TCT.1971.1083337)
6. [Strukov, D., Snider, G., Stewart, D. et al. The missing memristor found. Nature 453, 80–83 (2008).](https://doi.org/10.1038/nature06932)