Formal Methods Seminar, Fall'22
===============================

Guiding theme: weak consistency

#### Schedule

We meet Tuesdays, 11am, in room 527, 60FA.

| Date | Speaker | Topic |
| ---- | ------- | ----- |
| Sep 8  |       | Organizational Meeting
| Sep 15 | Chaitanya Agarwal | **Talk**  PAC Statistical Model Checking for Markov Decision Processes and Stochastic Games
| Sep 22 | Adam Chen (Stevens)      | **Talk** Veracity: Declarative Multicore Programming with Commutativity
| Sep 29 | Stefan Leue (Uni. of Konstanz) | **Talk** Checking Legal Contracts and Repairing Neural Networks
| Oct 6  | Sebastian Wolff      | A.1 Sequential consistency
| Oct 13 | Zach Destefano      | A.2 TSO: Modeling - TSO intro
| Oct 20 | Nisarg Patel      | A.2 TSO: Modeling - TSO characterization
| Oct 27 | Jacob Salzberg     | A.2 TSO: Verification
| Nov 3  | Daniel Feldan      | A.4 Axiomatic models
| Nov 10 |       |
| Nov 17 |       |
| Nov 24 |       | Thanksgiving
| Dec 1  |       | 
| Dec 8  |       | 
| Dec 15 | Kishor Jothimurugan (UPenn)  | **Talk** Specification-guided Reinforcement Learning



Topics
------

### A. Weak Memory Models

  - Nagarajan, Sorin, Hill, Wood:
    *Introduction to Consistency and Coherence*.
    Chapter 1 of *A Primer on Memory Consistency and Cache Coherence*.
    Springer, 2020.  
    [[PDF]](https://link.springer.com/content/pdf/10.1007/978-3-031-01764-3_1.pdf)

#### A.1. Sequential Consistency (SC)

  - Lamport:
    *How to Make a Multiprocessor Computer That Correctly Executes Multiprocess Progranm*.
    IEEE Transactions on Computers, 1979.  
    [[PDF]](https://www.microsoft.com/en-us/research/uploads/prod/2016/12/How-to-Make-a-Multiprocessor-Computer-That-Correctly-Executes-Multiprocess-Programs.pdf)

  - Nagarajan, Sorin, Hill, Wood:
    *Memory Consistency Motivation and Sequential Consistency*.
    Chapter 3 of *A Primer on Memory Consistency and Cache Coherence*.
    Springer, 2020.  
    [[PDF]](https://link.springer.com/content/pdf/10.1007/978-3-031-01764-3_3.pdf)

  - Lamport:
    *Time, Clocks, and the Ordering of Events in a Distributed System*.
    Communications of the ACM, 1978.  
    [[PDF]](https://dl.acm.org/doi/pdf/10.1145/359545.359563)

#### A.2. Total Store Ordering (TSO)

##### Modelling

  - Nagarajan, Sorin, Hill, Wood:
    *Total Store Order and the x86 Memory Model*.
    Chapter 4 of *A Primer on Memory Consistency and Cache Coherence*.
    Springer, 2020.  
    [[PDF]](https://link.springer.com/content/pdf/10.1007/978-3-031-01764-3_4.pdf)

  - Adve, Hill:
    *A Unified Formalization of Four Shared-Memory Models*.
    IEEE Transactions on Parallel and Distributed Systems, 1993.  
    [[PDF]](https://pages.cs.wisc.edu/~markhill/papers/topds93_drf1.pdf)

  - Owens:
    *Reasoning about the Implementation of Concurrency Abstractions on x86-TSO*.
    ECOOP, 2010.  
    [[PDF]](https://link.springer.com/content/pdf/10.1007/978-3-642-14107-2_23.pdf)

  - Sewell, Sarkar, Owens, Zappa Nardelli, Myreen:
    *x86-TSO: A Rigorous and Usable Programmer’s Model for x86 Multiprocessors*.  
    [[PDF]](https://dl.acm.org/doi/pdf/10.1145/1785414.1785443)

##### Verification

  - Atig, Bouajjani, Burckhardt, Musuvathi:
    *On the Verification Problem for Weak Memory Models*.
    POPL, 2010.  
    [[PDF]](https://dl.acm.org/doi/pdf/10.1145/1707801.1706303)

  - Bouajjani, Meyer, Möhlmann:
    *Deciding Robustness against Total Store Ordering*.
    ICALP, 2011.  
    [[PDF]](https://link.springer.com/content/pdf/10.1007/978-3-642-22012-8_34.pdf)

  - Bouajjani, Derevenetc, Meyer:
    *Checking and Enforcing Robustness against TSO*.
    ESOP, 2013.  
    [[PDF]](https://link.springer.com/content/pdf/10.1007/978-3-642-37036-6_29.pdf)


#### A.3. C11

TBA.

#### A.4. Axiomatic Memory Models

  - Alglave, Maranget, Tautschnig:
    *Herding cats: Modelling, Simulation, Testing, and Data-mining for Weak Memory.*
    TOPLAS 2013.
    [[PDF]](http://www0.cs.ucl.ac.uk/staff/j.alglave/papers/toplas14.pdf)
 
  - Alglave, Maranget, Sarkar, Sewell:
    *Fences in Weak Memory Models.*
    CAV 2010.
    [[PDF]](http://www0.cs.ucl.ac.uk/staff/J.Alglave/papers/cav10.pdf)
    
  - Alglave.
    *A formal hierarchy of weak memory models.*
    FMSD 2012.
    [[PDF]](http://www0.cs.ucl.ac.uk/staff/J.Alglave/papers/fmsd12-41-2.pdf)
    

TBA.

### B.  Non-volatile Memory

TBA.

### C. Relaxed Consistency in Distributed Systems

TBA.
