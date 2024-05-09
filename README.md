# MicroFarm.AI-Contributing-to-AI-powered-Disease-Detection-for-Sustainable-Agriculture
 Developed web app for plant disease classification, comparing VGG16 with custom CNN. Utilized Plant Village dataset, TensorFlow backend. Integrated OpenCV for leaf disease detection. Created user-friendly interface with Fast API and React. Allows real-time disease identification from uploaded images.

## Features

- Utilizes a CNN for plant disease classification.
- Compares the performance of VGG16 with a custom CNN.
- Integrates OpenCV for disease detection in plant leaves.
- Implements a user-friendly web interface using FastAPI for the backend and React for the frontend.
  
## Dataset

The application is trained on the Plant Village dataset, which contains 54,303 images of various plant diseases.

## Models

### Custom CNN Model

- Architecture:
  - Input Layer
  - Convolutional Layers with ReLU activation
  - MaxPooling Layers
  - Flatten Layer
  - Dense Layers with ReLU activation
  - Output Layer with Softmax activation
- Trained using TensorFlow backend.

### VGG16-based Model

- Architecture:
  - Pre-trained VGG16 base (excluding top layer)
  - Additional Fully-connected Layers
- Trained using TensorFlow backend.

## OpenCV Integration

Both models are integrated with OpenCV (`cv2`) for disease marking on plant leaves during inference, enhancing visualization of disease areas in the input images.

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/samarth-17/MicroFarm.AI-Contributing-to-AI-powered-Disease-Detection-for-Sustainable-Agriculture.git

2. Install dependencies:
    ```bash
   pip install -r requirements.txt
