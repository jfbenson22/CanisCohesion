[![DOI](https://zenodo.org/badge/619827249.svg)](https://doi.org/10.5281/zenodo.13891913)

Data Files for Benson et al. 'Intrinsic and environmental drivers of pairwise cohesion in wild Canis social groups'. Ecology

What follows is each datafile name and a description of each column. In many cases, the same data columns and column headings are carried across files. In these cases the column explanation is given for the first file in which it appears
Each datafile contains a model number (1-9) that corresponds to the model numbers used to identify models in the paper. The methods, structure, and results of each model are described in detail in the paper.

1. WolfCoyoteOverall_Model1.csv

dyadyad_season_year = canid pair ID with season and pack ID. This is unique ID for each pair-season combination

dyad_ID = Unique ID for canid pair. Used as part of random effects structure.

PackID = Unique canid social group ID. Used as part of the random effects structure.

Species1 = identifies genetic ancestry of canids (GW = gray wolf, EW = eastern wolf, RW = red wolf, Admixed = admixed wolf, coyote = coyote)

Species2 = identifies wolf vs. coyote

coyote = dummy code (1 = coyote, 0 = wolf)

wolf = dummy code (1 = wolf, 0 = coyote)

GW = dummy code (1 = gray wolf, 0 = not gray wolf)

EW = dummy code (1 = eastern wolf, 0 = not eastern wolf)

RW = dummy code (1 = red wolf, 0 = not red wolf)

Mixed = dummay code (1 = admixed wolf, 0 = not admixed wolf)

SA = study area. Used as part of random effects structure.

season = winter, den, or rend (rendezvous)

season2 = winter or nw (nonwinter)

den = dummy code (1 = den season, 0 = not den season)

rend = dummy code (1 = rendezvous season, 0 = not rendevous season)

winter = dummy code (1 = winter season, 0 = not winter season)

Cohesion = proportion of simulataneous locations for that season where pair was within 100m of each other

LoCoOL = proportion of Local Convex Hull home range overlap between pair within that season

KernelOL = probability of kernel home range utilization distribution overlap within that season

Adult = dummy code (1 = adult-adult pair, 0 = pairs with at least 1 non-adult)

2. WolfAge_Model2.csv

Exploit = dummy code (1 = heavy exploitation, 0 = no/light exploitation)

LargePred = dummy code (1 = large predator of other species present, 0 large predators of other species not present)

Prey = dummy code (1 = main prey is large ungulate, 0 = main prey is not large ungulate)

Beaver = dummy code (1 = beaver present, 0 = beavers not present)

Human = measure of human landscape alteration (0 = no alteration)

PCV = coefficient of variation of precipitation within season

Long = longitude

Lat = latitude

3. WolfBreeding_Model3.csv

Breed_pair = dummy code (1 = breeding pair, 0 = pair with at least 1 non-breeder)

FF = dummy code (1 = female-female pair, 0 = not female-female pair)

MM = dummy code (1 = male-male pair, 0 = not male-male pair)

FM = dummy code (1 = female-male pair, 0 = not female-male pair)

Same = dummy code (1 = same sex pair, 0 = not same sex pair)

4. CoyoteAge_Model4.csv

Prey = dummy code (1 = large prey (ungulate), 0 = small prey)

SE = dummy code (1 = southeastern coyote, 0 = coyote from other region)

NE = dummy code (1 = northeastern coyote, 0 = coyote from other region)

West = dummy code (1 = western coyote, 0 = coyote from other region)

5. CoyoteBreeding_Model5.csv

6. WolfPackSize_Model6.csv

PackSize = number of animals in social group

7. CoyotePackSize_Model7

8. HROverlapBreed_Model8

9. HROverlapAge_Model9
