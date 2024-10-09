# Face Mask Detection

## Overview
This project is an intelligent facial recognition system designed to detect whether a person is wearing a face mask or not. The system utilizes deep learning techniques to classify images into two categories: mask and no mask. It features color-coded indicators to visually demonstrate compliance, providing a **green border** around faces that are wearing masks and a **red border** around faces that are not.

## Features
- **Dataset**: Conducted thorough facial scans on a dataset of 1000+ faces.
- **Deep Learning Model**: Built using **Convolutional Neural Networks (CNN)** implemented with **TensorFlow** and **Keras**.
- **Color-Coded Indicators**: Displays a **green border** around detected faces that comply with mask-wearing and a **red border** for non-compliance.
- **High Accuracy**: Achieved **95% accuracy** in detecting mask-wearing compliance.

## Technologies Used
- **TensorFlow**: For building and training the deep learning model.
- **Keras**: High-level neural network API used to simplify model building.
- **CNN (Convolutional Neural Networks)**: For feature extraction and classification.
- **imutils**: For image processing utilities.
- **Matplotlib**: For visualizing model performance and results.

## Installation
To get started with this project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/face-mask-detector-2.git
   ```

2. Navigate to the project directory:
   ```bash
   cd face-mask-detector-2
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
To run the Face Mask Detector:

1. Ensure that you have a webcam or images to test the system.
2. Run the script:
   ```bash
   python detect_mask.py
   ```
3. The system will begin detecting faces, displaying green borders for compliance (mask-wearing) and red borders for non-compliance.

## Dataset
The dataset used in this project consists of over **1000+ face images**, pre-labeled for mask or no mask. The data is split into training and testing sets to evaluate the model's performance.

## Model Training
To train the model from scratch, run the `train_model.py` script:
```bash
python train_model.py
```
This will train the CNN model using the provided dataset and save the model to the disk for later use.

## Results
The model achieved an accuracy of **95%** in detecting mask-wearing status. The performance of the model was visualized using **Matplotlib**, showing the accuracy and loss over the training epochs.

## Future Enhancements
- Improve the dataset by adding more diverse images to increase the model's robustness.
- Enhance real-time performance by optimizing the code for lower latency.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
- [TensorFlow](https://www.tensorflow.org/)
- [Keras](https://keras.io/)
- [imutils](https://github.com/jrosebr1/imutils)
- [Matplotlib](https://matplotlib.org/)

---
