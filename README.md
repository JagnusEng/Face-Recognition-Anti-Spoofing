# 🛡️ Face Recognition & Anti-Spoofing System

This project is a real-time face recognition and anti-spoofing system built using deep learning and computer vision. It uses MTCNN for face detection, FaceNet for facial recognition, and a custom CNN model to detect fake face attacks like printed photos or videos.

## 🔍 Features
- Detect faces in real time using MTCNN
- Identify and verify faces using FaceNet embeddings
- Prevent spoofing attacks using a CNN trained on real vs. fake face images

## 🛠️ Tech Stack
- Python, OpenCV
- TensorFlow/Keras
- MTCNN, FaceNet
- Google Colab
- Kaggle Dataset: [Real and Fake Face Detection](https://www.kaggle.com/datasets/ciplab/real-and-fake-face-detection)

## 🗂️ Project Structure
```
notebooks/
├── face_anti_spoofing.ipynb   # Main Colab notebook

dataset/
├── training_real/             # Real face images
├── training_fake/             # Fake face images

outputs/
├── embeddings/                # Saved face embeddings
├── models/                    # Trained CNN model

scripts/ (optional)
```

## 🚀 How to Run (In Google Colab)
1. Mount Google Drive
2. Upload `kaggle.json`
3. Download the dataset using Kaggle API
4. Run the notebook to:
   - Detect faces
   - Extract embeddings
   - Train anti-spoofing model
   - Make predictions on new images

## 📈 Results
- Anti-spoofing model accuracy: ~90%
- Face recognition using cosine similarity

## 📌 Example Use Cases
- Secure login with facial verification
- Employee check-in system
- Door unlock with face ID

## 📄 License
MIT License

## 🙌 Acknowledgments
- [Kaggle - Real and Fake Face Detection Dataset](https://www.kaggle.com/datasets/ciplab/real-and-fake-face-detection)
- MTCNN: Face Detection
- FaceNet: Face Embedding Model
