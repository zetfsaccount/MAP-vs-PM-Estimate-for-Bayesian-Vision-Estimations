Based on: http://www.cns.nyu.edu/malab/bayesianbook.html
# MAP-vs-PM-Estimate-for-Bayesian-Vision-Estimations
1) (Based on Problem 6.3) In Section 6.1, we noted that the probability of rain the next day was given by the posterior mean estimate, and was different from the most probable value of the rainfall rate, r, on the island, which is the MAP estimate. Suppose you’ve been on the island for 4 days, and it has rained only once.

a) Show that the MAP estimate for r is 0.25 and, according to Laplace’s rule of succession (Eq. (6.14)), the posterior mean (PM) estimate is 0.33.

b) Verify Eq. (6.14) numerically, by discretizing r into several hundred or thousand values equally spaced between 0 and 1. Given 1 rainy day out of 4, calculate the likelihood for each r value, and enter these into Bayes’ formula with a uniform prior. Calculate the posterior mean as ∑ r p(r|xobs). Show that it is equal to the value obtained using the formula.

c) Imagine that you repeat this 4-day experiment 1000 times (for example you live this 4-day period in your life again and again as in a sci-fi movie). In each 4-day experiment, the probability of rain is r = 0.25. Simulate the experiments, where rain every day is the outcome of a Bernoulli process with probability r. For each experiment compute the MAP and PM estimates of r using the formulas. Next, compute the means of MAP and PM estimates across the 1000 experiments. Which one is closer to the true r?

d) Repeat (c) with r = 0.75.

e) Repeat (c) with r = 0.5.

f) Interpret your results in (c)-(e). Why does this pattern make intuitive sense?

2) (Based on Problem 6.7) Create the plots in Figure 6.7, which correspond to trials in learning the slope parameter k in the relation F = ks (see Section 6.4). The toddler performs several trials, your plots will reflect the computations after 1, 5, and 15 trials. On each trial, she sends a command s that is drawn from a uniform distribution on [2,10], and her force measurement is drawn from a Gaussian distribution with a mean of 1.5s and standard deviation 2. The prior over k is flat. Your plots should look like those in Fig. 6.7: (center) the likelihood function over k computed from the measurement on the tth trial; (right) the posterior based on the measurements made up to and including the tth trial; (left) a graphical representation of the data, with the line corresponding to the posterior mean estimate of k based on the measurements made up to and including the tth trial.

(optional) Make a movie of the evolution of trials, likelihood function, and posterior distribution for 20 trials. Make sure that the axes do not change from frame to frame. Choose the ranges on both axes large enough. Make sure that the numbers on the axes are easily legible and that the lines in your plots are sufficiently thick. Save your movie. You can use the animation functions of matplotlib (https://matplotlib.org/3.5.0/gallery/animation/simple_anim.html)
