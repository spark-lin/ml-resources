# Some resources for Machine Learning

Very personal and biased recommendation of ML resources. <br/>
**Disclaimer**: I'm a noivce in ML research, and I read only a few of the list.

## Table of Contents
- [Machine Learning](#machine-learning)
- [Deep Learning](#deep-learning)
- [Reinforcement Learning](#reinforcement-learning)
- [Graphical Model](#graphical-model)
- [Optimization](#optimization)
- [Learning Theory](#learning-theory)
- [Some Related Topics](#some-related-topics)
- [Some Math Backgrounds](#some-math-backgrounds)
- [For Math Geeks](#for-math-geeks)


## Machine Learning
There are many ML books, but most of them are encyclopedic. <br/>
I recommend to take a course using Murphy or Bishop book.

### Textbook
- Machine Learning: A Probabilistic Perspective (Murphy) :sparkles:
- Pattern Recognition and Machine Learning (Bishop) :sparkles:
- The Elements of Statistical Learning (Hastie et al.)
- Pattern Classification (Duda et al.)
- Bayesian Reasoning and Machine Learning (Barber)

### Lecture
- [Stanford CS229 Machine Learning](http://cs229.stanford.edu)
- [CMU 10701 Mahine Learning](http://www.cs.cmu.edu/~tom/10701_sp11/)
- [Oxford Machine Learning](https://www.cs.ox.ac.uk/people/nando.defreitas/machinelearning/)


## Deep Learning
Goodfellow et al. is new classic. <br/>
For vision and NLP, Stanford lectures would be helpful.

### Textbook
- Deep Learning (Goodfellow et al.) :sparkles:

### Lecture
- [Stanford CS231n Convolutional Neural Networks for Visual Recognition](http://cs231n.stanford.edu)
- [Stanfrod CS224d Deep Learning for Natural Language Processing](http://cs224d.stanford.edu)
- [Oxford Deep Natural Language Processing](https://github.com/oxford-cs-deepnlp-2017/lectures)

### Tutorial
- [ICML 2017 Sequence-To-Sequence Modeling with Neural Networks](https://sites.google.com/view/seq2seq-icml17)


## Reinforcement Learning
For classic (non-deep) RL, Sutton & Barto is the classic. <br/>
For deep RL, lectures and tutorials would be better.

### Textbook
- Reinforcement Learning: An Introduction (Sutton & Barto) :sparkles:
- Algorithms for Reinforcement Learning (Szepesvári)
- Dynamic Programming and Optimal Control (Bertsekas)

### Lecture
- [UCL Reinforcement Learning](http://www0.cs.ucl.ac.uk/staff/d.silver/web/Teaching.html)
- [Berkeley Deep RL Bootcamp](https://sites.google.com/view/deep-rl-bootcamp/lectures)
- [Berkeley CS294 Deep Reinforcement Leanring](http://rll.berkeley.edu/deeprlcourse/)
- [CMU 10703 Deep Reinforcement Learing and Control](https://katefvision.github.io/)

### Tutorial
- [ICML 2017 Deep Reinforcement Learning, Decision Making, and Control](https://sites.google.com/view/icml17deeprl)


## Graphical Model
Koller & Friedman is comprehensive, but too encyclopedic. <br/>
I recommend to take an introductory course using Koller & Friedman book. <br/>

Wainwright & Jordan only focuses on variational inference, <br/>
but it is must-read book for probabilistic model, e.g. generative model.

### Textbook
- Probabilistic Graphical Models: Principles and Techniques (Koller & Friedman)
- Graphical Models, Exponential Families, and Variational Inference (Wainwright & Jordan) :sparkles:

### Lecture
- [Stanford CS228 Probabilistic Graphical Models](http://cs.stanford.edu/~ermon/cs228/index.html)
- [CMU 10708 Probabilistic Graphical Models](http://www.cs.cmu.edu/~epxing/Class/10708/)


## Optimization
Boyd & Vandenberghe is the classic, but I think it's too boring. <br/>
Reading chapter 2-5 and understanding Fenchel's duality would be enough.

Rockafellar and Bertsekas more concentrates on convex analysis. <br/>
Nocedal & Wright more concentrates on optimization.

### Textbook
- Convex Optimization (Boyd & Vandenberghe) :sparkles:
- Convex Analysis (Rockafellar)
- Convex Optimization Theory (Bertsekas)
- Numerical Optimization (Nocedal & Wright)

### Lecture
- [Stanford EE364a Convex Optimization I](http://stanford.edu/class/ee364a/)
- [Stanford EE364b Convex Optimization II](http://stanford.edu/class/ee364a/)
- [MIT 6.253 Convex Analysis and Optimization](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-253-convex-analysis-and-optimization-spring-2012/index.htm)

### Tutorial
- [ICML 2017 Recent Advances in Stochastic Convex and Non-Convex Optimization](http://people.csail.mit.edu/zeyuan/topics/icml-2017)


## Learning Theory
In my understanding, there are two things in learning theory:
- Learning Theory: VC-dimension, PAC bound, Rademacher complexity
- Online Learning: regret bound, multi-armed bandit

For learning theory, Kearns & Vazirani is the classic; but it's too old-fashined. <br/>
Personally, I prefer recent books like Shalev-Shwartz & Ben-David. <br/>
Abu-Mostafa is a good introductory book, and I think it's enough for most people.

For online learning, Cesa-Bianchi & Lugosi is the classic. <br/>
For multi-armed bandit problem, Bubeck & Cesa-Bianchi is a good survey.

### Textbook (Learning Theory)
- Learning from Data (Abu-Mostafa)
- Foundations of Machine Learning (Mohri et al.)
- Understanding Machine Learning: From Theory to Algorithms (Shalev-Shwartz & Ben-David)
- An Introduction to Computational Learning Theory (Kearns & Vazirani) 

### Textbook (Online Learning)
- Prediction, Learning, and Games (Cesa-Bianchi & Lugosi)
- Regret Analysis of Stochastic and Nonstochastic Multi-armed Bandit Problems (Bubeck & Cesa-Bianchi)

### Lecture
- [Caltech Learning from Data](https://work.caltech.edu/telecourse.html)
- [CMU 15859 Machine Learning Theory](http://www.cs.cmu.edu/~avrim/ML14/)
- [Berkeley CS281b/Stat241b Statistical Learning Theory](https://www.stat.berkeley.edu/~bartlett/courses/2014spring-cs281bstat241b/)
- [UPenn Stat928 Statistical Learning Theory](http://stat.wharton.upenn.edu/~skakade/courses/stat928/)


## Some Related Topics

### Information Theory
- Elements of Information Theory (Cover & Thomas)
- Information Theory, Inference, and Learning Algorithms (MacKay)

### Network Science
- Networks, Crowds, and Markets (Easley & Kleinberg)
- Network Science (Barabási)
- Random Graphs (Bollobás)

### Game Theory
- Algorithmic Game Theory (Nisan et al.)
- Multiagent Systems (Shoham & Leyton-Brown)

### Algorithm & Computation Theory
- Introduction to Algorithms (Cormen et al.)
- Randomized Algorithms (Motwani & Raghavan)
- Approximation Algorithms (Vazirani)
- Parameterized Algorithms (Cygan et al.)
- Introduction to the Theory of Computation (Sipser)
- Computational Complexity: A Modern Approach (Arora & Barak)


## Some Math Backgrounds

### Analysis
- Rudin series & Stein series


## For Math Geeks
Miscellaneous topics, which I will cover later.

### Textbook
- Topology for Computing (Zomorodian)
- Methods of Information Geometry (Amari & Nagaoka)
- Algebraic Geometry and Statistical Learning Theory (Watanabe)
