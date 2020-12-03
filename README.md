# Day-Anderson-SubmittedToGRL
This repository includes data associated with the article entitled "Wind erosion on Mars exposes ideal targets for sample return", currently in review for 
publication in Geophysical Research Letters. 

For questions or more information contact the corresponding author at daym@epss.ucla.edu 

Contents of this repository: 
1. Two data files representing input topography to Large Eddy Simulations 
2. Two data files presenting the dimensionless shear stress across the associated topography as modeled by LES 

Input topography from HiRISE digital elevation models: 
Topography used to perturb flow in this system is taken from a HiRISE DEM of the Jezero crater western delta deposit. For computational tractibility, the HiRISE DEM is 
down sampled to a resolution of 100 m/px. By convention, data files begin with "h" and are followed by the direction of wind modeled in the associated simulation (direction
from which the wind blows). Note that the topography in hE and hSW is the same, but rotated so that the wind forcing is in the +x direction. 

Output shear stress distribution: 
The Large Eddy Simulation numerically models the interactions between a turbulent atmosphere and topogrpahic obstacles. The resulting output is a dimensionless distribution of
shear stress across the domain. See the full manuscript text for a detailed description of this raw output. 

