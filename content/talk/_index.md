---
title: 

# Listing view
view: compact

# Optional header image (relative to `assets/media/` folder).
banner:
  caption: '<a href=https://modvic.com>Bruce Rosenbaum</a> and Jim Su'
  image: 'Redo.jpg'
---

# Invited Talks
| <h3>Speaker</h3> | <h3>Affiliation</h3> |
| ------- | ----------- |
| [Matteo Lostaglio](#matteo-lostaglio) | PsiQuantum|
| [Marcos Rigol](#marcos-rigol) | Penn State University|


# Contributed Talks

| <h3>Speaker</h3> | <h3>Affiliation</h3> |
| ------- | ----------- |
| [Stefan Aimet](#stefan-aimet) | Freie Universität Berlin|
| [Lindsay Bassman Oftelie](#lindsay-bassman-oftelie) | CNR-Pisa|
| [Felix Binder](#felix-binder) | Trinity College Dublin|
| [Tanmoy Biswas](#tanmoy-biswas) | Los Alamos National Laboratory, Los Alamos|
| [Federico Cerisola](#federico-cerisola) | University of Exeter|
| [Guilherme de Sousa](#guilherme-de-sousa) | University of Maryland|
| [Paul Erker](#paul-erker) | Atominstitut (TU Wien) & IQOQI Vienna (ÖAW)|
| [David Gelbwaser-Klimovsky](#david-gelbwaser-klimovsky) | Technion|
| [Santiago Hernandez Gomez](#santiago-hernandez-gomez) | Istituto Nazionale di Ottica del Consiglio Nazionale delle Ricerche (CNR-INO)|
| [Michal Horodecki](#michal-horodecki) | International Centre for Theory of Quantum Information|
| [Karen Hovhannisyan](#karen-hovhannisyan) | University of Potsdam|
| [Lata Kharkwal Joshi](#lata-kharkwal-joshi) | SISSA Trieste, Italy|
| [Philip Kurian](#philip-kurian) | Quantum Biology Laboratory, Howard University|
| [Patryk Lipka-Bartosik](#patryk-lipka-bartosik) | University of Geneva|
| [Florian Meier](#florian-meier) | Atominstitut, TU Wien, Austria|
| [Harry Miller](#harry-miller) | University of Manchester|
| [Anthony Munson](#anthony-munson) | University of Maryland, College Park|
| [Zakaria Mzaouali](#zakaria-mzaouali) | Institute of Theoretical and Applied Informatics, Polish Academy of Sciences|
| [Laetitia Paula Bettmann](#laetitia-paula-bettmann) | Trinity College Dublin|
| [Dario Poletti](#dario-poletti) | Singapore University of Technology and Design|
| [Haitao Quan](#haitao-quan) | Peking University|
| [Alberto Rolandi ](#alberto-rolandi-) | University of Geneva|
| [Huang Ruo Cheng](#huang-ruo-cheng) | Nanyang Technological University|
| [Valerio Scarani](#valerio-scarani) | CQT, National University of Singapore|
| [Finn Schmolke](#finn-schmolke) | Institut für theoretische Physik I, Universität Stuttgart|
| [Oles Shtanko](#oles-shtanko) | IBM Quantum|
| [Janine Splettstoesser](#janine-splettstoesser) | Chalmers University of Technology|
| [Amit Vikram](#amit-vikram) | JQI and Dept. of Physics, University of Maryland, College Park|
| [Amanda Younes](#amanda-younes) | University of California, Los Angeles|
| [Maciej Zgirski](#maciej-zgirski) | Institute of Physics, PAN, Warsaw|


# Titles and Abstracts

### Stefan Aimet
*Freie Universität Berlin*

#### Experimentally probing Landauer's principle in the quantum many-body regime
Landauer's principle establishes a bridge between information theory and thermodynamics, by fundamentally relating the erasure of a single bit of information to a minimum amount of heat dissipation. While extensively explored in the context of small quantum systems, extending this principle to complex quantum many-body systems is essential for understanding equilibration, with thermodynamics emerging as an effective coarse-grained description. This talk aims to present the first experimental measurement of Landauer’s principle in a quantum field simulator consisting of two coupled one-dimensional ultra-cold Bose gases. We characterized entropy production along a global mass quench, decomposing it into its information-theoretic contributions using mutual information and relative entropy. Additionally, we may briefly discuss theoretical work on the quantum thermodynamics of local quantum quenches in the many-body domain.

---

### Lindsay Bassman Oftelie
*CNR-Pisa*

#### Dynamic Cooling on Contemporary Quantum Computers
A key hurdle for the success of quantum computers is the ability to prepare pure (i.e., cold) qubits. Dynamic cooling, whereby a target qubit is cooled at the expense of heating up $N-1$ further identical qubits by means of a global unitary operation, was proposed as a means of effective cooling over two decades ago.  A standard back-of-the-envelope high temperature estimate establishes that the target qubit temperature can only be dynamically cooled by at most a factor of $1/\sqrt{N}$.  Here, we provide the exact expression for the smallest temperature to which the target qubit can be cooled and reveal that there is a crossover from the high initial temperature regime where the scaling is in fact $1/\sqrt{N}$ to a low initial temperature regime where a much faster scaling of $1/N$ occurs. This slow $1/\sqrt{N}$ scaling, relevant for early high-temperature NMR quantum computers, is the reason dynamic cooling was initially dismissed as ineffectual; the fact that current low-temperature quantum computers fall in the fast $1/N$ scaling regime reinstates the appeal of dynamic cooling. We further show that the associated work cost of cooling is exponentially more advantageous in the low temperature regime.  Finally, we explore the complexity, in terms of quantum circuits, of dynamic cooling and discuss schemes for implementation on near-term quantum computers. We examine the effect of hardware noise on cooling and conclude that it is a promising technique for near-future quantum computers with reduced levels of noise.

---

### Felix Binder
*Trinity College Dublin*

#### Thermodynamic Overfitting and Generalization: Energetic Limits on Predictive Complexity
Efficiently harvesting thermodynamic resources requires a precise understanding of their structure. This becomes explicit through the lens of information engines---thermodynamic engines that use information as fuel. Maximizing the work harvested using available information is a form of physically-instantiated machine learning that drives information engines to develop complex predictive memory to store an environment's temporal correlations.  We show that an information engine's complex predictive memory poses both energetic benefits and risks. While increasing memory facilitates detection of hidden patterns in an environment, it also opens the possibility of thermodynamic overfitting, where the engine dissipates additional energy in testing. To address overfitting, we introduce thermodynamic regularizers that incur a cost to engine complexity in training due to the physical constraints on the information engine. We demonstrate that regularized thermodynamic machine learning generalizes effectively. In particular, the physical constraints from which regularizers are derived improve the performance of learned predictive models. This suggests that the laws of physics jointly create the conditions for emergent complexity and predictive intelligence.

---

### Tanmoy Biswas
*Los Alamos National Laboratory, Los Alamos*

#### Catalytic enhancement in the performance of the microscopic two-stroke heat engine
We consider a model of a heat engine operating in the microscopic regime: the two-stroke engine. It produces work and exchanges heat in two discrete strokes that are separated in time. The engine consists of two d-level systems initialized in thermal states at two distinct temperatures. Additionally, an auxiliary non-equilibrium system called catalyst may be incorporated into the engine, provided the state of the catalyst remains unchanged after the completion of a thermodynamic cycle. This ensures that the work produced arises solely from the temperature difference. Upon establishing the rigorous thermodynamic framework, we characterize two-fold improvement stemming from the inclusion of a catalyst. Firstly, we show that the presence of a catalyst allows for surpassing the optimal efficiency of two-stroke heat engines which are not assisted by a catalyst. In particular, we prove that the optimal efficiency for two-stroke heat engine consisting of two-level systems is given

---

### Alec Boyd
*Trinity College Dublin*

#### Thermodynamic Overfitting and Generalization: Energetic Limits on Predictive Complexity


---

### Federico Cerisola
*University of Exeter*

#### Exploring nanoscale thermodynamics on suspended carbon nanotubes
State of the art nanoscale electromechanical devices provide exciting platforms to explore and test thermodynamics at small scales, where fluctuations dominate and quantum effects become relevant. In particular, suspended carbon nanotubes (CNTs) are a very rich and promising platform which features a wide range of phenomena, from quantised electron transport through quantum dots, to spin qubits and mechanical motion. In this talk, I will discuss recent experiments where we have measured ultra-strong coupling between the charge transport along the CNT and the mechanical motion. Furthermore, through precise measurement of the quantum dot’s population and CNT displacement, we estimate the energy and entropy of the different degrees of freedom. In this way, we explore the entropy to energy conversion between the charge state of the dot and the mechanical displacement. A thorough understanding of these exchanges naturally leads to a generalised formulation of the Landauer bound that takes into account the non-equilibrium nature of these devices and strong coupling to the reservoirs. Moreover, the coupling between mechanics and electron transport can lead to non-equilibrium steady states that can exhibit long lived self-sustained oscillations. Finally, I will discuss the first observation of coupling between a spin qubit and mechanical motion of the CNT. We have further developed a detailed theoretical model to understand the origin and nature of this coupling and estimate its strength. The observation of the spin-mechanics coupling further opens the doors to a new range of experimental tests of thermodynamics involving energetic coherences.

---

### Guilherme de Sousa
*University of Maryland*

#### Modeling continuous quantum feedback using a general signal processing filter
To manipulate quantum systems efficiently, one needs to make measurements of quantum observables, collect the measurement outcome, and act accordingly, providing feedback. The typical procedure to perform a quantum measurement is understood using projective measurements that destroy all quantum coherence and leave the state in a particular eigenstate of the measured operator. This process is invasive as it destroys the quantumness of the state and can lead to a quantum Zeno effect in the limit of quick and repeated measurements.

---

### Paul Erker
*Atominstitut (TU Wien) & IQOQI Vienna (ÖAW)*

#### Quantum Coding with Finite Thermodynamic Resources
Quantum direct coding or Schumacher compression generalised the ideas of Shannon theory, gave an operational meaning to the von Neumann entropy and established the term qubit. But remembering that information processing is carried out by physical processes prompts one to wonder what thermodynamic resources are required to compress quantum information and how they constrain one's ability to perform this task. That is, if Alice and Bob only have access to thermal quantum states and clocks with finite accuracy, how well can they measure, encode and decode pure quantum state messages? In this work we examine these questions by modelling Alice's typical measurement as a unitary involving a measurement probe, investigating imperfect timekeeping on encoding and decoding and considering the role of temperature in Bob's appended qubits. In doing so, we derive fidelity bounds for this protocol involving the correlations Alice can form with their measurement probe, the variance of the clock's ticks and the temperature of Bob's qubits. Finally, we give an insight into the entropy produced by these two agents throughout the compression protocol by relating the resources they use to a quantum thermodynamic cooling protocol.

---

### David Gelbwaser-Klimovsky
*Technion*

#### Thermalization of systems that break detailed balance
Systems that break time-reversal symmetry can break detailed balance at equilibrium (DBE) when the interaction strength with the thermal bath goes beyond the weak coupling limit, as we showed in a recent work (see PRL 131, 040401 (2023)). In this presentation, we show that the lack of DBE influences how the system reaches thermal equilibrium. Instead of the standard exponential decay, thermalization can oscillate when the correct temperature conditions are met. Moreover, we demonstrate that the transition from the exponential to the oscillatory dynamics occurs at a critical temperature where the dynamical matrix has an exceptional point. This point is characterized by the divergences of time scales.

---

### Santiago Hernandez Gomez
*Istituto Nazionale di Ottica del Consiglio Nazionale delle Ricerche (CNR-INO)*

#### Interferometry of quantum correlation functions and non-classical work distribution
Kirkwood-Dirac quasiprobabilities are directly connected to the quantum correlation function of two observables measured at two distinct times, and are therefore relevant for fundamental physics and quantum technologies. However, their experimental reconstruction may be challenging when expectation values of incompatible observables are involved. Strategies to reconstruct them using weak values, or combining strong measurements have been used in the past. Here, we use a more direct approach, making use of an interferometric scheme with the help of an auxiliary system, we fully reconstruct the characteristic function of the Kirkwood-Dirac quasiprobability distribution. 
In our experiment, the interferometric scheme is realized on a nitrogen-vacancy center in diamond using the electronic spin as a quantum system and the nuclear spin of the nitrogen as an auxiliary qubit. 
Thus we infer the quasiprobability distribution of the work exerted by the system from the measured characteristic function, and we show the behavior of the first and second moments of work. 
We are also able to study the uncertainty of measuring the Hamiltonian of the system at two times, via the Robertson-Schr{\o}dinger uncertainty relation, for different initial states.

---

### Michal Horodecki
*International Centre for Theory of Quantum Information*

#### On unstructured stochastic thermodynamical processes
Nonreciprocity, arising from the breaking of time-reversal symmetry, has become a fundamental tool in diverse quantum technology applications. It enables directional flow of signals and efficient noise suppression, constituting a key element in the architecture of current quantum information and computing systems.  We explore its potential in optimizing the charging dynamics of a quantum battery. By introducing nonreciprocity through reservoir engineering during the charging process, we induce a directed energy flow from the quantum charger to the battery, resulting in a substantial increase in energy accumulation. Despite local dissipation, the nonreciprocal approach demonstrates a fourfold increase in battery energy compared to conventional charger-battery systems. 
This effect is observed in the stationary limit and remains applicable even in overdamped coupling regimes, eliminating the need for precise temporal control over evolution parameters. Our result can be extended to a chiral network of quantum nodes, serving as a multi-cell quantum battery system to enhance storage capacity. The proposed approach is straightforward to implement using current state-of-the-art quantum circuits, both in photonics and superconducting quantum systems. In a broader context, the concept of nonreciprocal charging has significant implications for sensing, energy capture, and storage technologies or studying quantum thermodynamics. 

---

### Karen Hovhannisyan
*University of Potsdam*

#### Long-time equilibration can determine transient thermality
When two initially thermal many-body systems start to interact strongly, their transient states quickly become non-Gibbsian, even if the systems eventually equilibrate. To see beyond this apparent lack of structure during the transient regime, we use a refined notion of thermality, which we call g-local. A system is g-locally thermal if the states of all its small subsystems are marginals of global thermal states. We numerically demonstrate for two harmonic lattices that whenever the total system equilibrates in the long run, each lattice remains g-locally thermal at all times, including the transient regime. This is true even when the lattices have long-range interactions within them. In all cases, we find that the equilibrium is described by the generalized Gibbs ensemble, with three-dimensional lattices requiring special treatment due to their extended set of conserved charges. We compare our findings with the well-known two-temperature model. While its standard form is not valid beyond weak coupling, we show that at strong coupling it can be partially salvaged by adopting the concept of a g-local temperature.

---

### Lata Kharkwal Joshi
*SISSA Trieste, Italy*

#### Quantum Mpemba effect in a trapped-ion quantum simulator
The non-equilibrium physics of many-body quantum systems harbor various unconventional phenomena. In recent studies on thermalization following quantum quenches on specific states an interesting and puzzling phenomena has emerged -- the quantum Mpemba effect. In this effect, following a quantum quench, an initially tilted ferromagnet restores its symmetry more rapidly when it is farther from a symmetric state compared to when it is closer. In this talk I will present the first experimental evidence of this effect in a trapped-ion quantum simulator. The symmetry breaking and restoration are monitored through entanglement asymmetry, probed via randomized measurements, and postprocessed using the classical shadows technique. Furthermore, a direct comparison between the late time thermal symmetric theoretical state and the experimental state offer direct evidence of subsystem thermalization.

---

### Philip Kurian
*Quantum Biology Laboratory, Howard University*

#### Quantum-enhanced photoprotection in neuroprotein architectures of quantum emitters in thermal environments
Superradiance is the phenomenon of many identical quantum systems absorbing and/or emitting photons collectively at a higher rate than any one system can individually. This phenomenon has been studied analytically in idealized distributions of electronic two-level systems (TLSs), each with a ground and excited state, as well as numerically in realistic photosynthetic nanotubes and cytoskeletal architectures. Superradiant effects are studied here in realistic biological mega-networks of tryptophan (Trp) molecules, which are strongly fluorescent amino acids found in many proteins. Each Trp molecule acts as a chromophore absorbing in the ultraviolet spectrum and can be treated approximately as a TLS, with its $1L_a$ excited singlet state; thus, organized Trp networks can exhibit superradiance. Such networks are found, for example, in microtubules, actin filaments, and amyloid fibrils. Microtubules and actin filaments are spiral-cylindrical protein polymers that play significant biological roles as primary constituents of the eukaryotic cytoskeleton, while amyloid fibrils have been targeted in a variety of neurodegenerative diseases. We treat these proteinaceous Trp networks as open quantum systems, using a non-Hermitian Hamiltonian to describe interactions of the chromophore network with the electromagnetic field. We numerically diagonalize the Hamiltonian to obtain its complex eigenvalues, where the real part is the energy and the imaginary part is its associated enhancement rate. We find that all three of these structures exhibit highly superradiant states near the low-energy portion of the spectrum, which enhances the magnitude and robustness of the quantum yield to static disorder and thermal noise. The high quantum yield and stable superradiant states in these biological architectures may play a photoprotective role in vivo, downconverting highly energetic ultraviolet photons emitted from reactive free radical species and thereby mitigating biochemical stress and photophysical damage. Contrary to conventional assumptions that quantum effects cannot survive in large biosystems at high temperatures, our results suggest that macropolymeric collectives of TLSs in microtubules, actin filaments, and amyloid fibrils exhibit increasingly observable and robust effects with increasing length, up to the micron scale, due to quantum coherent interactions in the single-photon limit. Superradiant enhancement and high quantum yield exhibited in neuroprotein polymers could thus play a crucial role in information processing in the brain, the development of neurodegenerative diseases such as Alzheimer's and related dementias, and a wide array of other pathologies characterized by anomalous protein aggregates.

---

### Patryk Lipka-Bartosik
*University of Geneva*

#### Thermodynamic Computing via Autonomous Quantum Thermal Machines


---

### Patryk Lipka-Bartosik
*University of Geneva*

#### Thermodynamic Computing via Autonomous Quantum Thermal Machines
We develop a physics-based model for classical computation based on autonomous quantum thermal machines. These machines consist of few interacting quantum bits (qubits) connected to several environments at different temperatures. Heat flows through the machine are here exploited  for computing.  The  process starts by setting the temperatures of the environments according to the logical input. The machine evolves, eventually reaching a non-equilibrium steady state, from which the output of the computation can be determined via the temperature of an auxilliary finite-size reservoir. Such a machine, which we term a ``thermodynamic neuron'', can implement any linearly-separable function, and we discuss explicitly the cases of NOT, 3-majority and NOR gates. In turn, we show that a network of thermodynamic neurons can perform any desired function. We discuss the close connection between our model and artificial neurons (perceptrons), and argue that our model provides an alternative physics-based analogue implementation of neural networks, and more generally a platform for thermodynamic computing. 

---

### Matteo Lostaglio
*PsiQuantum*

#### Quantum Classical Thermodynamics
Thermodynamic phenomena such as catalysis are characterized by complex interactions between physical and chemical processes that require challenging multiscale modeling. Transport and equilibration are typically described at a mesoscopic scale via computational fluid-dynamics (CFD) simulations (Navier-Stokes, lattice-Boltzmann…), reaction-diffusion equations and other models. To what extent can quantum theory, with its underlying linear, unitary dynamics, be used to efficiently simulate the nonlinear, non-unitary differential equations of classical thermodynamics? I will give an overview of recent remarkable progress as well as outstanding challenges of this nascent research direction.

---

### Florian Meier
*Atominstitut, TU Wien, Austria*

#### Autonomous Quantum Processing Unit: Constructing a thermodynamically self-contained model of quantum computation
Computation is an input-output process, where a program encoding a problem to be solved is inserted into a machine that outputs a solution. Whilst a formalism for quantum Turing machines which lifts this input-output feature into the quantum domain has been developed, this is not how quantum computation is physically conceived. Usually, such a quantum computation is enacted by the manipulation of macroscopic control interactions according to a program executed by a classical system. To understand the fundamental limits of computation, especially in relation to the resources required, it is pivotal to work with a fully self-contained description of a quantum computation where computational and thermodynamic resources are not obscured by the classical control.

In this talk, we investigate the question: Can we build a physical model for quantum computation that is fully autonomous?, by envisaging a quantum machine where the program to be executed as well as the control are both quantum. We do so by developing a framework that we dub the autonomous Quantum Processing Unit (aQPU). This machine, consisting of a timekeeping mechanism, instruction register and computational system allows an agent to input their problem and receive the solution as an output, autonomously. Using the theory of open quantum systems and results from the field of quantum clocks we are able to model the thermodynamic cost of computation, including the contributions coming from the control. We find that inputting only finite thermodynamic resources leads to imperfect computation, and that perfect precision for the computation requires divergent thermodynamic resources.

Finally, we discuss how the aQPU formalism applies beyond computation and address the ongoing discourse surrounding the work cost of controlling quantum thermal machines. Serving as a formalism for rendering such machines autonomous, the aQPU allows for the assessment of control costs within this domain, offering a potential resolution to such questions.

A preprint of the work to be presented can be found on https://arxiv.org/abs/2402.00111.

---

### Harry Miller
*University of Manchester*

#### Generalised linear response theory for the full quantum work statistics
When a small system is driven out of equilibrium, the dissipated work cost is a stochastic variable and it is important to consider its higher order fluctuations alongside average behaviour. A fundamental question is to understand the role of quantum mechanics in such processes. In this talk I will discuss the utility of Kubo’s linear response theory (LRT) for exploring stochastic thermodynamics in quantum regimes. The power of LRT lies in the fact that it can be used to study work statistics from a phenomenological point of view without the need for an exact dynamical model. I will demonstrate how it can be used to derive refined constraints on the form of work distributions that can arise, and it will be shown how LRT predicts a distinctly quantum signature in the work distribution through increased dispersion at low temperatures. I will link this signature to the breakdown in the energy equipartition theorem that is usually encountered in equilibrium statistical mechanics.

---

### Anthony Munson
*University of Maryland, College Park*

#### Work trades off with complexity in computationally restricted thermodynamics
According to Landauer, irreversible computation requires work. In principle, one can often evade work costs by implementing reversible transformations. In practice, complexity—the difficulty of realizing a quantum process—poses an obstacle: a realistic agent can perform only a limited number of gates and so not every reversible transformation. Hence an agent, if unable to complete a task unitarily, may expend work on an irreversible process, such as erasure, to finish the job. We pinpoint a work–complexity trade-off, quantifying how protocols that involve higher-complexity unitaries require less work and vice versa. We illustrate with the task of resetting qubits to the all-zero state using a limited number of gates and work-costing erasure. To quantify the resetting’s optimal efficiency, we introduce the complexity entropy, which quantifies a state's apparent randomness to an agent who can implement only limited-complexity measurement effects. The complexity entropy emerges as a general tool for quantifying the optimal efficiencies with which complexity-restricted agents can perform tasks in quantum thermodynamics and information processing.

---

### Zakaria Mzaouali
*Institute of Theoretical and Applied Informatics, Polish Academy of Sciences*

#### Efficiency Optimization in Quantum Computing: Balancing Thermodynamics and Computational Performance
We investigate the computational efficiency and thermodynamic cost of the D-Wave quantum annealer under reverse-annealing with and without pausing. Our experimental results demonstrate that the combination of reverse-annealing and pausing leads to improved computational efficiency while minimizing the thermodynamic cost compared to reverse-annealing alone. Moreover, we find that the magnetic field has a positive impact on the performance of the quantum annealer during reverse-annealing but becomes detrimental when pausing is involved. Our results provide strategies for optimizing the performance and energy consumption of quantum annealing systems employing reverse-annealing protocols. 

---

### Laetitia Paula Bettmann
*Trinity College Dublin*

#### Quantum stochastic thermodynamics in the mesoscopic-leads formulation
Accurately modelling macroscopic reservoirs in open systems theory is crucial to resolve thermodynamic effects that arise at a finite temperature, beyond the linear response and outside of the weak coupling regime. In the mesoscopic-leads formulation, macroscopic reservoirs are modeled by a finite collection of modes that are continuously damped toward thermal equilibrium by an appropriate Gorini-Kossakowski-Sudarshan-Lindblad (GKSL) master equation. The system together with the finite number of lead modes is referred to as the extended system. To access the time-resolved full distribution of integrated thermodynamic currents, such as heat and entropy production, for systems with a quadratic Hamiltonian, we employ a trajectory-unraveling technique on the GKSL master equation governing the dynamics of the covariance matrix of the extended system. We show that the integral fluctuation theorems for the total entropy production, as well as the martingale and uncertainty entropy production, hold. Furthermore, we investigate the fluctuations of the dissipated heat in finite-time Landauer erasure.

---

### Dario Poletti
*Singapore University of Technology and Design*

#### Steady state currents in superconducting quantum processors
A deeper understanding of the emergence of out-of-equilibrium statistical physics, and enhanced ability to control quantum many-body systems with single-site precision, can lead to a new era of quantum transport exploration. 
In order to reach that, we focus on a nonequilibrium scenario in which two nonintegrable systems prepared in different states are locally and non-extensively coupled to each other. 
We show the emergence of steady-like currents which are well defined and typical. We identify their origin to be from a prethermalization mechanism. 
We then discuss the experimental realization of these findings on state-of-the-art experimental setups.  

---

### Haitao Quan
*Peking University*

#### Special Relativistic Covariant Fluctuation Theorems
Fluctuation theorems establish connections between fluctuations and irreversibility by considering stochastic thermodynamic quantities. In this study, we derive special relativistic covariant fluctuation theorems by defining covariant work, heat, and entropy. We focus on a driven scalar field in contact with a Markovian heat bath. For moving inertial observers relative to the heat bath, both the energy components and the momentum components of work and heat must be included to formulate the corresponding fluctuation theorems, and the four-velocity of the heat bath plays an important role. It turns out that, the irreversibility is characterized by the conventional thermodynamic quantities in the rest reference frame of the heat bath, regardless of the reference frame of the observer. Even in the nonrelativistic case, the above identification is nontrivial. We study the work statistics for a Klein-Gordon field in a driving process measured by a moving inertial observer to explicitly verify the covariant version of the Jarzynski equality.

---

### Marcos Rigol
*Penn State University*

#### Typical eigenstate entanglement entropy as a diagnostic of quantum chaos and integrability
Quantum-chaotic systems are known to exhibit eigenstate
thermalization and to generically thermalize under unitary dynamics. In
contrast, quantum-integrable systems exhibit a generalized form of eigenstate
thermalization and need to be described using generalized Gibbs ensembles
after equilibration. I will discuss evidence that the entanglement properties
of highly excited eigenstates of quantum-chaotic and quantum-integrable
systems are fundamentally different. They both exhibit a typical bipartite
entanglement entropy whose leading term scales with the volume of the
subsystem. However, while the coefficient is constant and maximal in quantum-
chaotic models, in integrable models it depends on the fraction of the system
that is traced out. The latter is typical in random Gaussian pure states. I
will also discuss the nature of the subleading corrections that emerge as a
consequence of the presence of abelian and nonabelian symmetries in such
models.

---

### Alberto Rolandi 
*University of Geneva*

#### Collective Advantages in Finite-Time Thermodynamics
A central task in finite-time thermodynamics is to minimize the excess or dissipated work Wdiss when manipulating the state of a system immersed in a thermal bath. We consider this task for an N-body system whose constituents are identical and uncorrelated at the beginning and end of the process. In the regime of slow but finite-time processes, we show that Wdiss can be dramatically reduced by considering collective protocols in which interactions are suitably created along the protocol. This can even lead to a sublinear growth of Wdiss with N: Wdiss ∝ N^x with x < 1; to be contrasted to the expected Wdiss ∝ N satisfied in any noninteracting protocol. We derive the fundamental limits to such collective advantages and show that x = 0 is in principle possible; however, it requires long-range interactions. We explore collective processes with spin models featuring two-body interactions and achieve noticeable gains under realistic levels of control in simple interaction architectures. As an application of these results, we focus on the erasure of information in finite time and prove a faster convergence to Landauer’s bound.

---

### Huang Ruo Cheng
*Nanyang Technological University*

#### Quantum Pattern Engine
Quantum information-processing techniques enable work extraction from a system’s inherently quantum features, in addition to the classical free energy it contains. Meanwhile, the science of computational mechanics affords tools for the predictive modelling of non-Markovian classical and quantum stochastic processes. 
We combine tools from these two sciences to develop a theoretical prototype for a predictive quantum engine: a machine that charges a battery by feeding on a multipartite quantum system whose parts are temporally correlated via a classical stochastic process. In other words, the engine’s fuel is a classical stochastic process with quantum outputs. We also test the engine on simple models to benchmark the performance of our engine against various alternatives, including one without coherent quantum information-processing and one without predictive functionality; our predictive quantum engine is shown to outperform these alternatives in terms of work output.
Finally, we evaluate the engine’s performance on fuel processes with different degrees of temporal correlations and find the work yield to increase with such correlations. Additionally, our results suggest that there exists a phase boundary in parameter space where memory of past observations can
enhance the work extraction. Our work opens the prospect of machines that harness environmental free energy in an essentially quantum, essentially time-varying form.


---

### Valerio Scarani
*CQT, National University of Singapore*

#### Reverse processes as Bayesian retrodiction
A quantum translation of Crooks' fluctuation theorem (1998) was presented by Tasaki already in the year 2000; but exporting fluctuation theorems to more general quantum processes has proved challenging for years, with issues related to the definition of work, the role of coherences, etc. In 2021, some of us put up an approach to fluctuation theorems that avoids all those problems, and also opens new perspectives for classical stochastic thermodynamics [1,2]. The core of the idea is to define reverse processes as Bayesian retrodiction of the forward process. In the quantum case, the reverse map is given by the Petz map (as previously proposed by Kwon and Kim [PRX 9, 031029 (2019)] with a different motivation). This talk presents this approach, arguing for its universality [2,3]. The rederivation of known fluctuation theorems will also be sketched, and novel research questions will be overviewed [3-6].

---

### Finn Schmolke
*Institut für theoretische Physik I, Universität Stuttgart*

#### Measurement-induced synchronization
Observing a quantum object may dramatically affect its dynamics in a non-classical manner. We show that a continuously monitored quantum many-body system can undergo a spontaneous transition from stochastic dynamics to noise-free stable synchronization at the level of individual quantum trajectories, when subject to standard homodyne detection. This effect can occur in generic many-body quantum systems based on the existence of decoherence-free subspaces. Such a synchronization transition is always associated with the localization of the state in Hilbert space. On the trajectory level, ergodicity is thus typically broken and synchronization may appear along individual realizations while being absent at the ensemble level. 
These findings can be extended and generalized to predict the asymptotic fate of quantum trajectories. Generically, if the corresponding Lindblad equation admits multiple steady states, localization transitions and ergodicity breaking still occur but the conditions may depend on the measurement scheme. 

---

### Oles Shtanko
*IBM Quantum*

#### Preparing thermal states on noiseless and noisy programmable quantum processors
Thermal (Gibbs) states are important for the study of thermal equilibrium and quantum thermodynamics. Although the simulation of Gibbs states for quantum Hamiltonians is challenging for classical computers, the advent of quantum computing offers new possibilities for their preparation using quantum circuits. While many methods for Gibbs state sampling have been proposed recently, they often suffer from noise sensitivity and typically require fault-tolerance. I will explore a few algorithms that may be more practical. The first algorithm exploits the ergodicity of the target Hamiltonian, as given by the Eigenstate Thermalization Hypothesis, and shows promise for efficiency on quantum computers for some Hamiltonians. The second algorithm provides a universal approach, but requires exponential running time. Both algorithms incorporate an error mitigation strategy that may prove amenable to today's noisy quantum hardware.

---

### Janine Splettstoesser
*Chalmers University of Technology*

#### Nonthermal resources and fluctuations in nanoscale engines


---

### Janine Splettstoesser
*Chalmers University of Technology*

#### Nonthermal resources and fluctuations in nanoscale engines
Standard thermodynamic machines transform heat into work or vice versa. Macroscopic quantities, like temperatures, quantify the efficiency of their operation. This is different in nanoscale systems—often smaller than the length scales on which thermalisation takes place and where fluctuations can be of the same magnitude as average quantities. In this talk, I will show some properties of nanoelectronic devices, operating as engines, that are unique to the small scales on which they are realized. 
I will start by introducing novel relations between charge currents flowing in nanoelectronic conductors and their noise. In contrast to standard fluctuation-dissipation relations, valid in equilibrium, these relations for generic nonequilibrium situations consist in inequalities, setting bounds on the currents that can be obtained given a certain noise level of the signal. This has direct implications on the performance of nanoelectronic engines, complementing recently introduced thermodynamics uncertainty relations.
However, noise is not only a nuisance, but noisy resources can be beneficial for the operation of an engine! In the second part of my talk, I will introduce engines working without absorbing heat or work from the resource on average, seemingly violating the second law of thermodynamics. This is possible when the resource has nonthermal properties (namely, it cannot be characterized by a temperature or potential) and requires a minimum amount of fluctuations in the input.

---

### Amit Vikram
*JQI and Dept. of Physics, University of Maryland, College Park*

#### Quantum dynamics from the energy spectrum
In this talk, we’ll provide an overview of some recent results that uncover universal connections between quantum dynamics and the energy spectrum, which can be intuitively regarded as refinements of the energy-time uncertainty principle. At the level of the fine structure of the spectrum, “quantum chaos” has often been associated with rigidity in spectral fluctuations, as exemplified by the eigenvalues of random matrices. We will show that this rigidity is directly indicative of a dynamical form of quantum ergodicity, which measures the ability to use an orthonormal basis for “quantum time-keeping” in the Hilbert space. Moreover, this quantum dynamical phenomenon captures the classical intuition behind ergodicity as exploring all regions of a phase space, addressing a long-standing question of the latter’s counterpart in an isolated quantum system. Zooming out to the overall profile of the energy spectrum, we will show that the spectral form factor sets a quantum speed limit that is nontrivial for asymptotically long times, and tighter than comparable versions of known speed limits based on the energy-time uncertainty principle. Applying this speed limit to the scrambling of information in a many-body system, we will obtain bounds on the fast scrambling of initial states under arbitrary interactions with a bath at any temperature. This sets an exact limit on the fastest allowed scrambling or thermalization time in an arbitrary quantum mechanical system.

---

### Amanda Younes
*University of California, Los Angeles*

#### Cooling by heating of a trapped ion using sunlight
Laser cooling typically uses carefully tuned lasers to couple atoms to a near-vacuum optical mode of the electromagnetic field, allowing them to be cooled by spontaneous emission into that mode. When this coupling is controlled by the occupation of another mode, cooling can sometimes be performed by heating that mode, known as ‘cooling by heating’. An experimentally accessible implementation is resolved-sideband cooling, a commonly used technique to cool trapped ions to their motional ground state (corresponding to microkelvin temperatures). While this scheme typically uses a coherent, narrowband laser to drive the cooling, we propose using unfiltered sunlight instead as a demonstration of cooling by heating. We measure the spectrum of sunlight coupled into single mode optical fiber for delivery to the ion, compare it to the spectrum of a blackbody in quasi-one dimension, and provide estimates of the achievable cooling rate with typical experimental parameters. Finally, we discuss and demonstrate a related scheme for cooling the internal states of the ion using sunlight, an example of internal cooling by heating.

---

### Maciej Zgirski
*Institute of Physics, PAN, Warsaw*

#### Quantum thermodynamics with a single superconducting vortex
We introduce the Single Vortex Box (SVB) – a nanodevice that allows to treat a single superconducting vortex as a macroscopic, albeit quantized “particle”, which can be created and annihilated with pulses of electrical current [1,2]. Using the method of fast nanosecond resolving switching thermometry [3], we measure the temperature rise and the subsequent thermal relaxation resulting from the expulsion of just a single magnetic field vortex out of the SVB. Our experiment provides a calorimetric estimation of the dissipation in a superconductor due to a single moving vortex. This is a feat of the fundamental importance that has never been accomplished before for the lack of appropriate tools. Our pioneering demonstration is also a pivotal step towards the development of the vortex electronics i.e. memory cells, superconducting diodes, and logical elements.

---
