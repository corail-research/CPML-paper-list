
## Improving contraint programming with machine learning

This list categorizes key research directions in the the role of ML in enhancing the CP pipeline.

---

### 1. Learning to model - Learning constraints 

- [AIJ'2017] [Constraint acquisition](https://www.sciencedirect.com/science/article/pii/S0004370215001162)
- [AAAI'2018] [Learning constraints from examples](https://ojs.aaai.org/index.php/AAAI/article/view/12217)
- [AIJ'2023] [Learning constraints through partial queries](https://www.sciencedirect.com/science/article/abs/pii/S0004370223000425)
- [CPAIOR'2024] [Acquiring Constraints for a Non-linear Transmission Maintenance Scheduling Problem](https://link.springer.com/chapter/10.1007/978-3-031-60597-0_3)
- [JAIR'2025] [A Query-Based Constraint Acquisition Approach for Enhanced Precision in Program Precondition Inference](https://www.jair.org/index.php/jair/article/view/16206)
  
#### 1.1 Passive constraint acquisition

- [ECML'2005] [A SAT-based version space algorithm for acquiring constraint satisfaction problems](https://link.springer.com/chapter/10.1007/11564096_8)
- [CP'2022] [Constraint acquisition based on solution counting](https://drops.dagstuhl.de/entities/document/10.4230/LIPIcs.CP.2022.15)
- [IJCAI'2023] [Learning constraint networks over unknown constraint languages](https://www.ijcai.org/proceedings/2023/208)
- [AMAA'2021] [Classifier-based constraint acquisition](https://link.springer.com/article/10.1007/s10472-021-09736-4)
- [ECAI'2020] [Robust constraint acquisition by sequential analysis](https://ebooks.iospress.nl/volumearticle/54908)
- [IJAR'2024] [A statistical approach to learning constraints](https://www.sciencedirect.com/science/article/pii/S0888613X24000719)
- [AAAI'2024] [What are the rules? Discovering constraints from data](https://ojs.aaai.org/index.php/AAAI/article/view/28658)
- [ICTAI'2021] [Unsupervised constraint acquisition](https://ieeexplore.ieee.org/document/9643314/)
- [CP'2011] [A constraint seeker: Finding and ranking global constraints from examples](https://link.springer.com/chapter/10.1007/978-3-642-23786-7_4)
- [CP'2012] [A model seeker: Extracting global constraint models from positive examples](https://link.springer.com/chapter/10.1007/978-3-642-33558-7_13)
- [IJAIT'2024] [Enhancing Constraint Acquisition through Hybrid Learning: An Integration of Passive and Active Learning Strategies](https://www.worldscientific.com/doi/10.1142/S0218213024500209)
- [CP'2016] [Learning parameters for the sequence constraint from solutions](https://link.springer.com/chapter/10.1007/978-3-319-44953-1_26)
- [CP'2017] [Learning the parameters of global constraints using branch-and-bound](https://link.springer.com/chapter/10.1007/978-3-319-66158-2_33)
- [ICTAI'2010] [On learning constraint problems](https://ieeexplore.ieee.org/document/5670015/)
- [CP'2022] [Learning constraint programming models from data using generate-and-aggregate](https://drops.dagstuhl.de/entities/document/10.4230/LIPIcs.CP.2022.29)
- [IJCAI'2022-Workshop] [Extrapolating Constraint Networks by Symbolic Classification](https://cora.ucc.ie/items/83a5c4c6-3db0-457a-bc88-2d6c7cf9ceca)
- [AAAI'2025] [Generalizing Constraint Models in Constraint Acquisition](https://dl.acm.org/doi/10.1609/aaai.v39i11.33236)
- [SETN'2024] [The Impact of Solution Diversity on Passive Constraint Acquisition](https://dl.acm.org/doi/10.1145/3688671.3688759)


#### 1.2 Interactive constraint acquisition

- [COLT'1994] [Oracles and queries that are sufficient for exact learning](https://www.sciencedirect.com/science/article/pii/S002200009690032X)
- [InfComput'1995] [Exact learning boolean functions via the monotone theory](https://www.sciencedirect.com/science/article/pii/S0890540185711649)
- [ML'1988] [Queries and concept learning](https://link.springer.com/article/10.1023/A:1022821128753)
- [IJCAI'2007] [Query-Driven Constraint Acquisition](https://dl.acm.org/doi/10.5555/1625275.1625282)
- [IJCAI'2013] [Constraint Acquisition via Partial Queries](https://dl.acm.org/doi/10.5555/2540128.2540198)
- [IJCAI'2016] [Multiple Constraint Acquisition](https://www.ijcai.org/Abstract/16/105)
- [AIJ'2023] [Learning constraints through partial queries](https://www.sciencedirect.com/science/article/abs/pii/S0004370223000425)
- [DM&CP'2016] [New approaches to constraint acquisition](https://hal.science/hal-01606245v1)
- [CP'2018] [Efficient Methods for Constraint Acquisition](https://link.springer.com/chapter/10.1007/978-3-319-98334-9_25)
- [CP'2019] [Structure-Driven Multiple Constraint Acquisition](https://link.springer.com/chapter/10.1007/978-3-030-30048-7_41)
- [AAAI'2021] [Parallel constraint acquisition](https://ojs.aaai.org/index.php/AAAI/article/view/16504)
- [CP'2023] [Guided Bottom-Up Interactive Constraint Acquisition](https://drops.dagstuhl.de/entities/document/10.4230/LIPIcs.CP.2023.36)
- [CPAIOR'2018] [Time-Bounded Query Generator for Constraint Acquisition](https://link.springer.com/chapter/10.1007/978-3-319-93031-2_1)
- [SDCI'2019] [Pa-QUACQ: Algorithm for Constraint Acquisition System](https://link.springer.com/chapter/10.1007/978-3-030-11914-0_27)
- [Constraints'2020] [Efficient multiple constraint acquisition](https://link.springer.com/article/10.1007/s10601-020-09311-4)
- [AAAI'2024] [Learning to learn in interactive constraint acquisition](https://dl.acm.org/doi/10.1609/aaai.v38i8.28655)
- [CP'2020] [Omissions in Constraint Acquisition](https://dl.acm.org/doi/10.1007/978-3-030-58475-7_54)
- [IJCAI'2016] [Constraint Acquisition Using Recommendation Queries](https://dl.acm.org/doi/abs/10.5555/3060621.3060722)
- [ICTAI'202] [Machine Learning Based Recommendation Queries for Constraint Acquisition](https://ieeexplore.ieee.org/abstract/document/10849506/)
- [ECAI'2014] [Boosting Constraint Acquisition via Generalization Queries](https://ebooks.iospress.nl/publication/36923)
- [ICTAI'2015] [Detecting types of variables for generalization in constraint acquisition](https://ieeexplore.ieee.org/document/7372165)
- [IJCAI'2024] [Using large language models to improve query-based constraint acquisition](https://dl.acm.org/doi/abs/10.24963/ijcai.2024/212)
- [KR'2023] [Active disjunctive constraint acquisition](https://proceedings.kr.org/2023/50/)
- [AAAI'2022] [GEQCA: Generic qualitative constraint acquisition](https://ojs.aaai.org/index.php/AAAI/article/view/20282)
- [JAIR'2024] [Query-driven Qualitative Constraint Acquisition](https://jair.org/index.php/jair/article/view/14752)
- [IJSEKE'2023] [Exact learning of qualitative constraint networks from membership queries](https://www.worldscientific.com/doi/10.1142/S0218194023500171)
- [CP'2021] [Learning Max-CSPs via active constraint acquisition](http://dagstuhl.sunsite.rwth-aachen.de/opus/frontdoor.php?source_opus=15345)


#### 1.3 Learning and constraining complex functions

- [AIJ'2017] [Empirical decision model learning](https://www.sciencedirect.com/science/article/pii/S0004370216000126)
- [CP'2011] [Neuron constraints to model complex real-world problems](https://link.springer.com/chapter/10.1007/978-3-642-23786-7_11)
- [Constraints'2016] [A lagrangian propagator for artificial neural networks in constraint programming](https://link.springer.com/article/10.1007/s10601-015-9234-6)
- [CPAIOR'2015] [Embedding decision trees and random forests in constraint programming](https://link.springer.com/chapter/10.1007/978-3-319-18008-3_6)

---

### 2. Learning to model - Learning the objective function 

#### 2.1 Passive learning

- [OR'2025] [Inverse optimization: Theory and applications](https://pubsonline.informs.org/doi/10.1287/opre.2022.0382)
- [NIPS'2007] [Predicting Structured Data](https://mitpress.mit.edu/9780262528047/predicting-structured-data/)
- [EMNLP'2002] [Discriminative training methods for hidden markov models: Theory and experiments with perceptron algorithms](https://aclanthology.org/W02-1001/)
- [ICML'2022] [Decision-focused learning: Through the lens of learning to rank](https://proceedings.mlr.press/v162/mandi22a.html)
- [CPAIOR'2024] [An Efficient Structured Perceptron for {NP}-Hard Combinatorial Optimization Problems](dl.acm.org/doi/10.1007/978-3-031-60599-4_17)
- [CP'2019] [Vehicle routing by learning from historical solutions](https://link.springer.com/chapter/10.1007/978-3-030-30048-7_4)
- [CP'2021] [Data Driven VRP: A Neural Network Model to Learn Hidden Preferences for VRP](https://drops.dagstuhl.de/entities/document/10.4230/LIPIcs.CP.2021.42)
- [Constraints'2023] [Learn and route: learning implicit preferences for vehicle routing](https://link.springer.com/article/10.1007/s10601-023-09363-2)
- [CP'2020] [Pushing data into CP models using graphical model learning and solving](https://dl.acm.org/doi/10.1007/978-3-030-58475-7_47)
- [IJCAI'1995] [Valued constraint satisfaction problems: Hard and easy problems](https://dl.acm.org/doi/10.5555/1625855.1625938)
- [CP'2015] [Anytime hybrid best-first search with tree decomposition for weighted CSP](https://link.springer.com/chapter/10.1007/978-3-319-23219-5_2)
- [IJCAI'2023] [Scalable Coupling of Deep Learning with Logical Reasoning](https://www.ijcai.org/proceedings/2023/402)

#### 2.2 Interactive learning

- [AAAI'1997] [A constraint-based approach to preference elicitation and decision making](https://www.cs.toronto.edu/~cebly/Papers/_download_/preferences.pdf)
- [AIJ'2010] [Elicitation strategies for soft constraint problems with missing preferences: Properties, algorithms and experimental studies](https://www.sciencedirect.com/science/article/pii/S0004370209001453)
- [AIJ'2006] [Constraint-based optimization and utility elicitation using the minimax decision criterion](https://www.sciencedirect.com/science/article/pii/S0004370206000245)
- [SUM'2019] [An interactive polyhedral approach for multi-objective combinatorial optimization with incomplete preference information](https://link.springer.com/chapter/10.1007/978-3-030-35514-2_17)
- [DA2PL'2020] [Bayesian preference elicitation for multiobjective combinatorial optimization](https://hal.science/hal-02979845v1)
- [IJCAI'2016] [Constructive preference elicitation by setwise max-margin learning](https://dl.acm.org/doi/10.5555/3060832.3060910)
- [AAAI'2018] [Constructive preference elicitation over hybrid combinatorial spaces](https://dl.acm.org/doi/10.5555/3504035.3504394)
- [JAIR'2015] [Coactive learning](https://jair.org/index.php/jair/article/view/10939)
- [IIS'2024] [“I Want It That Way”: Enabling Interactive Decision Support Using Large Language Models and Constraint Programming](https://dl.acm.org/doi/10.1145/3685053)

---

### 3. Learning to model - Automatic model generation 

#### 3.1 Approaches for generation

- [IJCAI'2016] [Constraint detection in natural language problem descriptions](https://dl.acm.org/doi/10.5555/3060621.3060725)
- [PTHG'2019] [User-oriented solving and explaining of natural language logic grid puzzles](https://www.bartbogaerts.eu/articles/2019/005-HG-Zebra/ZebraTutor.pdf)
- [EMNLP'2020] [LGPSolver - Solving Logic Grid Puzzles Automatically](https://aclanthology.org/2020.findings-emnlp.100/)
- [ArXiv'2021] [Evaluating large language models trained on code](https://arxiv.org/abs/2107.03374)
- [CP'2024] [Constraint modelling with LLMs using in-context learning](https://drops.dagstuhl.de/entities/document/10.4230/LIPIcs.CP.2024.20)

  
#### 3.2 Benchmarks and competitions

- [Constraints'2024] [Ner4Opt: named entity recognition for optimization modelling from natural language](https://link.springer.com/article/10.1007/s10601-024-09376-5)
- [NeurIPS'2022] [NL4Opt Competition: Formulating Optimization Problems Based on Their Natural Language Descriptions](https://proceedings.mlr.press/v220/ramamonjison23a.html)
- [ECAI'2025] [CP-Bench: Evaluating Large Language Models for Constraint Modelling](https://arxiv.org/abs/2506.06052v1)

---

### 4. Learning to branch

#### 4.1 Online variable-selection heuristic

- REF
- REF
- REF

#### 4.2 Offline variable-selection heuristic

- REF
- REF
- REF

#### 4.3 Online value-selection heuristic

- REF
- REF
- REF

#### 4.4 Offline value-selection heuristic

- REF
- REF
- REF


---
### 5. Learning to reason

#### 5.1 Deductive learning of nogoods

- REF
- REF
- REF

#### 5.2 Learning Lagrangian multipliers in CP

- REF
- REF
- REF

---

### 6. Reshaping the solver engine

#### 6.1 Adaptive large neighborhood search
- REF
- REF
- REF

#### 6.2 Monte-Carlo tree search
- REF
- REF
- REF

#### 6.3 Solvers augmented with belief propagation
- REF
- REF
- REF

#### 6.4 Skipping the search phase
- REF
- REF
- REF


---

### 7. Learning to configure a CP solver

#### 7.1 Optimized configurations for entire problem classes
#### 7.2 Instance-specific methods
#### 7.3 Configuration from instance descriptions
#### 7.4 Acceleration techniques


---

### 8. Learning for generic and specific combinatorial problems

#### 8.1 Resource constrained project scheduling problem (RCPSP)
#### 8.2 Job shop scheduling problem (JSSP)
#### 8.3 Cyclic hoist scheduling problem (CHSP)
#### 8.4 Generic representation of combinatorial problems

---
