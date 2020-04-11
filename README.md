# Literature-Review-On-Knowledge-Distillation
Notes and highlights of my footprints upon Knowledge Distillation for ML in the Edge  
This is a note on the papers I found and read on knowledge distillation.
#ML in the Edge 
Reference [Embedded Machine Learning Design for Dummies](https://pages.arm.com/machine-learning-for-dummies.html)

Notes:
* Edge device doesn't do training but inference only, and can do data collection. Cloud does the training.
* Edge: IoT device, Edge Server, or other Edge Device
* Drawbacks of Cloud-Local Edge: latency and reliability (vechile), power cost for data transmission, privacy, less accessible to local environment and personalisation.
* Trends of ML-Edge: **Reliable**, **Responsive**, **Secure**, **Less Power Requirements**, and **Independent to Internet Connections**.)
* Deploy ML-Edge: flexibility between hardware and model capability
	- Use Cases
	- Perfect model for the best performance trade-off
	- Hardware Selection: lower-capacity device on reduced accuracy model, and how to adapt the ML model for a given device (finetuning)
	- Team development tools
	- **Balance those issues w.r.t. the best Unit Cost**

#Knowledge Distillation and ML-Edge

ML in Edge requires model compression and acceleration. To fulfil these two goals, there are four key techniques: **designning efficient and small NN**, **pruning pre-trained NN**, **quantisation**, and **knowledge distillation**(KD).

The main motivation of KD is to transfer the learned knowledge from the teacher model(s), which is normally large and complicated to a relatively simpler and smaller student model, which is suitable to be deployed into edge devices. There are two mainstream of KD: from deep large to shallow and small, and from ensembles of classifiers to an individual classifier. 

The brief KD pipline is: 
1. Get the teacher model: train from large dataset or pre-trained models
2. Train the student model: train with true labels and logits of the teacher model(s) via a combined loss function. ![](https://latex.codecogs.com/gif.latex?a=b&plus;c*2)


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