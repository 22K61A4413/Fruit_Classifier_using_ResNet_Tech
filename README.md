# Fruit_Classifier_using_ResNet_Tech

# 🍉 Fruit Classifier using ResNet | Deep Learning Project

A **Deep Learning-based Fruit Classification System** built using **ResNet (Residual Neural Network)** to classify fruit images into **five categories** — 🍎 Apple, 🍌 Banana, 🍇 Grapes, 🥭 Mango, and 🍓 Strawberry.

---

## 🚀 Project Overview

This project demonstrates the power of **Convolutional Neural Networks (CNNs)** and **transfer learning** using **ResNet architecture**.  
By leveraging a pre-trained ResNet model (trained on ImageNet), the system accurately classifies fruit images and provides results through a web-based interface.

---

## 🧠 Key Features

- 🍏 **Classifies 5 Fruit Types:** Apple, Banana, Grapes, Mango, and Strawberry  
- ⚡ **Powered by ResNet:** Uses a pre-trained **ResNet50** model for efficient and accurate learning  
- 🧩 **Transfer Learning:** Reduces training time and improves accuracy by reusing ImageNet weights  
- 🖥️ **Web App Interface:** Simple Flask web app for uploading and predicting fruit images  
- 📈 **High Accuracy:** Robust performance with minimal data preprocessing  

---

## 🧰 Tech Stack

| Component | Technology Used |
|------------|------------------|
| **Programming Language** | Python 🐍 |
| **Deep Learning Framework** | PyTorch |
| **Model Architecture** | ResNet50 |
| **Frontend** | HTML, CSS |
| **Backend** | Flask |
| **Deployment** | ngrok (for public access) |

---

## 🧬 Model Details

**ResNet50 (Residual Network)** introduces *skip connections* to solve the **vanishing gradient problem**, allowing deeper networks to learn efficiently.

### 🧩 Architecture Workflow

Input Image → Preprocessing → ResNet50 Feature Extractor → Fully Connected Layers → Prediction (Fruit Label)

---

## 📂 Dataset

The dataset contains 5 fruit classes:
- 🍎 **Apple**
- 🍌 **Banana**
- 🍇 **Grapes**
- 🥭 **Mango**
- 🍓 **Strawberry**

Images are preprocessed (resized, normalized, and augmented) for better model generalization.

---

## ⚙️ How to Run Locally

**Clone the repository**
   ```bash
   git clone https://github.com/22K61A4413/Fruit_Classifier_using_ResNet_Tech.git
   cd Fruit_Classifier_using_ResNet_Tech

Fruit Classifier Live Demo :  https://github.com/22K61A4413/Fruit_Classifier_using_ResNet_Tech.git
   cd Fruit_Classifier_using_ResNet_Tech

## Example Output ##

Input: strawberry.jpg  
Output: 🍓 Predicted Fruit → Strawberry (Confidence: 98.4%)

# Conclusion

This project showcases how transfer learning with ResNet can be used to build efficient and accurate computer vision applications.
It’s a perfect example of how deep learning models can classify images effectively — even with limited training data.

“Innovation in AI is not about reinventing — it’s about improving what already works.” 🚀

⭐ If you like this project, don’t forget to star the repo!
