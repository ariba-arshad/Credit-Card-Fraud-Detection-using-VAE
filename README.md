# Credit Card Fraud Detection using VAE

Developed and trained a VAE in PyTorch on a credit card transaction dataset (~590,000 samples) for unsupervised fraud detection. Achieved a training loss of 0.602, recall: 0.70 and precision: 0.84. Analyzed and visualized latent space representations using PCA to interpret model behavior.

📁 Datasets Used

credit card fraud detection dataset 2023 from Kaggle

- Number of Fraudulent Transactions: 284315
- Number of Normal Transactions: 284315

🚀 VAE Architecture

- Encoder compresses input into latent vector with mean and variance.
- Decoder reconstructs image from sampled latent vector.
- Loss = Reconstruction Loss + KL Divergence

More information is given in Architecture.pdf

📊 Evaluation Metrics

- Loss: 0.6
- Accuracy: 76.6922%
- Precision: 0.8337
- Recall: 0.6669
- F1-score: 0.7410
