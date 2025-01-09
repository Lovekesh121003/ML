# Fish Disease Detection and Recognition

This project implements a deep learning-based solution for detecting and recognizing fish diseases in aquaculture. It utilizes a custom-trained model based on ResNet-50, fine-tuned on a dataset of fish skin images across seven disease categories.

---

## Features
- Detects and classifies fish diseases into seven categories:
  1. Aeromoniasis
  2. Bacterial Gill Disease
  3. Bacterial Red Disease
  4. Saprolegniasis
  5. Healthy Fish
  6. Parasitic Diseases
  7. White Tail Disease
- Achieves high accuracy (96% after 20 epochs, with potential to reach 97% with extended training).
- Built using ResNet-50 as the base model for feature extraction.

---

## Dataset
The dataset contains 1,750 images, with 250 images per class. These images were sourced from:
- University agricultural departments
- Agricultural farms in Odisha, India
- Agricultural website portals

### Preprocessing:
- Images were resized and normalized to fit the input requirements of ResNet-50.
- Data augmentation techniques were applied to enhance generalization.

---

## Model Architecture
- **Base Model**: ResNet-50 (pre-trained on ImageNet).
- **Custom Layers**: Fully connected layers were added on top of ResNet-50 for classification.

### Training Details:
- **Framework**: TensorFlow/Keras
- **Optimizer**: Adam
- **Loss Function**: Categorical Crossentropy
- **Epochs**: 20
- **Accuracy**: 96%


---

## Future Work
- Increase training epochs to enhance accuracy.
- Expand dataset with more diverse samples.
- Deploy the model as a web app for user-friendly disease detection.

---

## Acknowledgments
- Agricultural organizations and farms for providing images.
- Open-source contributors for tools and frameworks.

---

## Contact
For queries or contributions, feel free to reach out:
- **Name**: Lovekesh Jain
- **Email**: lovekeshjain13@gmail.com
- **GitHub**: https://github.com/Lovekesh121003

