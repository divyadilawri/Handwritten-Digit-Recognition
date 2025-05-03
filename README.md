Handwritten Digit Recognition using CNN (MNIST):

This project builds a powerful Convolutional Neural Network (CNN) to accurately identify handwritten digits from the MNIST dataset, achieving approximately 99.2% accuracy on the validation set. It features a comprehensive preprocessing pipeline using OpenCV to handle noisy or real-world imperfect digit inputs.

🔧 Features:

✅ 4-layer CNN architecture with Batch Normalization and Dropout to improve generalization.

🧹 Image preprocessing pipeline with adaptive thresholding, morphological filtering,  and digit centering in a 28x28 frame.

🔄 Data augmentation techniques including rotation, zoom, translation, and shear via ImageDataGenerator.

🧪 Model trained and tested on over 60,000 MNIST digit samples.

📊 Evaluation includes a confusion matrix and F1 score for detailed performance analysis.

🧠 Trained model saved in .h5 format, ready for image upload-based predictions.


📦 Tech Stack:
Python, TensorFlow/Keras, OpenCV, NumPy, Matplotlib
CNN with ReLU activation, Softmax output, and Adam optimizer
Includes model performance visualization, confusion matrix, F1 score, and live prediction functionality
