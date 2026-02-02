# 🧠 Deep Learning From Scratch: The Journey to GPT

Welcome to my learning journey! This repository is a step-by-step implementation of neural networks, starting from basic calculus and building up to a functional **Generative Pre-trained Transformer (GPT)**. 

The goal of this project is to demystify the "magic" of AI by building every component from the ground up without relying on high-level libraries for the core logic.

---

## 🗺️ Learning Roadmap

I have organized the notebooks in order of increasing complexity. If you are a beginner, follow them in this order:

### 1. [Micrograd: Backpropagation from Scratch](https://github.com/SathwikVakalapudi/DeepLearningFromScratch/blob/main/1_micrograd_from_scratch.ipynb)
* **The Goal:** Understand how computers "learn" using math.
* **Key Concepts:** Scalar values, the Chain Rule (Calculus), and building a custom engine to calculate gradients.
* **The "Aha!" Moment:** Realizing that training a neural network is just "nudging" numbers in the direction that reduces error.

### 2. [Bigram Model: The Simplest Language Model](https://github.com/SathwikVakalapudi/DeepLearningFromScratch/blob/main/2sequence%20modeling_bigram.ipynb)
* **The Goal:** Predict the next character based on the current one.
* **Key Concepts:** Probability distributions and basic sampling.
* **The "Aha!" Moment:** Seeing that language can be modeled as a statistical game of "what comes next?"

### 3. [MLP: Multi-Layer Perceptron for Sequences](https://github.com/SathwikVakalapudi/DeepLearningFromScratch/blob/main/Sequence%20modeling_MLP.ipynb)
* **The Goal:** Improve predictions by looking at a "context window" of characters.
* **Key Concepts:** Feature Embeddings and Hidden Layers.
* **The "Aha!" Moment:** Learning that we can represent words as coordinates (Vectors) to help the model find patterns.

### 4. [The GPT Architecture: Self-Attention](https://github.com/SathwikVakalapudi/DeepLearningFromScratch/blob/main/attention_gpt.ipynb)
* **The Goal:** Build a mini-version of the architecture that powers ChatGPT.
* **Key Concepts:** Self-Attention, Multi-Head Attention, and Residual Connections.
* **The "Aha!" Moment:** Understanding how "Attention" allows the model to focus on the most important words in a sentence.

---

## 🤝 Open to Collaborate!

I am actively learning and looking to improve these implementations. I would love to collaborate with you!

* **Found a bug?** Open an issue.
* **Have a better explanation?** Submit a Pull Request.
* **Want to learn together?** Feel free to reach out or fork this repo to start your own journey.

Whether you are a beginner or an expert, your feedback and contributions are welcome. Let's make learning AI less intimidating for everyone!

---

## 💡 Beginner Tips
1.  **Don't panic about the math:** Focus on the *intuition* first. 
2.  **Break it:** Try changing the `learning_rate`. See what happens when the model is too small.
3.  **Follow the Data:** Always check the `shape` of your tensors. If the shapes match, you're 90% of the way there!

---

> "What I cannot create, I do not understand." – Richard Feynman

---
