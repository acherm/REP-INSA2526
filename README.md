# REP-INSA2526
Reproducibility of experiments (INSA 2526)

* Introduction/motivation
  - slides: [https://docs.google.com/presentation/d/1Fur0bjt4oVZmi8S2vZjk0z02wtJhk5hMT2kv9UC1p3o/edit?usp=sharing ](https://docs.google.com/presentation/d/1LeCvVMUIRe9eeWsDNSONTR1vcKXWRGKkeqRnspweHXI/edit?usp=sharing)
  - context: computational science; scientific methods in industry; automated SE; continuous SE/DevOps; software/AI eating the world (data+software+challenges) 
  - Neil deGrasse + Alain Aspect + Lecun/Musk + ...
  - terminologies (reproductibility; repeatability; replicability; frictionless reproducibility)
  - initiatives (reproducible builds; software heritage; open source; open data; paperswithcode; etc.)
  - historical examples (reproducibility crisis)
  - some examples (climate models)
  - reproducibility and science
  - reproducibility in IT and outside IT (eg banks)
  - replicability in science
  - replicability in IT and outside IT
  - take away: (frictionless) reproducibility is key to innovation! 
   - perspective: need to master automated software engineering and variability

* Lab session #1 [https://docs.google.com/presentation/d/1z2pX_o7cXoPtgdgdDhPsdYRpazkz_YTRJiusBpA-ZII/edit?usp=sharing](https://docs.google.com/presentation/d/1CO0ET1FL0ldZBcQ5UMzn2_gyB5unr_A0_IWs-85sI5c/edit?usp=sharing)

* Reproducibilty foundations (methods, tools, techniques)
  - slides: https://docs.google.com/presentation/d/1eYXHFeSKa2SA8hQyvBB_Z0OY4ufakst5lVNMZzyuvLI/edit?usp=sharing
  - Reproducibility mindset
  - Open source software and tools
  - Master your computing environment
  - Explore the variants space
  - Threats to validity
  - Automate everything
  - Test and doubt about the quality of your software
 



* Lab session #2 aka Reproducibility [https://docs.google.com/document/d/1yhZf-0iTnPSw4Rh6FfIAXO_AtRATVaOppNidoUMsuPY/edit?usp=sharing](https://docs.google.com/document/d/1yhZf-0iTnPSw4Rh6FfIAXO_AtRATVaOppNidoUMsuPY/edit?usp=sharing)

* Lab session #3 aka Replicability, Variability and Consensus
https://docs.google.com/document/d/1wB7FjJAdTXDGu8Fa-Yt0tuJh9ZnYY7wK1SP10tEhwzg/edit?usp=sharing

* Lab session #4 Towards reproducing and replicating results (of one of the papers below)
https://docs.google.com/document/d/1gnkR7Us5mGhrtArIkKXLVO057eRS9msx3txhldJ-768/edit?usp=sharing


## Papers to reproduce and replicate (choose 1 out of 2)

* Many Analysts, One Data Set: Making Transparent How Variations in Analytic Choices Affect Results
R. Silberzahn et al.
2018 Advances in Methods and Practices in Psychological Science

  - Do soccer referees issue more red cards to dark-skinned players than to light-skinned players in top European leagues?
(And secondarily: how much do results vary across independent teams making different analytic choices on the same dataset?)
  - Reproducibility: reproduce the work/results of (a subset of) 29 teams, using code and explanations in technical reports (hint: considering all teams is certainly impossible; share the workloads)
  - Replicability: be the 30th, 31th, …, Nth team!


* Evaluating superhuman models with consistency checks
L Fluri, D Paleka, F Tramèr
2024 IEEE Conference on Secure and Trustworthy Machine Learning (SaTML), 194-232

  - there are three possible topics: LLMs forecasting future events, Chess AI experiments, Legal AI experiments (hint: try to focus hard on one of the third topic)
  - https://github.com/ethz-spylab/superhuman-ai-consistency
  - for the chess part, also related to this study: "Axel Martin, Djamel Eddine Khelladi, Théo Matricon, Mathieu Acher:
Re-evaluating metamorphic testing of chess engines: A replication study. Inf. Softw. Technol. 181: 107679 (2025)" https://blog.mathieuacher.com/ReproducibilityMetamorphicTestingChess/
  - does it generatlize to other Leela configuratiions/versions? or other positions?
  - does it generalize to other LLMs/prompts/configurations?


## Resources

  * École Jeunes Chercheuses et Jeunes Chercheurs en Programmation https://gpl-ejcp.github.io/ejcp2023 
  * Frictionless reproducibility and deep variability https://hal.science/hal-04601752
  * Teaching Reproducibility and Embracing Variability: From Floating-Point Experiments to Replicating Research Mathieu Acher, Arnaud Gotlieb, Helge Spieker, Gauthier Le Bartz Lyan https://hal.science/hal-05190848v1
  * 2024 ACM Conference on Reproducibility and Replicability https://acm-rep.github.io/2024/ 
  - Practical strategies for teaching reproducibility.
By Fraida Fund, Stephanie Lieggi, Kate Keahey, Cormac Flanagan, Marc Richardson,  Haryadi Gunawi and Sarah Cohen Boulakia
  * https://forum.recherche-reproductible.fr/
  * MOOC REPRODUCIBLE RESEARCH II (Arnaud Legrand, Konrad Hinsen, C Pouzat, Matthieu Simonin, etc.)
