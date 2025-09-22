# Projects

- <h2>Primal Dual Linear Programming on AMD GPUs in PyTorch</h2>
<h4>June-September 2025</h4>
I was part of a four person team working with AMD and IPAM (Instute for Pure and Applied Mathematics) aiming to implement a convex optimization algorithm using PyTorch to solve linear programs.
The algorithm is called the 'Primal Dual Hybrid Gradient Method', and is easily accelerated by GPUs with parallelization. The project sought to see if this could be done using PyTorch, instead of more complicated kernel optimization and C code, enabling developers to easier 'see' what's going on compared to other implementations.

This project culminated in the release of an open source python package: simply run <i>pip install torchPDLP</i>, which will be updated periodically. Our repository can be found <a href="https://github.com/SimplySnap/torchPDLP">here</a>. For bugs, please report them on github and we will update the package periodically. A final report containing our results can be found <a href="https://arxiv.org/abs/2508.16806v1">here</a>. Our implementation yielded orders of magnitude of speedup on large LP instances when compared to CPU methods.

Finally, I developed a fully novel parallel algorithm to find a better starting point for general convex optimization problems. This is called 'fishnet casting' and is inspired by genetic algorithm literature: crossover, mutation and selection. This has yielded mixed results, though seems to scale better with size of problems. After a month of fine tuning, I have put this idea on pause, simply because fishnet was based on an assumption that the Primal Dual Hybrid Gradient algorithm is very start-point sensitive in runtime, which, through testing, I have validated it is not.
Though this enhancement (a more basic form), is found in the master branch & python package, a more robust implementation is found <a href="https://github.com/SimplySnap/torchPDLP/branches/fishnet-casting">here</a>.


<p></p>
- <h2>Game-Playing Agent: using Markov Searches, alpha-beta pruning and other strategies to play games on the fly</h2>
<h4>April-June 2025</h4>
In this project, I was part of a team of three, designing an 'intelligent' agent, able to play any game on the fly. The project included implementing algorithms like Markov Tree Searches, minimax, persistent tree search, and other strategies from the early AI literature. Think a connect four robot, chess engine, tic tac toe tool and catan player all in one.


<p></p>
- <h2> Wildfire Prediction: supervised and unsupervised learning for wildfire insights from satellite data</h4>
<h4>February-April 2025</h4>
I worked in a team of three cleaning and analysing NASA satellite datasets using supervised methods (NNs, Random Forests) and unsupervised methods (DBSCAN). The goal was to better understand what environmental variables make wildfires more likely, and to better recognize when satellite 'fire pixels' actually correspond to wildfires.

<p></p>
- <h2>Strange Attractor Art: graphing unique & beautiful strange attractors</h2>
<h4>2023</h4>
Generating strange attractors in python.
div style="display: flex; flex-direction: row; gap: 10px;">
  <img src="/projects/attractor_1.png" alt="Strange Attractor 1" style="height:150px;"/>
  <img src="/projects/attractor_2.png" alt="Strange Attractor 2" style="height:150px;"/>
  <img src="/projects/attractor_3.png" alt="Strange Attractor 3" style="height:150px;"/>
</div>

<p></p>
- <h2>Native Plant Restoration: designing and stewarding California-native gardens for ecosystem resilience</h2>
<h4>September 2024-Present</h4>
Independent work improving local plant biodiversity, managing invasive species like Chinese Sumac, ensuring year-round pollinator food sources, and spreading milkweed for endangered Monarch butterflies. A deeply rewarding hobby to make a change from mathematics.
<video controls style="max-width: 100%; height: 300px;">
  <source src="/projects/hbird_vid.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>