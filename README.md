# SUSY
Experimenting Machine Learning Techniques on SUSY dataset.

##  Dataset

I'm using a montecarlo generated SUSY dataset. This dataset introduced in [1], The supersymmetry data set consists of 5,000,000 Monte-Carlo samples of supersymmetric and non-supersymmetric collisions with 18 features. The signal process is the production of electrically-charged supersymmetric particles which decay to W bosons and an electrically-neutral supersymmetric particle that is invisible to the detector. 

The first 8 features are considered low which means that they can directly be measured from collisions. The other 10 are high-level featured which means that they are reconstructed (reconstruction in particle physics means hand constructed based on our physics knowledge). These high-level features are known to be important in our classification problem. 

SUSY Dataset can be downloaded from this Github repository [releases](https://github.com/MohamedElashri/SUSY/releases/tag/1). 

## Project Purpose 

I want to have a real exercise about applying ML Algorithms on real particle physics dataset. Super-Symmetry is one of important searches conducted now and the paper presenting the original anslysis keeps room for improvment. My goal is to play with the dataset and try to get efficent and more accurate classification. Also the computation time and resources are always constrained so I will try to optimize that for our additional gain, if any. 




[1] Baldi, P., Sadowski, P. & Whiteson, D. Searching for exotic particles in high-energy physics with deep learning. Nat Commun 5, 4308 (2014). https://doi.org/10.1038/ncomms5308

