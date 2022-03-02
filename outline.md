# 0. Preliminary work
- list of packages to install in advance
	- redist, sf, redistmetrics, tidyverse, ggplot2, make an account on Dave's, others?
- reading (an expert witness report, Kosuke 3rd OH?)
- maybe a news article about this redistricting cycle

# 1. How do we evaluate a plan?
- What is a redistricting plan?
	- look at a map in Dave's
	- let's make our own: shapefiles, projections (Amos tweets)
	- geom_sf()
	- geographies: precincts, VTDs, districts, Census geographies, etc.
- What is a "fair" plan?
	- Requirements: laws and norms, state constitutions, guidelines, VRA, etc.
	- Evaluation statistics

# 2. Simulations
- Adjacency graphs, spanning trees, etc.
	- contiguity
	- what even is a split? different ways of thinking about this
- redist_map()
	- geometry and adjacency combination
- What even is sampling / simulation?
	- different ways of doing the same thing.
 	- some names: MCMC, SMC, etc.
- Our first simulation
	- plans matrix
	- comparing enacted to simulated
- What is a good sample?
	- diversity, weights, etc.
- How to incorporate requirements
	- constraints: splits, Gibbs & VRA, state quirks, etc.
