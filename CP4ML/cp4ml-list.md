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
