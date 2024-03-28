# Image Classification using Pre-trained ResNet18

This project demonstrates how to perform image classification using a pre-trained ResNet18 model in PyTorch. The ResNet18 model is fine-tuned on a custom dataset consisting of positive and negative samples.

## Getting Started

To get started with this project, follow the steps below:

### Prerequisites

Make sure you have the following prerequisites installed on your system:

- Python (>=3.6)
- PyTorch
- torchvision
- PIL (Python Imaging Library)

You can install the required Python packages using pip:

```bash
pip install torch torchvision pillow
cd image-classification
##Place your dataset in the appropriate directories:

##Positive samples in the Positive_tensors directory
##Negative samples in the Negative_tensors directory
##Modify the Dataset class to match your dataset structure if necessary.

##Train the model by running the training script:
python train.py
##Evaluate the trained model on the validation dataset:
python evaluate.py
##Use the model to predict the class of an image:
##python predict.py --image_path path/to/image.jpg

