# Neural Eyes - Assistive Vision System for the Visually Impaired

## Overview
Neural Eyes is a **computer vision-based assistive tool** designed to help visually impaired individuals navigate their surroundings safely. The system detects **both static and moving objects in real-time** using a combination of **Convolutional Neural Networks (CNN) and Support Vector Machines (SVM)**, providing **speech output** to describe detected objects.

## Key Features
- **Real-time Object Detection**: Uses **CNN for feature extraction** and **SVM for classification**.
- **Moving Object Tracking**: Detects and tracks objects in motion.
- **Text-to-Speech Conversion**: Converts detected objects into verbal descriptions.
- **YOLO-Based Object Recognition**: Accurately classifies and localizes objects.
- **Portable Solution**: Runs on **Raspberry Pi** for real-time deployment.
- **Optimized Processing**: Uses **OpenCV and TensorFlow** for efficient performance.

## Project Components
- 📄 **[Neural Eyes Detailed Report](Neural Eyes detailed Report.pdf)** – Comprehensive documentation covering methodology, results, and conclusions.
- 📄 **[Neural Eyes Paper](NEURAL EYES)** – Research paper outlining the technical details and implementation.
- 📂 **Dataset & Model** – Trained using the **COCO128 dataset**.
- 🖼️ **Visualizations** – Graphs and charts explaining model performance.

## Methodology
1. **Data Collection**: Images sourced from the COCO128 dataset.
2. **Preprocessing**: Data augmentation and annotation for training.
3. **Feature Extraction**: 
   - **CNN extracts relevant object features**.
   - **SVM classifies detected objects** based on extracted features.
4. **Moving Object Detection & Tracking**:
   - **Background subtraction** and **optical flow techniques** detect motion.
   - **YOLO and OpenCV track moving objects** in real-time.
5. **Object Detection**:
   - Uses a **combination of CNN and SVM** to improve accuracy.
6. **Speech Output**:
   - Converts detected object names into **audio feedback** for visually impaired users.

## Results
- Achieved **over 90% accuracy** in object classification.
- Successfully detects **both static and moving objects** in real-time.
- **SVM improves classification performance**, especially for similar objects.
- Optimized to run on **low-power devices like Raspberry Pi**.

## Future Improvements
- **Enhance moving object detection** in **low-light conditions**.
- **Improve speech synthesis** for more natural and expressive output.
- **Integrate gesture-based controls** for better user interaction.
