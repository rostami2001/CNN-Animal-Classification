# CNN Animal Classification Project

This repository contains the implementation of a Convolutional Neural Network (CNN) project for animal image classification. It was developed as part of the "Computational Intelligence" course at Ferdowsi University of Mashhad in Winter 2025. The project focuses on building, training, and evaluating CNN models using the Animals10 dataset, with techniques like hyperparameter tuning, overfitting prevention, and transfer learning.

**Note:** This is one of my early projects in neural networks, so it might not be perfectly optimized or complete.

## Project Overview
The goal is to classify images of 10 different animals using a custom CNN. The project is divided into phases as per the assignment:
1. **Model Designing (Phase 1):** Design a CNN with up to 1.4 million parameters and train it on Animals10 (70% train, 10% validation, 20% test). Evaluate with metrics like accuracy, precision, recall, F1-score, confusion matrix, ROC curves, and visualizations.
2. **Parameter Limitation (Phase 2):** Reduce parameters to under 400,000 without changing the core architecture, retrain, and evaluate.
3. **Overfitting Prevention (Phase 3):** Apply techniques (e.g., Data Augmentation, Dropout, Weight Regularization, Normalization Layers) to both models from Phases 1 & 2 to prevent overfitting.
4. **Transfer Learning (Phase 4):** Fine-tune the best model on a new dataset (Dog Sentiment Classification) with fewer data points. First freeze layers and train the final layer, then unfreeze one block and retrain.

Datasets:
- **Animals10:** 10 classes of animals (e.g., dog, cat, horse, spider).
- **Dog Sentiment Classification:** 10 classes of dog emotions/sentiments (smaller dataset for transfer learning).


## Results Summary
- **Phase 1:** Best model achieved ~72% test accuracy with 1,292,682 parameters.
- **Phase 2:** Reduced model to 392,634 parameters, ~73% test accuracy.
- **Phase 3:** Overfitting reduced; accuracies improved to ~75% (Model 1) and ~74% (Model 2).
