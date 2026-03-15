# The Mathematical Neuron
In **1943**, neurophysiologist Warren McCulloch and mathematician Walter Pitts published *"A logical Calculus of the Ideas Immanent in Nervous Activity"*, the first mathematical model of a neural network.

Working at the University of Chicago, they showed that simple binary threshold units could, in principle, compute logical functions. This was done with neurons that are activated (output of 1) or inactivated (output of 0) based on a weighted sum of inputs. If the weighted sum exceeds a threshold, it is activated. Otherwise the neuron is deactivated.

This architecture contrasts from later architectures that use a 'weight and bias' architecture that allows neurons to be activated on a spectrum. The architecture McCulloch and Pitts use is much closer to how the brain works with a threshold that a neuron's excitation along the axon (connection) must exceed to fire an electrical potential.

## Assumptions 
McCulloch and Pitts make certain assumptions that are helpful to note:
1. The activity of a neuron is an "all-or-none" process.
2. A certain fixed number of synapses must be excited within the period of latent addition in order to excite a neuron at any time.
3. The structure of the net does not change with time.

Notably the last assumption is very different to more recent architectures of machine learning models that allow a dynamic architecture of weights and neuron biases based on results from backpropagation. 

## Limitations
Though this is a mathematical model of the function of neurons and can allow for computation with the use of logic gates, the most important feature of learning (the adustment of weights) is still absent and must be manually input and tuned. The next question was if a machine could lear its own weights and adjust them programmatically.