Models were trained using the following details:
- covariates = age (years)
- algorithm = Hierarchical Bayesian Regression
- hyperparameters = Bspline models, batch effects for site and sex  (0=F, 1=M)
- configurations 
	likelihood = 'SHASHb'
	model_type = 'bspline'
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
- age range = 6.1 - 17.1 (mean = 11.2, std = 2.3)
- voxel/IDP = IDP
	Parcellation based on [King et al. 2019, Nature Neuroscience](https://www.nature.com/articles/s41593-019-0436-x).
	IDPs  1-10 = Volume (summed Jacobian determinants)
	IDPs 11-20 = GMD (mean within parcel)
	IDPs 21-30 = WMD (mean within parcel)
	
For additional information on the models, please see Gaiser et al. 2023 [bioRxiv](https://www.biorxiv.org/content/10.1101/2023.04.26.538263v1).
