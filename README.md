# AI_NN_2026

A single study deck that compiles the concepts taught in **CHM 501: Artificial Intelligence in Chemistry/Biochemistry (ASU, Fall 2026)**, from least squares to AlphaFold.

| File | What it is |
|---|---|
| `AI_NN_2026.pptx` | Editable 58-slide deck (PowerPoint) |
| `AI_NN_2026.pdf` | Same deck as PDF |

## Contents

1. **Foundations:** linear algebra, least-squares regression, nonlinear optimizers (gradient descent, Newton–Raphson), no-free-lunch, overfitting and the Bayesian Information Criterion
2. **Neural networks:** biological vs artificial neurons, network anatomy and parameter counts, activation functions, curse of dimensionality, supervised learning, backpropagation
3. **Images:** regression vs classification, softmax and cross-entropy, convolution kernels, CNN building blocks, LeNet-5, U-Net
4. **Representation & generative models:** data augmentation and invariance, PCA, autoencoders, discriminative vs generative AI, GANs, diffusion models
5. **Sequences, attention & graphs:** tokens and embeddings, RNNs/LSTMs, attention (Q/K/V), transformers, graph neural networks
6. **Agentic AI:** agent loop and components, reinforcement learning, recursive self-improvement
7. **Protein structure prediction:** X-ray/NMR/cryo-EM, folding problem, MSA and co-evolution, AlphaFold1/2, confidence metrics, ColabFold, ESMFold, RoseTTAFold, RFdiffusion
8. **Intrinsically disordered proteins:** prevalence, LLPS, sequence patterning, coarse-grained simulation, PARROT, metapredict, the HW5 toolchain
9. **Cheat sheet:** choosing an architecture, glossary

## Notes

- Written as a concept summary in my own words; it does not reproduce the instructor's slides or figures. Cited results are attributed on the slides.
- The gradient-descent, activation-function and BIC charts are computed exactly (BIC uses seeded synthetic data from y = 2 + 1.5x).
- Lecture 11 was not available; IDP slides covering it summarize the HW5 tools instead.
