# Brain-Tumor-MRI
🧠 Brain Tumor MRI Classification

This project is a deep learning-based pipeline for classifying brain MRI scans into different categories of tumors (glioma, meningioma, pituitary) and non-tumor.
It uses DenseNet121 (transfer learning with ImageNet weights) and custom preprocessing techniques to achieve robust performance.

📌 Features

✅ Preprocessing (resizing, normalization, noise reduction, sharpening)

✅ Data Augmentation for improving generalization

✅ DenseNet121 as backbone (transfer learning)

✅ Early stopping to prevent overfitting

✅ Training & evaluation with accuracy, precision, recall, F1-score

📂 Project Structure
Brain-Tumor-Classification/
│── train.py                      # Model training script
│── preprocessing.py              # Image preprocessing script
│── models/
│   └── DenseNet121_Preprocessed_Augmented.h5   # Saved trained model
│── data/
│   ├── Training/
│   ├── Testing/
│── README.md

🚀 How to Run
1. Clone the Repository
git clone https://github.com/your-username/brain-tumor-classification.git
cd brain-tumor-classification

2. Install Dependencies
pip install -r requirements.txt

3. Preprocess Data
python preprocessing.py

4. Train Model
python train.py

📊 Results

Model: DenseNet121 (fine-tuned)

Accuracy: ~XX% on test set (update with your results)

Evaluation Metrics: Precision, Recall, F1-score, Confusion Matrix

📌 Future Work

Experiment with other architectures (EfficientNet, ResNet, ViT, etc.)

Hyperparameter tuning for improved performance

Visualization of model predictions (Grad-CAM, heatmaps)

✨ Acknowledgements

Dataset: Brain Tumor MRI Dataset (Kaggle)

Pretrained model: DenseNet121 (ImageNet)
