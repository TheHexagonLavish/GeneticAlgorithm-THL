GeneticAlgorithm-THL
====================

<h2> **README IN PROGRESS**</h2>


<h3>Genetic algorithm for personal environments</h3>

<strong>Description</strong>:


Originally, <strong>PIR</strong> (Premier Information Retrieval®) was a research project that was to be developed for the purpose of "penetrating"
an individual's  personal environment via means of retrieving data from outside the parameters of patterns 
and perform retrieval of information on the boundaries of six <i>set</i> points of data. 
<strong>PIR</strong> is multi-faceted in the context that this software will be utilized in multiple 
erformances of customized "events" for different purposes. This genetic algorithm is just one part 
of many stages of <strong>PIR</strong> and its capabilities.

This genetic algorithm is part of the ongoing research project, <strong>PIR</strong>.
It is based on simple comparisons between individuals but I want the program to simulate a convergence of 
restricted mating sequences. This program was developed so that the genetic algorithm retrieves information
about the current population (i.e., "parent") and allocates that data for the next population (i.e., "child")
by "reminding" the algorithm of the current population's scaling. Once a population has been scaled, the
statistic gets updated per generation. At least, that's what I'm trying to do.

In this project, the population's overall fitness will increase over time due to how the GA works; to create a new
population, there are three basic ways of doing so:

1. [Elite] children
2. Crossover
3. Mutation

Elite children are the elements that represent the population with the highest fitness. Since the GA in this project
will be programmed to scale a statistic to the next generation, a fixed number of elite children will automatically
be allocated to the next generation as well. 

Crossover is when two individuals are combined to produce two offspring. Parents are chosen probabilistically according
to an individual hypothesis. Mutation is applied to the population with a percentage of the population chosen
with uniform probability and each chosen individual has a random bit inverted. 

It's intended that the GA will be an addition to the PCA model and Gaussian mixture models that will also be attributed
to the <strong>PIR</strong> research project. 


<h3>© 2013 The Hexagon Lavish. All Rights Reserved.</h3>

<i>Permission to modify this software program for the purpose
of being contributive to the programming of this software,
is hereby granted on the condition that the above copyright notice 
appear in all copies and that both the copyright notice and this 
permission notice and warranty disclaimer appear in supporting documentation, 
and that the name of Desmond J. Watson not be used in advertising or publicity 
pertaining to distribution of the software without specific written prior permission.</i>

<i>The owners of this software, Desmond J. Watson and The Hexagon Lavish, 
disclaims all warranties with regards to this software, including all implied
warranties of merchantability and fitness. In no event shall the owners
of this software, Desmond J. Watson or The Hexagon Lavish, be liable for 
any special, indirect or consequential damages or any damages whatsoever 
resulting from loss of use, data or profits, whether in an action of contract, 
negligence or other tortious action, arising out of or in, connection with the 
use or performance of this software.</i>
