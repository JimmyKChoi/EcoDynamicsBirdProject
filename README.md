# EcoDynamicsBirdProject
Repository for the interspecies competition model coded for Justin Yeakel's QSB256 Ecological Dynamics graduate course.

Pre-modeling proposal
<img width="302" height="395" alt="image" src="https://github.com/user-attachments/assets/c749689e-6d12-45e9-a1ec-a6a538f4236b" />

(Heritability stuff did not end up getting added, sadly.)

This model has 13, count 'em, *THIRTEEN* parameters. Let me walk you through them.

| Parameter  | Description |
| ------------- | ------------- |
| **reps**  | # of replicates you want to conduct. Plotting multiple replicates in one model run helps to show off the stochastic nature of these simulations.  |
| **tmax**  | Maximum # of timesteps you want to simulate.  |
| **N0**  | Starting # of individuals in each species/population. Symmetrical (same for both sides).  |
| **carry_cap** | Carrying capacity in each species/population. Symmetrical.  |
| **mean1** | Initial mean trait value of species 1.  |
| **sd1** | Initial trait value standard deviation of species 1 (variation).  |
| **mean2** | Initial mean trait value of species 2.  |
| **sd2** | Initial trait value standard deviation of species 2 (variation).  |
| **env_opt** | Trait optimum as selected for by the environment. Single value.  |
| **mutation1** | Offspring trait mutation/developmental noise term for species 1.  |
| **mutation2** | Offspring trait mutation/developmental noise term for species 2.  |
| **inv_sel_str** | Width of selection surface, inverse of selection strength.  |
| **comp_rate** | Proportion of each species/population that participates in interspecies competition. Symmetrical.  |
 
Much credit to Justin Yeakel at the University of California, Merced's Life & Environmental Sciences department for the
words of wisdom and showing me this [code vignette](https://jdyeakel.github.io/teaching/ecology/sections2024/4_evolution/) to get started with. Justin, if you're reading this, I owe you a beer. :)
