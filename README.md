# Face Recognition System  

A high-performance face recognition system designed using **FaceNet**, **MTCNN**, and **Support Vector Machine (SVM)**, optimized for accuracy and real-time video processing.  

## Features  
- **Face Detection**:  
  - Utilized **MTCNN** for efficient and accurate face detection from images and video feeds.  
- **Face Embedding Generation**:  
  - Implemented **FaceNet** to generate 128-dimensional embeddings for each detected face, ensuring robust feature representation.  
- **Face Classification**:  
  - Leveraged **SVM** for precise classification of known and unknown faces based on embeddings.  
- **Dataset**:  
  - Processed over **5,000 facial images** to create a diverse and robust training and testing dataset.  
- **Real-Time Processing**:  
  - Optimized the system to process video feeds at **30 FPS** using a standard webcam input.  
- **Enhanced Performance**:  
  - Improved detection accuracy and robustness by tuning hyperparameters and incorporating a **confidence threshold**, enhancing unknown face detection by **20%**.  

## Highlights  
- **Accuracy**: Achieved **97.5% accuracy** on the testing dataset.  
- **Scalability**: Designed to handle large datasets and real-time applications efficiently.  
- **Robustness**: Enhanced dataset diversity to improve model generalization to unseen faces.  

## Tech Stack  
- **Face Detection**: MTCNN  
- **Face Recognition**: FaceNet  
- **Classification**: SVM  
- **Programming Language**: Python  
- **Libraries Used**: TensorFlow, NumPy, OpenCV, Scikit-learn  

## Applications  
- Secure authentication systems.  
- Attendance management in educational or corporate environments.  
- Real-time surveillance systems.  

This project serves as a comprehensive demonstration of face detection, embedding generation, and classification, combining cutting-edge machine learning techniques for real-world applications.  
