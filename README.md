# 🫁 Early Lung Cancer Detection Using Deep Learning

## 📌 Overview

Early Lung Cancer Detection is a Deep Learning-based medical image analysis system designed to assist in the early diagnosis of lung cancer using CT scan images. The system utilizes a Convolutional Neural Network (CNN) to classify lung CT scans into different categories and provides visual explanations using Grad-CAM heatmaps.

The goal of this project is to support healthcare professionals by providing faster, more accurate, and interpretable predictions for lung cancer detection.

---

## ✨ Features

- 🧠 Deep Learning-based CT Scan Classification
- 🫁 Detection of Healthy, Benign, and Malignant Cases
- 📊 Automated Image Preprocessing
- 🔥 Grad-CAM Heatmap Visualization
- 🌐 User-Friendly Flask Web Application
- ⚡ Fast and Reliable Predictions
- 📈 Model Performance Visualization

---

## 🚀 How It Works

1. User uploads a lung CT scan image.
2. Image is preprocessed (resizing and normalization).
3. CNN model analyzes the image.
4. The system predicts the category:
   - Healthy
   - Benign
   - Malignant
5. Grad-CAM generates a heatmap showing important regions.
6. Results are displayed through a Flask web interface.

---

## 🏗️ System Workflow

```text
CT Scan Image
       │
       ▼
Image Preprocessing
       │
       ▼
CNN Feature Extraction
       │
       ▼
Classification
       │
       ▼
Grad-CAM Visualization
       │
       ▼
Prediction Results
       │
       ▼
Flask Web Interface
```

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|----------|
| Python | Programming Language |
| TensorFlow | Deep Learning Framework |
| Keras | CNN Model Development |
| OpenCV | Image Processing |
| NumPy | Numerical Computation |
| Matplotlib | Visualization |
| Seaborn | Data Analysis & Graphs |
| Flask | Web Application |
| Jupyter Notebook | Model Development |

---

## 📂 Dataset

The model is trained using lung CT scan images belonging to categories such as:

- Adenocarcinoma
- Large Cell Carcinoma
- Squamous Cell Carcinoma
- Benign
- Malignant
- Normal

The dataset helps the model learn patterns associated with different lung conditions.

---

## 🧠 Model Architecture

The project uses a Convolutional Neural Network (CNN) for:

- Feature Extraction
- Pattern Recognition
- Image Classification

CNN automatically learns important image features such as:

- Edges
- Textures
- Shapes
- Tumor Regions

---

## 🔥 Grad-CAM Visualization

Grad-CAM (Gradient-weighted Class Activation Mapping) is integrated to improve model interpretability.

Benefits:

- Highlights important regions influencing predictions.
- Helps understand model decisions.
- Improves trust and transparency in AI-assisted diagnosis.

---

## 📊 Output

The system provides:

- Predicted Class
- Confidence Score
- Original CT Scan Image
- Grad-CAM Heatmap
- Visual Explanation of Prediction

---

## 🚀 Installation

### Clone the Repository

```bash
git clone https://github.com/yourusername/early-lung-cancer-detection.git
cd early-lung-cancer-detection
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Application

```bash
python app.py
```

or

```bash
flask run
```

---

## 📁 Project Structure

```text
Early-Lung-Cancer-Detection/
│
├── dataset/
├── models/
├── static/
├── templates/
├── app.py
├── train_model.py
├── predict.py
├── gradcam.py
├── requirements.txt
└── README.md
```

---

## 🎯 Advantages

- Early disease detection
- Reduced manual workload
- Consistent diagnosis support
- Explainable AI through heatmaps
- Easy-to-use web interface
- Scalable and extensible architecture

---

## ⚠️ Limitations

- Performance depends on dataset quality.
- Requires CT scan images.
- Not a replacement for professional medical diagnosis.
- Accuracy can be improved with larger clinical datasets.

---

## 🔮 Future Enhancements

- Integration with hospital systems
- Mobile application support
- Real-time clinical deployment
- Detection of additional lung diseases
- Larger and more diverse training datasets
- Faster prediction and inference models
- Automated report generation

---

## 👨‍💻 Team Members

- M. Kalyani
- K. Tejasree
- G. Yamini
- G. Mohana Krishna
- R. Lohitha

**SRM University AP**  
Department of Computer Science and Engineering

---



## ⭐ Support

If you find this project useful, consider giving it a ⭐ on GitHub.
