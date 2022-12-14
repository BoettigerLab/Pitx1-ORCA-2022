# Boundary stacking interactions enable cross-TAD enhancer-promoter communication during limb development

Tzu-Chiao Hung<sup>a,\*</sup>, David M. Kingsley<sup>a, b</sup>, Alistair N. Boettiger<sup>b</sup>, 

<sup>a</sup> Department of Developmental Biology, Stanford University School of Medicine, Stanford, CA 94305, USA

<sup>b</sup> Howard Hughes Medical Institute, Stanford University School of Medicine, Stanford, CA 94305, USA

Correspondence: boettiger@stanford.edu 


This repository contains original code and model parameters to used in the analyses and simulations described in our work investigating chromatin folding at the Pitx1 locus in mammalian limb development using Optical Reconstruction of Chromatin Architecture.

The intention of this repository is to make the transparent the workflow behind the data analysis and behind the simulations.  

The chromatin tracing image data is deposited at the [4DN data portal](https://data.4dnucleome.org/) and can be retrieved there, following publication and public release.  We will update the link here when it is available.  

To run the polymer simulations, this code requires the open-access [polychrom repository](https://github.com/open2c/polychrom) developed by the open2c team.  We added several additional functions to the repository to allow non-uniform loading of Cohesin.  These additions can be found in our open-access fork of the project, [https://github.com/BoettigerLab/polychrom](https://github.com/BoettigerLab/polychrom).  

Project Abstract: 
While long-range enhancers and their target promoters are frequently contained within a TAD, many developmentally important genes have their promoter and enhancers within different TADs. Hypotheses about molecular mechanisms enabling cross-TAD interactions between cis-elements remain to be assessed. To test these hypotheses, we use Optical Reconstruction of Chromatin Architecture (ORCA) to characterize the conformations of the Pitx1 locus on thousands of single chromosomes in developing mouse limbs. Our data supports a model in which neighboring boundaries are stacked with each other as a result of loop-extrusion, bringing boundary-proximal cis-elements into contact. This stacking interaction also explains the appearance of architectural stripes in the population average maps (eg. Hi-C data). Through molecular dynamics simulations, we further propose that increasing boundary strengths facilitates the formation of the stacked boundary conformation, counter-intuitively facilitating border bypass. This work provides a revised view of the TAD borders’ function, both facilitating as well as preventing cis-regulatory interactions, and introduces a framework to distinguish border-crossing from border-respecting enhancer-promoter pairs. 