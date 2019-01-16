---
layout: default
title: ariaDNE 
description: course webpage
--- 
## ariaDNE: A Robustly Implemented Algorithm for Dirichlet Normal Energy

[Shan Shan](https://sshanshans.github.io) &emsp; &emsp; Shahar Z. Kovalsky &emsp; &emsp; Julie M. Winchester &emsp; &emsp; Doug M. Boyer &emsp; &emsp; Ingrid Daubechies

![teaser](./ariadne/teaser.jpg?raw=true)

[Paper](https://besjournals.onlinelibrary.wiley.com/doi/abs/10.1111/2041-210X.13148) &emsp; &emsp; &emsp;  [Supplementary](https://besjournals.onlinelibrary.wiley.com/action/downloadSupplement?doi=10.1111%2F2041-210X.13148&file=mee313148-sup-0001-AppendixA.pdf)  &emsp; &emsp; &emsp; [Code](https://github.com/sshanshans/ariaDNE)

### Abstract
The *Dirichlet energy of the normal* measures how much a 3D surface bends; DNE, a discretized version for 3D meshes, is effective for biological studies of morphological surfaces. Recent studies found that the DNE algorithm is sensitive to various surface preparation procedures, raising concerns regarding comparability and objectivity when utilizing DNE in morphological research. We provide *a* *r*obustly *i*mplemented *a*lgorithm for computing the Dirichlet normal energy (ariaDNE) on 3D meshes. We show that ariaDNE is much more stable than DNE when preparation-related mesh surface attributes such as resolution (polygon count), mesh representation (i.e., a different set of points/nodes or triangles representing the same continuous surface) and noise are varied through simulation. We also show that the effects of smoothing and boundary faces are more limited on ariaDNE than DNE. Further, ariaDNE retains the potential of DNE for biological studies, illustrated by it effectively differentiating species by dietary preferences. AriaDNE can be a useful tool to uniformly quantify shape on samples of surface meshes collected with different instruments or at different resolutions, and prepared by varying procedures. To facilitate the field to move towards this goal, the supplementary materials provide ariaDNE values for specimens used in previously published DNE analyses. Scripts for computing ariaDNE can be found by link within this manuscript.

### ariaDNE for previously published DNE analysis
* [Boyer, Doug M. "Relief index of second mandibular molars is a correlate of diet among prosimian primates and other euarchontan mammals." Journal of Human Evolution 55.6 (2008): 1118-1137.](./ariadne/mesh73.csv)
* [Bunn, Jonathan M., et al. "Comparing Dirichlet normal surface energy of tooth crowns, a new technique of molar shape quantification for dietary inference, with previous methods in isolation and in combination." American Journal of Physical Anthropology 145.2 (2011): 247-261.](./ariadne/mesh88.csv)
* [Winchester, Julia M., et al. "Dental topography of platyrrhines and prosimians: convergence and contrasts." American Journal of Physical Anthropology 153.1 (2014): 29-44.](./ariadne/mesh89.csv)
* [Pampush, James D., et al. "Wear and its effects on dental topography measures in howling monkeys (Alouatta palliata)." American journal of physical anthropology 161.4 (2016): 705-721.](./ariadne/meshP.csv)
* [Pampush, James D., et al. "Introducing molaR: a new R package for quantitative topographic analysis of teeth (and other topographic surfaces)." Journal of Mammalian Evolution 23.4 (2016): 397-412.](./ariadne/mesh192.csv)
* [Prufrock, Kristen A., Doug M. Boyer, and Mary T. Silcox. "The first major primate extinction: an evaluation of paleoecological dynamics of North American stem primates using a homology free measure of tooth shape." American journal of physical anthropology 159.4 (2016): 683-697.](./ariadne/mesh194.csv)
* [López-Torres, Sergi, et al. "Dental topographic analysis of paromomyid (Plesiadapiformes, Primates) cheek teeth: more than 15 million years of changing surfaces and shifting ecologies." Historical Biology 30.1-2 (2018): 76-88.](./ariadne/mesh345.csv)
* [Pampush et al. "Atelidae Adaptive Dental Topography Dynamics."](./ariadne/mesh509.csv)
* [Pampush et al. "Howler Wear Project."](./ariadne/mesh203.csv) 
* [M. A. Berthaume and K. Schroer. "Extant ape dental topography and its implications for reconstructing the emergence of early homo. Journal of human evolution." 112:1529, 2017.](./ariadne/berthaume2017.csv)
* [M. A. Berthaume, et al. "Dental topography and the diet of homo naledi." Journal of human evolution, 118:14-26, 2018.](./ariadne/berthaume2018.csv)





<br/>
<br/>
<br/>
