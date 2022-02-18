# 0. Preliminary work
- list of packages to install in advance
	- redist, sf, redistmetrics, others?
- reading (an expert witness report, Kosuke 3rd OH?)
- maybe a news article about this redistricting cycle

# 1. How do we evaluate a plan?
- What is a redistricting plan?
	- shapefiles, projections (Amos tweets)
	- geom_sf()
	- geographies: precincts, VTDs, districts, Census geographies, etc.
- What is a "fair" plan?
	- Requirements: laws and norms, state constitutions, guidelines, VRA, etc.
	- Evaluation statistics

# 2. Simulations
- Adjacency graphs, spanning trees, etc.
	- contiguity
- redist_map()
	- geometry and adjacency combination
- Our first simulation
	- plans matrix
	- comparing enacted to simulated
- What is a good sample?
	- diversity, weights, etc.
- How to incorporate requirements
	- constraints: splits, Gibbs & VRA, state quirks, etc.