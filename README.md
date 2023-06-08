# muon_electron scattering study using python
When muons with energy E_mu interacts with atoms/matters, one of the possible muon-electron elastic scattering. so, The electron due to the influence of the incoming muon, gets scattered off with an angle theta_e and with energy E_e'. Similarly, the muon gets scattered off with an angle of theta_mu and with energy E_mu'. The angles are measured with respect to a reference axis (here z-axis).

Here are some of the python codes :
- To creat a datasheet based on theoritical formulas of two body kinematics (for mu-e elastic scattering ) and using the datasheet plot the graph of theta_mu vs theta_e. The code 1te_tm_plot.ipyb represents the same.
- The code ML_modl.ipynb creates a Machine Learning model that takes theta_e and theta_mu as its input features and gives the energy of the incomming muon as its labels (output). Further it plots the graph of predicted energy and real energy of muons. And also does the gaussian fit to the histogram of the energy difference. This is necessary to get the accuracy of the model.
- The code ML_modl.ipynb shows how to read the output file (.root file) from the simulation and plot various graphs using uproot module.



The files required ,as an example to run these python codes, i.e. newmu_table.csv & scat_Be_500GeV_10Cr.root  are also available here.
