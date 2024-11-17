Statistik Projekte Finanzmathematik
==============================

This Repository contains two projects which were created during my work as a business mathematician at Wüstenrot and Württembegische Insurance.

**Project 1:** My main line of was the calculation of claims reserves. One estimates future cash flows from historic claims data. 
In application, the so called Chain-Ladder-Method is used. The like-named folder conatins my script summarizing the derivation of the method, 
together with statistical assumptions and viability testing of the model.

**Project 2:** In the year 2023 Germany was hit with extraordinary inflation rates inflicting capital needs for claims reserves. The task was to calculate branch specific inflation rates. 
Typically, claims are lognormal distributed. Inflation is visible by an unusual change of expectation values of the distributions over the years and quarters.  
Instead of just using the arithmetic mean to estimate expectation values, one may use estimations adapted to lognormal distributions for better accuracy.   
In the second folder you find on the one hand a pdf-file, which contains a derivation of an expectation value estimator, adapted to lognormal distributions, using Maximum Likelhood Estimation. It turns out to be the geometric mean together with an inflation invariant scale factor.
On the other hand you find a Jupyter notebook comparing the convergence speeds of the two different estimators for lognormal distributions.
