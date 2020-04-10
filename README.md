# Literature-Review-On-Knowledge-Distillation
Notes and highlights of my footprints upon Knowledge Distillation for ML in the Edge  
This is a note on the papers I found and read on knowledge distillation.

#Knowledge Distillation and ML in Edge

ML in Edge requires model compression and acceleration. To fulfil these two goals, there are four key techniques: **designning efficient and small NN**, **pruning pre-trained NN**, **quantisation**, and **knowledge distillation**(KD).

The main motivation of KD is to transfer the learned knowledge from the teacher model(s), which is normally large and complicated to a relatively simpler and smaller student model, which is suitable to be deployed into edge devices. There are two mainstream of KD: from deep large to shallow and small, and from ensembles of classifiers to an individual classifier. 




#paper lines:
## How it begins?
Hinton, Geoffrey, Oriol Vinyals, and Jeff Dean. "Distilling the knowledge in a neural network."arXiv preprint arXiv:1503.02531(2015).
## How it develops?
Problems to solve:
1. N teacher : M student
2. Teacher selection
3. Parameter Refinement 
4. 

### pure KD
### KD in Edge area
### Recent papers in Top-tier conferences
## Hints and the Future
## Hands on small demos