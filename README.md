# Brain-Tumor-MRI
This project focuses on the classification of brain MRI images into different categories such as glioma, meningioma, pituitary tumor, and no tumor. The dataset consists of thousands of MRI scans that undergo preprocessing steps like resizing, normalization, noise reduction, and sharpening to improve the quality of the images for training.

A transfer learning approach is applied using DenseNet121, which is initialized with ImageNet weights and fine-tuned on the brain tumor dataset. Data augmentation techniques are also used to make the model more robust and prevent overfitting. The model is trained with early stopping and evaluated using accuracy, precision, recall, F1-score, and confusion matrix.

After training, the model is saved in .h5 format for reuse in inference or deployment. The final system achieves high classification performance and demonstrates the potential of deep learning in assisting medical diagnosis for brain tumor detection.
