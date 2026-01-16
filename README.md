# Violence Detection Using Deep Learning

## Project Pitch
This project demonstrates how deep learning–based computer vision models can support automated violence detection systems, helping reduce human exposure to harmful visual content and enabling faster, data-driven decision-making in content moderation and public safety applications.

---

## Project Overview
Violent content detection is a critical challenge in large-scale digital platforms and public safety systems. Manual monitoring is costly, slow, and psychologically harmful for human reviewers.

In this project, I developed and evaluated deep learning models to automatically classify images into:
- **Violent**
- **Non-Violent**

The project explores both **image classification** and **object detection** approaches to understand their effectiveness, limitations, and practical trade-offs.

---

## Why This Problem Matters
- Exposure to violent content poses psychological risks to human moderators
- Automated detection can improve response time in safety-critical systems
- Scalable AI solutions are essential for national-level digital safety platforms

This work aligns with applications in:
- Content moderation
- Smart surveillance
- Public safety analytics
- AI ethics and responsible deployment

---

## Dataset
- Labeled images representing violent and non-violent human activities
- Balanced and preprocessed for supervised learning

**Preprocessing steps included:**
- Image resizing
- Normalization
- Data augmentation to improve generalization

> **Note:** The dataset is not included due to size and licensing constraints.

---

## Methodology
The project followed an end-to-end deep learning workflow:

1. Image preprocessing and augmentation
2. Feature extraction using Convolutional Neural Networks (CNN)
3. Model training and validation
4. Performance evaluation using appropriate metrics
5. Comparative experimentation with object detection (YOLOv5)

---

## Models Used
### CNN-Based Image Classification
- Used to learn spatial patterns associated with violent actions
- Provided a strong baseline for classification performance

### YOLOv5 (Object Detection – Experimental)
- Explored for detecting violent actions within complex scenes
- Allowed spatial localization rather than image-level prediction

**Why YOLOv5?**
YOLOv5 offers real-time detection capability and is suitable for deployment in large-scale monitoring systems where speed and localization matter.

---

## Model Evaluation
Performance was evaluated using:
- Accuracy
- Training and validation loss

The results demonstrated:
- Effective separation between violent and non-violent classes
- Stable convergence during training
- Promising generalization on unseen data

---

## Key Insights
- CNN models effectively capture visual patterns linked to violent behavior
- Object detection approaches introduce additional complexity but enable localization
- Model performance depends heavily on data quality and class balance

---

## Limitations
- Image-based classification does not capture temporal context
- False negatives remain a critical risk in safety-related applications
- The model is trained on static images, not video sequences

---

## Future Improvements
- Extend the approach to video-based violence detection (3D CNNs / LSTM)
- Incorporate temporal features for improved accuracy
- Apply explainability techniques to support ethical AI deployment
- Optimize models for real-time inference

---

## Tools & Technologies
- Python
- TensorFlow / Keras
- YOLOv5
- OpenCV
- Jupyter Notebook
- Google Colab

---

## Project Structure
violence-detection-deep-learning/
│
├── yolo5Fin.ipynb # Final training and evaluation notebook
├── docs/
│ └── Deep_Learning_Violence_Detection.pdf
├── README.md


---

## Author
**Lama Turki**  
Data Scientist | Analytics & Forecasting  
Machine Learning • Computer Vision • AI Ethics
