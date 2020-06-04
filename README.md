INFOTOPO

Programs for Information Topology Data Analysis INFOTOPO : new rewrited version of the 2017 scripts available at https://github.com/pierrebaudot/INFOTOPO/
 
Programs for Information Topology Data Analysis Information Topology is a program written in Python (compatible with Python 3.4.x), with a graphic interface built using TKinter [1], plots drawn using Matplotlib [2], calculations made using NumPy [3], and scaffold representations drawn using NetworkX [4]. It computes all the results on information presented in the study [5,6,7,8,9], that is all the usual information functions: entropy, joint entropy between k random variables (Hk), mutual informations between k random variables (Ik), conditional entropies and mutual informations and provides their cohomological (and homotopy) visualisation in the form of information landscapes and information paths together with an approximation of the minimum information energy complex [5,6,7,8,9]. It is applicable on any set of empirical data that is data with several trials-repetitions-essays (parameter m), and also allows to compute the undersampling regime, the degree k above which the sample size m is to small to provide good estimations of the information functions [5,6,7,8,9]. The computational exploration is restricted to the simplicial sublattice of random variable (all the subsets of k=n random variables) and has hence a complexity in O(2^n). In this simplicial setting we can exhaustively estimate information functions on the simplicial information structure, that is joint-entropy Hk and mutual-informations Ik at all degrees k inferior or equal to n and for every k-tuple, with a standard commercial personal computer (a laptop with processor Intel Core i7-4910MQ CPU @ 2.90GHz * 8) up to k equal n equal 21 in reasonable time (about 3 hours). Using the expression of joint-entropy and the probability obtained using equation and marginalization [5], it is possible to compute the joint-entropy and marginal entropy of all the variables. The alternated expression of n-mutual information given by equation then allows a direct evaluation of all of these quantities. The definitions, formulas and theorems are sufficient to obtain the algorithm [5]. We will further develop a refined interface but for the moment it works like this, and requires minimum Python use knowledge. Please contact pierre.baudot [at] gmail.com for questions, request, developments (etc.). The version V1.2, includes more commentaries and notes in the programs, the previous readfile has been included in the visualization, energy vs entropy landscapes have been added to vizualisation, the shuffles for statistical dependence test has been implemented in COMPUTATION and VISUALIZATION, The determination of the undersampling dimension :



[1] J.W. Shipman. Tkinter reference: a gui for python. . New Mexico Tech Computer Center, Socorro, New Mexico, 2010. 
[2] J.D. Hunter. Matplotlib: a 2d graphics environment. Comput. Sci. Eng., 9:22–30, 2007. 
[3] S. Van Der Walt, C. Colbert, and G. Varoquaux. The numpy array: a structure for efficient numerical computation. Comput. Sci. Eng., 13:22– 30, 2011. [4] A.A. Hagberg, D.A. Schult, and P.J. Swart. Exploring network structure, dynamics, and function using networkx. Proceedings of the 7th Python in Science Conference (SciPy2008). Gel Varoquaux, Travis Vaught, and Jarrod Millman (Eds), (Pasadena, CA USA), pages 11–15, 2008. 
[5] Baudot P., Tapia M., Bennequin, D. , Goaillard J.M., Topological Information Data Analysis. 2019, Entropy, 21(9), 869    PDF
[6] Baudot P., The Poincaré-Shannon Machine: Statistical Physics and Machine Learning aspects of Information Cohomology. 2019, Entropy , 21(9),  PDF
[7] Tapia M., Baudot P., Dufour M., Formizano-Treziny C., Temporal S., Lasserre M., Kobayashi K., Goaillard J.M.. Neurotransmitter identity and electrophysiological phenotype are genetically coupled in midbrain dopaminergic neurons. Scientific Reports. 2018. PDF. BioArXiv168740. PDF
[8] Baudot P., Elements of qualitative cognition: an Information Topology Perspective. Physics of Life Reviews. 2019 LINK. extended version on Arxiv. PDF
[9] Baudot P., Bennequin D., The homological nature of entropy. Entropy, 2015, 17, 1-66; doi:10.3390. PDF
[10] Baudot P., Bennequin D., Topological forms of information. AIP conf. Proc., 2015. 1641, 213. PDF







