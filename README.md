# Stochastic-Processes-and-Metropolis-Hastings
This repository contains a single Jupyter notebook with my solutions to an assignment on stochastic processes, random walks/Brownian motion, and the Metropolis–Hastings algorithm.


Stochastic matrices and Markov chains:
Worked with a 5‑state transition matrix, used the fact that each row of a stochastic matrix sums to 1 to find a missing entry, and multiplied the initial distribution by the matrix several times to see how the state probabilities evolve over generations.
  
Absorbing Markov chains (canonical form):
Rewrote the transition matrix in canonical form, splitting transient and absorbing states into blocks Q and R, then used the standard formulas to find (i) expected number of visits to each transient state, (ii) expected time to absorption and (iii) probabilities of ending in each absorbing state.

Effect of time step and randomness on simulations:
Ran many independent walks to see how the mean position after 2500 steps depends on dt and created histograms to check whether final positions are normal.

Metropolis–Hastings algorithm in 4D optimisation:
Implemented and debugged a Metropolis–Hastings to search for the maximum in a 4D function, explained why the method sometimes accepts “worse” moves, compared small vs large proposal step sizes, and discussed why the function is suitable.

Practical experiments:
Ran the algorithm several times with different seeds and starting points, plotted function value versus step, reported the maximum found and final positions (w,x,y,x) in each run, compared acceptance ratios, and reflected on whether the found maximum is likely global or just local.
