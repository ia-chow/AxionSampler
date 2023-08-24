# AxionSampler

Important notebooks:

**rosenbrock_function_sampling_mcmc.ipynb** and **rosenbrock_function_sampling_nested.ipynb**
demonstrate implementation of MCMC and nested sampling, using emcee and PyMultiNest 
respectively, to sample a test function (in this case the 2d Rosenbrock function)

**2d_u_function_sampling.ipynb** shows the result of MCMC and nested sampling on a test 
u-shaped 2D function (analogous to the $\Omega_a - m_a$ plane of the actual ULA distribution)

**3d_u_function_dm.ipynb** and **3d_u_function_de.ipynb** show the marginalized $\Omega_a - m_a$ 
contours of the u distribution for 3D, using DM and DE as the third parameter 
respectively

**4d_u_function_MCMC_NESTED.ipynb** shows the theoretical marginalized $\Omega_a - m_a$
contours of the full test 4d function, as well as the results of MCMC and nested sampling

**Planck_analysis_edited.ipynb** contains the work-in-progress of getting the sampling
using the DE and DM emulators to work with mass as a free parameter
