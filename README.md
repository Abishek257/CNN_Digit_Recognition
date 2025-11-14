# CNN_Digit_Recognition
A complete CNN image classification project with a training notebook and a saved TensorFlow model.

**📦 CNN Image Classification — Model & Notebook**

A simple and clean repository showcasing a Convolutional Neural Network (CNN) built for image classification.

This project includes:

📝 **CNN.ipynb**     — the full training and evaluation notebook

🧠 **bestmodel.h5**  — the final trained model saved after achieving the best performance

**🚀 Project Overview**

This project demonstrates how to build, train, evaluate, and save a Convolutional Neural Network for image classification tasks. The notebook is designed to be easy to follow, making it suitable for learners and developers experimenting with deep learning model development.

The model was trained using TensorFlow/Keras, and the repository includes the complete workflow from data preprocessing to saving the best-performing model.

📂**Repository Structure**

├── CNN.ipynb        # Full training & evaluation notebook

├── bestmodel.h5     # Saved trained CNN model

└── README.md        # Project documentation

🧰 **Features**

✔️ Clean and modular CNN architecture

✔️ Data preprocessing & augmentation

✔️ Training with metrics visualization

✔️ Model evaluation on validation/test data

✔️ Automatic saving of best model weights (bestmodel.h5)

✔️ Ready for inference or fine-tuning

🧠 **Model Details**

The CNN architecture typically includes:

Convolutional layers

Max-pooling layers

Dense layers

Softmax output for multi-class classification

Training and evaluation steps are included inside the notebook with clear explanations and plots.

▶️ **How to Use**

1️⃣ **Clone the Repository**

git clone https://github.com/yourusername/your-repo-name.git

cd your-repo-name

2️⃣ **Install Dependencies**

Ensure you have Python 3.8+ and install required packages:

pip install tensorflow numpy matplotlib

3️⃣ **Run the Notebook**

Open the notebook using Jupyter or Colab:

jupyter notebook CNN.ipynb

4️⃣ **Load the Trained Model (Optional)**

from tensorflow.keras.models import load_model

model = load_model("bestmodel.h5")

predictions = model.predict(x_test)

