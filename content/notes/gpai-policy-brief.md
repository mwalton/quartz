---
title: "Five considerations to guide the regulation of “General Purpose AI” in the EU’s AI Act"
date: 2023-06-15
tags:
- gpai
- ai policy
---
[Five considerations to guide the regulation of “General Purpose AI](https://www.washingtonpost.com/documents/523e5232-7996-47c6-b502-ed5e1a385ea8.pdf)

- commission's original AI act proposal exempted developers of GPAI from compliance w/ documentation & accountability requirements
	- [THE LOBBYING GHOST IN THE MACHINE: Big Tech’s covert defanging of Europe’s AI Act](https://corporateeurope.org/sites/default/files/2023-02/The%20Lobbying%20Ghost%20in%20the%20Machine.pdf)
	- [“Proposal for a Regulation of the European Parliament and of the Council Laying Down Harmonised Rules on Artificial Intelligence (Artificial Intelligence Act) and Amending Certain Union Legislative Acts,](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=celex:52021PC0206)
- GPAI would not qualify as "high risk" under article 28
- **AI Act approach to GPAI will set regulatory tone for addressing AI harms globally**
- offers five key considerations
	1. Scope: GPAI is an expansive category, future-proofing requires definition that applies beyond LLMs
	2. GPAI carries inherent risk that can't be mitigated @ application layer
	3. Must be regulated throughout production cycle to account for range of stakeholders. Emphasis on early stage data use & design choices
	4. GPAI developers should not be able to relinquish responsibility using a standard legal disclaimer
	5. Avoid endorsing narrow methods / creating "checkbox exercises"
## GPAI is an expansive category.  

For the EU AI Act to be future proof, it must apply across a spectrum of products, rather than narrowly scoped to chatbots/LLMs
- current definition in approach for trilogue negotiations:
> intended by the provider to perform generally applicable functions such as image and speech recognition, audio and video generation, pattern detection, question answering, translation and others; a general purpose AI system may be used in a plurality of contexts and be integrated in a plurality of other AI systems
- suitable defintion should include many methods / tasks upon which other systems can be built
- should not be narrowly bound to generative ai; include, for instance, health risk & welfare benefit models

## GPAI models carry inherent risks and have caused demonstrated and wide-ranging harms.

The fact that these risks can be carried over to a range of downstream uses heightens, rather than mitigates, the need for regulation at the stage of development.
- GPAI (language) models can be fine tuned for benign tasks (generating poetry) or high risk (resume screening / creditworthiness)
- [On the Machine Learning of Ethical Judgments from Natural Language](https://aclanthology.org/2022.naacl-main.56/)
- risk of entrenching anti-democratic speech / biased worldviews
	- [https://arxiv.org/abs/2005.14050](https://arxiv.org/abs/2005.14050)
	- [You reap what you sow: On the Challenges of Bias Evaluation Under Multilingual Settings](https://aclanthology.org/2022.bigscience-1.3/)
- risk of [memorizing & reproducing private / personal information](https://arxiv.org/abs/2301.13188)
- systemic concerns that impact individual & aggregate populations
	- [The right to contest AI](https://columbialawreview.org/content/the-right-to-contest-ai/)
	- [The Subjects and Stages of AI Dataset Development: A Framework for Dataset Accountability](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4217148)
- fine-tuning for specific use cases heightens risk of unfair, inaccurate or harmful results
- complicates future-proofing as harms may be difficult to anticipate
- **Malleability of GPAI is precisely why these models must be regulated**

## GPAI must be regulated throughout the product cycle

not just at the application layer, in order to account for the range of stakeholders involved. The original development stage is crucial, and the companies developing these models must be accountable for the data and design choices they make.

- includes data collection, cleaning, annotation, model development, testing and evaluation
- downstream actors (providers, application developers & users) lack visibility into core components of pre-trained models
- loophole for liability / accountability: lower-resourced downstream actors held accountable at application layer; higher-resourced large companies profit w/o responsibility

## Any regulatory approach that allows developers of GPAI to relinquish responsibility using a standard legal disclaimer would be misguided

It creates a dangerous loophole that lets original developers of GPAI (often well resourced large companies) off the hook, instead placing sole responsibility with downstream actors that lack the resources, access, and ability to mitigate all risks.

- eg: burying legal disclaimers in technical documentation
- opt-in/out approach insufficient in mitigating risk
- legal disclaimer approach passes all liability to downstream actors (may lack resources, access & technical capability to scrutinize and mitigate inherent risk from GPAI models)
- unreasonable for upstream developers to claim immunity for design & data collection processes they control

## Regulation should avoid narrow methods of evaluation and scrutiny for GPAI that could result in a superficial checkbox exercise.

This is an active and hotly contested area of research and should be subject to wide consultation, including with civil society, researchers and other non-industry participants.

- Regulation should leave scope for broad & robust scrutiny at development stage:
	- documentation: Data Statements, Data Sheets, and Model Cards
	- evaluation suites
		- [Measuring Fairness with Biased Rulers: A Comparative Study on Bias Metrics for Pre-trained Language Models](https://aclanthology.org/2022.naacl-main.122/)
		- [Towards Intersectionality in Machine Learning: Including More Identities, Handling Underrepresentation, and Performing Evaluation](https://arxiv.org/abs/2205.04610)
		- [Ethical and social risks of harm from Language Models](https://arxiv.org/abs/2112.04359)
- Regulation should not endorse narrow benchmarks for evaluation
	- [Trade-offs between Group Fairness Metrics in Societal Resource Allocation](https://arxiv.org/abs/2202.12334)
	- [AI and the Everything in the Whole Wide World Benchmark](https://arxiv.org/abs/2111.15366)
