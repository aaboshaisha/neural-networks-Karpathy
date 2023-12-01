**Neural Network and Language Modeling**

My implementation of Andrej Karpathy's Neural Networks: Zero to Hero playlist. Included are personal notes and solutions to proposed exercises.

This repository contains a comprehensive series on neural networks and language modeling. The content covers key concepts such as backpropagation, building multilayer perceptrons (MLP), activations and gradients, BatchNorm, and even extends to creating a Generatively Pretrained Transformer (GPT) from scratch.

### Overview: 

1. **Neural Networks and Backpropagation:**
   - In-depth explanation and hands-on implementation of backpropagation and neural network training using micrograd.
   - Implementing the core of the autograd engine.

2. **Language Modeling with Torch.Tensor:**
   - Building a bigram character-level language model (makemore) and its evolution into a modern Transformer language model.
   - Focus on torch.Tensor usage, language modeling framework, and key concepts like model training, sampling, and loss evaluation.

3. **Multilayer Perceptron (MLP) Implementation:**
   - Introduction to machine learning basics with the implementation of an MLP character-level language model.
   - Covers model training, learning rate tuning, hyperparameters, evaluation, train/dev/test splits, under/overfitting, etc.

4. **Activations & Gradients, BatchNorm:**
   - In-depth exploration of MLP internals, analyzing forward pass activations, backward pass gradients, and potential pitfalls.
   - Introduction to Batch Normalization as a key innovation in training deep neural networks.

5. **Manual Backpropagation Exercise:**
   - Hands-on backpropagation through a 2-layer MLP (with BatchNorm) without using PyTorch autograd.
   - Builds a strong intuitive understanding of gradient flow in the compute graph and efficient Tensor handling.

6. **Building a WaveNet Architecture:**
   - Deepening the 2-layer MLP into a tree-like structure resembling the WaveNet architecture.
   - Insights into torch.nn, deep learning development process, and understanding multidimensional tensor shapes.

7. **Generatively Pretrained Transformer (GPT):**
   - Building a GPT from scratch following the "Attention is All You Need" paper.
   - Connection to ChatGPT, GitHub Copilot, and insights into autoregressive language modeling.


