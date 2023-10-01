# Neuroevolution for Compiler Code Optimization Control

This repo contains work performed for a workshop paper presented at GECCO 2023. 
The accompanying PDF is the longer, non-printed manuscript that was submitted as part of the MSc in Artificial Intelligence and Adaptive Systems.

This project uses FAIR's/Meta Research's CompilerGym environment in combination with Ray and Evosax in order to evolve neural network policies for optimizing binary executables for minimum code size during compilation.

```
@inproceedings{10.1145/3583133.3596380,
author = {Heckel, Kade},
title = {Neuroevolutionary Compiler Control for Code Optimization},
year = {2023},
isbn = {9798400701207},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3583133.3596380},
doi = {10.1145/3583133.3596380},
abstract = {The optimization performed by compilers when generating executable programs is critical for software performance yet tuning this process to maximize efficiency is difficult due to the large number of possible modifications and the almost limitless number of potential input programs. To promote the application of artificial intelligence and machine learning to this challenge, Facebook Research released Compiler Gym[1], a reinforcement learning environment to allow the training of agents to perform compiler optimization control on real C/C++ programs. Whereas previously published approaches use techniques such as Proximal Policy Optimization or Deep Q Networks, this work utilizes neuroevolution and achieves competitive performance on the cBench-v1[2] program set while demonstrating the highly adaptive properties of the neuroevolution approach.},
booktitle = {Proceedings of the Companion Conference on Genetic and Evolutionary Computation},
pages = {2362–2365},
numpages = {4},
keywords = {compilers, neuroevolution},
location = {Lisbon, Portugal},
series = {GECCO '23 Companion}
}
```
