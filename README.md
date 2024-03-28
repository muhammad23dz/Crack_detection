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
Usage
Clone the repository to your local machine:
bash
Copy code
git clone https://github.com/your_username/image-classification.git
Navigate to the project directory:
bash
Copy code
cd image-classification
Place your dataset in the appropriate directories:

Positive samples in the Positive_tensors directory
Negative samples in the Negative_tensors directory
Modify the Dataset class to match your dataset structure if necessary.

Train the model by running the training script:

bash
Copy code
python train.py
Evaluate the trained model on the validation dataset:
bash
Copy code
python evaluate.py
Use the model to predict the class of an image:
bash
Copy code
python predict.py --image_path path/to/image.jpg
License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
PyTorch
torchvision
vbnet
Copy code

Replace `"your_username/image-classification"` with the actual GitHub repository URL w# Crack_detection
