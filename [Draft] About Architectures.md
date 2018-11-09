# Artificial Neural Nets V.S. Human Brain Nets - What have we missed in the architecture level?

There are two major theories of the brain's cognitive function - [the theory of modularity and the theory of distributive processing](https://en.wikipedia.org/wiki/Functional_specialization_(brain)). Instead of asking whether the brain and its regions are functionally interconnected or specialized, I tend to think of them as complementary to each other. 

For the modularity theory,  specialized regions that are domain specific for different cognitive processes. From the evolutionary perspective, human mind evolved with enhaced functionality developing as a result of increasingly fitting somewhere and gaining more adaptiveness, such as prefrontal cortex that handle high-level cognitive processes, visual area V4 and V5 in charge of the perception of color and vision motion.

For distributive processing, brain areas are highly interconnected and process information in a distributed manner. Thanks to technological advances of brain imaging techniques such as MRI and PET scans, neural interactions can be measured by analysis in neuroimaging, which provides more evidence to support the interaction theory of distributive processing. Many regions in the brain are physically interconnected in a nonlinear system, procuding behaviors as a result of a variety of system organizations.

The two theories can be combined to collaboratively characterize the functioning of the brain. Modularity is a matter of degree rather than a rigid separation, and the nervous system also integrates and connects the information produced in these regions.

===

One of the biggest breakthroughs for artificial neuron networks is to realize the importance of the idea of distributive representation, leading to much powerful expressivity. The specific meaning of each individual neuron unit is not neccessary, but instead the space spanned by a set of peer units carry a semantically meaningful manifold, sort of a collective productoin. Considering a fully-connected layer, each unit has access to its previous and next layers, receiving signals from all units in the previous layer and sending signals to all units in the next layer. There is no any specialization for each unit, since every unit has a similar role to one another. The only differences between each peer unit is their weights of connections to the two layers. Relying on such level of differences, one cannot expect that some sort of specialization and modularity will emerge. Of course, scalar units hold too limited information to carray subspace-level semantics and develop specialization, and thus we should consider multi-dimension neuron unit or neuron node envoloping a bunch of atomic units to build a gaint neuron network. From this point of view, a standard DNN would turn into a chain computation architecture by wrapping units of each layer into a neuron node, without any branch or bypass. Therefore, each time we run a forward pass, every node would be activated and then updated regardless of whether it should be or not. I guess the chain architecture may be one of the factors that cause catastrophic forgetting or the interference problem.

I tend to think of a multi-way graph-structured architecture instead of a single-way chain-structured architecture, with branching or mergining possibly occuring at any point, which can be seen as an ultimate exention to skip connections, lateral connections and highway. We can image a gaint high-dimensional mesh net with some fractal structure, that it, with local-scale structures that holds unforgetable details as well as global-scale structures that make any regions be able to interacte with one another and exchange information efficently. Moreover, this gaint mesh net will not be operated fully, but instead only a small fraction of nodes will be actived to interact, forming a small subgraph performing computation.

A quetion would be raised in the above computation framework - why do we pick the actived subgraph out of the gaint mesh net? This question actually implies a navigation problem that it requires choosing nodes and edges at each step.



Muliway

Meshnet

Imagination world

two-level navigation

Attention can be viewed as a virtual action that happens in human's mental world,

"Use Yi (use wish), don't use Li (apply force)" old philosophy from Chinese Tai Chi martial art.

Attention is a mental action taken in our imagination world.
