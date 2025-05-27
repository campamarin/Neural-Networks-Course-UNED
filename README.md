# Neural Networks – Course Project

This repository contains selected simulations and theoretical analyses from my coursework on **Neural Networks** for the Master in Advanced Physics in UNED (Curso de *Redes Neuronales* del Máster de Física Avanzada de la UNED). 

## Notes

- The document is written in Spanish.
- The code in the appendix is also available as plain text inside the PDF, and may be extracted or reused for educational purposes.
- The project is intended as a comprehensive review and self-contained study of introductory on Neural Networks.

## Project Highlights

The most relevant parts of the project included in this repository are:

### Problem 3 – Attractor Neural Networks (Hopfield Network)

A simulation of a Hopfield-type attractor neural network using **Hebbian learning**. An image representing the letter **"A"** is presented to the network, and the learning dynamics and memory retrieval are analyzed. This provides insight into pattern storage and stability in recurrent networks.

### Problem 4 – Diluted Hopfield Network

A continuation of Problem 3, this simulation explores how a **diluted network architecture** (with fewer synaptic connections) affects the performance and memory capacity of the Hopfield network under the same learning rule.

### Problem 7B – Deep Neural Networks on MNIST

A feedforward neural network is trained using the **Backpropagation (BP)** algorithm to classify digits from the **MNIST dataset**. The focus is on studying how increasing the number of hidden layers affects learning performance, exploring the **transition to deep learning**. The results include accuracy measurements and convergence behavior under different architectures.

### Problem 8 – Critical Analysis of Deep Learning Training

This section offers a theoretical and empirical discussion on the **difficulties in training deep neural networks**. It includes observations on how increasing depth and adjusting the learning rate influence convergence, stability, and generalization.

## Structure

- Jupyter notebooks and Python scripts are included for the practical problems.
- Mathematical derivations and theoretical discussions are summarized in accompanying notes (PDF or Markdown).
- The code is well-commented and designed for experimentation and educational use.

## Requirements

- Python 3.x
- NumPy
- Matplotlib
- TensorFlow or PyTorch (for Problem 7B)

## License

This work is provided for educational and academic purposes. Feel free to reuse or adapt the code with proper citation.

