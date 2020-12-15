# Independent-Approximates
Estimation methods for heavy-tail distributions

See "Independent Approximates enable estimation of heavy tail distributions

The software is provided under GPL v3 license. Proprietary licenses available upon request.

Kenric P. Nelson
President
Photrek, LLC
kenric.nelson@gmail.com

Abstract – Independent Approximates (IAs) are proven to enable a closed-form estimation of the generalized Pareto and Student’s t distributions, while a broader proof including the Levy stable distributions is described for future research. (IAs) are selected from independent, identically distributed samples by partitioning the samples into groups of n and retaining the median of the samples in those groups which have approximately equal samples. The marginal distribution along the diagonal of equal values is has density proportional to the nth power of the original density. This nth-power-distribution, which the IAs approximate, has faster tail decay enabling closed-form estimation of its moments and retains a functional relationship with the original density. Computational experiments with between 1000 to 100,000  Student’s t samples are described. With 10,000 samples the estimations have a relative bias less than 0.01 and a relative precision less than ±0.1.

Statistical estimation of the parameters of a heavy-tail distribution is an infamously difficult problem. As the rate of tail decay decreases, i.e. becomes heavier, the probability of outlier samples, which overwhelm statistical analysis, increases. As a result, the statistical moments either diverge to infinity or become undefined with the higher-order moments becoming unstable first. So for instance, the Student’s t-distribution, whose asymptotic probability density function (pdf) is defined by the degree of freedom   , has an undefined mean when   (the Cauchy distribution is  ), a variance which diverges between   and is undefined when  , and a skewness (third moment) which is undefined for  . Each successive moment requires higher degrees of freedom. 

Nevertheless, the study of complex adaptive systems has shown that the nonlinear dynamics of both natural and man-made systems make heavy-tail distributions ubiquitous [1] and thus essential for accurate modeling of important signals and systems. A few examples include the distribution of ecological systems (generalized Pareto) [2], the foraging patterns on birds (Levy) [3], log-return of markets (Student’s t) [4], [5], and the distribution of words in a language (Zipf Law) [6]. Comprehensive survey’s of statistical analysis of heavy-tail distributions include Resnick [7], Kotz and Nadarajah [8] and of modeling for complex systems include Aschwanden [9], Tsallis [10], and Cirillo [11]. Despite the extensive investigation of heavy-tail distributions and the importance for modeling the stochastic properties of nonlinear systems, estimation using closed-form solutions as opposed to iterative optimization have been limited.

A. Clauset, C. R. Shalizi, and M. E. J. Newman, “Power-Law Distributions in Empirical Data,” SIAM Rev., vol. 51, no. 4, pp. 661–703, Nov. 2009.
[2]	R. W. Katz, G. S. Brush, and M. B. Parlange, “Statistics of Extremes: Modeling Ecological Disturbances,” Ecology, vol. 86, no. 5, pp. 1124–1134, May 2005.
[3]	G. M. Viswanathan, V. Afanasyev, S. V. Buldyrev, E. J. Murphy, P. A. Prince, and H. E. Stanley, “Lévy flight search patterns of wandering albatrosses,” Nature, vol. 381, no. 6581, pp. 413–415, 1996.
[4]	A. L. M. Vilela, C. Wang, K. P. Nelson, and H. E. Stanley, “Majority-vote model for financial markets,” Phys. A Stat. Mech. its Appl., vol. 515, pp. 762–770, Feb. 2019.
[5]	V. Pisarenko and D. Sornette, “New statistic for financial return distributions: Power-law or exponential?,” Phys. A Stat. Mech. its Appl., vol. 366, pp. 387–400, Jul. 2006.
[6]	S. T. Piantadosi, “Zipf’s word frequency law in natural language: A critical review and future directions,” Psychon. Bull. Rev., vol. 21, no. 5, pp. 1112–1130, Oct. 2014.
[7]	S. Resnick, Heavy-Tail Phenomena: Probabilistic and Statistical Modeling. New York, NY: Springer, 2007.
[8]	S. Kotz and S. Nadarajah, Multivariate T-Distributions and Their Applications. Cambridge University Press, 2004.
[9]	M. J. Aschwanden, Self-organized criticality in astrophysics : the statistics of nonlinear processes in the universe. Springer Science & Business Media, 2011.
[10]	C. Tsallis, “Statistical mechanics for complex systems: On the structure of q-triplets,” in Physical and Mathematical Aspects of Symmetries, S. Duarte, J. Gazeau, S. Faci, T. Micklitz, R. Scherer, and F. Toppan, Eds. Cham: Springer International Publishing, 2017, pp. 51–59.
[11]	R. Cirillo, The Economics of Vilfredo Pareto. Routledge, 2012.

