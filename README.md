🛑 Traffic Sign Recognition using CNN
🚀 Overview

This project implements a Convolutional Neural Network (CNN) to classify traffic signs from the German Traffic Sign Recognition Benchmark (GTSRB) dataset.
It can be used for real-time traffic sign detection in autonomous driving systems.

📂 Dataset

Source: GTSRB Dataset

Contains 43 classes of traffic signs.

Includes thousands of labeled images.

🛠️ Tech Stack

Language: Python

Libraries:

TensorFlow / Keras

NumPy, Pandas

Matplotlib (visualization)

OpenCV (image preprocessing)

⚙️ Features

Image preprocessing (resizing, normalization).

Data augmentation for better generalization.

CNN model built using TensorFlow/Keras.

Accuracy evaluation + confusion matrix visualization.

📈 Model Results

Achieved ~97% accuracy on test set.

Confusion matrix used to evaluate misclassifications.

Example plots:

# Example training plot code
plt.plot(history.history['accuracy'])
plt.plot(history.history['val_accuracy'])
plt.title('Model Accuracy')
plt.xlabel('Epoch')
plt.ylabel('Accuracy')
plt.legend(['Train', 'Validation'], loc='lower right')
plt.show()


<img width="936" height="355" alt="image" src="https://github.com/user-attachments/assets/84735fd4-3278-47c7-8905-93ab402bacb7" />


▶️ How to Run

Clone the repository:

git clone https://github.com/geddadasaisuchendra/Traffic_Sign_Recognisation.git
cd Traffic_Sign_Recognisation


Install requirements:

pip install -r requirements.txt


Run training script:

python train.py


Evaluate model:

python evaluate.py

🎯 Future Improvements

Integrate with OpenCV for real-time detection via webcam.

Deploy as a Flask/Streamlit web app.

Optimize with transfer learning (e.g., MobileNetV2).

👤 Author

Developed by Sai Suchendra Geddada

📧 saisuchendrageddada25@gmail.com
