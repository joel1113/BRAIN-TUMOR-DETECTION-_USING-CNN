# Brain Tumor Detection Using CNN

## Project Description
Automated system for detecting and classifying brain tumors from MRI images using Convolutional Neural Networks (CNNs). The model classifies tumors into glioma, meningioma, pituitary tumor, and no tumor with high accuracy, leveraging TensorFlow and Keras. Data augmentation techniques improve model robustness. This project aims to enhance diagnostic accuracy and reduce workload for radiologists.

## Features
- CNN architecture with convolutional, max-pooling, dropout, and dense layers
- Data augmentation: rotation, flipping, scaling
- Multi-class classification of brain tumor types
- Performance evaluation using accuracy, precision, recall, and F1-score
- Visualizations including confusion matrices and tumor heatmaps
  <img width="1394" height="710" alt="image" src="https://github.com/user-attachments/assets/07ae8400-7cbd-468b-bc3e-ce5a0aebcd7b" />

## Installation
1. Clone the repository:
2. Create and activate a Python environment (optional but recommended):
3. Install required packages:

## Usage
- Prepare your MRI dataset following the given structure.
- Run the Jupyter notebook `brain-tumor-detection.ipynb` for training and evaluation.
- Use the pre-trained model or retrain as needed.
- Visualize results with provided scripts.

## Dataset
The model is trained on labeled MRI brain scan images categorized into four classes: glioma, meningioma, pituitary tumor, and no tumor. Public datasets such as BraTS were used for training and validation.

## Results
The CNN model achieves strong classification performance with high accuracy and F1-scores, supported by confusion matrix visualizations and tumor heatmap overlays for interpretability.

![Brain Tumor Detection CNN Illustration] <img width="652" height="1134" alt="image" src="https://github.com/user-attachments/assets/8a67ca7d-197b-4774-a76c-32098bd70ee8" />


## Contributing
Contributions are welcome! Please fork the repository, create a feature branch, and submit a pull request with your improvements.

## License
Specify your license here, e.g., MIT License.

## Acknowledgements
- Thanks to Dr. Sriman Kothuri and the team at SR University for their guidance.
- Inspired by related research in deep learning for medical imaging.

