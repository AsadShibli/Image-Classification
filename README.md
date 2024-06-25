# Imbalanced Garbage Image Classification 

This repository provides a comprehensive workflow for building and evaluating various deep learning models on an imbalanced image dataset. The primary goal is to develop an effective classification model that addresses the challenges posed by the imbalanced nature of the data.

## Kaggle Dataset : 
https://www.kaggle.com/datasets/farzadnekouei/trash-type-image-dataset
## Demo 

![image](https://github.com/AsadShibli/Image-Classification/assets/119102237/b2ad0471-cdab-47d1-b383-9d19bf1b2a5f)

## Models Included
This repository includes the implementation of four models:
1. **Custom CNN Model**: A custom-built Convolutional Neural Network.
2. **CNN with Image Augmentation**: Enhancing the custom CNN with image augmentation techniques.
3. **Pretrained VGGNet Model**: Utilizing a pretrained VGGNet for classification.
4. **Pretrained ResNet50 Model**: Leveraging a pretrained ResNet50 for classification.

## Evaluation Metrics
Given the imbalanced nature of the dataset, the model performance is evaluated using:
- Accuracy
- Confusion Matrix
- Classification Report
- ROC AUC Curve

## Deployment
After identifying the optimal model, it is deployed using [Gradio](https://www.gradio.app/). Additionally, users can upload the model to [Hugging Face Spaces](https://huggingface.co/spaces) for broader accessibility.

## Contributing
Contributions are welcomed and encouraged for further experimentation and improvements. Feel free to fork this repository and submit pull requests.
