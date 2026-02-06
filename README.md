# Learning a Generative Latent Space of Fashion Style Using Variational Autoencoders

## Overview

This project explores the use of Variational Autoencoders (VAEs) to learn a generative latent representation of fashion style. Instead of treating fashion items as fixed embeddings, this approach models style as a continuous probability distribution, enabling sampling, interpolation, and exploration of stylistic variation.

By learning this generative latent space, the model can synthesize new style representations, reveal relationships between styles, and provide insight into the structure of fashion data.

This project is developed as part of:

**DSCI/CSE 498 – Deep and Generative Learning**  
Lehigh University, Spring 2026

## Abstract

Fashion style is inherently continuous, multimodal, and difficult to represent using discrete labels alone. Traditional approaches represent fashion items as fixed embeddings optimized for similarity or classification tasks, but these methods do not explicitly model the underlying distribution of styles. In this project, I propose to learn a generative latent representation of fashion style using a Variational Autoencoder (VAE). The model will be trained on fashion item embeddings derived from images and associated metadata, enabling the encoder to map each item to a latent probability distribution that captures stylistic variation.

This approach enables sampling of new style representations, interpolation between styles, and exploration of the latent space. The learned latent space will be analyzed to evaluate whether meaningful stylistic structure emerges, such as clustering of items with similar stylistic characteristics, which may align with attributes such as category, season, or occasion. By sampling from the latent distribution and decoding the resulting representations, the model can synthesize novel stylistic points that are consistent with the learned distribution but do not correspond directly to existing items.

The final deliverable will include implementation, experiments, and visualizations demonstrating latent space structure, interpolation, and sampling. More broadly, modeling fashion style as a continuous generative space enables applications such as exploring stylistic variation, generating new style representations, improving recommendation systems, and identifying gaps or emerging trends within a fashion catalog.

## Goals

The main objectives of this project are:

- Learn a generative latent representation of fashion style using a VAE
- Model fashion style as a continuous probability distribution
- Generate new stylistic representations through latent space sampling
- Interpolate between fashion styles in latent space
- Analyze latent structure through visualization and clustering

## Status

Milestone 0: Proposal and repository setup complete.  

