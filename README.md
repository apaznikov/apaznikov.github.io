# Alexey Paznikov

![Alexey Paznikov](img/Alexey-Paznikov.jpg){width=300px}

SOFTWARE ENGINEER · RESEARCH SCIENTIST · ASSOCIATE PROFESSOR

- ✉️ apaznikov [at] gmail.com
- 🌐 [GitHub](https://github.com/apaznikov)
- 📌 [LinkedIn](https://www.linkedin.com/in/apaznikov/)

## Navigation
- [Education](#education)
- [Research Interests and Hard Skills](#research-interests-and-hard-skills)
- [Soft Skills](#soft-skills)
- [Experience](#experience)
  - [Saint Petersburg Electrotechnical University “LETI”](#saint-petersburg-electrotechnical-university-leti)
  - [Huawei](#huawei)
  - [Rzhanov Institute of Semiconductor Physics Siberian Branch of Russian Academy of Sciences](#rzhanov-institute-of-semiconductor-physics-siberian-branch-of-russian-academy-of-sciences)
  - [Siberian State University of Telecommunications and Information Sciences](#siberian-state-university-of-telecommunications-and-information-sciences)
  - [Intel Corporation](#intel-corporation)
- [Honors & Awards](#honors--awards)
- [Selected Publications](#selected-publications)
  - [Journal Articles](#journal-articles)
  - [Conference Proceedings](#conference-proceedings)
- [Program Committees & Journal Editorial Boards](#program-committees--journal-editorial-boards)
- [Research Grants](#research-grants)
- [Attended Schools and Workshops](#attended-schools-and-workshops)

## Education

**Siberian State University of Telecommunications and Information Sciences**  
Novosibirsk, Russia  
*Ph.D. in Computer Science*  
2010-2013

- Thesis: [Functioning Organization Algorithms of Multicluster Hierarchical Computer Systems](cpct.sibsutis.ru/~apaznikov/uploads/Main/paznikov-thesis.pdf) (Supervisors: Corresponding Member of RAS Prof. V.G. Khoroshevsky, M.G. Kurnosov)
- [Abstract (in Russian)](cpct.sibsutis.ru/~apaznikov/uploads/Main/paznikov-autoref.pdf)

**Siberian State University of Telecommunications and Information Sciences**  
Novosibirsk, Russia  
*M.S. in Computer Science*  
2005-2010

## Research Interests and Hard Skills

- Performance engineering
  - Microarchitecture-aware Code Optimization
  - Data Layout Optimization (cache memory optimization)
  - Code Layout Optimization
  - SIMD-instructions (Vectorization)
  - IR Analysis and Transformation
  - LLVM, Source-to-source Transformation (Clang), Profiling/Instrumentation

- HPC
  - MPI, Task Mapping, Collective Operations
  - One-sided Communications (MPI RMA)
  - Hybrid Computing Models (MPI+threads, MPI+shared memory)
  - Distributed Data Structures
  - Computer Cluster Administration

- Multithreading
  - Scalable Locks
  - Concurrent Data Structures (Lock-free, Relaxed, Persistent)
  - Transactional Memory
  - Non-volatile Memory
  - OpenMP

- Other Interests
  - PGAS Languages
  - CUDA
  - Machine Learning
  - Cloud Computing
  - GNU/Linux

## Experience

### Saint Petersburg Electrotechnical University “LETI”

**ASSOCIATE PROFESSOR & SENIOR RESEARCHER**  
2016-2023

- Teaching courses: Parallel Programming, Computer Systems, Performance Engineering (Compiler Optimization).
- Development LLVM transformation passes for data layout transformations (structure splitting/peeling, field reordering) and profiling tools.
- Models and algorithms for cache-aware data layout optimization.
- Development of efficient collectives for MPI in Remote Memory Access (RMA) model. [GitHub](https://github.com/apaznikov/rmacoll)
- Development of scalable relaxed distributed data structures for distributed-memory systems [GitHub](https://github.com/apaznikov/mpi-relaxed)
- Designing scalable locks based on delegation of critical sections’ execution technique. [Bitbucket](https://bitbucket.org/apaznikov/rcl)
- Development of scalable concurrent algorithms and data structures. Study of the performance of atomic operations.
- Supervising undergraduate and graduate students (more than 30 bachelor/master students, 6 PhD students) and mentoring international interns.

### Huawei

**SENIOR RESEARCH ENGINEER (PART-TIME CONSULTANT)**  
Mar 2021-Nov 2021

- Designing algorithms for data layout optimization.
- LLVM-based source-code static analysis.

### Rzhanov Institute of Semiconductor Physics Siberian Branch of Russian Academy of Sciences

**RESEARCH SCIENTIST**  
2011-2018

- Optimizing mapping MPI-programs to geographically-distributed computer systems (MPIGridMap project). [Link](cpct.sibsutis.ru/~apaznikov/index.php?n=Research.Mpigridmap)
- Decentralized scheduling software suite for multiclusters and computational Grids (GBroker project). [Link](gbroker.cpct.sibsutis.ru)
- Implementation of collective operations for distributed arrays in Cray Chapel language (PGAS model) and development of Cray Chapel profiling tools. [Bitbucket](https://bitbucket.org/apaznikov/chapel)

### Siberian State University of Telecommunications and Information Sciences

**ASSOCIATE PROFESSOR**  
2009-2016

- Teaching courses: Parallel Computing Technologies (multithreading and distributed computing), Theory of Distributed Computer Systems Functioning Organization, Object-oriented Programming (C++).
- Designing and administration of computer clusters. Multicluster computer system located in SibSUTIS and ISP SB RAS.
- Supervising undergraduate students (thesis and research projects).

### Intel Corporation

**SOFTWARE ENGINEER (INTERN)**  
June 2011-August 2011

- Investigation of Array Building Blocks (Intel ArBB), Intel Cilk Plus, and Intel Threading Building Blocks (Intel TBB) interoperability.

## Honors & Awards

- Best Section Oral Presentation Award, The XIII Majorov International Conference on Software Engineering and Computer Systems, 2021
- Best Paper Award, V Russian Conference ”Supercomputer Technologies”, 2018
- Best young researcher in higher education, 2014 (Novosibirsk)
- Finalist, Novosibirsk City Hall Research Grant, 2014
- Finalist, Award on Youth Science and Innovation Competition U.M.N.I.K., 2012
- Best Paper Award, II Russian Conference ”Supercomputer Technologies”, 2011
- II Award, XLIX International Scientific Student Conference NSU, Novosibirsk, 2011
- III Award, XLVI International Scientific Student Conference NSU, Novosibirsk, 2008

## Selected Publications

### Journal Articles

1. PaznikovA.A. Binomial Tree Broadcast in Remote Memory Access Model // Tomsk state university journal of control and computer science, 2023 (accepted)
1. Heidari S. M., PaznikovA.A. Multipurpose Cloud-Based Compiler Based on Microservice Architecture and Container Orchestration // Symmetry. – 2022. – V. 14. – No. 9. – P. 1818.
1. Kholod I., Rukavitsyn A., Paznikov A., Gorlatch S. Parallelization of the self-organized maps algorithm for federated learning on distributed sources // The Journal of Supercomputing. – 2020. – P. 1-17.
1. Paznikov A. Distributed relaxed queue in Remote Memory Access Model // Tomsk state university journal of control and computer science, 2020. – N. 50 – pp. 97-105 (in Russian).
1. Goncharenko E.A., Paznikov A. Analysis of the efficiency of atomic operations in multi-core shared-memory computer systems // Tomsk state university journal of control and computer science, 2020. – N. 51 – pp. 102-110 (in Russian).
1.	Paznikov A., Shichkina Y. Algorithms for Optimization of Processor and Memory Affinity for Remote Core Locking Synchronization in Multithreaded Applications // Information. – 2018. – Vol. 9 – N. 1 – pp. 1-12.
1.	Paznikov A. Optimization of Remote Core Locking Synchronization in Multithreaded Programs for Multicore Computer Systems // Information Technology in Industry. – 2018. – Vol. 6 – N. 2 – pp. 7-12.
1.	Smirnov V., Omelnichenko A., Paznikov A. Thread-safe Associative Arrays Based on Transactional Memory // Proceedings of Saint Petersburg Electrotechnical University. – 2018. – Vol. 1 – pp. 12-18 (in Russian).
1.	Zharikov V., Paznikov A. Adaptive Algorithm of Barrier Synchronization in the MPI Standard on Based on LogP Parallel Computing Model // Proceedings of Saint Petersburg Electrotechnical University. – 2018. – Vol. 4 – pp. 26-32 (in Russian).
1.	AnenkovA., PaznikovA.AlgorithmsforOptimizationofConcurrentPoolBasedonDiffractingTreesforMulticoreComputerSystems // Tomsk state university journal of control and computer science, 2017. - No. 39. - pp. 73-84 (in Russian).
1.	Paznikov A. Optimization of Remote Core Locking synchronization // Tomsk state university journal of control and computer science, 2017. – N. 38 – pp. 52-58 (in Russian).
1.	Paznikov A., Kurnosov M., Kupriyanov M. Multilevel Algorithms of Mapping Parallel MPI-programs to Computational Clusters // Problemy informatiki. - 2015. - No. 1. - pp. 4-17 (in Russian).
1.	Kulagin I., Paznikov A., Kurnosov M. Heuristic Algorithms of Communication Optimization in Parallel PGAS-Programs // Vestnik SibSUTIS. - 2014. - No. 3. - pp. 52-66 (in Russian).
1.	Polyakov A., Moldovanova O., Paznikov A., Kurnosov M., Mamoilenko S., Efimov A. Algorithms of Fault-tolerant Resources Management of Geographically Distributed Computer Systems // Vestnik SibSUTIS. - 2014. - No. 4. - pp. 11-29 (in Russian).
1.	Kurnosov M., PaznikovA. Heuristic Algorithms of Mapping MPI-programs onto Multicluster Computer and GRID systems // Numerical Methods and Programming. - 2013. - No. 14. - pp. 1-10 (in Russian).
1.	Kurnosov M., Paznikov A. Decentralized Scheduling Algorithms of Geographically-distributed Computer Systems // Vestnik TSU. 2012. - No. 1 (18). - pp. 133-143 (in Russian).
1.	Kurnosov M., Paznikov A. Modelling of Decentralized Algorithms for Scheduling Jobs in Grid Systems // Problemy Informatiki. 2012. - No. 2. - pp. 45-54 (in Russian).
1.	Khoroshevsky V., Kurnosov M., Mamoilenko S., Pavsky K., Efimov A., Paznikov A., Perishkova E. Scalable Software Tools for Parallel Multiprogramming in Distributed Computer Systems // Vestnik SibSUTIS. - 2011. - No. 4. - pp. 3-18 (in Russian).
1.	Kurnosov M., Paznikov A. Algorithms and Software Tools for Decentralized Scheduling of MPI Programs in Multicluster Computer Systems // Vestnik TSU. - 2011. - No. 3 (16). - pp. 78-85 (in Russian).
1.	KurnosovM., PaznikovA.DecentralizedServiceofParallelTaskStreamsinGeographically-distributedComputerSystems//Vestnik SibSUTIS. - 2010. - No. 2 (10). - pp. 79-86 (in Russian).

### Conference Proceedings

1. Paznikov A.A., Burachenko A.V., Abuelsoud M.M. Decentralized lock-free distributed queue in MPI Remote Memory Access model // Journal of Physics: Conference Series, 2023 (accepted).
1. PaznikovA.,KurnosovM.MPItaskmappingformulti-clusterHPCsystems//JournalofPhysics: ConferenceSeries, 2023(accepted).
1.	Mohammed O. T., Paznikov A. A., Gorlatch S. Accelerating Neural Network Training Process on Multi-Core Machine Using OpenMP //2022 III International Conference on Neural Networks and Neurotechnologies (NeuroNT). – IEEE, 2022. – С. 7-11.
1.	Kholod I., Rukavitsyn A., Paznikov A., Gorlatch S. Parallelization of the self-organized maps algorithm for federated learning on distributed sources // The Journal of Supercomputing. – 2021. – V. 77. – №. 6. – P. 6197-6213.
1.	Mohammed O. T., Heidari M. S., Paznikov A. A. Optimizing regular computations based on neural networks and Graph Traversal // Procedia Computer Science. – 2021. – V. 186. – P. 337-343.
1.	Paznikov A. A., Kupriyanov M. S. Adaptive MPI collective operations based on evaluations in LogP model // Procedia Computer Science. – 2021. – V. 186. – P. 323-330.
1.	Mohammed O. T., Heidari M. S., Paznikov A. A. Mathematical Computations Based on a Pre-trained AI Model and Graph Traversal //2020 9th Mediterranean Conf. on Embedded Computing (MECO). – IEEE, 2020. – P. 1-4.
1.	Paznikov A. A., Gurin A. V., Kupriyanov M. S. Implementation in Actor Model of Leaderless Decentralized Atomic Broadcast //2020 9th Mediterranean Conf. on Embedded Computing (MECO). – IEEE, 2020. – P. 1-4.
1.	Anenkov A. D., Paznikov A. A., Kupriyanov M. S. Scalable Concurrent Pools Based on Diffracting Trees // XXIII Int. Conf. on Soft Computing and Measurements (SCM). – IEEE, 2020. – P. 62-65.
1.	Mohammed O. T. Heidari M. S., Paznikov A. A., Kupriyanov M. S. Towards Optimization of Big Numbers Computation through an AI Pre-trained Model and Graph Traversal //2020 XXIII International Conference on Soft Computing and Measurements (SCM). – IEEE, 2020. – P. 153-156.
1.	Goncharenko E.A., Paznikov A.A., Tabakov A.V. Evaluating the performance of atomic operations on modern multicore systems // Journal of Physics: Conference Series, 2019 – V. 1399. – pp. 1-8.
1.	Tabakov A.V., Paznikov A.A. Using relaxed concurrent data structures for contention minimization in multithreaded MPI programs // Journal of Physics: Conference Series, 2019 – V. 1399. – pp. 1-5.
1.	Paznikov A.A., Smirnov V.A., Omelnichenko A.R. Towards Efficient Implementation of Concurrent Hash Tables and Search Trees Based on Software Transactional Memory // Int. Multi-Conf. on Industrial Engineering and Modern Technologies, 2019. – pp. 1-5.
1.	PaznikovA., Anenkov A. Implementation and Analysis of Distributed Relaxed Concurrent Queues in Remote Memory Access Model // 13th Int. Symposium “Intelligent Systems – 2018” (INTELS’18). Procedia Computer Science, 2019. – Vol. 150. – pp. 654-662.
1.	Tabakov A., Paznikov A. Algorithms for Optimization of Relaxed Concurrent Priority Queues in Multicore Systems // Int. Conf. of Russian Young Researchers in Electrical and Electronic Engineering (EIConRus), 2019. – P. 360-365
1.	Goncharenko E. A., Paznikov A. A. Analysis of the Influence of Cache Coherence Mechanism Performance on Atomic Operations in Multicore Computing Systems // XXII Int. Conf. on Soft Computing and Measurements (SCM). – 2019. – P. 111-114.
1.	Tabakov A. V., Paznikov A. A. Modelling of Parallel Threads Synchronization in Hybrid MPI+ Threads Programs // XXII Int. Conf. on Soft Computing and Measurements (SCM). – 2019. – P. 197-199.
1.	AnenkovA., PaznikovA., KurnosovM.Algorithmsforaccesslocalizationtoobjectsofscalableconcurrentpoolsbasedondiffracting trees in multicore computer systems // 14th Int. scientific-technical conf. on Actual Problems of Electronic Instrument Engineering (APEIE-2018), 2018. – Vol. 1, Part 4. – pp. 374-380.
1.	Pavskiy V., Pavskiy K., Paznikov A. Mathematical models and calculation of reliability indices of scalable distributed computer systems under full restoration // 14th Int. scientific-technical conf. on Actual Problems of Electronic Instrument Engineering (APEIE2018), 2018. – Vol. 1, Part 4. – pp. 502-505.
1.	Zharikov V., PaznikovA., Pavsky K., Pavsky V. Adaptive Barrier Algorithm in MPI Based on Analytical Evaluations for Communication Time in the LogP Model of Parallel Computation // Int. Multi-conf. on Industrial Engineering and Modern Technologies (Far East Con-2018), 2018. – pp. 1-5.
1.	Paznikov A., Pavsky K., Pavsky V., Kupriyanov M. Simulation of the algorithms for optimization of remote core locking method for multicore computer systems // II Int. Conf. on Control in Technical Systems (CTS), 2017. – pp. 51-54.
1.	Paznikov A., Kurnosov M., Kupriyanov M. Algorithms of collective operations for distributed arrays in partitioned global address space // II Int. Conf. on Control in Technical Systems (CTS), 2017. – pp. 5-8.
1.	Paznikov A. Optimization of Thread Affinity and Memory Affinity for Remote Core Locking Synchronization in Multithreaded Programs for Multicore Computer Systems // Vibroengineering Procedia. – 2017. – Vol. 12. – pp. 213-218.
1.	Pavsky V., Pavsky K., Paznikov A., Kupriyanov M. Mathematical Models and the Effectiveness of Functioning of Scalable Distributed Computer Systems // XX Int. Conf. on Soft Computing and Measurements (SCM). – 2017. – pp. 496-499.
1.	Paznikov A. Optimization of Remote Core Locking Synchronization in Multithreaded Programs for Multicore Computer Systems. Proc. of the 2nd Russian-Pacific Conference on Computer Technology and Applications, 2017 (accepted for publication).
1.	Paznikov A. Optimization of Remote Core Locking synchronization // XI Int. Conf. on Computer-aided Technologies in Applied Mathematics. - 2016. - pp. 80-81 (in Russian).
1.	Kulagin I., Paznikov A., Kurnosov M. Heuristic Algorithms for Optimizing Array Operations in Parallel PGAS-programs // 13th Int. Conf. ”Parallel Computing Technologies” (PaCT-2015). - 2015. - Lecture Notes in Computer Science (LNCS), Vol. 9251. - pp. 405-409.
1.	Paznikov A. Efficiency Analysis Tools for Cray Chapel programs // Proc. of the X Russian Conf. ”New Information Technologies of Complex Structures Research”. - 2014. - pp. 10-11 (in Russian).
1.	Kurnosov M., Paznikov A. Efficiency analysis of decentralized grid scheduling with job migration and replication // ACM Int. Conf. on Ubiquitous Information Management and Communication (IMCOM/ICUIMC). - 2013. - pp. 1-7.
1.	Paznikov A. Block Reduction Algorithm for Cray Chapel language // Int. Conf. of Young Scientists ”Current Problems of Applied Mathematics and Computer Science”. - 2012. - pp. 64 (in Russian).
1.	Kurnosov M., Paznikov A. Decentralized Resource Management Algorithms in Distributed Grid systems // Int. Conf. ”Mathematical and Informational Technologies” (MIT-2011). - 2011. - pp. 1-6 (in Russian).
1.	Kurnosov M., Paznikov A. Decentralized Parallel Programs Scheduling in Distributed Computer Systems // IX Int. Conf. ”High Performance Parallel Computations on Cluster Systems”. - 2009. - pp. 260-265 (in Russian).
1.	Kurnosov M., Paznikov A. Optimization of MPI Processes Mapping into Computer Cluster // Proc. of the VII Int. Conf. ”High Performance Parallel Computations on Cluster Systems”. - 2007. - pp. 218-225 (in Russian).

## Program Committees & Journal Editorial Boards
- Guest Editor, MDPI ”Symmetry”. Special Issue ”Symmetry in Distributed Algorithms and Parallel Algorithms and Their Applications” (2021-2023, Basel, Switzerland)
- Program Committee Member, The XIII Majorov International Conference on Software Engineering (2021, Russia)
- Invited Expert, The Third Summer School on Practice and Theory of Distributed Computing (2020, Russia)
- Program Committee Member, The Majorov International Conference on Software Engineering 
and Computer Systems (2020, Russia)
- Organizer and Committee Member, 13th International Symposium ”Intelligent Systems – 2018” (2018, Russia)

## Research Grants
- Principal investigator, Adaptive data layout optimization algorithms and software, Huawei Technologies (2021-2023)
- Principal investigator, Grant 22-21-00686. Algorithms and software for optimizing parallel program execution in remote memory access model, Russian Science Foundation (2022-2023)
- Principal investigator, Grant of the Vladimir Potanin Foundation for Master’s Degree Teachers, The Vladimir Potanin Foundation (2020-2021)
- Principal investigator, Grant 19-07-00784. Design of methods, algorithms, and software for scalable synchronization for multiprocessor computer systems, Russian Foundation for Basic Research (2019-2021)
- Principal investigator, Project SP-4971.2018.5. Development of Scalable Tools for Synchronization in Distributed Computer Systems, Russian Federation President Council on Grants for governmental support for young Russian scientists (2018-2020)
- Principal investigator, 1) Tools for optimization of communications in MPI-programs, 2) Scalable tools for thread synchronization on multiarchitectural hierarchical computer systems, Government of Saint Petersburg (2017, 2018)
- Principal investigator, Grant 12-07-31016. Algorithms and Software for Optimizing of Parallel Programs’ Execution in Exascale Grid Systems, Russian Foundation for Basic Research (2012-2013)
- Principal investigator, Award on Youth Science and Innovation Competition U.M.N.I.K., The Foundation for Assistance to Small Innovative Enterprises in Science and Technology, Russia (2012-2014)

## Attended Schools and Workshops

- The Third Summer School on Practice and Theory of Distributed Computing + Concurrent and distributed computing conference (Hydra), Moscow, 2020
- The Second Summer School on Practice and Theory of Distributed Computing, Saint Petersburg, 2019
- Summer School on Practice and Theory of Concurrent Computing, ITMO University, 2017
- Intel Summer School, Intel Corporation, 2011
- Intel Parallel Programming Professional (Intel Compilers), Intel Corporation, 2011
- II British-Russian Seminar of Streaming Data Processing and Programming, ICT SB RAS, 2011
- German-Russian School on Parallel Programming using High-Performance Computer Systems, The High Performance Computing Center Stuttgart (HLRS), 2007-2011