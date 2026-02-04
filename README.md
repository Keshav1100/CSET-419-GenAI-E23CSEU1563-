# Week 1 (14-01-2026)

- Folder: [Week_01](Week_01/)

## Summary

- **Image generation:** Created an image-generation model using a pre-trained, simple generator.
- **Synthetic X-rays:** Generated synthetic chest X-ray images for multiple diseases.
- **Evaluation:** Used the generated images with a pre-trained DenseNet-based classifier to check predicted labels.
- **Fine-tuning:** Fine-tuned the classifier on selected data to improve prediction results.

---

# Week 2 (21-01-2026)

- Folder: [Week_02](Week_02/)

## Summary

- **GAN Architecture:** Implemented a Generative Adversarial Network (GAN) with customizable parameters.
- **MNIST Dataset:** Trained the GAN on the MNIST dataset with configurable epochs, batch size, and noise dimensions.
- **Image Generation:** Generated synthetic digit images using the trained generator network.
- **LeNet-5 Classification:** Evaluated the generated images using a LeNet-5 classifier to assess generation quality.
- **Accuracy Evaluation:** Calculated classifier accuracy on generated images and provided detailed prediction analysis.

---

# Week 3 (28-01-2026)

- Folder: [Week_03](Week_03/)

## Summary

- **Variational Autoencoder (VAE):** Implemented a VAE with fully connected encoder and decoder networks.
- **Fashion-MNIST Dataset:** Trained the VAE on the Fashion-MNIST dataset for generative modeling of clothing items.
- **Reparameterization Trick:** Applied the reparameterization trick to enable backpropagation through the stochastic sampling layer.
- **Loss Function:** Combined reconstruction loss (Binary Cross Entropy) and KL divergence for training.
- **Sample Generation:** Generated new synthetic fashion images from random noise vectors in latent space.
- **Latent Space Visualization:** Visualized the 2D latent space to understand the learned representations of different fashion item classes.
- **Reconstruction Quality:** Compared original test images with VAE reconstructions to evaluate generation quality.

---

# Week 4 (04-02-2026)

- Folder: [Week_04](Week_04/)

## Summary

- **N-Gram Model:** Implemented statistical n-gram based text generation using bigram sequences and random sampling.
- **LSTM Text Generation:** Built an RNN/LSTM architecture with embedding layer to generate contextually relevant text sequences.
- **Transformer Architecture:** Implemented a custom Transformer model with multi-head self-attention, positional embeddings, and feed-forward networks.
- **Custom Corpus:** Trained models on a curated dataset of 40+ sentences covering AI, machine learning, and NLP topics.
- **Model Comparison:** Analyzed trade-offs between statistical models, sequential neural networks, and attention-based transformers.
- **Text Generation:** Generated meaningful text using seed words with all three model architectures.
- **Attention Mechanisms:** Explored parallel processing and contextual understanding using transformer self-attention.

```
