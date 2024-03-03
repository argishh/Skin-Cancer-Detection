# Skin Cancer Classification Using Transfer Learning

This project aims to accurately classify skin cancer types using a deep learning approach, specifically employing Transfer Learning with the ResNet-18 architecture. The model is trained on a comprehensive dataset of skin lesion images, with the goal of assisting dermatologists in the early detection and diagnosis of skin cancer.

## Project Overview

Skin cancer is one of the most common types of cancer globally. Early detection is crucial for effective treatment and patient prognosis. This project leverages the power of Convolutional Neural Networks (CNNs), specifically the ResNet-18 model, through Transfer Learning to classify skin lesions into various cancerous and non-cancerous categories.

## Dataset

The dataset comprises dermatoscopic images, labeled into different categories based on the type of skin cancer. Each image has been preprocessed to a standard size and format suitable for input into the ResNet-18 model.

Number of Training images: 2077 \
Number of Testing images: 660 \
Number of Validation images: 560

Categories -
- Benign
- Malignant

## Model

I've used ResNet-18 architecture, which is known for its efficiency and accuracy in image classification tasks. The model has been pretrained on the ImageNet dataset and fine-tuned for the specific task of skin cancer classification.

### Training

The model was trained using the following parameters:

- **Optimizer:** Adam
- **Loss Function:** Cross-Entropy Loss
- **Batch Size:** *X*
- **Number of Epochs:** *Y*

*Note: Replace X and Y with the actual values used in your project.*

### Performance

The model achieved the following performance metrics:

Classification Report -

|              | precision | recall | f1-score | support |
|--------------|-----------|--------|----------|---------|
| 0            | 0.80      | 0.93   | 0.86     | 10800   |
| 1            | 0.89      | 0.72   | 0.80     | 9000    |
| accuracy     |           |        | 0.83     | 19800   |
| macro avg    | 0.85      | 0.82   | 0.83     | 19800   |
| weighted avg | 0.84      | 0.83   | 0.83     | 19800   |

<br>

## Acknowledgments

I would like to thank the creators of the dataset and the PyTorch team for providing the tools and libraries that made this project possible.

---