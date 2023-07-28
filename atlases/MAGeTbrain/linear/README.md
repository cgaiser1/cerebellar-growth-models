Models were trained using the following details:
- covariates = age (years)
- algorithm = Hierarchical Bayesian Regression
- hyperparameters = Linear models, batch effects for site and sex  (0=F, 1=M)
- configurations 
	likelihood = 'SHASHb'
	model_type = 'linear'
	alg = 'hbr'
	linear_mu='True'
	random_mu = 'True'
	random_intercept_mu='True'         
	random_slope_mu = 'True' 
	random_sigma = 'True'
	centered_sigma = 'True'
	random_intercept_sigma ='True'         
	random_slope_sigma = 'True'
	inscaler_type='standardize'
	outscaler_type='standardize'
- sample size = 7,270
- number of sites = 2 (Generation R study, see study details [here](https://link.springer.com/article/10.1007/s10654-016-0224-9))
- voxel/IDP = IDP
	Parcellation based on [Park et al. 2014, NeuroImage](https://www.sciencedirect.com/science/article/pii/S1053811914001840) ([github](https://github.com/CoBrALab/MAGeTbrain)) with additional vermal ROIs available from [CoBrA lab](https://www.cobralab.ca/) upon request.
	
For additional information on the models, please see Gaiser et al. 2023 [bioRxiv](https://www.biorxiv.org/content/10.1101/2023.04.26.538263v1).
