# Where to find what you need in my personnal jupyter notebook : 

### FOLDER HMC : 
    
    Basic_HMC_introduction 
        Introduction to the Basic HMC code written from scrach thanks to
        https://colindcarroll.com/2019/04/11/hamiltonian-monte-carlo-from-scratch/
           
    Modelisation_pymc3_Example
        simple model ax**2+bx where the distribution of a and b are recovered thanks to the pymc3 sampler
    
    pyhmc_introduction
        Introduction to understand how pyhmc works
    
    Speedtest_HMC
        Compares the speed of the basic HMC algorithm, pymc3 and pyHMC
        
        
        
### FOLDER Visibility

    Basic visibility visualisation
        First visualisation of the visibility for a simple model in 1 dimension
        
    Hera sim local 
        Local version of the code hera_sim 
        
    hera_visibility_gradient 
        tests the pymc3 method on the visibility simulated with hera_sim. This code tries to adapt hera_sim to compute the gradient.
    
    hera_visibility_introduction 
        tests the pymc3 method on the visibility simulated with hera_sim. This code uses the non gradient based sampler from pymc3. It shows the correlation between two parameters recovered.
        
    visibility_modelisation
        simple model of visibility in 1 dimension whith visualisation. Tests pymc3 on this model (classic sampler + gradient based sampler). 
        
    visibility_modelisation_2D
        Model of visibility in 2 dimensions with derivatives. First try of myhmc sampler. 
    
    visibility_modelisation_complete
        generalisation of visibility_modelisation_2D with a code that can compute many sources.
        
    visibility_theano
        I tried unsuccessfully to write the visibility into theano directly without convertin into theno.Op object
