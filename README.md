
## About Me


I am Grishma, currently pursuing my graduate studies at the University of Pittsburgh. My academic background includes a dual degree in B.S.M.S. from IISER Bhopal, where I concentrated on pure mathematics with a focus on Algebra Geometry. Throughout my master's program at the University of Pittsburgh, I collaborated with Dr. Bard Ermentrout in the field of Computational Neuroscience. Presently, I am engaged in research with Dr. Hessam Babaee, exploring reduced order modeling (ROM).



## Education
- PhD, Computational Modeling and Simulation Program (MEMS Dept) | University of Pittsburgh (Aug 2021- Aug 2025(exp)) (GPA: 3.859 out of 4)
- M.S., Applied Mathematics	                             | University of Pittsburgh (December 2020)	 		
- B.S.M.S. Dual Degree, Major: Mathematics Minor: Physics	     | Indian Institute of Science Education and Research Bhopal (May 2017)	 			        		

## Work Experience
**Teaching Assistant/ Instructor at University of Pittsburgh**
- Instructor and mentor for classes of 25+ students in Pre-Calculus, Calculus1, Calculus2, Calculus3, Business Calculus and Differential Equations.
- Followed established course outline to prepare lessons,convey information and enhance understanding of course material.
            
 
### **Publications**

1. **Donello, M.**, **Palkar, G.**, Naderi, M.H., Fernández, D.C., & Babaee, H.  
*Oblique projection for scalable rank-adaptive reduced-order modelling of nonlinear stochastic partial differential equations with time-dependent bases.*  
**Proceedings of the Royal Society A: Mathematical, Physical and Engineering Sciences**, 479(2278), 20230320, 2023.

2. **Palkar, G.**, Jian-young Wu, & Ermentrout, B.  
*The inhibitory control of traveling waves in cortical networks.*  
**PLoS Computational Biology**, 19(4): e1010697, 2023.



## Research Projects

### Completed
#### Project 1: 
##### Achievement:
The method achieved simulations 10^3 times faster than traditional methods and 10 times faster than comparable ROMs, with 99.99% accuracy and enhanced stability. The model demonstrates robustness in small singular value scenarios, adaptability to rank changes, and high parallelizability, ensuring computational efficiency and minimal intrusion.

##### Project discription: 
Time-dependent basis reduced-order models (TDB ROMs) have successfully been used for approximating the solution to nonlinear stochastic partial differential equations (PDEs). For many practical problems of interest, discretizing these PDEs results in massive matrix differential equations (MDEs) that are too expensive to solve using conventional methods. While TDB ROMs have the potential to significantly reduce this computational burden, they still suffer from the following challenges: (i) inefficient for general nonlinearities, (ii) intrusive implementation, (iii) ill-conditioned in the presence of small singular values and (iv) error accumulation due to fixed rank. To this end, we present a scalable method for solving TDB ROMs that is computationally efficient, minimally intrusive, robust in the presence of small singular values, rank-adaptive and highly parallelizable. These favourable properties are achieved via oblique projections that require evaluating the MDE at a small number of rows and columns. The columns and rows are selected using the discrete empirical interpolation method (DEIM), which yields near-optimal matrix low-rank approximations. We show that the proposed algorithm is equivalent to a CUR matrix decomposition. Numerical results demonstrate the accuracy, efficiency and robustness of the new method for a diverse set of problems.

#### Project 2: 
##### Achievement: 
I explore the geometric foundations of Reduced Order Modeling (ROM) through the lens of Riemannian manifold theory to identify key sources of error in existing state-of-the-art ROM techniques. This investigation leads to the development of a novel oversampling strategy designed to capture a wider range of data variability, thereby improving model accuracy while significantly reducing computational cost. The proposed oversampling method, seamlessly integrated into the ROM framework, demonstrates a tenfold reduction in computational expense compared to conventional approaches. I validate its performance on a range of challenging problems, including highly nonlinear and stiff systems discretized on finite element meshes—scenarios in which traditional ROM techniques often incur costs comparable to full-order models.


#### Project 3: 	
##### Achievement: 
Seizure prediction and analysis: I built a one-dimensional spiking neuronal network to explore how waves move through and are controlled in the brain. This work helped reveal how sensitive cortical networks are to different types of stimuli. I also created and studied a simplified model of synaptic activity to understand its stability and how it can shift into unhealthy, seizure-like states. Through detailed analysis of how spatial and temporal inhibition works, I showed how wave propagation in the brain can suddenly break down, offering new insights into the mechanisms behind seizures.

##### Project discription: 
Propagating waves of activity can be evoked and can occur spontaneously in vivo and in vitro in cerebral cortex. These waves are thought to be instrumental in the propagation of information across cortical regions and as a means to modulate the sensitivity of neurons to subsequent stimuli. In normal tissue, the waves are sparse and tightly controlled by inhibition and other negative feedback processes. However, alterations of this balance between excitation and inhibition can lead to pathological behavior such as seizure-type dynamics (with low inhibition) or failure to propagate (with high inhibition). We develop a spiking one-dimensional network of neurons to explore the reliability and control of evoked waves and compare this to a cortical slice preparation where the excitability can be pharmacologically manipulated. We show that the waves enhance sensitivity of the cortical network to stimuli in specific spatial and temporal ways. To gain further insight into the mechanisms of propagation and transitions to pathological behavior, we derive a mean-field model for the synaptic activity. We analyze the mean-field model and a piece-wise constant approximation of it and study the stability of the propagating waves as spatial and temporal properties of the inhibition are altered. We show that that the transition to seizure-like activity is gradual but that the loss of propagation is abrupt and can occur via either the loss of existence of the wave or through a loss of stability leading to complex patterns of propagation.



#### Project 4: Fifth Year Thesis Project under the supervision of Dr. Sanjay Kumar Singh at the IISER-Bhopal(May 2016 - May 2017)
The objective of my project was to study Vector Bundles over Compact Riemann Surfaces. The goal was to study vector bundles and prove a theorem of Andre Weils . We constructed a vector bundle associated to the representation of the fundamental group of a compact Riemann surface and saw that the vector bundle is an indecomposable degree zero vector bundle. Now, there is a natural question that comes to mind: " Characterize those degree zero vector bundles that come from representations". Andre Weil’s theorem gives an answer to this question.

### Ongoing 
##### Project 1: 
Developed a novel domain decomposition method tailored for transport-dominated problems, achieving a 12-fold reduction in simulation data size and substantially lowering computational time. The approach naturally supports parallelization by enabling concurrent solutions of subdomains across multiple processors or computational nodes, making it highly efficient for large-scale simulations.

##### Project 2: 
Parametric Optimization Using TDB-CUR: In collaboration with a colleague from the University of Waterloo, we are applying TDB-CUR to large-scale parametric optimization problems, guided by a Master's student. This project aims to leverage low-rank modeling to accelerate optimization under uncertainty.


#### Technical Skills: Matlab, Python, C++, Julia, Fortran, R, SQL, Latex, XPPAUT
#### Research: Mathematical Modeling, Reduced Order Modeling, Data-Driven Modeling, Uncertainty Quantification, Computational Fluid Dynamics, Machine Learning, Computational Neuroscience

## Graduate Coursework
- Data-driven modeling for engrs, UPitt, Grade A+
- Machine learning, UPitt, Grade: A
- Data centric computing, UPitt, Grade A
- Numerical solutions of ode/pde, Grade A+/A
- Numerical Linear Algebra, University of Pittsburgh, Grade A
- Applied Predictive Modeling
- Introduction to Natural Language Processing and Large Language Models




## Workshops and Conferences
- Presented a Minisymposium at SIAM-NNP, RIT, NY (USA) - Nov 2024
- Presented a Minisymposium at 2024 SIAM Annual Meeting (AN24)
- Poster Presentation at SIAM-NNP, NJIT, NJ (USA) - October 2023
- Talk at AWM Pitt Graduate Seminar - https://youtu.be/VWMUYsA2dE0?si=0AzSiOcfDXDd7yO3 - March 2021
- Graduate Career Design Workshop and Series, University of Pittsburgh, PA (USA) - 2022
- GIAN programme lectures by Prof. Ram Murty on Modular Forms, IISER-Bhopal (India) - 2016
- Summer Programme in Mathematics (SPIM 2015), Harish Chandra Research Institute, Allahabad (India) - 2015
- VIJYOSHI, Indian Institute of Science, Bangalore (India) - 2012


  
## Awards and Scholarships
- Awarded scholarship under Goa Scholar’s Scheme for demonstrating strong potential in the field of science and research - August 2019
- Awarded Inspire Fellowship by Ministry of Human Resource Development , Government of India for demonstrating exemplar performance in coursework and research potential - 2012-2017
- Rajhans award for securing highest marks in the science subject during the higher secondary board examination - June 2010

## Admin work
- President of Association for Women in Mathematics Chapter , University of Pittsburgh - 2020

## A Little More About Me
Languages:
- Konkani(Native)
- Hindi(Fluent)
- English(Fluent)

Interests and hobbies are:
- Drawing, Painting
- Gardening
- Gym, Kung-Fu (Wushu Style)
