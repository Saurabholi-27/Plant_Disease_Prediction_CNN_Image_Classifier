# Plant Disease Prediction Model  

This project was developed as part of the AICTE Internship on *AI: Transformative Learning*, a collaborative initiative by Microsoft, SAP, AICTE, and Edunet Foundation. The objective of the project was to build a machine learning-based solution to predict plant diseases using image data, leveraging deep learning techniques and computer vision.  

---

## **Overview**  
The Plant Disease Prediction Model is designed to identify diseases in plants based on image inputs. The system uses a Convolutional Neural Network (CNN) architecture for feature extraction and classification, aiming to provide a reliable tool for early disease detection in agriculture.  

---

## **Features**  
1. **Data Preprocessing:**  
   - Images are preprocessed with resizing, augmentation, and train-test splitting.  
   - Parameters optimized to enhance model performance and generalization.  

2. **Model Architecture:**  
   - Built with TensorFlow/Keras using convolutional, pooling, and dense layers.  
   - Tailored for image classification tasks.  

3. **Performance Evaluation:**  
   - Results visualized through accuracy and loss graphs.  

4. **Prediction System:**  
   - Capable of processing new image data for disease prediction.  
   - Trained model saved locally and on Google Drive for reuse and deployment.  

---

## **Libraries and Dependencies**  
The following libraries were utilized:  
- **Python Libraries:** `random`, `os`, `json`, `numpy`, `matplotlib`, `tensorflow`, `Pillow`  
- **Utilities:** Kaggle API for dataset download and management  

---

## **Steps to Implement**  
1. **Install and Authenticate Kaggle API:**  
   - Configure Kaggle credentials to download the dataset.  

2. **Preprocess Data:**  
   - Prepare datasets using image resizing and augmentation.  

3. **Build and Train CNN Model:**  
   - CNN model constructed using TensorFlow/Keras, with reproducibility ensured via fixed random seeds.  

4. **Evaluate Model:**  
   - Assess the performance through metrics like accuracy and visualize the results.  

5. **Save and Deploy Model:**  
   - Model saved to local storage and uploaded to Google Drive for further use.  
   - [Model Link](https://drive.google.com/file/d/1RZ_40gyZsoPXKmEurwkVO6hfM3Ns1c9f/view?usp=drive_link)  

---

## **Results**  
- Successfully implemented a deep learning-based plant disease prediction system.  
- Achieved reliable performance in detecting and classifying plant diseases from images.  

---

## **Acknowledgments**  
I would like to express my sincere gratitude to my mentor, Abdul Aziz Md, for their constant support and guidance throughout this internship. I am also thankful to AICTE, Microsoft, SAP, and Edunet Foundation for providing this opportunity to explore and apply emerging technologies in AI and Machine Learning.  

---

## **Future Scope**  
- Integration with real-time image capture devices like drones or smartphones.  
- Deployment as a mobile or web-based application for easy accessibility by farmers.  
