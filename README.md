# 🌿 Money Plant Disease Classification Dataset 

<p align="center">
  <img src="https://img.shields.io/badge/Dataset-6000%20Images-brightgreen">
  <img src="https://img.shields.io/badge/Classes-3-blue">
  <img src="https://img.shields.io/badge/Accuracy-99.95%25-success">
  <img src="https://img.shields.io/badge/License-CC%20BY%204.0-orange">
  <img src="https://img.shields.io/badge/Domain-Precision%20Agriculture-green">
</p>

---

## 📌 Overview
This repository presents a **high-quality money plant (Epipremnum aureum) disease dataset** along with a deep learning-based classification approach for **ornamental horticulture and precision agriculture**.

🎯 **Goal:** Enable early disease detection to improve plant health monitoring and smart agriculture systems.

📊 **Dataset Summary:**
- 1872 original images  
- 6000 augmented images  
- Image size: **224 × 224 (processed)**  
- Format: RGB (JPG)  

---

## 📁 Dataset Classes

<table>
<tr>
<td align="center">
<b>🟡 Manganese Toxicity</b><br>
<img src="Dataset/MoneyPlant/MoneyPlant/Manganese Toxicity/MT_6.jpg" width="200"><br>
Yellowing between veins
</td>

<td align="center">
<b>🟤 Bacterial Wilt</b><br>
<img src="Dataset/MoneyPlant/MoneyPlant/Bacterial wilt disease/BT_17.jpg" width="200"><br>
Brown, wilted leaf
</td>
</tr>

<tr>

  <td align="center">
<b>🌿 Healthy</b><br>
<img src="Dataset/MoneyPlant/MoneyPlant/Healthy/Healthy_3.jpg" width="200"><br>
Healthy green leaf
</td>
</tr>

</table>

---

## 📊 Dataset Statistics

| Class                | Original Images | Augmented Images |
|---------------------|----------------|------------------|
| Bacterial Wilt      | 576            | 2000             |
| Manganese Toxicity  | 596            | 2000             |
| Healthy             | 700            | 2000             |
| **Total**           | **1872**       | **6000**         |

---

## 🌍 Data Collection

- 📍 Location: Gazipur, Bangladesh  
- 📅 Time: September – December 2023  

### 📷 Devices Used
- Samsung Galaxy S22  
- Redmi Note 11 Pro Plus  

### ⚠️ Challenges
- Uneven lighting  
- Leaf overlapping  
- Reflection/glare  
- Background noise  
- Pest interference  

---

## 🧠 Data Preprocessing

- Image resizing (424×424 → 224×224)  
- Noise reduction (Gaussian smoothing)  
- Image segmentation  
- Normalization  
- Manual labeling (expert verified)  

### 🔁 Data Augmentation
- Zoom (0.6 – 1.5)  
- Horizontal flip  
- Vertical flip  
- Rotation (10°–20°)  
- Scaling (0.8 – 1.2)  

---
## 🔬 Experimental Setup

- Train/Test Split: Standard deep learning pipeline  
- Steps:
  1. Data preprocessing  
  2. Data augmentation  
  3. Model training  
  4. Validation  
  5. Testing  


## 🤖 Model Architecture
Input Image (224×224×3)
        ↓
Convolution Layers
        ↓
Batch Normalization
        ↓
   MaxPooling
       ↓
   Dense Layer
        ↓
Softmax Output (3 Classes)

---

## 📊 Evaluation Metrics

- Accuracy  
- Precision  
- Recall  
- F1-Score  
- Confusion Matrix  

---

## 📈 Performance

| Dataset Type | Precision | Recall | F1-Score | Accuracy |
|--------------|----------|--------|----------|----------|
| Raw Dataset  | 0.95     | 0.96   | 0.95     | 95.10%   |
| Augmented    | 0.99     | 0.99   | 0.99     | **99.95%** |

### 🧾 Class-wise Performance

| Class               | Precision | Recall | F1-Score |
|--------------------|----------|--------|----------|
| Bacterial Wilt     | 1.00     | 1.00   | 1.00     |
| Manganese Toxicity | 0.99     | 0.99   | 0.99     |
| Healthy            | 1.00     | 1.00   | 1.00     |

---


## 💡 Applications

- 🌱 Smart agriculture  
- 📱 Mobile-based plant disease detection  
- 🤖 Automated plant monitoring  
- 🌿 Precision horticulture  

---

## ⚠️ Limitations

- Limited to 2 diseases + healthy class  
- Region-specific dataset  
- Seasonal bias  
- Smartphone-based variability  

---

## 🚀 Future Work

- Add more disease classes  
- Multi-region dataset expansion  
- Cross-plant generalization  

---

## 📚 Citation

If you use this dataset:

**Paper:**  
Money Plant Disease Atlas: A Comprehensive Dataset for Disease Classification in Ornamental Horticulture  
Link: https://www.sciencedirect.com/science/article/pii/S2352340924011788

**Dataset:**  
Ahmad, MD Hasan (2024), “Advanced Dataset on Money Plant Diseases for AI Pathology Research”, Mendeley Data, V3, doi: 10.17632/rzjww3vdxt.3
Link: https://data.mendeley.com/datasets/rzjww3vdxt/3

---


