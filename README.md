# awesome-deep-neuroevolution
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRsWelcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)



<p align="center">
<img src="https://github.com/Alro10/awesome-deep-neuroevolution/blob/master/deepneuroevolution.png" alt="alt text" width="80%" height="60%">
</p>

A collection of Deep Neuroevolution and evolutionary computation resources. Inspired by [awesome-deep-learning-papers](https://github.com/terryum/awesome-deep-learning-papers), [awesome-meta-learning](https://github.com/dragen1860/awesome-meta-learning), the early paper by [OpenAI-Evolution Strategies](https://arxiv.org/abs/1703.03864) and the amazing work from **Uber AI Labs** [blog](https://eng.uber.com/deep-neuroevolution/)


A good survey of Deep Reinforcement Learning: [A Brief Survey of Deep Reinforcement Learning](https://arxiv.org/abs/1708.05866)

## [Table of Contents]()

* [Papers](#Papers)
* [Conferences](#Conferences)
* [Tutorials](#Tutorials)
* [Resources](#Resources)
* [Researchers](#Researchers)


## Papers

| Title | Authors | Code | Year |
| ----- | ------- | -------- | ---- |
| [Evolution Strategies as a Scalable Alternative to Reinforcement Learning](https://arxiv.org/abs/1703.03864) | Tim Salimans, Jonathan Ho, Xi Chen, Szymon Sidor, Ilya Sutskever | [[repo](https://github.com/openai/evolution-strategies-starter)]![github](github.jpg) [[blog](https://blog.openai.com/evolution-strategies/)] | 2017 |
| [Deep Neuroevolution: Genetic Algorithms Are a Competitive Alternative for Training Deep Neural Networks for Reinforcement Learning](https://arxiv.org/abs/1712.06567) | Felipe Petroski Such, Vashisht Madhavan, Edoardo Conti, Joel Lehman, Kenneth O. Stanley, Jeff Clune | [[repo](https://github.com/uber-research/deep-neuroevolution)]![github](github.jpg) [[blog](https://eng.uber.com/deep-neuroevolution/)]| 2017 |
| [Safe Mutations for Deep and Recurrent Neural Networks through Output Gradients](https://arxiv.org/abs/1712.06563) | Joel Lehman, Jay Chen, Jeff Clune, Kenneth O. Stanley | [repo](https://github.com/uber-research/safemutations)![github](github.jpg) | 2017 |
| [Improving Exploration in Evolution Strategies for Deep Reinforcement Learning via a Population of Novelty-Seeking Agents](https://arxiv.org/abs/1712.06560)| Edoardo Conti, Vashisht Madhavan, Felipe Petroski Such, Joel Lehman, Kenneth O. Stanley, Jeff Clune | [repo](https://github.com/uber-research/deep-neuroevolution)![github](github.jpg) | 2017, NIPS 2018 |
| [On the Relationship Between the OpenAI Evolution Strategy and Stochastic Gradient Descent](https://arxiv.org/abs/1712.06564) | Xingwen Zhang, Jeff Clune, Kenneth O. Stanley | [blog](https://eng.uber.com/deep-neuroevolution/) | 2017 |
| [ES Is More Than Just a Traditional Finite-Difference Approximator](https://arxiv.org/abs/1712.06568) | Joel Lehman, Jay Chen, Jeff Clune, Kenneth O. Stanley | [blog](https://eng.uber.com/deep-neuroevolution/) | 2017 |
| [Playing Atari with Six Neurons](https://arxiv.org/abs/1806.01363) | Giuseppe Cuccu, Julian Togelius, Philippe Cudre-Mauroux | [[repo](https://github.com/giuse/DNE/tree/nips2018)] ![github](github.jpg) | 2018, AAMAS 2019 |
| [Simple random search provides a competitive approach to reinforcement learning](https://arxiv.org/abs/1803.07055)| Horia Mania, Aurelia Guy, Benjamin Recht | [[repo](https://github.com/modestyachts/ARS)]![github](github.jpg) | 2018 |
| [Regularized Evolution for Image Classifier Architecture Search](https://arxiv.org/abs/1802.01548) | Esteban Real, Alok Aggarwal, Yanping Huang, Quoc V Le | [repocolab](https://colab.research.google.com/github/google-research/google-research/blob/master/evolution/regularized_evolution_algorithm/regularized_evolution.ipynb) | 2018, AAAI 2019 |
| [Evolution-Guided Policy Gradient in Reinforcement Learning](https://arxiv.org/abs/1805.07917) | Shauharda Khadka, Kagan Tumer | [repo](https://github.com/ShawK91/erl_paper_nips18) ![github](github.jpg)| NIPS 2018 |
| [Evolutionary Stochastic Gradient Descent for Optimization of Deep Neural Networks](https://arxiv.org/abs/1810.06773)| Xiaodong Cui, Wei Zhang, Zoltán Tüske, Michael Picheny | not yet | NIPS 2018 |
| [Experimental Evaluation of Metaheuristic Optimization of Gradients as an Alternative to Backpropagation](https://ieeexplore.ieee.org/abstract/document/8780709) | Oleksandr Zavalnyi et al. |  not yet  | 2018 |
| [CEM-RL: Combining evolutionary and gradient-based methods for policy search](https://arxiv.org/abs/1810.01222) | Aloïs Pourchot, Olivier Sigaud | [repo](https://github.com/apourchot/CEM-RL)![github](github.jpg) | ICLR 2019 |
| [Efficient Multi-objective Neural Architecture Search via Lamarckian Evolution](https://arxiv.org/abs/1804.09081) | Thomas Elsken, Jan Hendrik Metzen, Frank Hutter | [openreview](https://openreview.net/forum?id=ByME42AqK7) | 2018, ICLR2019 |
| [Exploring Randomly Wired Neural Networks for Image Recognition](https://arxiv.org/abs/1904.01569) | Saining Xie, Alexander Kirillov, Ross Girshick, Kaiming He  | not yet | 2019 |
| [Designing neural networks through neuroevolution](https://www.nature.com/articles/s42256-018-0006-z.pdf?origin=ppub) | Kenneth O. Stanley, Jeff Clune, Joel Lehman and Risto Miikkulainen | it is a letter | Nature machine intelligence January 2019|
| [Guided evolutionary strategies: escaping the curse of dimensionality in random search](https://arxiv.org/abs/1806.10230) | Niru Maheswaranathan, Luke Metz, George Tucker, Dami Choi, Jascha Sohl-Dickstein| [repo](https://github.com/brain-research/guided-evolutionary-strategies) ![github](github.jpg) | ICML 2019|
| [Collaborative Evolutionary Reinforcement Learning](https://arxiv.org/abs/1905.00976v2) | Shauharda Khadka, Somdeb Majumdar, Tarek Nassar, Zach Dwiel, Evren Tumer, Santiago Miret, Yinyin Liu, Kagan Tumer | -------- | ICML 2019 |
| [Trust Region Evolution Strategies](https://pdfs.semanticscholar.org/6557/f9e7832dd127ab3ea2bcd0d1a6b924d4efc2.pdf) | Guoqing Liu et al. | not yet | AAAI 2019 |
| [Deep Neuroevolution of Recurrent and Discrete World Models](https://arxiv.org/abs/1906.08857) | Sebastian Risi, Kenneth O. Stanley | [repo](https://github.com/sebastianrisi/ga-world-models) | 2019 |
| [Proximal Distilled Evolutionary Reinforcement Learning](https://arxiv.org/abs/1906.09807) | Cristian Bodnar, Ben Day, Pietro Lio' | not yet | AAAI 2019 |
| [POET: open-ended coevolution of environments and their optimized solutions](https://www.researchgate.net/publication/334220089_POET_open-ended_coevolution_of_environments_and_their_optimized_solutions) | Rui Wang, Joel Lehman, Jeff Clune and Kenneth O. Stanley | not yet | GECCO 2019 |
| [COEGAN: evaluating the coevolution effect in generative adversarial networks](https://dl.acm.org/citation.cfm?id=3321746) | V. Costa, N. Lourenço, J. Correia, and P. Machado |[repo](https://github.com/vfcosta/coegan) | GECCO 2019 |
| [Evolution and self-teaching in neural networks: another comparison when the agent is more primitively conscious]() | Nam Le | not yet  | GECCO 2019 |
| [Diverse Agents for Ad-Hoc Cooperation in Hanabi](https://arxiv.org/abs/1907.03840) | Rodrigo Canaan, Julian Togelius, Andy Nealen, Stefan Menzel | not yet | CoG 2019 |
| [EPNAS: Efficient Progressive Neural Architecture Search](https://arxiv.org/abs/1907.04648) | Yanqi Zhou, Peng Wang, Sercan Arik, Haonan Yu, Syed Zawad, Feng Yan, Greg Diamos | not yet | 2019 |
| [Acoustic Model Optimization Based On Evolutionary Stochastic Gradient Descent with Anchors for Automatic Speech Recognition](https://arxiv.org/abs/1907.04882)  | Xiaodong Cui, Michael Picheny (IBM Research)| not yet | Interspeech 2019 |
| [Fast DENSER: Efficient Deep NeuroEvolution](https://www.researchgate.net/publication/332306893_Fast_DENSER_Efficient_Deep_NeuroEvolution) | Filipe Assunção, Nuno Lourenço, Penousal Machado, Bernardete Ribeiro | [repo](https://github.com/fillassuncao/f-denser) | EuroGP 2019 |
| [AlphaStar: An Evolutionary Computation Perspective](https://arxiv.org/abs/1902.01724) | Kai Arulkumaran, Antoine Cully, Julian Togelius | not yet | GECCO 2019 |
| [Automatic Design of Artificial Neural Networks for Gamma-Ray Detection](https://www.researchgate.net/publication/332977799_Automatic_Design_of_Artificial_Neural_Networks_for_Gamma-Ray_Detection) | Filipe Assunção, João Correia, Rúben Conceição, Mário Pimenta, Bernardo Tomé, Nuno Lourenço, Penousal Machado | not yet | 2019 |
| [Evolvability ES: Scalable and Direct Optimization of Evolvability](https://arxiv.org/abs/1907.06077) | Alexander Gajewski, Jeff Clune, Kenneth O. Stanley, Joel Lehman | [repo](https://github.com/uber-research/Evolvability-ES) | GECCO 2019 |
| [Towards continual reinforcement learning through evolutionary meta-learning](https://dl.acm.org/citation.cfm?id=3322044) | Djordje Grbic and Sebastian Risi  | not yet  | GECCO 2019|
| [Automated Neural Network Construction with Similarity Sensitive Evolutionary Algorithms](http://rvc.eng.miami.edu/Paper/2019/IRI19_EA.pdf) | Haiman Tian et al. | not yet| 2019 |
| [Provably Robust Blackbox Optimization for Reinforcement Learning](https://arxiv.org/abs/1903.02993) | Krzysztof Choromanski, Aldo Pacchiano et al. | not yet  | 2019 |
| [Go-Explore: a New Approach for Hard-Exploration Problems](https://arxiv.org/abs/1901.10995) | Adrien Ecoffet, Joost Huizinga, Joel Lehman, Kenneth O. Stanley, Jeff Clune | not yet | 2019 |
| [Culturally Evolved GANs for Generating Fake Stroke Faces](https://www.researchgate.net/publication/334811480_Culturally_Evolved_GANs_for_Generating_Fake_Stroke_Faces) | Kaitav Mehta et al. | not yet  | ICTS4eHealth'19 |
| [An Evolution Strategy with Progressive Episode Lengths for Playing Games](https://ml.informatik.uni-freiburg.de/papers/19-IJCAI_PEL.pdf) | Lior Fuks, Noor Awad , Frank Hutter and Marius Lindauer | [code](https://github.com/liorfuks/meta_pop) | IJCAI 2019 |
| [On Hard Exploration for Reinforcement Learning: A Case Study in Pommerman](https://arxiv.org/abs/1907.11788) | Chao Gao, Bilal Kartal, Pablo Hernandez-Leal, Matthew E. Taylor | not yet | 2019 |
| [A Knee-Guided Evolutionary Algorithm for Compressing Deep Neural Networks](https://www.researchgate.net/publication/334782953_A_Knee-Guided_Evolutionary_Algorithm_for_Compressing_Deep_Neural_Networks) | Yao Zhou et al. | not yet | 2019 |
| [Multi-task Deep Reinforcement Learning with Evolutionary Algorithm and Policy Gradients Method in 3D Control Tasks](https://www.researchgate.net/publication/334809110_Multi-task_Deep_Reinforcement_Learning_with_Evolutionary_Algorithm_and_Policy_Gradients_Method_in_3D_Control_Tasks) | Shota Imai et al. | not yet | In book: Big Data, Cloud Computing, and Data Science Engineering 2019 |
| ----- | ------- | -------- | ---- |
| ----- | ------- | -------- | ---- |


## Conferences

- Genetic and evolutionary computation
  - [GECCO](https://gecco-2019.sigevo.org/index.html/HomePage)
- Machine learning
  - [ICLR](https://iclr.cc/)  
- Artificial intelligence  
  - [AAAI](https://www.aaai.org/)


## Tutorials

* [Paper experiments replication: Deep Neuroevolution Uber](https://towardsdatascience.com/paper-repro-deep-neuroevolution-756871e00a66)
* [Introduction to Genetic Algorithms — Including Example Code-Java](https://towardsdatascience.com/introduction-to-genetic-algorithms-including-example-code-e396e98d8bf3)
* [Genetic Algorithm for 2D function-Matlab](https://github.com/Alro10/genetic-algorithm-optimization)[github](github.jpg)

## Resources

* [VINE: An Open Source Interactive Data Visualization Tool for Neuroevolution](https://eng.uber.com/vine/) by Uber AI Labs.
* [EvoGrad: A Lightweight Library for Gradient-Based Evolution](https://eng.uber.com/evograd/) by Uber AI Labs.
* [POET](https://eng.uber.com/poet-open-ended-deep-learning/) by Uber AI Labs.

## Researchers

* [Kenneth O. Stanley](https://eng.uber.com/author/kenneth-stanley/)- Uber AI Labs.
* [Jeff Clune](https://eng.uber.com/author/jeff-clune/)- Uber AI Labs.
* [Risto Miikkulainen](https://scholar.google.com/citations?user=2SmbjHAAAAAJ&hl=es)- University of Texas at Austin.
* [Nuno Lourenço](https://www.cisuc.uc.pt/people/show/2906)- University of Coimbra.

*Know of a recent, good paper? Send a pull request or open an issue!* :+1:
