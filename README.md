# Galaxy Image Classification with Machine Learning and Deep Learning  

## Project Description  
The purpose of this activity is to apply and compare different galaxy image classification algorithms using Machine Learning and Deep Learning techniques. The dataset used is **T_F_DR14_ZooSpec_10000**, which contains images represented as pixel values (64x64) along with classifications provided by volunteers.  

## Tasks Performed  

### 1. Image Visualization  
- Reconstructed galaxy images from pixel values.  
- Filtered data to select only galaxies of type **1 (spiral)** and **2 (elliptical)**.  

### 2. Application of Machine Learning Algorithms  
The following algorithms were implemented and compared:  
- **SVM without Kernel**  
- **SVM with Kernel**  
- **Decision Trees**  
- **Multilayer Perceptron**  
- **Naive Bayes**  
- **K-Nearest Neighbors (KNN)**  

For each algorithm, the following evaluation metrics were calculated:  
- **Confusion Matrix**  
- **Sensitivity**  
- **Precision**  
- **Accuracy**  
- **Classification Report**  
- **ROC Curve**  

A comparative table was created to analyze the results of each algorithm.  

### 3. Convolutional Neural Networks (Deep Learning)  
A Deep Learning library (**TensorFlow, Keras, ApacheMxnet, etc.**) was used to train a **Convolutional Neural Network (CNN)** model and compare its performance with traditional Machine Learning algorithms using the same evaluation metrics.  

### 4. Unsupervised Learning  
A scenario was simulated where the **Target** column was unavailable, and unsupervised learning algorithms were applied to classify images across the entire dataset:  
- **K-Means**  

## Conclusion  
This project enabled the analysis and comparison of different approaches to galaxy image classification using both Machine Learning and Deep Learning techniques. Supervised and unsupervised models were explored, and their performance metrics were evaluated to determine which approach yields the best results in each case.  
