# Projects
<h2>Parallel Particle Swarm Optimization</h2>
<h4>April-June 2026</h4>
Particle Swarm Optimization (PSO) is a metaheuristic based optimization method that excels at solving non-convex and non-differentiable optimization problems. I worked in a team of three desiging a highly performant CUDA implementation of PSO for GPUs.

We also used MPI to coordinate multi-swarm optimization across clusters, investigating throughput and solution quality with different mutli-swarm communication topology.

<p></p>

<h2>Entropy in Environmental Spatial Cyclic Games</h2>
<h4>September-December 2025</h4>
I led the programming side of a team of three investigating nonlinearity and entropy in environmental spatial cyclic games. These are phenomena found in nature, where species interactions across space leads to cyclic interactions between species where group dynamics balance, reaching stationarity with some repeating frequency. We investigated long term dynamics under changing parameters in a three species game akin to Rock Paper Scissors.

As part of this team, I coined a new type of system entropy that quantifies the complexity of inter-species spatial boundaries. I then wrote parallelized implementations of the game and investigated how different parameters lead to different entropic behaviour. This project combined parallel algorithm design with PDEs and mathematical biology. Very fun.

<p></p>
<h2>Graph Neural Cellular Automata</h2>
<h4>October-December 2025</h4>
I worked in a team of two designing graph machine learning models that learnt cellular automata dynamics on graphs.

<p></p>
<h2>Primal Dual Linear Programming on AMD GPUs in PyTorch</h2>
<h4>June-September 2025</h4>
I was part of a four person team working with AMD and IPAM (Instute for Pure and Applied Mathematics) aiming to implement a convex optimization algorithm using PyTorch to solve linear programs.
The algorithm is called the 'Primal Dual Hybrid Gradient Method', and is easily accelerated by GPUs with parallelization. The project sought to see if this could be done using PyTorch, instead of more complicated kernel optimization and C code, enabling developers to easier 'see' what's going on compared to other implementations.

This project culminated in the release of an open source python package: simply run <i>pip install torchPDLP</i>, which will be updated periodically. Our repository can be found <a href="https://github.com/SimplySnap/torchPDLP">here</a>. For bugs, please report them on github and we will update the package periodically. A final report containing our results can be found <a href="https://arxiv.org/abs/2508.16806v1">here</a>. Our implementation yielded orders of magnitude of speedup on large LP instances when compared to CPU methods.

Finally, I developed a fully novel parallel algorithm to find a better starting point for general convex optimization problems. This is called 'fishnet casting' and is inspired by genetic algorithm literature: crossover, mutation and selection. This has yielded mixed results, though seems to scale better with size of problems. After a month of fine tuning, I have put this idea on pause, simply because fishnet was based on an assumption that the Primal Dual Hybrid Gradient algorithm is very start-point sensitive in runtime, which, through testing, I have validated it is not.
Though this enhancement (a more basic form), is found in the master branch & python package, a more robust implementation is found <a href="https://github.com/SimplySnap/torchPDLP/branches/fishnet-casting">here</a>.


<p></p>
<h2> Wildfire Prediction: supervised and unsupervised learning for wildfire insights from satellite data</h4>
<h4>February-April 2025</h4>
I worked in a team of three cleaning and analysing NASA satellite datasets using supervised methods (NNs, Random Forests) and unsupervised methods (DBSCAN). The goal was to better understand what environmental variables make wildfires more likely, and to better recognize when satellite 'fire pixels' actually correspond to wildfires.

<p></p>
<!-- 
<h2>Strange Attractor Art: graphing unique & beautiful strange attractors</h2>
<h4>2023</h4>
Generating strange attractors in python.
<div style="display: flex; flex-direction: row; gap: 10px;">
  <img src="/projects/attractor_1.png" alt="Strange Attractor 1" style="height:150px;"/>
  <img src="/projects/attractor_2.png" alt="Strange Attractor 2" style="height:150px;"/>
  <img src="/projects/attractor_3.png" alt="Strange Attractor 3" style="height:150px;"/>
</div> >

<p></p>
<h2>Native Plant Restoration: designing and stewarding California-native gardens for ecosystem resilience</h2>
<h4>September 2024-Present</h4>
Independent work improving local plant biodiversity, managing invasive species like Chinese Sumac, ensuring year-round pollinator food sources, and spreading milkweed for endangered Monarch butterflies. A deeply rewarding hobby to make a change from mathematics.
<center><video controls style="max-width: 100%; height: 300px; justify-content:center;">
  <source src="/projects/hbird_vid.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video></center>