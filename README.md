# Feasible Diversity

*Exploring integer partitioning as a way of predicting bounds on biodiversity and its most likely configuration*

Much recent work has focused on bounds to species richness.  The idea that the number of species should be self-limiting (e.g. like logistic growth) seems dubious to me.  However, to properly evaluate such ideas, we should start with something simple and investigate what added complexity is needed to explain real world patterns.  In thinking about species richness, I start with the total number of individuals in a large system (think continents)---this quantity likely does have an upper bound due to the total amount of energy available to the system and the physiological/life history strategies those organisms have to exploit that energy.  So if $N$ is given, what would we expect for $S$?  I'm using integer partitioning to derive the macroscopic distribution over $S$ given microstate configurations (i.e. the partitioning of individuals across species).  This macroscopic distribution is bounded ($S \leq N$) but I'm interested in its internal mode ($\hat{S} << N$) and how real communities match or deviate from that most likely $S$, and what that means about their unique biology.
