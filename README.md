# Underwater Image Segmentation using U-Net: A Deep Learning Approach

## Overview
This project focuses on the application of deep learning, specifically U-Net architecture, for underwater image segmentation. The goal is to accurately classify pixels in underwater scenes into five different classes: human, reef, wreck, robot, and fish. The dataset used for this project is the SUIM Potsdam dataset, which contains RGB images of underwater scenes and corresponding segmentation masks.

## Project Structure

The project is organized as follows:

- **Dataset:** The SUIM Potsdam dataset is utilized, consisting of 80% for training and 20% for evaluation. The dataset is structured as follows:
  - `train_val/`: Contains 1525 paired samples for training/validation.
    - `images/`: RGB images of underwater scenes.
    - `masks/`: Segmentation labels where each RGB color represents a different object category.
  - `TEST/`: Includes 110 paired samples for reference evaluation.
    - `images/`: RGB test images.
    - `masks/`: Ground truth labels.

## Usage
1. **Dataset Download:**
   - Access the SUIM Potsdam dataset: [SUIM Potsdam Dataset](https://irvlab.cs.umn.edu/resources/suim-dataset)

2. **Environment Setup:**
   - Ensure you have the necessary dependencies installed. Use the provided Jupyter Notebook or Python scripts for running the model.

3. **Training:**
   - Train the U-Net model using the provided code on the training dataset.

4. **Evaluation:**
   - Evaluate the trained model on the test dataset to assess its segmentation performance.

## Results and Analysis
The project includes an analysis of the segmentation results. Interpretation of results suggests that the model has successfully converged. Possible improvements include increasing the number of epochs or exploring loss functions that penalize errors on less frequent pixels more significantly.

## Contributing
Feel free to contribute to this project by opening issues or submitting pull requests.

## Acknowledgments
- The SUIM Potsdam dataset: [SUIM Potsdam Dataset](https://irvlab.cs.umn.edu/resources/suim-dataset)
- U-Net architecture: [U-Net: Convolutional Networks for Biomedical Image Segmentation](https://arxiv.org/abs/1505.04597)
