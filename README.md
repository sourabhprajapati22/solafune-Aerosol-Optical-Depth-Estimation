# **Solafune - Aerosol Optical Depth (AOD) Estimation**

Aerosol Optical Depth (AOD) is a crucial parameter for understanding air quality and climate change. It quantifies the amount of aerosols present in the atmosphere. Accurate AOD estimation has significant implications for public health, weather forecasting, and climate research. The ultimate goal of this project is to advance methodologies for AOD estimation, contributing to global efforts in environmental protection and climate change mitigation.

---

## **Evaluation Metric**
The **Pearson Correlation Coefficient (R)** is used as the evaluation metric.

```math
R = \frac{\sum (X_i - \bar{X})(Y_i - \bar{Y})}{\sqrt{\sum (X_i - \bar{X})^2} \sqrt{\sum (Y_i - \bar{Y})^2}}
```

![Pearson R Equation](https://github.com/user-attachments/assets/62f95fa6-d4b2-40c7-9c64-01e42ed7a6f6)

---

## **Dataset**
The dataset consists of **satellite imagery from Sentinel-2**.

🔗 **[Competition Data](https://solafune.com/competitions/ca6ee401-eba9-4f7d-95e6-d1b378a17200?menu=data&tab=&modal=%22%22)**

---

## **Leaderboard Performance**
**My Rank:** **35** out of **313** participants  

### **My Best Model (Ensemble)**
| Model | Public Score | Private Score | Score Type |
| --- | --- | --- | --- |
| CatBoost + RandomForest + XGBoost + LightGBM | **0.9678** | **0.9538** | Best Score |

### **Winner’s Score**
| Public Score | Private Score |
| --- | --- |
| **0.9906** | **0.9897** |

---
