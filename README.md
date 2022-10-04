# BennettLab_MSB_2020_Code
Contains all the code to recreate results for the paper published in bioRxiv in 2022: "Tunable dynamics in a multi-strain transcriptional pulse generator" (Matthew Bennett's lab at Rice University)


To run the jupyter notebooks, one needs to have the following software installed:

1- Python 3.7
2- Jupyter Notebook
3- PyStan 

Note: Stan is a software package that implements Hamiltonian Monte Carlo (HMC) that is a Bayesian inference method for sampling posterior probability distribution over parameters of a model. PyStan is the Python interface for Stan. Please see https://mc-stan.org/ for more details about Stan. For installing PyStan, please follow the steps given in https://pystan.readthedocs.io/en/latest/windows.html#windows.


For each figure in the main text and the supplement, there is an individual notebook that can be run to create it. "Index.ipynb" contains a link to each notebook. 

Also there is a notebook for the implementation of the Bayesian inference that uses Hamiltonian Monte Carlo (HMC). The HMC is implemented in the software Stan. One does not need to know the details of the Hamiltonian Monte Carlo method to be able to re-run the Bayesian inference implementation. You can change some inputs of the Bayesian inference algorithm (such as the number of iterations or prior distributions of the parameters) and run your own inference and compare the results. 
Our inference results that are used in the paper are saved in the file fitResults1.pkl.
