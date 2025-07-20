# 🧠 Parkinson’s Diagnosis via Speech – Research Project

**Numerical and Graphical Feature-Based Speech Analysis for Parkinson’s Disease Detection**  
🎓 Final-Year B.Tech Research Thesis · Siksha 'O' Anusandhan University  
📁 Repo: `parkinsons-diagnosis-ai-research`

---

## 📖 Abstract

Parkinson’s Disease (PD) is a progressive neurodegenerative disorder that often impacts a patient’s speech well before motor symptoms are clinically apparent. This research presents a machine learning pipeline that analyzes both **numerical acoustic features** and **graphical waveform patterns** to aid in early-stage PD detection.

Our experimentation covered over **10 traditional ML models**, **10+ deep learning architectures**, and a **custom multimodal fusion model** that combines both feature domains.

---

## 📊 Key Contributions

- 📌 Built and compared **19+ models** across structured and unstructured speech data
- ⚗️ Explored **9 dataset permutations** with varying preprocessing pipelines
- 🧠 Designed a **Multimodal Neural Network** to fuse numerical + spectrogram features
- 📈 Documented comparative analysis, ROC-AUC, F1 scores, and confusion matrices
- 📄 Published as a formal thesis under a research-backed academic program

---

## 🧪 Techniques & Models Used

### 🏗️ Classical ML Models:
- Logistic Regression, Random Forest, Decision Tree, KNN  
- SVM (Linear & RBF), XGBoost  
- Gaussian Naive Bayes  
- Ensemble methods: VotingClassifier, AdaBoost, Bagging  

### 🧠 Deep Learning Models:
- Fully Connected DNN  
- CNN (Spectrogram image input)  
- LSTM, BiLSTM  
- 1D-CNN + LSTM hybrids  
- Multimodal Neural Network (early + late fusion)

> All models were evaluated on consistent test sets with F1, AUC, and recall as key metrics.

---

## 🗂️ Datasets Used

- 🧾 **MDVR-KCL Dataset** (Italy)  
- 🎙️ **Italian Parkinson’s Dataset** — Publicly available voice recordings

### Features Extracted:
- Acoustic: Fundamental frequency, jitter, shimmer, NHR, HNR  
- Spectral: MFCCs, Delta-MFCCs  
- Graphical: Spectrogram generation via Librosa/Matplotlib

> ⚠️ Raw datasets are not included due to license restrictions.  


---

## 📎 Resources

- 📄 **Thesis Report**: [`coming soon`]
- 📚 **Dataset Source Info**:  
  - [UCI ML Repository – PD Dataset](https://archive.ics.uci.edu/ml/datasets/Parkinsons)  
  - [MDVR-KCL Dataset Info](https://archive.ics.uci.edu/ml/datasets/Parkinsons+Telemonitoring)  
- 📖 **Research Guide**: Prof. Ishan Ayus 

---

## 👥 Team

- **Utsav Poddar** – *Team Lead, Research & Engineering (Numerical Method)*  
- **Nigmananda Behera** – *Research & Engineering (Graphical Method)*  
- **Shaan Rout** – *Research & Synthesis*
- **Yameshwar Kumar Rai** – *Synthesis*   
- Department of Computer Science, Siksha 'O' Anusandhan University

---

## 🧠 Why This Research Matters

Early detection of Parkinson’s can drastically improve patient quality of life.  
By using **non-invasive voice data** and combining both structured and visual speech features, we demonstrate the potential for fast, low-cost screening tools that require no medical imaging or wearable sensors.

This work bridges **AI**, **signal processing**, and **healthcare innovation** — and could serve as a stepping stone for building real-time diagnosis apps for use in clinics, remote care, or personal monitoring.

---

## 📜 License

This repository and all its contents — including the thesis PDF, notebooks, models, and documentation — are released under:

> **Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International**  
> (CC BY-NC-ND 4.0)

**You may:**
- View, clone, and share this repo
- Reference the thesis in academic works (with proper citation)

**You may NOT:**
- Modify or build upon this work  
- Use for commercial purposes  
- Train or deploy this in commercial pipelines without written permission

Read full license here: [https://creativecommons.org/licenses/by-nc-nd/4.0/](https://creativecommons.org/licenses/by-nc-nd/4.0/)

---

> 🧪 *Built with care for science, not for sale.*

