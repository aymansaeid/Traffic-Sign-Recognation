# Traffic Sign Recognition - Machine Learning Project  

## 1. Problem Definition  

In this project, a machine learning model will be developed to classify different traffic signs.  

The automatic recognition of traffic signs provides a crucial application area for autonomous driving systems and road safety.  

The study aims to compare the performance of two different machine learning algorithms:  

- A tree-based model (Random Forest or XGBoost).  
- A deep learning-based model (Convolutional Neural Network, CNN).  

---  

## 2. Summary of the Dataset Used in the Study  

The project will use the **GTSRB - German Traffic Sign Recognition Benchmark** dataset available on Kaggle (https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign/data). This dataset contains the following details about various traffic signs:  

- **Total Number of Classes**: 43 (e.g., stop sign, speed limit, warning signs, etc.).  
- **Total Number of Images**: 50,000+.  
- **Image Dimensions**: Each image will be normalized to 32x32 pixels.  
- **Dataset Structure**: The dataset is organized into “train” and “test” folders, with each class having its own subfolder.  

This dataset provides a sufficient amount of labeled data to train both machine learning and deep learning models.  

### **Data Preprocessing:**  
- Images will be normalized to a size of 32x32 pixels.  
- Data augmentation techniques (e.g., rotation, flipping) will be applied to improve model performance.  

---  

## 3. Machine Learning Algorithms and Evaluation Methods  

### **Algorithms to be Used:**  

**A - Tree-Based Model**  

**B - Convolutional Neural Network (CNN)**  

### **Evaluation Methods:**  
- **Accuracy**: The accuracy rates of both models will be compared.  
- **Training Time**: The training durations of the algorithms will be recorded.  
- **Confusion Matrix**: An analysis will be conducted to determine which traffic signs are harder to recognize.  
- **Model Complexity**: The complexity and computational cost of the tree-based model and CNN will be compared.  

