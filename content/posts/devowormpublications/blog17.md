+++
title =  "Upcoming Update on DevoWorm Project to OpenWorm"
tags = ["DevoWorm", "Bradly Alicea"]
date = "2016-04-06"
+++

<p align="center">
    <img src="https://3.bp.blogspot.com/-joTW__0vd-U/VwVRGry5bgI/AAAAAAAAKvU/nxbMN7zqE-Uas78Az2iiSsVPelyBZHezw/s320/photo-main.jpg"/>
</p>

Next Friday (4/15) at 9:00am Pacific Time, I will be presenting an update to the [OpenWorm Journal Club](https://www.youtube.com/user/OpenWorm) on advances in the DevoWorm subproject (How a Worm Develops). It has been a year and a half [since the previous update](http://syntheticdaisies.blogspot.com/2014/09/upcoming-devoworm-talk-to-openworm-group.html) [1], and we have made significant progress on a number of fronts:

* as of right now, our group consists of [myself](https://bradly-alicea.weebly.com/), [Richard Gordon](https://en.wikipedia.org/wiki/Richard_Gordon_(theoretical_biologist)), [Tom Portegys](http://tom.portegys.com/), [Steve McGrew](http://www.nli-ltd.com/), and Gabriel Pascualy.

* DevoWorm now consists of three interests groups, all of which are fairly informal: Digital Morphogenesis, Developmental Dynamics, and Reproduction and Developmental Plasticity. It is hoped that as the project matures and attracts more collaborators, the interest groups will keep the subproject focused on specific goals.

<p align="center">
    <img src="https://2.bp.blogspot.com/-J6kNbkAenLk/VwVRLRRT46I/AAAAAAAAKvY/nw6t827D5pQE24jdQaWaQE62yYNs2XpzQ/s200/devoworm-logo.png"/>
</p>

Tom, Steve, and Gabriel have been taking the lead on the Morphozoic platform, which is part of the Digital Morphogenesis interest group. Morphozoic is a hybrid model (Cellular Automata/ANN) that can approximate morphogenetic processes. The Cellular Automata component utilizes an approach called nested neighborhoods that captures the action of cell-cell communication and signaling gradients in a way conventional [Moore neighborhoods](https://en.wikipedia.org/wiki/Moore_neighborhood) do not. Tom has also produced a number of demos ranging from simulating biological pattern formation to image processing. This work will be featured in an soon to be published book chapter [2].

Richard Gordon and myself have been taking the lead on the Developmental Dynamics interest group. To this end, we have worked out differentiation trees [3] for [Caenorhabditis elegans](https://figshare.com/articles/dataset/C_elegans_Embryonic_Differentiation_Tree_10_division_events_/2118049) [4] and [Ciona intestinalis](https://figshare.com/articles/figure/C_intestinalis_Embryonic_Differentiation_Tree_1_to_112_cell_stage_/2117152) [5]. Differentiation trees are essentially reorganizations of the lineage tree based on the size differential of daughter cells after a cell division event, and may point us to subtle spatial patterns such as the precursors of tissue formation. More generally, we have been attempting to work out cross-species comparisons of early embryonic development, as well as novel computational characterizations of both mosaic and regulative development in multiple species. Some of this work will be featured in an upcoming publication in a special issue of the journal Biology [6].

The Reproduction and Developmental Plasticity interest group is focused on the evolution and development of C. elegans [life-history](https://en.wikipedia.org/wiki/Life_history_theory), and stems from work I did in [Nathan Schroeder's Laboratory at UIUC](http://publish.illinois.edu/nematodes/) [7, 8]. So far, this interest group has involved [experimental evolution](https://en.wikipedia.org/wiki/Experimental_evolution) and the induction of [developmental plasticity](https://en.wikipedia.org/wiki/Developmental_plasticity) resulting from [L1 larval arrest](https://wormbase.org//species/all/phenotype/WBPhenotype:0000059#0--10) in mutant genotypes. This is the newest area of DevoWorm, but is a necessary component of understanding for working towards [whole-organism simulation](https://en.wikipedia.org/wiki/OpenWorm).

<p align="center">
    <img src="https://3.bp.blogspot.com/-0wtgKCtQLQM/VwVvy_yda1I/AAAAAAAAKvo/-90yY00WZUAhti5Cm-CbnfsIwT_4zacpA/s400/JClub-update.png"/>
</p>

<p align="center">
    All three DevoWorm project interest groups in their "2-cell phenotype". 
</p>

If you are interested in joining the DevoWorm group or just attending one of our group meetings, please attend the OpenWorm presentation or contact one of the current group members. More generally, the OpenWorm project is [currently recruiting volunteers](https://openworm.org/get_involved.html#scientist), so [fill out an application](https://docs.google.com/forms/d/e/1FAIpQLSdzVilyRX3z9e0PeAoQdXhBDiNXp2ugqpnT536xA2iQbLNymQ/viewform?formkey=dC1CUDQtTV82MEJJcjY0NjdCcHpYdmc6MQ#gid=0) and state your skills and specific interests. We are looking for people with a diversity of backgrounds, from hard-core programming and data analysis skills to science communication specialists and biologists with an interest in theoretical synthesis.


## NOTES:
[1] Alicea, B., McGrew, S., Gordon, R., Larson, S., Warrington, T., and Watts, M. (2014). [DevoWorm: differentiation waves and computation in C. elegans embryogenesis](https://www.biorxiv.org/content/10.1101/009993v1). bioRxiv, doi:10.1101/009993

[2] Portegys, T., Pascualy, G., Gordon, R., and Alicea, B. (2016). Morphozoic: cellular automata with nested neighborhoods as a novel representation for morphogenesis. Forthcoming in Multi-Agent Based Simulations Applied to Biological and Environmental Systems.

[3] Gordon, R. (1999). The Hierarchical Genome and Differentiation Waves: novel unification of development, genetics and evolution. World Scientific and Imperial College Press, Singapore and London.

[4] Alicea, B. and Gordon, R. (2016). [Caenorhabditis elegans Embryonic Differentiation Tree](https://figshare.com/articles/dataset/C_elegans_Embryonic_Differentiation_Tree_10_division_events_/2118049) (10 division events). doi:10.6084/m9. figshare.2118049.

[5] Alicea, B. and Gordon, R. (2016). [Ciona intestinalis Embryonic Differentiation Tree](https://figshare.com/articles/figure/C_intestinalis_Embryonic_Differentiation_Tree_1_to_112_cell_stage_/2117152) (1- to 112-cell stage). doi: 10.6084/m9.figshare.2117152.

[6] Alicea, B. and Gordon, R. (2016). Quantifying mosaic development: towards an Evo-Devo Postmodern Synthesis via differentiation trees of embryos. Biology (Special Issue: beyond the modern evolutionary synthesis). Submitted.

[7] Alicea, B. (2016). [Evolution in Eggs and Phases: experimental evolution of fecundity and reproductive timing in Caenorhabditis elegans](https://www.biorxiv.org/content/10.1101/042143v1). bioRxiv, doi:10.1101/042143.

[8] Alicea, B. (2016). [Genotype-specific developmental plasticity shapes the timing and robustness of reproductive capacity in Caenorhabditis elegans](https://www.biorxiv.org/content/10.1101/045609v1). bioRxiv, doi:10.1101/045609.



Posted by [Bradly Alicea](https://www.linkedin.com/in/bradlyalicea/)