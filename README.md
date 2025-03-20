# OCTMNIST-Classification-Using-Neural-Networks

## 📌 Project Overview
This project focuses on **classifying OCTMNIST images** using a **Neural Network**. The model was optimized using various **training enhancement techniques** such as **Early Stopping, Learning Rate Scheduling (LRS), Gradient Accumulation, and Data Augmentation** to improve performance.

---

## 📂 Dataset
The **OCTMNIST dataset** contains optical coherence tomography (OCT) images categorized into different classes. The objective is to build a **robust classification model** that can effectively distinguish between different eye conditions.

### **Preprocessing Steps:**
- Resized images for uniform input shape.
- Applied **normalization** and **data augmentation** where applicable.
- Converted labels into categorical format for multi-class classification.

---

## 🛠️ Tech Stack
- **Programming Language:** Python  
- **Deep Learning Framework:** TensorFlow / PyTorch  
- **Libraries Used:**
  - `TensorFlow / PyTorch` – Model implementation
  - `matplotlib & seaborn` – Data visualization
  - `numpy & pandas` – Data handling
  - `scikit-learn` – Performance evaluation

---

## 🔍 Model Training & Optimization Techniques

### **1️⃣ Base Neural Network Model**
- Implemented a **basic CNN architecture** for image classification.
- Used **ReLU activation** and **Softmax for final classification**.

### **2️⃣ Performance Enhancement Techniques**
✅ **Early Stopping** – Stopped training when validation loss stopped improving.  
✅ **Learning Rate Scheduling (LRS)** – Adjusted learning rates dynamically to enhance training.  
✅ **Gradient Accumulation** – Accumulated gradients over multiple batches to stabilize training.  
✅ **Data Augmentation** – Applied random transformations to increase dataset diversity.

---

## 📊 Results & Analysis

| Optimization Method       | Accuracy  |
|--------------------------|-----------|
| **Early Stopping**       | **0.81**  |
| **Learning Rate Scheduler (LRS)** | **0.79**  |
| **Gradient Accumulation** | **0.76**  |
| **Data Augmentation**     | **0.71**  |

🔹 **Early Stopping & Learning Rate Scheduling** proved to be the most effective for this task.  
🔹 **Data Augmentation reduced accuracy**, suggesting excessive noise or variation in this dataset.

---

🚀 This is a showcase repository for my project **OCTMNIST Classification Using Neural Networks**.
The source code is currently private for personal reasons.

