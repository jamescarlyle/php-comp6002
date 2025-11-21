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



https://ntulearnvideo.ntu.edu.sg/media/Memristive%20Materials%20and%20%20Devices%20for%20Post-Moore%20Electronics%20by%20Prof%20Mario%20Lanza%20%7C%2019%20Sept%202025%2C%20Arc%20LHN-LT/0_gv25pttc

https://github.com/UCL-EPSRC-DTP/2026-27-project-catalogue/blob/main/projects/2531bd1665.md

https://www.southampton.ac.uk/study/postgraduate-research/projects/silicon-synapses-for-artificial-intelligence-hardware#about

https://www.nature.com/articles/s41928-023-01053-4

https://semiengineering.com/is-in-memory-compute-still-alive/

https://sotonac.sharepoint.com/teams/sust.ai/Lists/Project%20Proposals/DispForm.aspx?ID=38&e=utr6pK

https://cdn.southampton.ac.uk/study/postgraduate-research/projects/optoelectronic-ai-processors-for-cryogenic-space-electronics#about

https://cmc-dresden.org/media/

file:///Users/jamescarlyle/Downloads/s41586-025-08733-5.pdf

https://iopscience.iop.org/article/10.1088/2631-8695/adfbbb

https://greencompute.uk/References/Neuromorphic/Brain-inspired%20computing%20needs%20a%20master%20plan.pdf

https://cpb.iphy.ac.cn/article/2020/2027/cpb_29_4_048401.html#:~:text=2%2C%203%2C%20%C2%A7%5D-,Strukov%20D%20B%20Snider%20G%20S%20Stewart%20D%20R%20Williams%20R%20S%202008%20Nature%20453%2080

https://www.nature.com/articles/nature06932#citeas

https://cpb.iphy.ac.cn/article/2020/2027/cpb_29_4_048401.html

https://pubs.rsc.org/en/content/articlehtml/2025/tc/d4tc01796j
This article presents a novel optoelectronic memristor device designed for neuromorphic vision sensors. The key innovation is a two-terminal memristor based on PMMA/ZnO/2-iodofluorene (2IF), which can switch between multiple resistance states when stimulated optically (mainly with UV light) or electrically. The device displays stable and linear conductance updates with multilevel states, enabling efficient, fault-tolerant image pattern recognition and in-memory processing directly in the sensing hardware.

what are some research questions around optomewhat are some research questions around optomemristors? Optomemristors—memristive devices whose resistive state is controllable by both electrical and optical stimuli—are a vibrant research topic at the intersection of neuromorphic computing, materials science, and sustainable AI hardware. Key research questions in the field include:

Neuromorphic and Brain-Inspired Computing
How can optomemristors emulate complex biological synaptic functions, such as multi-factor (three-factor) plasticity and dendritic computation, using both electrical and optical control?​

What are the mechanisms through which optomemristors can perform in-memory learning tasks, such as reinforcement learning or logic operations (like XOR gates), at the device level?​

Device Materials and Physics
What material systems (e.g., chalcogenide films, 2D materials, composites) exhibit optimal optoelectronic responses for stable and tunable memristive behavior under light and electrical stimuli?​

How do optical parameters (wavelength, intensity) and device structure influence the light-induced modulation of resistance, and can these be engineered for specific neuromorphic functions?​

Integration, Scaling, and Energy Efficiency
How can optomemristor devices be scaled up and integrated with complementary electronic and photonic circuits to build large, efficient neuromorphic arrays for real-world AI?​

How does the optical control of memristors contribute to reduced power consumption, increased speed, and lower cross-talk in high-density circuits compared to purely electronic systems?​

Artificial Sensing and Memory Applications
Can optomemristors be engineered for multi-modal sensing and processing (e.g., artificial retina, optical synapses, visual systems) that exploit their fast, broadband, and non-contact optical control?​

What is the potential for optomemristors to enable new types of nonvolatile, multi-level memories, or combined sensing-memory-computation devices, by integrating light-regulated molecular or nanostructured layers?​

Challenges and Future Prospects
What are the main reliability, endurance, and reproducibility challenges for optomemristor devices under repeated electrical and optical stimulation, and how can these be mitigated?​

How can the physics of light-assisted ion migration, chemical transitions, or band structure engineering be further exploited to enhance device performance and multifunctionality?​

These questions collectively span fundamental device physics, materials design, system integration, and advanced applications in brain-inspired and energy-efficient computation.​

https://www.nature.com/articles/s44287-024-00037-6?fromPaywallRec=false

https://www.nature.com/articles/s41586-025-08733-5

https://www.youtube.com/watch?v=FvXadN9uyak

https://pmc.ncbi.nlm.nih.gov/articles/PMC7797931/#:~:text=Summary,neuromorphic%20computing%20systems%20are%20discussed.
The expeditious development of information technology has led to the rise of artificial intelligence (AI). However, conventional computing systems are prone to volatility, high power consumption, and even delay between the processor and memory, which is referred to as the von Neumann bottleneck, in implementing AI. To address these issues, memristor-based neuromorphic computing systems inspired by the human brain have been proposed. A memristor can store numerous values by changing its resistance and emulate artificial synapses in brain-inspired computing. Here, we introduce six types of memristors classified according to their operation mechanisms: ionic migration, phase change, spin, ferroelectricity, intercalation, and ionic gating. We review how memristor-based neuromorphic computing can learn, infer, and even create, using various artificial neural networks. Finally, the challenges and perspectives in the competing memristor technology for neuromorphic computing systems are discussed.

https://iopscience.iop.org/article/10.1088/2631-8695/adfbbb/pdf
With the advent of innovative technologies and the emerging demands forin situ edge decisionmaking, the weaknesses of the conventional von Neumann computing paradigm have become
increasingly evident. While such architectures were considered reliable until recently, they have
struggled to meet the growing requirements for greater processing speed, lower power consumption,
and enhanced scalability. To highlight these challenges, several studies since the early 2010s, have
focused on neuromorphic computing based on memristors. Unlike traditional computing, this
approach relies more on how the human brain processes information, offering a promising alternative
for future edge AI applications. Memristor-based systems, particularly those employing crossbar
architectures like 1T1R and 1R arrays, enable analog computation and efficient matrix-vector
multiplication, laying the foundation for energy-efficient, scalable hardware. This comprehensive
review paper explores the fundamentals of memristor, neuromorphic computing with memristor,
learning algorithms focusing on Artificial Neural Networks(ANN), Binary Neural Networks(BNN),
and Spiking Neural Networks(SNN), while exploring other learning models as well by comparing the
accuracy percentage of each model and edge AI tasks such as image classification, emotion
recognition, and multimodal learning. Furthermore, it addresses the intrinsic advantages of
computation-in-memory architecture regarding scalability, latency reduction, and parallelism. It also
offers insights into the challenges such as device-to-device variability, low endurance, non-ideal
switching properties, and compatibility with complementary metal–oxide–semiconductor(CMOS)
technologies. This study flow will help understand each technique’s central concept to highlight future
development challenges, discussing the status and prospects of neuromorphic and brain-inspired
computing technologies.

https://pmc.ncbi.nlm.nih.gov/articles/PMC12508526/pdf/research.0916.pdf
The memristor, as an emerging nonvolatile device, has garnered considerable attention due to its low
power consumption, high density, and multifunctionality. This review summarizes recent advances in the
application of memristors for logic gates, with a focus on key breakthroughs and challenges in material
design, device performance, and logic circuit implementation. It covers a variety of material systems
including 2-dimensional materials, perovskite materials, and optoelectronic materials, as well as novel
structures such as array architectures and wearable textile memristors, evaluating their suitability for
achieving stable and efficient logic operations. In addition, the review provides a comparative analysis of
different implementation strategies for basic logic, optoelectronic logic, and combinational logic, offering
an in-depth discussion of their respective characteristics and advantages. This review also emphasizes the
application prospects of memristor logic gates in reconfigurable computing, neuromorphic computing,
and in-memory computing architectures, providing a theoretical foundation and practical support for the
development of high-density integration and efficient memristor logic circuits.

