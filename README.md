# Grad-CAM-Visualization-ResNet18-CIFAR-10-Ship-Class-
Image classification on CIFAR-10 using ResNet50 with complete PyTorch pipeline: data loading, training, validation, confusion matrix, accuracy metrics, and Grad-CAM visualization for model interpretability. Demonstrates reliable performance and explainable deep learning.
🚢 CIFAR-10 Classification with ResNet50 (PyTorch)

This project implements a custom ResNet50 deep learning model from scratch in PyTorch and trains it on the CIFAR-10 dataset, achieving strong image-classification performance across 10 categories (airplane, dog, ship, etc.).

📌 Key Features

Full PyTorch training pipeline

Custom implementation of ResNet50 architecture

CIFAR-10 training with:
✔ Data augmentation
✔ Cross-entropy loss
✔ Adam optimizer
✔ Learning-rate scheduling

Evaluation and accuracy tracking

Grad-CAM visualization for model explainability

Clean and modular code structure

📁 CIFAR10-ResNet50
 ├── data/               # CIFAR-10 dataset
 ├── models/             # ResNet50 implementation
 ├── train.py            # Training loop
 ├── evaluate.py         # Testing and metrics
 ├── gradcam.py          # Grad-CAM visualization
 ├── requirements.txt
 └── README.md
🚀 How to Run
1️⃣ Install Dependencies
pip install -r requirements.txt
2️⃣ Train the Model
python train.py
3️⃣ Evaluate
python evaluate.py
4️⃣ Generate Grad-CAM Heatmaps
python gradcam.py

🧠 Results

Model correctly classifies CIFAR-10 images

Grad-CAM heatmaps show where the model focuses while making predictions, improving explainability and trust.

📊 Sample Grad-CAM

Heatmaps reveal the regions of the image that contributed most to the predicted class (e.g., “ship” in the example below).

📎 Future Improvements

Add early stopping

Add confusion matrix visualization

Compare performance with other architectures (VGG, EfficientNet, ViT, etc.)

🙌 Acknowledgements

PyTorch

CIFAR-10 dataset

ResNet original paper (He et al., 2015)
