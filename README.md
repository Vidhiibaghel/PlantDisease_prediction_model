# PlantDisease_prediction_model
This project is a Deep Learning–based Plant Disease Classification Model that identifies plant diseases from leaf images with high accuracy. It helps farmers and researchers detect diseases early and take preventive measures.
📌 Features
🌱 Classifies 38 plant disease classes (healthy & diseased)

📊 Supports confidence score prediction for each class

🖼️ Works with both healthy and diseased leaves

🚀 Trained using TensorFlow/Keras with data augmentation

📈 Provides evaluation metrics including confusion matrix & classification report

💾 Model saved in .keras and .h5 formats for easy deployment.

📂 Dataset

It contains images across 38 categories such as:

🍎 Apple (Apple Scab, Black Rot, Cedar Rust, Healthy)

🌽 Corn (Cercospora Leaf Spot, Northern Leaf Blight, Rust, Healthy)

🍇 Grape (Black Rot, Esca, Leaf Blight, Healthy)

🍅 Tomato (Bacterial Spot, Early Blight, Late Blight, Leaf Mold, Healthy)

🥔 Potato (Early Blight, Late Blight, Healthy)

and more...

🛠️ Model Training
Architecture: Convolutional Neural Network (CNN)

Input Size: 224×224

Optimizer: RMSProp

Loss Function: Categorical Crossentropy

Callbacks: Early Stopping to avoid overfitting

Evaluation: Accuracy, Loss curves, Confusion Matrix

