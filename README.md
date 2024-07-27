# Automatic Prediction of Molecular Properties Using Substructure Vector Embeddings within a Feature Selection Workflow

All source code and images are associated with the paper:

"Automatic Prediction of Molecular Properties Using Substructure Vector Embeddings within a Feature Selection Workflow" 

By S. G. Jung, G. Jung & J. M. Cole



## Introduction

The description of each file is summarized below:

*(i) smile_descriptors.py*

Script to generate descriptor features based on SMILES of chemical molecules & solvents. 

*(ii) feature_analyses.py*

Script to perform statistical feature analyses

*(iii) feature_engineering.py*

Script to perform feature engineering. By default, a brute-force method is used.

*(iv) GBFS.py*

Script to perform gradient boosted feature selection, generate feature ranking, and carry out recursive feature selection. See "Gradient Boosted and Statistical Feature Selection" in [https://github.com/Songyosk/GBSFS4MPP](https://github.com/Songyosk/GBFS4MPPML).

*(v) Multicollinearity_reduction.py*

Script to perform multicollinearity reduction, which includes correlation analysis and hierarchical clustering analysis. Correlation and linkage thresholds are defined to elminate features. 

*(vi) permutation_importance.py*

Script to analyze and identify features that are importance when permutation is performed

*(vii) recursive_feature_elimination.py*

Script to perform recursive feature elimination 

*(viii) optimization.py*

Script to perform Bayesian optimization, which determines the architecture of the predictive model based on a defined hyperparameter space.  

*(ix) utilities.py and read_json.py*

Scripts containing helper functions 



## Acknowledgements
J.M.C. is grateful for the BASF/Royal Academy of Engineering Research Chair in Data-Driven Molecular Engineering of Functional Materials, which is partly sponsored by the Science and Technology Facilities Council (STFC) via the ISIS Neutron and Muon Source; this Chair is supported by a PhD studentship (for S.G.J.). STFC is also thanked for a PhD studentship that is sponsored by its Scientific Computing Department (for G.J.).


## 🔗 Links
[![portfolio](https://img.shields.io/badge/Research_group-000?style=for-the-badge&logo=ko-fi&logoColor=white)](http://www.mole.phy.cam.ac.uk/)


## License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
