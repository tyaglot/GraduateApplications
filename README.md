# GraduateApplications
Materials to support my graduate school applications.

(Dec 16th, 2020) Currently I am in the process of getting permission from my employer, Google, to actually put anything on here.
Apologies to any admissions committee member that checks this page before I am able to legally put anything up, my hands are tied.

What I would like to have here:
* The paper and code for CopyCheck, an image matching system integrating traditional feature descriptors and neural network derived image embeddings.
* TaggedMeans, the full batch multilabel embedding loss function used to train the embedding generator in CopyCheck.
* InvariantCores, another loss function that trains the network to generate split embeddings, one for the base image, and one for any modification (rotation, translation) applied to it. The goal being that the image and transformation embeddings can be fed into a generative feed forward network to recover the modified image, and the transformation embeddings derived from one image can be used to transform another.
* REVOLVER, Chiral Reversible Networks. A generalization of reversible networks (ala The Reversible Residual Network: Backpropagation Without Storing Activations, Gomez et al) to use multiple "lanes".
* RESOLVER, Chiral LSTM. Adaptation of the REVOLVER architecture to modify multiple lanes simultaneously and add LSTM style information gating.
