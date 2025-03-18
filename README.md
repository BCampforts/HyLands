# HyLands

## What is HyLands
HyLands is a landscape evolution model that simultaneously runs fluvial incision, sediment transport and deep seeted landslides
## User manual HyLands

Installation: 
 - Download and extract topotoolbox from: https://github.com/wschwanghart/topotoolbox (the HyLands branch, which is the default branch on the linked repository so nothing has to be adjusted, downloaded fodler will be named: topotoolbox-HyLands by default)
 - Before working with HyLands the directories and functions must be on the search path of Matlab. Enter following code into the command line: addpath(genpath(['C:\path\to\wherever\you\extracted\this\topotoolbox-HyLands']));
 - to verify installation: enter: doc HYLANDS (info on the model) or doc HYLANDS_set (info on the parameter values) in the command window.
 
Documentation: 
 - For documentation, and after adding the topotoolbox folder to the path, enter: doc HYLANDS (info on the model) or doc HYLANDS_set (info on the parameter values) in the command window. 
        

HyLands comes with 1 tutorial (the example provided on the documentation page: doc HYLANDS), and 7 sripts, described in full length in the GMD discussion paper: Campforts B., Shobe M.C., et al. : HyLands 1.0: a Hybrid Landscape evolution model to simulate the impact of landslides and landslide-derived sediment on landscape evolution. Discussion paper in Geoscientific Model Development, https://geoscientific-model-development.net

All the scripts can be downloaded from https://github.com/BCampforts/pub_hylands_campforts_etal_GMD and executed in Matlab. 
- HyLands_NoLS_DL.m;    https://doi.org/10.5446/45969
- HyLands_NoLS_TL.m;    https://doi.org/10.5446/45967
- HyLands_NoLS_Mixed.m; https://doi.org/10.5446/45968
- HyLands_LS_NB.m;      https://doi.org/10.5446/45973
- HyLands_LS_B_LS.m;    https://doi.org/10.5446/45970
- HyLands_LS_LS.m;      https://doi.org/10.5446/45971
- HyLands_LS_A_LS.m;    https://doi.org/10.5446/45972


## Requirements

TTLEM/HyLands is plat-form independent and requires Matlab 2018a or higher 

## References

When you use HyLAnds/TTLEM, please reference to this publication:

 
  HyLands: Campforts B., Shobe M.C., et al. : HyLands 1.0: a Hybrid
  Landscape evolution model to simulate the impact of landslides and
  landslide-derived sediment on landscape evolution. Discussion paper in
  Geoscientific Model Development  
 
  TTLEM: Campforts, B., Schwanghart, W., & Govers, G. (2017). 
  Accurate simulation of transient landscape evolution
  by eliminating numerical diffusion: the TTLEM 1.0 model. Earth Surface
  Dynamics, 5(1), 47–66. https://doi.org/10.5194/esurf-5-47-2017

Other relevant publications: 

Campforts, B. and Govers, G. (2015): Keeping the edge: A numerical method that avoids knickpoint smearing when solving the stream power law, J. Geophys. Res. Earth Surf., 120(7), 1189–1205, [doi:10.1002/2014JF003376] 
https://www.researchgate.net/publication/279957445_Campforts_and_Govers-2015-JGR_ES_Keeping_the_edge_SI

Schwanghart, W. & Scherler, D. (2014): TopoToolbox 2 – MATLAB-based 
software for topographic analysis and modeling in Earth surface sciences. 
Earth Surface Dynamics, 2, 1-7. [DOI: 10.5194/esurf-2-1-2014]
https://www.researchgate.net/publication/259706134_Short_Communication_TopoToolbox_2_-_MATLAB-based_software_for_topographic_analysis_and_modeling_in_Earth_surface_sciences
  
Schwanghart, W., Kuhn, N. J. (2010): TopoToolbox: a set of Matlab 
functions for topographic analysis. Environmental Modelling & Software, 
25, 770-781. [DOI: 10.1016/j.envsoft.2009.12.002]
https://www.researchgate.net/publication/223084856_TopoToolbox_A_set_of_MATLAB_functions_for_topographic_analysis

## Version History

HyLands V1.0 --- 15. March 2020 
- HyLands added to ttlem

V1.0 --- 25. June 2016 
- release
