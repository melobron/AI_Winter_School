# AI_Winter_School
대한기계학회 2022동계 인공지능 강습

1. Pre-trained Models

	- TensorFlow Hub

2. Transfer Learning

	1. Categories

		<p align="center">
			<img src="./imgs/image1.png" />
		</p>

		- Inductive transfer learning (Multi-task learning): same domains but **different source/target Tasks**
		- Transductive transfer learning (Domain Adaptation): samd tasks but **different source/target Domains**
		- Unsupervised transfer learning: different Tasks/Domains
		- Domain Confusion
		- Zero-shot / One-shot / Few-shot learning  

	2. Methodologies

		- Parameter transfer
		- Instance transfer: use target domain data + some portion of source domain data
		- Feature representation transfer
		- Relational knowledge transfer

3. Self Supervised Learning

	Generate the labels from unlabeled data according to itself -> train on this unsupervised data in a supervised manner

	1. Image Augmentation

		- 'Unsupervised learning of visual representation by solving jigsaw puzzles', ECCV, 2016
		- RotNet 'Unsupervised representation learning by predicting image rotation', ICLR, 2018

	2. Contrastive Learning

		- SimCLR 'Simple framework for contrastive learning of visual representations', 2020

4. Explainable AI (XAI)

	1. Class Activation Map (CAM)

	2. Grad-CAM

	3. Layer-wise Relevance Propagation (LRP)

5. Graph Neural Network (GNN)

	- NetworkX, PyTorch Geometric(PyG), Deep Graph Library (DGL), Graph Nets, Spektral

6. Physics Informed Neural Network (PINN)

	- DeepXDE

