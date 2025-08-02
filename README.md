 🧠 A–Z Character Classifier using CNN (Google Colab + TensorFlow)

This project builds a Convolutional Neural Network (CNN) to classify **handwritten English alphabets (A–Z)** using grayscale images. The model is trained in **Google Colab** and saved as a `.keras` file for reuse.


 📌 Features

- 📷 Image preprocessing (grayscale, 64×64 resize)
- 🧠 CNN model with 3 convolution layers
- 📈 Training + validation using Google Colab
- ✅ Accuracy evaluation + confusion matrix
- 💾 Save and load trained model (`.keras`)
- 🧪 Predict a new image (single-letter image)
- 🌐 Optional web app via Flask or Gradio

 📂 Project Structure

```
📁 Google Drive
├── 📁 Image/                ← Original dataset
├── 📁 resized_Image/        ← Grayscale resized images
├── 📄 A_Z_CNN_Classifier.ipynb
├── 📄 AZ_CNN_model.keras
```
```
📚 Requirements (Used in Colab)
TensorFlow
NumPy
OpenCV (cv2)
Matplotlib / Seaborn
scikit-learn
```

