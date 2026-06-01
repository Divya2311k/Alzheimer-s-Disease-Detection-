# 🧠 Alzheimer’s Detection with CNN-SVM

This project leverages **Artificial Intelligence and Medical Imaging** to enable early detection of Alzheimer’s disease from MRI scans. By combining **Convolutional Neural Networks (CNNs)** for deep feature extraction and **Support Vector Machines (SVMs)** for robust classification, the system achieves reliable stage identification (Mild, Very Mild, Moderate, Demented).

### ✨ Key Features
- **Hybrid CNN-SVM Model**: CNN extracts spatial features, SVM refines classification.
- **Explainability with Grad-CAM**: Heatmaps highlight critical brain regions influencing predictions.
- **Streamlit Interface**: User-friendly dashboard for uploading MRI scans and viewing results.
- **Real-time Retraining**: Model adapts to new data for improved accuracy over time.
- **Prediction History**: Results stored in SQLite database for reference and tracking.

### ⚙️ Tech Stack
- **Languages & Frameworks**: Python (3.x), PyTorch, scikit-learn, OpenCV, Streamlit  
- **Environment**: Anaconda distribution for dependency management  
- **Tools**: VS Code with Jupyter integration for experimentation and debugging  

### 🚀 Motivation
Alzheimer’s affects millions worldwide, and early detection is critical for timely intervention. Traditional manual MRI analysis is time-consuming and error-prone. This project demonstrates how **AI-driven diagnostics** can enhance accuracy, efficiency, and transparency in healthcare.

---

## 📌 How to Run
1. Clone the repository  
2. Set up environment with Anaconda (`conda install requirements.txt`)  
3. Launch Streamlit app:  
4. Upload MRI scans → View predictions + Grad-CAM heatmaps  

---

## 📖 Research Basis
This project builds on recent studies integrating CNNs and SVMs for Alzheimer’s detection, achieving accuracies up to **99%** in benchmark datasets. It addresses challenges like dataset limitations, interpretability, and real-world deployment by offering a modular, explainable, and scalable solution.

---

## 👩‍💻 Author
Divya — Data Analyst & AI Enthusiast  
Passionate about **AI-driven healthcare, explainable models, and recruiter-ready analytics projects**.
