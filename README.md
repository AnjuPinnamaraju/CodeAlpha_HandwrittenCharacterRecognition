# CodeAlpha_HandwrittenCharacterRecognition
It focuses on recognizing handwritten English alphabets (A–Z) using deep learning (CNN) techniques on the EMNIST Letters dataset.

📌 Objective
- Develop a character recognition model using the **EMNIST Letters dataset**.
- Apply **image processing and deep learning** (CNN) to identify handwritten alphabets.
- Evaluate the model based on its prediction accuracy and performance metrics.

🧠 Technologies Used
- Python  
- TensorFlow / Keras  
- NumPy  
- Matplotlib  
- EMNIST Dataset (via `tensorflow_datasets` or `emnist` library)

 📁 Dataset Information
- **Dataset**: EMNIST Letters (Balanced)
- **Source**: Extended MNIST (EMNIST)
- **Classes**: 26 (Letters A–Z, lowercase mapped to uppercase)
- **Image Size**: 28x28 grayscale

 🏗️ Model Architecture
- Conv2D → MaxPooling2D  
- Conv2D → MaxPooling2D  
- Flatten  
- Dense Layer (ReLU)  
- Dropout  
- Output Layer (Softmax – 26 classes)

🔧 Steps Followed
1. Load and preprocess the EMNIST dataset
2. Normalize pixel values and reshape images
3. One-hot encode the labels (A to Z)
4. Build the CNN model using TensorFlow/Keras
5. Train the model on training data
6. Evaluate accuracy on test data
7. Visualize predictions vs actual labels

 📊 Evaluation
- **Loss & Accuracy Graphs** during training
- **Accuracy Score** on test set
- **Classification report** (Precision, Recall, F1-score)
- Visual output of predicted vs true letters
