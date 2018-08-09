This directory contains stochastic mappings for the Hawaiian silversword analysis. Each page corresponds to an independent posterior sample of phylogeny (topology and divergence times), biogeographic history, and paleogeographic configuration of the islands.

- `biogeo_silversword.model_G4.stoch_map` corresponds to the +G4 analysis, where the four Modern Island areas (Kauai, Oahu, Maui Nui, and Hawaii) appear in sequence. This is the most paleogeographically realistic model considered here.
- `biogeo_silversword.model_G1.stoch_map` corresponds to the +G1 analysis, where the four Modern Island areas (Kauai, Oahu, Maui Nui, and Hawaii) were assumed to originate at the same time as Kauai. This is a model is considered "hotspot-naive".
- `biogeo_silversword.model_G0.stoch_map` corresponds to the -G analysis, where geographical features were ignored (i.e. islands were always present, no distances between islands). This model is considered "geography-naive".

Stochastic mappings were generated assuming expected birth and death rate priors of 0.1 and sampling probability of 0.61. Only 100 of 2000 possible samples are presented here.
