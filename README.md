# Neural Networks: Zero to Hero

This repository contains my detailed implementations of Andrej Karpathy's [Neural Networks: Zero to Hero](https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ) lecture series and exercises, using Jupyter Notebooks. The notebooks provide an in-depth exploration of neural networks and deep learning concepts, ensuring a strong fundamental understanding of the material.

## Contents

This course covers the complete journey of building neural networks from scratch in code, starting from basic concepts and advancing to state-of-the-art models.

### Neural Networks:

- **Backpropagation**: 
  - Understand the core algorithm that enables neural networks to learn by updating weights through gradient descent (efficient computation of gradients).
  
- **Multi-Layer Perceptrons (MLPs)**:
  - Learn to implement fully-connected feedforward neural networks that are the building blocks of deep learning.
  
- **Convolutional Neural Networks (CNNs)**:
  - Dive into networks designed for image processing, using convolutional & pooling layers to capture spatial features.

- **Deep Neural Networks (DNNs)**:
  - Progress to advanced architectures, including modern models like **Generative Pre-trained Transformers (GPTs)**, commonly used in natural language processing.

### Diagnostic Tools for Neural Networks

- Explore methods for monitoring and improving neural network performance, including:
  - Understanding training dynamics
  - Debugging common issues such as vanishing gradients and overfitting

### Tokenization and Byte-Pair Encoding (BPE)

- **Tokenization**:
  - Learn how to split text data into tokens (smaller, manageable chunks) for processing in neural networks.
  
- **Byte-Pair Encoding (BPE)**:
  - Implement a popular tokenization method (lossless text compression) used in language models & NLP that optimizes for both vocabulary size and token granularity.

### Focus on Language Modeling (LM)

The primary focus of this course is on **Language Modeling (LM)**, a core task in natural language processing where the goal is to predict the next word or token in a sequence. Language models offer an excellent introduction to deep learning due to the broad applicability of the techniques learned, which can be transferred to other fields like **Computer Vision (CV)** and **Reinforcement Learning (RL)**.

## Learning Objectives

- Build neural networks from scratch and gain a deep understanding of how they work.
- Master techniques for training, optimizing, and diagnosing neural networks.
- Gain hands-on experience in language modeling, tokenization, and neural network architectures.
- Apply concepts from neural networks to real-world applications, including computer vision and natural language processing.

## Repository Contents
- Detailed Jupyter Notebook implementations of each lecture
- Exercises and solutions for hands-on practice
- Additional resources and references for further learning

## Prerequisites
- Basic understanding of Python programming
- Familiarity with linear algebra and calculus
- Interest in deep learning and neural networks

## Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/ml-with-dan/karpathy-nn-zero-to-hero.git
   cd karpathy-nn-zero-to-hero
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch Jupyter Notebook to start working through the lessons:
   ```bash
   jupyter notebook
   ```

## Contributions and Feedback

Contributions, issues, and feedback are welcome! Please submit a pull request or open an issue on this repository.

## Acknowledgements

Special thanks to [Andrej Karpathy](https://karpathy.ai/) for creating the original **Neural Networks: Zero to Hero** course and inspiring this project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. Feel free to use this repo for educational purposes.

