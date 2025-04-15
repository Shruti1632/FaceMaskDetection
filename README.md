# Real-Time Face Mask Detection System 😷
This project introduces a real-time Facial Mask Recognition system leveraging Convolutional Neural Networks (CNNs) to detect and categorize individuals based on their mask-wearing # 🛡️ Real-Time Face Mask Detection System

This project implements a **real-time facial mask recognition system** utilizing **Deep Learning** techniques to identify individuals based on their mask-wearing status. By leveraging **Convolutional Neural Networks (CNNs)**, the system classifies faces into categories: "with mask," "without mask," and "improperly worn mask." This solution is designed to aid in enforcing health protocols and ensuring public safety in various environments.

---

## 📌 Project Overview

The Face Mask Detection System is engineered to:

- **Detect faces** in real-time using computer vision.
- **Classify mask-wearing status** into three categories: with mask, without mask, and improperly worn mask.
- **Operate efficiently** on systems equipped with **GPU acceleration** to handle real-time video streams.

This system is particularly beneficial in settings such as:

- Airports
- Public transportation
- Healthcare facilities
- Educational institutions
- Retail environments

---

## 🧠 Technologies & Tools

- **Programming Language**: Python
- **Deep Learning Frameworks**: TensorFlow, Keras
- **Computer Vision Library**: OpenCV
- **Machine Learning Algorithms**: Convolutional Neural Networks (CNN), Support Vector Machine (SVM)
- **Hardware Acceleration**: GPU (for training and inference)
- **Model Evaluation Metrics**: Accuracy, Precision, Recall, F1 Score

---

## 🚀 Getting Started

To set up and run the Face Mask Detection System locally:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Shruti1632/FaceMaskDetection.git
   cd FaceMaskDetection
   ```

2. **Install the required dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Train the model** (if not pre-trained):
   ```bash
   python TrainMaskDetector.py
   ```

4. **Run the detection system**:
   ```bash
   python DetectMaskVideo.py
   ```

   This command will initiate the webcam feed and display real-time mask detection results.

---

## 📊 Model Performance

The system's performance is evaluated using the following metrics:

- **Accuracy**: Proportion of total correct predictions.
- **Precision**: Proportion of positive predictions that are actually correct.
- **Recall**: Proportion of actual positives correctly identified.
- **F1 Score**: Harmonic mean of Precision and Recall.

These metrics ensure the model's reliability in diverse real-world conditions.

---

## 📁 Repository Structure

- `TrainMaskDetector.py`: Script to train the mask detection model.
- `DetectMaskVideo.py`: Script to run real-time mask detection using webcam input.
- `requirements.txt`: List of Python dependencies.
- `LICENSE`: MIT License file.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙋‍♀️ Author

**Shruti Pawar**

- [GitHub](https://github.com/Shruti1632)
- [LinkedIn](https://www.linkedin.com/in/shruti-pawar-0a9031235/)

---

Feel free to reach out for collaborations, suggestions, or contributions to enhance this project further.
