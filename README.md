
# Overview
This repository aims to serve as a (hopefully) comprehensive list of publications related to the integration of Constraint Programming (CP) and Machine Learning (ML). It accompanies the survey paper "Combining Constraint Programming and Machine Learning: From Current Progress to Future Opportunities" (JAIR, 2025) [[link](https://www.jair.org/index.php/jair/article/view/19533)].

# Contributing
The initial set of references corresponds to those discussed in Section 3 of the survey. Over time, we hope the repository evolves into a living collection that reflects the growing body of research in this area.
We encourage the community to contribute new references via pull requests. Contribution guidelines are provided below:

1. **Scope:** Only include methods that combine both Constraint Programming (CP) and Machine Learning (ML) within the same pipeline.
2. **Format:** Add your entry in the correct section of the repository and follow the template below.
3. **Pull Request:** Open a pull request with a clear title (e.g., Add [Venue'Year] Title). In the PR description, include 1–2 short paragraphs explaining why this paper belongs to the CP+ML field.


# Format of references

All related references are listed following the template below:

```
[<Venue>'<Year>] <Title of the paper>
```

When available, a direct link to the paper is also provided. The structure of this repository mirrors the organization used in the survey paper.

# Citing

If this repository or the associated paper has been useful in your research, please consider citing it using the following BibTeX entry:

```bibtex
@article{cappart2025combining,
  title={Combining Constraint Programming and Machine Learning: From Current Progress to Future Opportunities},
  author={Cappart, Quentin and Guns, Tias and Lombardi, Michele and Pesant, Gilles and Tsouros, Dimos},
  journal={Journal of Artificial Intelligence Research},
  volume={84},
  year={2025}
}
```
# Paper list


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
- [CP'2005] [Spread: A balancing constraint based on statistics](https://link.springer.com/chapter/10.1007/11564751_35)
- [EURO'2014] [Bound-consistent spread constraint](https://link.springer.com/article/10.1007/s13675-013-0018-8)
- [CPAIOR'2007] [The Deviation Constraint](https://link.springer.com/chapter/10.1007/978-3-540-72397-4_19)
- [CP'2007] [Bound-Consistent Deviation Constraint](https://link.springer.com/chapter/10.1007/978-3-540-74970-7_44)
- [IJOC'2005] [Achieving Domain Consistency and Counting Solutions for Dispersion Constraints](https://pubsonline.informs.org/doi/abs/10.1287/ijoc.2015.0654?casa_token=X3Ghcly9L54AAAAA%3AM2sVNQp5h8XKs10QLQ2hX-qR7amsniwkR991BQqrRXCaNADcTM6cRBoNaUj4g7BpF0J2EFc8MFEA&journalCode=ijoc)
- [Constraints'2010] [Markov constraints: steerable generation of Markov sequences](https://link.springer.com/article/10.1007/s10601-010-9101-4)
- [CP'2004] [A Regular Language Membership Constraint for Finite Sequences of Variables](https://link.springer.com/chapter/10.1007/978-3-540-30201-8_36)
- [Constraints'2006] [A Cost-Regular Based Hybrid Column Generation Approach](https://link.springer.com/article/10.1007/s10601-006-9003-7)
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

- [NeurIPS'2022] [NL4Opt Competition: Formulating Optimization Problems Based on Their Natural Language Descriptions](https://proceedings.mlr.press/v220/ramamonjison23a.html)
- [Constraints'2024] [Ner4Opt: named entity recognition for optimization modelling from natural language](https://link.springer.com/article/10.1007/s10601-024-09376-5)
- [ArXiv'2025] [Text2Zinc: A Cross-Domain Dataset for Modeling Optimization and Satisfaction Problems in MiniZinc](https://arxiv.org/abs/2503.10642)
- [ECAI'2025] [CP-Bench: Evaluating Large Language Models for Constraint Modelling](https://arxiv.org/abs/2506.06052v1)

---

### 4. Learning to branch

#### 4.1 Online variable-selection heuristic

- [ECAI'2004] [Boosting systematic search by weighting constraints](https://dl.acm.org/doi/10.5555/3000001.3000033)
- [FLAIRS'2007] [Learning to Identify Global Bottlenecks in Constraint Satisfaction Search](https://aaai.org/papers/flairs-2007-116/)
- [ICTAI'2019] [Refining constraint weighting](https://ieeexplore.ieee.org/document/8995307/)
- [ACM-Symposium'2019] [Conflict history based search for constraint satisfaction problem](https://dl.acm.org/doi/10.1145/3297280.3297389)
- [CP'2023] [Guiding Backtrack Search by Tracking Variables During Constraint Propagation](https://drops.dagstuhl.de/entities/document/10.4230/LIPIcs.CP.2023.9)
- [CP'2021] [Failure based variable ordering heuristics for solving CSPs](https://drops.dagstuhl.de/entities/document/10.4230/LIPIcs.CP.2021.9)
- [ICTAI'2014] [Correlation heuristics for constraint programming](https://ieeexplore.ieee.org/document/8372062)
- [AAAI'2018] [Learning robust search strategies using a bandit-based approach](https://ojs.aaai.org/index.php/AAAI/article/view/12211)
- [ECAI'2020] [Learning variable ordering heuristics with multi-armed bandits and restarts](https://ebooks.iospress.nl/volumearticle/54910)
- [IJCAI'2022] [Best heuristic identification for constraint satisfaction](https://www.ijcai.org/proceedings/2022/258)
- [ICTAI'2020] [On the Refinement of Conflict History Search Through Multi-Armed Bandit](https://ieeexplore.ieee.org/document/9288317)
- [AMAI'2022] [Online learning of variable ordering heuristics for constraint optimisation problems](https://link.springer.com/article/10.1007/s10472-022-09816-z)
- [CP'2022] [A portfolio-based approach to select efficient variable ordering heuristics for constraint satisfaction problems](https://drops.dagstuhl.de/entities/document/10.4230/LIPIcs.CP.2022.32)
- [AAAI'2025] [Prediction-Based Adaptive Variable Ordering Heuristics for Constraint Satisfaction Problems](https://ojs.aaai.org/index.php/AAAI/article/view/33239)

#### 4.2 Offline variable-selection heuristic

- [CPAIOR'2021] [Learning variable activity initialisation for lazy clause generation solvers](https://link.springer.com/chapter/10.1007/978-3-030-78230-6_4)
- [EAAI'2022] [Learning variable ordering heuristics for solving constraint satisfaction problems](https://www.sciencedirect.com/science/article/abs/pii/S0952197621004255)

#### 4.3 Online value-selection heuristic

- [CP'2004] [Impact-based search strategies for constraint programming](https://link.springer.com/chapter/10.1007/978-3-540-30201-8_41)
- [CPAIOR'2012] [Activity-based search for black-box constraint programming solvers](https://dl.acm.org/doi/abs/10.1007/978-3-642-29828-8_15)

#### 4.4 Offline value-selection heuristic

- [CPAIOR'2015] [Learning value heuristics for constraint programming](https://link.springer.com/chapter/10.1007/978-3-319-18008-3_8)
- [AAAI'2021] [Combining reinforcement learning and constraint programming for combinatorial optimization](https://ojs.aaai.org/index.php/AAAI/article/view/16484)
- [CPAIOR'2021] [Seapearl: A constraint programming solver guided by reinforcement learning](https://link.springer.com/chapter/10.1007/978-3-030-78230-6_25)
- [CP'2023] [Learning a Generic Value-Selection Heuristic Inside a Constraint Programming Solver](https://drops.dagstuhl.de/entities/document/10.4230/LIPIcs.CP.2023.25)
- [Constraints'2024] [Learning and fine-tuning a generic value-selection heuristic inside a constraint programming solver](https://link.springer.com/article/10.1007/s10601-024-09377-4)


---
### 5. Learning to reason

#### 5.1 Deductive learning of nogoods

- [Constraints'2009] [Propagation via lazy clause generation](https://link.springer.com/article/10.1007/s10601-008-9064-x)
- [CP'2012] [Inter-instance nogood learning in constraint programming](https://link.springer.com/chapter/10.1007/978-3-642-33558-7_19)
- [CP'2016] [Learning from learning solver](https://link.springer.com/chapter/10.1007/978-3-319-44953-1_29)
- [CP'2018] [Towards semi-automatic learning-based model transformation](https://link.springer.com/chapter/10.1007/978-3-319-98334-9_27)
- [AIJ'2016] [Learning general constraints in CSP](https://www.sciencedirect.com/science/article/pii/S0004370216300650)

#### 5.2 Learning Lagrangian multipliers in CP

- [CP'1999] [Cost-based domain filtering](https://link.springer.com/chapter/10.1007/978-3-540-48085-3_14)
- [CP'2004] [Theoretical foundations of CP-based lagrangian relaxation](https://link.springer.com/chapter/10.1007/978-3-540-30201-8_46)
- [Constraints'2012] [Improved filtering for weighted circuit constraints](https://link.springer.com/article/10.1007/s10601-012-9119-x)
- [CP'2024] [Learning Lagrangian Multipliers for the Travelling Salesman Problem](https://drops.dagstuhl.de/entities/document/10.4230/LIPIcs.CP.2024.22)
- [CP'2015] [General bounding mechanism for constraint programs](https://link.springer.com/chapter/10.1007/978-3-319-23219-5_12)
- [AAAI'2025] [Learning Valid Dual Bounds in Constraint Programming: Boosted Lagrangian Decomposition with Self-Supervised Learning](https://dl.acm.org/doi/10.1609/aaai.v39i11.33208)
---

### 6. Reshaping the solver engine

#### 6.1 Adaptive large neighborhood search
- [CP'1998] [Using Constraint Programming and Local Search Methods to Solve Vehicle Routing Problems](https://link.springer.com/chapter/10.1007/3-540-49481-2_30)
- [MISTA'2007] [Self-adapting large neighborhood search: Application to single-mode scheduling problems](https://www.semanticscholar.org/paper/Self-Adapting-Large-Neighborhood-Search%3A-to-Laborie-Godard/f0b2d8d701f0bb14a47dcde59ca2884120b7f26c)
- [CPAIOR'2018] [Revisiting the self-adaptive large neighborhood search](https://link.springer.com/chapter/10.1007/978-3-319-93031-2_40)

#### 6.2 Monte-Carlo tree search
- [ICCG'2006] [Efficient selectivity and backup operators in Monte-Carlo tree search](https://link.springer.com/chapter/10.1007/978-3-540-75538-8_7)
- [LION'2013] [Hybridizing constraint programming and monte-carlo tree search: Application to the job shop problem](https://link.springer.com/chapter/10.1007/978-3-642-44973-4_35)
- [CP'2013] [Bandit-based search for constraint programming](https://link.springer.com/chapter/10.1007/978-3-642-40627-0_36)
- [CP'2021] [Combining Monte Carlo tree search and depth first search methods for a car manufacturing workshop scheduling problem](https://drops.dagstuhl.de/entities/document/10.4230/LIPIcs.CP.2021.14)
- [LION'2023] [Learn, Compare, Search: One Sawmill’s Search for the Best Cutting Patterns Across and/or Trees](https://dl.acm.org/doi/10.1007/978-3-031-44505-7_37)

#### 6.3 Solvers augmented with belief propagation
- [AAAI'1982] [Reverend Bayes on Inference Engines: {A} Distributed Hierarchical Approach](https://dl.acm.org/doi/10.5555/2876686.2876719)
- [JAIR'2019] [From support propagation to belief propagation in constraint programming](https://jair.org/index.php/jair/article/view/11487)
- [CPAIOR'2023] [Exploiting Entropy in Constraint Programming](https://link.springer.com/chapter/10.1007/978-3-031-33271-5_21)

#### 6.4 Search with ant colony optimization

- [IEEE-TSMC'1996] [Ant system: optimization by a colony of cooperating agents](https://ieeexplore.ieee.org/document/484436)
- [IEEE-CIM'2007] [Ant colony optimization](https://ieeexplore.ieee.org/document/4129846)
- [ANTS'2004] [Integrating ACO and Constraint Propagation](https://link.springer.com/chapter/10.1007/978-3-540-28646-2_15)
- [ANTS'2008] [Integration of ACO in a Constraint Programming Language](https://link.springer.com/chapter/10.1007/978-3-540-87527-7_8)
- [CPAIOR'2010] [https://link.springer.com/chapter/10.1007/978-3-642-13520-0_26](https://link.springer.com/chapter/10.1007/978-3-642-13520-0_26)
- [HM'2013] [A Hybrid ACO+CP for Balancing Bicycle Sharing Systems](https://link.springer.com/chapter/10.1007/978-3-642-38516-2_16)
- [CP'2020] [Solving the Group Cumulative Scheduling Problem with CPO and ACO](https://link.springer.com/chapter/10.1007/978-3-030-58475-7_36)
- [Wiley'2013] [Ant Colony Optimization and Constraint Programming] (https://onlinelibrary.wiley.com/doi/book/10.1002/9781118557563)

#### 6.5 Skipping the search phase
- [CPAIOR'2018] [Model agnostic solution of CSPs via deep learning: A preliminary study](https://link.springer.com/chapter/10.1007/978-3-319-93031-2_18)
- [CP'2018] [Towards effective deep learning for constraint satisfaction problems](https://link.springer.com/chapter/10.1007/978-3-319-98334-9_38)
- [CP'2023] [FastMapSVM for Predicting CSP Satisfiability](https://drops.dagstuhl.de/entities/document/10.4230/LIPIcs.CP.2023.40)
- [ICAPS'2023] [An end-to-end reinforcement learning approach for job-shop scheduling problems based on constraint programming](https://dl.acm.org/doi/10.1609/icaps.v33i1.27243)
- [ICML'2025] [{ZebraLogic}: On the Scaling Limits of {LLM}s for Logical Reasoning](https://openreview.net/forum?id=sTAJ9QyA6l)
- [EMNLP'2024] [Puzzle Solving using Reasoning of Large Language Models: A Survey](https://aclanthology.org/2024.emnlp-main.646/) 

---

### 7. Learning to configure a CP solver
- [Computers'1976] [The algorithm selection problem](https://www.sciencedirect.com/science/article/abs/pii/S0065245808605203)
- [OR'2006] [Fine-tuning of algorithms using fractional experimental designs and local search](https://pubsonline.informs.org/doi/abs/10.1287/opre.1050.0243)
#### 7.1 Optimized configurations for entire problem classes
- [Constraints'1996] [Automatically configuring constraint satisfaction programs: A case study](https://link.springer.com/article/10.1007/BF00143877)
#### 7.2 Instance-specific methods
- [ECAI'2004] [Learning techniques for automatic algorithm portfolio selection](https://dl.acm.org/doi/10.5555/3000001.3000101)
- [ICCBR'2005] [Using CBR to select solution strategies in constraint programming](https://link.springer.com/chapter/10.1007/11536406_19)
- [CPAIOR'2014] [Proteus: A hierarchical portfolio of solvers and transformations](https://link.springer.com/chapter/10.1007/978-3-319-07046-9_22)
- [ArXiv'2010] [Machine learning for constraint solver design--A case study for the alldifferent constraint](https://arxiv.org/abs/1008.4326)
- [ICAICS'2008] [Using case-based reasoning in an algorithm portfolio for constraint solving](https://homepages.laas.fr/ehebrard/papers/aics2008.pdf)
- [TPLP'2014] [SUNNY: a lazy portfolio approach for constraint solving](https://www.cambridge.org/core/journals/theory-and-practice-of-logic-programming/article/abs/sunny-a-lazy-portfolio-approach-for-constraint-solving/F65F2BB44129A947982CF74830665F73)
- [ACM-Symposium'2015] [SUNNY-CP: a sequential CP portfolio solver](https://dl.acm.org/doi/10.1145/2695664.2695741)
- [JAIR'2021] [sunny-as2: Enhancing {SUNNY} for algorithm selection](https://jair.org/index.php/jair/article/view/13116)
- [ECAI'2010] [ISAC -- instance-specific algorithm configuration](https://dl.acm.org/doi/10.5555/1860967.1861114)
- [LION'2011] [Sequential model-based optimization for general algorithm configuration](https://link.springer.com/chapter/10.1007/978-3-642-25566-3_40)
#### 7.3 Configuration from instance descriptions
- [ECML-PKDD'2013] [SNNAP: Solver-based nearest neighbor for algorithm portfolios](https://link.springer.com/chapter/10.1007/978-3-642-40994-3_28)
- [ICAML'2022] [Opening the black box: Automated software analysis for algorithm selection](https://proceedings.mlr.press/v188/pulatov22a.html)
- [AAAI'2016] [Deep learning for algorithm portfolios](https://aaai.org/papers/10170-deep-learning-for-algorithm-portfolios/)
#### 7.4 Portfolio-based algorithm selection
- [CP'2011] [Algorithm selection and scheduling](https://link.springer.com/chapter/10.1007/978-3-642-23786-7_35)
- [CP'2012] [Parallel {SAT} solver selection and scheduling](https://link.springer.com/chapter/10.1007/978-3-642-33558-7_38)
- [LION'2015] [From sequential algorithm selection to parallel portfolio selection](https://link.springer.com/chapter/10.1007/978-3-319-19084-6_1)
- [ECAI'2023] [Automatic Parallel Portfolio Selection](https://ebooks.iospress.nl/doi/10.3233/FAIA230398)
#### 7.5 Acceleration techniques
- [JMLR'2022] [SMAC3: A versatile Bayesian optimization package for hyperparameter optimization](https://www.jmlr.org/papers/v23/21-0888.html)
- [CPAIOR'2022] [Model-Based Algorithm Configuration with Adaptive Capping and Prior Distributions](https://link.springer.com/chapter/10.1007/978-3-031-08011-1_6)
- [CP'2024] [Frugal Algorithm Selection](https://drops.dagstuhl.de/entities/document/10.4230/LIPIcs.CP.2024.38)

---

### 8. Learning for generic and specific combinatorial problems

#### 8.1 Resource constrained project scheduling problem (RCPSP)
- [ICAPS'2024] [Fast and robust resource-constrained scheduling with graph neural networks](https://ojs.aaai.org/index.php/ICAPS/article/view/27244)
- [CP'2024] [Learning Precedences for Scheduling Problems with Graph Neural Networks](https://drops.dagstuhl.de/entities/document/10.4230/LIPIcs.CP.2024.30)
#### 8.2 Job shop scheduling problem (JSSP)
- [WSC'2022] [Imitation learning for real-time job shop scheduling using graph-based representation](https://ieeexplore.ieee.org/document/10015445/)
- [ICAPS'2023] [An end-to-end reinforcement learning approach for job-shop scheduling problems based on constraint programming](https://ojs.aaai.org/index.php/ICAPS/article/view/27243)
- [KBS'2024] [Enhancing constraint programming via supervised learning for job shop scheduling](https://www.sciencedirect.com/science/article/pii/S0950705124003332)
#### 8.3 Cyclic hoist scheduling problem (CHSP)
- [CPAIOR'2023] [Predicting the Optimal Period for Cyclic Hoist Scheduling Problems](https://link.springer.com/chapter/10.1007/978-3-031-33271-5_16)
#### 8.4 Generic representation of combinatorial problems
- [NeurIPS'2019] [Exact combinatorial optimization with graph convolutional neural networks](https://papers.nips.cc/paper_files/paper/2019/hash/d14c2267d848abeb81fd590f371d39bd-Abstract.html)
- [CPAIOR'2021] [Seapearl: A constraint programming solver guided by reinforcement learning](https://link.springer.com/chapter/10.1007/978-3-030-78230-6_25)
- [CP'2023] [Learning a Generic Value-Selection Heuristic Inside a Constraint Programming Solver](https://drops.dagstuhl.de/entities/document/10.4230/LIPIcs.CP.2023.25)
- [Constraints'2024] [Learning and fine-tuning a generic value-selection heuristic inside a constraint programming solver](https://link.springer.com/article/10.1007/s10601-024-09377-4)
- [CPAIOR'2024] [Towards a Generic Representation of Combinatorial Problems for Learning-Based Approaches](https://link.springer.com/chapter/10.1007/978-3-031-60597-0_7)
- [IJCAI'2023] [One model, any CSP: graph neural networks as fast global search heuristics for constraint satisfaction](https://www.ijcai.org/proceedings/2023/476)
- [ICML'2025] [Self-Supervised Transformers as Iterative Solution Improvers for Constraint Satisfaction](https://openreview.net/forum?id=IQN6ID0snT)

---


## Improving machine learning with constraint programming

This list categorizes key research directions in the the role of CP in enhancing different ML tasks and methodologies.

---
### 1. CP-based learning for different ML model types

#### 1.1 Pattern mining
- [Springer-Book'2015] [Data mining: the textbook](https://link.springer.com/book/10.1007/978-3-319-14142-8)
- [WIREs'2017] [A survey of itemset mining](https://wires.onlinelibrary.wiley.com/doi/abs/10.1002/widm.1207?casa_token=Y0I-ZakXIHUAAAAA%3AitMQBFT2Vxn413XaFZN1aGKxs3xDhKi6heUwEFedjEWrL-UIZLUu8cX0-GE00Yo3DFpV6l2Gr2otOrVI0A)
- [AAAI'2010] [Constraint programming for data mining and machine learning](https://ojs.aaai.org/index.php/AAAI/article/view/7707)
- [AIJ'2011] [Itemset mining: A constraint programming perspective](https://www.sciencedirect.com/science/article/pii/S0004370211000646)
- [CP'2016] [A global constraint for closed frequent pattern mining](https://link.springer.com/chapter/10.1007/978-3-319-44953-1_22)
- [CP'2017] [Coversize: A global constraint for frequency-based itemset mining](https://link.springer.com/chapter/10.1007/978-3-319-66158-2_34)
- [AAAI'2013] [Miningzinc: A modeling language for constraint-based mining](https://dl.acm.org/doi/abs/10.5555/2540128.2540325)
- [CPAIOR'2015] [Constraint-based sequence mining using constraint programming](https://link.springer.com/chapter/10.1007/978-3-319-18008-3_20)
- [CP'2015] [PREFIX-PROJECTION global constraint for sequential pattern mining](https://link.springer.com/chapter/10.1007/978-3-319-23219-5_17)
- [Constraints'2017] [Mining time-constrained sequential patterns with constraint programming](https://link.springer.com/article/10.1007/s10601-017-9272-3)
- [CPAIOR'2018] [Episodesupport: A global constraint for mining frequent patterns in a long sequence of events](https://link.springer.com/chapter/10.1007/978-3-319-93031-2_7)
- [CP'2010] [Constraint programming for mining n-ary patterns](https://link.springer.com/chapter/10.1007/978-3-642-15396-9_44)
- [TKDE'2013] [k-Pattern Set Mining under Constraints](https://ieeexplore.ieee.org/document/6035705)
- [AIJ'2017] [Skypattern mining: From pattern condensed representations to dynamic constraint satisfaction problems](https://www.sciencedirect.com/science/article/pii/S000437021500065X)
- [DMKD'2017] [Flexible constrained sampling with guarantees for pattern mining](https://link.springer.com/article/10.1007/s10618-017-0501-6)
- [Constraints'2024] [Mining diverse sets of patterns with constraint programming using the pairwise Jaccard similarity relaxation](https://link.springer.com/article/10.1007/s10601-024-09373-8)
- [CPAIOR'2024] [Efficiently Mining Closed Interval Patterns with Constraint Programming](https://link.springer.com/chapter/10.1007/978-3-031-60597-0_4)
- [IDA'2023] [Explanations for Itemset Mining by Constraint Programming: A Case Study Using ChEMBL Data](https://link.springer.com/chapter/10.1007/978-3-031-30047-9_17)
  
#### 1.2 Clustering
- [CP'2015] [Constrained minimum sum of squares clustering by constraint programming](https://link.springer.com/chapter/10.1007/978-3-319-23219-5_39)
- [AIJ'2017] [Constrained clustering by constraint programming](https://www.sciencedirect.com/science/article/pii/S0004370215000806)
- [ECAI'2016] [Repetitive branch-and-bound using constraint programming for constrained minimum sum-of-squares clustering](https://ebooks.iospress.nl/doi/10.3233/978-1-61499-672-9-462)
- [CPAIOR'2020] [An Exact CP Approach for the Cardinality-Constrained Euclidean Minimum Sum-of-Squares Clustering Problem](https://link.springer.com/chapter/10.1007/978-3-030-58942-4_17)
- [AAAI'2017] [A framework for minimal clustering modification via constraint programming](https://ojs.aaai.org/index.php/AAAI/article/view/10765)
- [CP'2017] [Constraint programming for multi-criteria conceptual clustering](https://link.springer.com/chapter/10.1007/978-3-319-66158-2_30)
- [SEFM'2015] [Clustering Formulation Using Constraint Optimization](https://link.springer.com/chapter/10.1007/978-3-662-49224-6_9)
  
#### 1.3 Decision trees
- [CP'2009] [Minimising Decision Tree Size as Combinatorial Optimisation](https://link.springer.com/chapter/10.1007/978-3-642-04244-7_16)
- [Constraints'2020] [Learning optimal decision trees using constraint programming](https://link.springer.com/article/10.1007/s10601-020-09312-3)
  
#### 1.4 Bayesian networks
- [AIJ'2017] [Integer Linear Programming for the {B}ayesian network structure learning problem](https://www.sciencedirect.com/science/article/pii/S0004370215000417)
- [CP'2015] [Machine learning of Bayesian networks using constraint programming](https://link.springer.com/chapter/10.1007/978-3-319-23219-5_31)
- [IJCAI'2021] [Improved Acyclicity Reasoning for Bayesian Network Structure Learning with Constraint Programming](https://hal.science/hal-03268019/)
- [IDA'2015] [Constraint-Based Querying for {B}ayesian Network Exploration](https://link.springer.com/chapter/10.1007/978-3-319-24465-5_2)
  
#### 1.5 Neural networks
- [PACT'1996] [Evolutionary training of CLP-constrained neural networks](https://repository.ubn.ru.nl/bitstream/handle/2066/84496/84496.pdf)
- [CP'2019] [Training binarized neural networks using MIP and CP](https://link.springer.com/chapter/10.1007/978-3-030-30048-7_24)

---
### 2. CP-based loss functions

- [ICML'2019] [SATNet: Bridging deep learning and logical reasoning using a differentiable satisfiability solver](https://proceedings.mlr.press/v97/wang19e.html)
- [NeurIPS'2022] [Semantic probabilistic layers for neuro-symbolic learning](https://proceedings.neurips.cc/paper_files/paper/2022/hash/c182ec594f38926b7fcb827635b9a8f4-Abstract-Conference.html)
- [CPAIOR'2021] [Injecting Domain Knowledge in Neural Networks: A Controlled Experiment on a Constrained Problem](https://link.springer.com/chapter/10.1007/978-3-030-78230-6_17)
- [AAAI'2021] [Teaching the old dog new tricks: Supervised learning with constraints](https://ojs.aaai.org/index.php/AAAI/article/view/16491)
- [ICML'2020] [Deep Reasoning Networks for Unsupervised Pattern De-mixing with Constraint Reasoning](https://proceedings.mlr.press/v119/chen20a.html)
- [CP'2021] [CLR-DRNets: Curriculum Learning with Restarts to Solve Visual Combinatorial Games](https://drops.dagstuhl.de/entities/document/10.4230/LIPIcs.CP.2021.17)
- [CP'2022] [Combining Reinforcement Learning and Constraint Programming for Sequence-Generation Tasks with Hard Constraints](https://drops.dagstuhl.de/entities/document/10.4230/LIPIcs.CP.2022.30)
- [CPAIOR'2024] [An Improved Neuro-Symbolic Architecture to Fine-Tune Generative AI Systems](https://link.springer.com/chapter/10.1007/978-3-031-60599-4_19)
- [CPAIOR'2025] [Shaping Reward Signals in Reinforcement Learning Using Constraint Programming](https://link.springer.com/chapter/10.1007/978-3-031-95976-9_16)

---

### 3. CP-based inference

- [Annual-Reviews'2022] [Safe learning in robotics: From learning-based control to safe reinforcement learning](https://www.annualreviews.org/content/journals/10.1146/annurev-control-042920-020211)
- [CEUR-Workshop'2021] [Neuro-Symbolic Constraint Programming for Structured Prediction](https://iris.unitn.it/handle/11572/364929)
- [CPAIOR'2020] [Hybrid Classification and Reasoning for Image-Based Constraint Solving](https://link.springer.com/chapter/10.1007/978-3-030-58942-4_24)
- [Constraints'2024] [Perception-based constraint solving for sudoku images](https://link.springer.com/article/10.1007/s10601-024-09372-9)
- [IJCAI'2025] [Constrained Sequential Inference in Machine Learning Using Constraint Programming](https://ijcai-preprints.s3.us-west-1.amazonaws.com/2025/5386.pdf)
- [IJCAI'2023] [Constraints First: A New MDD-based Model to Generate Sentences Under Constraints](https://dl.acm.org/doi/abs/10.24963/ijcai.2023/210)
- [IJCAI'2024] [Markov Constraint as Large Language Model Surrogate](https://hal.science/hal-04676241/)
- [CP'2024] [Combining Constraint Programming Reasoning with Large Language Model Predictions](https://drops.dagstuhl.de/entities/document/10.4230/LIPIcs.CP.2024.25)
- [LAFM'2024] [Logic-based explainability: past, present and future](https://dl.acm.org/doi/abs/10.1007/978-3-031-75387-9_12)
- [ECML-PKDD'2024] [Learning Model Agnostic Explanations via Constraint Programming](https://link.springer.com/chapter/10.1007/978-3-031-70359-1_26)
---
