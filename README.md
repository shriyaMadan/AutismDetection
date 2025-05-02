# Autism Detection from Facial Images using Convolutional Neural Networks (CNN)

This project uses a Convolutional Neural Network (CNN) to classify facial images of children as either **Autistic** or **Non-Autistic**. The model is trained on a publicly available image dataset and achieves over **76% test accuracy**.

The goal is to explore the potential of computer vision in supporting early autism detection using facial cues.

- Source: [Kaggle - Autism Image Data](https://www.kaggle.com/datasets/cihan063/autism-image-data)
- Classes: `Autistic`, `Non_Autistic`
- Total Images: ~3,000 (1,500 per class)
- Pre-split into: `train/`, `valid/`, `test/`

### How to Run?
1. Install dependencies
pip install torch torchvision matplotlib scikit-learn

2. Train the model
python train.py

3. Evaluate performance
python evaluate.py

### Model 
- Architecture: Custom CNN (3 Conv layers + ReLU + MaxPool + FC)
- Loss Function: Binary Cross-Entropy
- Optimizer: Adam
- Input size: 224x224 RGB images
- Output: Probability of being Autistic

