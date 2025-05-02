# ⚽ Football Embeddings Experiments

This document outlines different configurations and visualizations of document embeddings for football match reports.

---

## 1. Baseline

- **Scaler**: StandardScaler  
- **Window Size**: 15  
- **Min Word Count**: 5  
- **Vector Size**: 200  

![Baseline Embedding](https://github.com/user-attachments/assets/965ca106-c4f5-4550-81d2-d84b124c6f3e)

---

## 2. PCA Scaling Applied

- **Scaler**: PCA  
- **Window Size**: 10  
- **Min Word Count**: 10  
- **Vector Size**: 72  

![PCA Scaling - 72D](https://github.com/user-attachments/assets/72711125-0481-44ea-9089-506996d70ef6)

---

## 3. Doc Vector Compression

- **Scaler**: PCA to 72D  
- **Doc Vector**: 32  

![PCA to 72D, DocVec 32](https://github.com/user-attachments/assets/ebd4c69d-efc2-44d0-8655-7c9673ce90cf)

---

## 4. Opponent Weighting = 0.9

- **Scaler**: PCA to 32D  
- **Doc Vector**: 32  
- **Window Size**: 10  
- **Opponent Weightings**: 0.9  

![Opp Weighting 0.9 - A](https://github.com/user-attachments/assets/114b2e6d-fb2d-4d16-8dbe-be25fa38931b)  
![Opp Weighting 0.9 - B](https://github.com/user-attachments/assets/78bd575d-fd57-46c8-a240-27f2e025e211)

---

## 5. Opponent Weighting = 0.5

- **Doc Vector**: 32  
- **Opponent Weightings**: 0.5  

![Opp Weighting 0.5 - A](https://github.com/user-attachments/assets/39808882-28e0-4bb5-9e90-43c4e43fe07d)  
![Opp Weighting 0.5 - B](https://github.com/user-attachments/assets/1237f07f-0078-4027-8c83-96e843c986a8)

---

## 6. Labeled Embedded Space

- **Opponent Weightings**: 0.5  
- **Visualization**: Clustered and labeled team spaces  

![Labeled Embedded Space](https://github.com/user-attachments/assets/47de7704-fdc6-4af6-9bea-7ba79a5eb9c3)

---

