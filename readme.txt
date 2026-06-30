## Folder Structure

- apical/: XOR computation performed by the apical dendrite
- apical_soma/: XOR computation performed by the soma, with synapses on the apical dendrite
- basal/: XOR computation performed by the basal dendrite
- basal_soma/: XOR computation performed by the soma, with synapses on the basal dendrite

Within each folder, subfolders "distributed" and "focal" correspond to dispersed and clustered synaptic distributions, respectively.

In each folder, the main simulation file to run is: mymodel_spiny_ampa_nmda_dcaspk.hoc

All simulations were run using NEURON(https://www.neuron.yale.edu/neuron/).