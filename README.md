# Nail Disease Diagnosis: Comparative Analysis of InceptionV3 and Xception Models

This project presents a deep learning-based diagnostic system to classify six types of nail diseases using two advanced convolutional neural network architectures — **InceptionV3** and **Xception**. The models are compared for accuracy, robustness, and efficiency using a publicly available medical image dataset.

---

## 🧠 Project Overview

Nail diseases such as fungal infections, pitting, and melanoma are often early indicators of serious health conditions. Traditional diagnosis relies on expert evaluation and is time-consuming. This study explores how deep learning can enhance speed and accuracy in nail disease detection.

- 📌 **Models Used**: InceptionV3, Xception
- 🎯 **Goal**: Compare performance in classifying 6 nail disease categories
- 🧪 **Accuracy Achieved**:
  - Xception: **97.5%**
  - InceptionV3: **95.12%**
- 📊 Evaluation: Accuracy, confusion matrix, AUC-ROC

---

## 📂 Dataset

- Source: [Kaggle - Nail Disease Detection using CNN](https://www.kaggle.com/code/nirmalgaud/nail-disease-detection-using-cnn/notebook)
- Total Images: 3,993
- Classes:
  - Healthy Nails
  - Blue Finger
  - Acral Lentiginous Melanoma
  - Pitting
  - Onychogryphosis
  - Clubbing

---

## 🧪 Methodology

1. **Data Preprocessing**
   - Image resizing and augmentation
   - Class balancing
2. **Model Training**
   - Transfer learning using InceptionV3 and Xception
   - Adam optimizer and categorical cross-entropy loss
3. **Evaluation Metrics**
   - Accuracy
   - Confusion matrix
   - AUC-ROC curve

---

## 🧬 Results

| Model       | Accuracy |
|-------------|----------|
| Xception    | 97.5%    |
| InceptionV3 | 95.12%   |

- Confusion matrices and AUC-ROC curves show superior classification of rare diseases using Xception.

---

## 🚀 Deployment

- A basic **web interface** was developed for real-time diagnosis.
- Future scope includes:
  - Improving model with larger dataset
  - Building a mobile app
  - Integrating **Explainable AI (XAI)** features

---

## 📚 References

1. Yamac et al., TSP 2022, IEEE. DOI: [10.1109/TSP55681.2022.9851300](https://doi.org/10.1109/TSP55681.2022.9851300)
2. Shandilya et al., BMC Medical Informatics and Decision Making, 2024.
3. Mehra et al., ICNTE 2021. DOI: 10.1109/ICNTE51185.2021.9487709
4. Sarıkaya Solak et al., Balkan Med J. 2024.
5. Alzahrani et al., ICCIT 2023. DOI: 10.1109/ICCIT58132.2023.10273947

---

## 👨‍💻 Authors

- **Arpana Indrajit** – Centurion University of Technology & Management
- Co-authors:
  - Mr. Santosh Kumar Pradhan
  - Mr. Shuvendu Parida
  - Mr. Lalit Kumar Behera
  - Dr. Sujata Chakravarty

---

## 📌 Conference Info

Presented at:  
**3rd International Conference on Microwave, Optical and Communication Engineering (ICMOCE-2025)**  
📍 IIT Bhubaneswar, May 23–25, 2025  
📄 Paper ID: 178  
📘 DOI to be assigned upon publication

---

## 🙏 Acknowledgements

We thank the research team, our mentors, and the conference reviewers for their support and valuable feedback.
