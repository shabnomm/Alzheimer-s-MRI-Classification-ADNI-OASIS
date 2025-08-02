# Alzheimer's MRI Classification (ADNI & OASIS Dataset)

This project aims to classify structural MRI scans of the human brain into different stages of Alzheimer's disease using deep learning techniques. The model leverages convolutional neural networks (CNNs) trained on the ADNI and OASIS datasets and achieves high accuracy with interpretability using Grad-CAM.

---

## 📌 Project Highlights

- ✅ Achieved **98.36% accuracy** on validation data
- 🧪 Used **ADNI** and **OASIS** public MRI datasets
- 🧠 Built a custom **CNN architecture** from scratch
- 🔁 Applied **data preprocessing** and **augmentation**
- 📊 Evaluated using **accuracy**, **F1-score**, and **confusion matrix**
- 🔍 Integrated **Grad-CAM** for model explainability
- ⚙️ Currently exploring **Generative AI** for synthetic MRI generation

---

## 🧬 Problem Statement

Alzheimer’s disease is a progressive neurodegenerative disorder. Early diagnosis is critical for effective intervention. This project focuses on automating the classification of Alzheimer's stages from MRI scans using deep learning to support medical professionals with reliable AI-powered predictions.

---

## 📁 Dataset Overview

- **ADNI (Alzheimer’s Disease Neuroimaging Initiative)**  
- **OASIS (Open Access Series of Imaging Studies)**  
- Categories:  
  - Non-Demented  
  - Very Mild Dementia  
  - Mild Dementia  
  - Moderate Dementia

Each image is labeled based on cognitive impairment stages.

---

## ⚙️ Technologies Used

| Tool/Library       | Purpose                     |
|--------------------|-----------------------------|
| Python             | Programming Language        |
| TensorFlow / Keras | CNN Model Development       |
| NumPy, Pandas      | Data Handling               |
| OpenCV, PIL        | Image Processing            |
| Matplotlib, Seaborn| Visualization               |
| Grad-CAM           | Model Explainability        |
| Google Colab       | Training Environment        |

---

## 🛠️ Project Workflow

1. **Data Collection & Preprocessing**  
   - Resize, normalize, and standardize MRI scans  
   - Label mapping and stratified splitting  
2. **Data Augmentation**  
   - Rotation, flipping, zooming to reduce overfitting  
3. **Model Building**  
   - Custom CNN with multiple Conv2D and MaxPooling layers  
   - Dropout and batch normalization for generalization  
4. **Model Evaluation**  
   - Accuracy, Precision, Recall, F1-score  
   - Confusion Matrix visualization  
5. **Explainability with Grad-CAM**  
   - Visual heatmaps to interpret model predictions  
6. **(In Progress)** Generative AI for synthetic MRI generation  

---

## 📈 Results

- ✅ **Validation Accuracy**: 98.36%  
- ✅ **F1-Score**: High across all classes  
- ✅ Clear Grad-CAM activation maps validating spatial learning

---

## 🧪 Next Steps

- [ ] Implement Generative Adversarial Networks (GANs) to synthesize MRI data  
- [ ] Test on noisy/low-resolution scans for robustness  
- [ ] Build a web-based classifier using Streamlit  

---

## 📷 Visuals

<Insert sample predictions, confusion matrix, and Grad-CAM visualizations here once available>

---

## 💡 Lessons Learned

- How to handle and preprocess biomedical image data  
- CNN design and performance tuning  
- Importance of model interpretability in medical AI  
- The potential of Generative AI in medical imaging

---

## 🧾 License

This project is for educational and research purposes only. Please consult official medical professionals before relying on AI-generated diagnosis.

---

## 🤝 Acknowledgments

- ADNI and OASIS dataset providers  
- TensorFlow and Keras open-source communities  
- Grad-CAM: https://github.com/jacobgil/pytorch-grad-cam

---

## 📬 Contact

**Author**: Mithun Shabnom  
**LinkedIn**: [Your LinkedIn URL]  
**Email**: [Your email]  
**GitHub**: https://github.com/shabnomm

---

⭐ Star this repo if you find it helpful!
