# Face Mask Detection

## Overview
This project is a Face Mask Detection system that identifies whether a person is wearing a mask or not using deep learning and computer vision techniques. While the need for mask-wearing surged during COVID-19, this technology remains crucial in various settings, including hospitals, healthcare facilities, laboratories, and other high-risk environments where mask compliance is necessary for safety and hygiene.

## Dataset
The dataset consists of labeled images of individuals with and without face masks. The images are preprocessed before training the model. 

## Technologies Used
- **Python** for scripting and implementation
- **TensorFlow/Keras** for deep learning model training
- **OpenCV** for real-time face detection
- **Scikit-Learn** for data preprocessing and evaluation
- **Matplotlib & Seaborn** for data visualization
- **Google Colab** for model training using GPU support

## Project Workflow
1. **Data Collection & Preprocessing**
   - Extract and preprocess images of masked and unmasked faces.
2. **Model Development**
   - Train a **Convolutional Neural Network (CNN)** for classification.
3. **Model Training & Validation**
   - Split the dataset into training and testing sets.
4. **Model Evaluation**
   - Measure accuracy, precision, recall, and F1-score.
5. **Real-Time Detection**
   - Integrate the trained model with OpenCV for live mask detection using a webcam.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/face-mask-detection.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the detection script:
   ```bash
   python detect_mask.py
   ```

## Results
- The model achieved **95%+ accuracy** on the test dataset.
- Successfully detects masks in real-time with minimal lag.

## Applications
- **Public Safety:** Can be deployed in offices, malls, and transport hubs.
- **Automated Monitoring:** Reduces the need for manual enforcement.
- **Scalability:** Can be integrated into larger surveillance systems.

## Contributing
Feel free to contribute by improving the model, optimizing performance, or integrating with IoT devices.


