# Curated_Repository

A selection of some programs I've written over the course of my research and learning that were particularly challenging or interesting to implement.

1. Implementation of Frontier based Binary Decision Diagram construction algorithms: 

   a. For simple paths: https://github.com/LorenzoNajt/TinyProjects/blob/master/ConnectedPartitionSampling/BDD/SIMPATH.py

   b. For connected partitions: https://github.com/LorenzoNajt/TinyProjects/blob/master/ConnectedPartitionSampling/BDD/Flats.py

   (Note: These were extremely finicky to code correctly. I ended up validating them against OEIS, but I'd like to find a better system if I have to program something similar in the future. In general it would be better to use Graphillion for this exact task.)

2. Rejection sampling to get connected graph partitions: https://github.com/LorenzoNajt/TinyProjects/blob/master/ConnectedPartitionSampling/BDD/Fast_Rejection_sampling.py

   The main point of interest here is that this uses Numba to do something a little bit complicated with graphs.

3. Algorithm to find the dual of a plane graph: https://github.com/LorenzoNajt/TinyProjects/blob/master/MarkovChains/Facefinder.py

