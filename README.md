# Probabilistic Generative Models

**Imperial College London – Department of Mathematics**  
**MSc in Applied Mathematics**  
**Dates:** Spring Term 2025 / 2026  
**Format:** 10 weeks, 3 hours per week  
**Lecturer:** Felipe Tobar  
**Teaching Assistants:** Camilo Carvajal Reyes, Skye Purchase  

---

## Introduction

This module provides a mathematically grounded introduction to **probabilistic generative modelling**, covering both classical inference techniques and modern deep generative models. The course develops a unified view of generative modelling as **probability density estimation, inference, and the transportation of probability measures**. The syllabus progresses from information-theoretic foundations and latent-variable inference to optimal transport, deep latent models, normalising flows, transformers, and diffusion models. 

---

## Assessment

- **Coursework 1 (Week 5):** Programming-based (classical models and transport)
- **Coursework 2 (Week 8):** Programming-based (deep generative models)
- **Final Exam:** Theory-based (covers all weeks; Weeks 9–10 assessed by exam only)

---

# Weekly Plan

---

## **Week 1 — Foundations of Generative Modelling & Information Theory**

### Content
- Generative vs discriminative modelling
- Probability measures, densities, and pushforwards
- Maximum likelihood estimation
- Introduction to information theory:
  - Entropy and cross-entropy  
  - KL divergence and its properties
- Likelihood-based modelling vs sampling-based modelling

### Literature
- Murphy — *Probabilistic Machine Learning*, Chapters 2–3  
- Cover & Thomas — *Elements of Information Theory*, Chapter 2  
- MacKay — *Information Theory, Inference, and Learning Algorithms*, Chapter 2  

---

## **Week 2 — Latent Variable Models & Expectation–Maximisation**

### Content
- Latent variable models
- Incomplete-data likelihoods
- Jensen’s inequality
- Expectation–Maximisation (EM) algorithm
- EM as coordinate ascent on a KL-based objective
- Gaussian mixture models and identifiability issues

### Literature
- Bishop — *Pattern Recognition and Machine Learning*, Sections 9.1–9.4  
- Murphy — *Probabilistic Machine Learning*, Chapter 11  
- Dempster, Laird & Rubin — *Maximum Likelihood from Incomplete Data via the EM Algorithm*  

---

## **Week 3 — Variational Inference**

### Content
- Variational approximations and variational families
- Evidence Lower Bound (ELBO)
- Mean-field variational inference
- Coordinate-ascent variational inference
- Relationship between EM and VI
- Amortised inference (conceptual bridge to deep models)

### Literature
- Blei et al. — *Variational Inference: A Review*  
- Jordan et al. — *An Introduction to Variational Methods for Graphical Models*  
- Murphy — *Probabilistic Machine Learning*, Chapter 10  

---

## **Week 4 — Bayesian Nonparametrics**

### Content
- Gaussian processes as distributions over functions
  - Kernels and covariance operators
  - Training and inference
  - GP classification
- Dirichlet processes:
  - Random probability measures  
  - Stick-breaking construction  
  - Dirichlet process mixture models

### Literature
- Rasmussen & Williams — *Gaussian Processes for Machine Learning*  
- Teh — *Dirichlet Processes*  
- Orbanz & Teh — *Bayesian Nonparametrics*  

---

## **Week 5 — Computational Optimal Transport**
**Coursework 1 released**

### Content
- The Monge and Kantorovich formulations
- Wasserstein distances and couplings
- Sinkhorn algorithm and entropic regularisation
- Comparison between OT and KL-based objectives
- Transport maps as generative models

### Literature
- Peyré & Cuturi — *Computational Optimal Transport*  
- Villani — *Topics in Optimal Transportation*  
- Cuturi — *Sinkhorn Distances*  

---

## **Week 6 — Deep Latent Variable Models: VAEs & GANs**

### Content
**Variational Autoencoders**
- Encoder–decoder architecture
- Reparameterisation trick
- ELBO interpretation
- Posterior collapse and expressivity limits

**Generative Adversarial Networks**
- Implicit generative models
- Adversarial objectives and divergence minimisation
- Jensen–Shannon divergence
- Wasserstein GANs

### Literature
- Kingma & Welling — *Auto-Encoding Variational Bayes*  
- Goodfellow et al. — *Generative Adversarial Nets*  
- Arjovsky et al. — *Wasserstein GAN*  
- Doersch — *Tutorial on Variational Autoencoders*  

---

## **Week 7 — Autoregressive Models & Transformers**

### Content
- Autoregressive factorisation of probability distributions
- Maximum likelihood training of sequence models
- Self-attention as conditional density modelling
- Transformer architecture from a probabilistic perspective
- Sampling strategies (temperature, top-k, top-p)

### Literature
- Vaswani et al. — *Attention Is All You Need*  
- Bengio et al. — *Neural Probabilistic Language Models*  
- Murphy — *Probabilistic Machine Learning*, Chapter 20  

---

## **Week 8 — Normalising Flows & Flow Matching**
**Coursework 2 released**

### Content
- Change-of-variables theorem
- Discrete normalising flows
- Continuous normalising flows and Neural ODEs
- Flow matching and vector-field supervision
- Connections to optimal transport and diffusion models

### Literature
- Papamakarios et al. — *Normalizing Flows for Probabilistic Modeling*  
- Lipman et al. — *Flow Matching for Generative Modeling*  
- Chen et al. — *Neural Ordinary Differential Equations*  

---



## **Week 9 — Diffusion Models**
*(Exam-only content)*

### Content
- Forward diffusion processes
- Reverse-time generative dynamics
- Denoising objectives
- Likelihood interpretation of diffusion models
- Connections to continuous normalising flows

### Literature
- Sohl-Dickstein et al. — *Deep Unsupervised Learning using Nonequilibrium Thermodynamics*  
- Ho et al. — *Denoising Diffusion Probabilistic Models*  

---

## **Week 10 — Score-Based Models & Unification**
*(Exam-only content)*

### Content
- Score matching
- Denoising score matching
- Reverse-time stochastic differential equations
- Score-based generative modelling
- Unification of flows, optimal transport, and diffusion models

### Literature
- Hyvärinen — *Estimation of Non-Normalized Statistical Models*  
- Song et al. — *Score-Based Generative Modeling via Stochastic Differential Equations*  
- De Bortoli et al. — *Diffusion Schrödinger Bridges*  

---
