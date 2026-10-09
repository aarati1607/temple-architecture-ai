# 🏛️ South Indian Temple Architecture Classifier

An interactive Deep Learning web application designed to identify and analyze South Indian temple architecture. Developed as part of an Indian Knowledge System initiative, this computer vision project utilizes Convolutional Neural Networks to classify historical monuments and provide explainable AI insights.

## ✨ Features
* **Real-Time Classification:** Upload temple photographs for immediate architectural classification.
* **Explainable AI (Grad-CAM):** Generates live heatmaps to visualize the specific structural features (e.g., Vimana, Gopurams, carved pillars) that influenced the model's prediction.
* **Confidence Metrics:** Displays Softmax probabilities and top-3 alternate predictions.
* **Heritage Metadata:** Outputs contextual architectural styles and regional mapping.
* **Downloadable Reports:** Export prediction data and metadata as JSON files.

## 🛠️ Tech Stack
* **Frameworks:** PyTorch, torchvision
* **Architecture:** MobileNetV3-Small (Transfer Learning)
* **Web Interface:** Streamlit
* **Computer Vision:** OpenCV, pytorch-grad-cam
* **Data Processing:** Pandas, NumPy, Scikit-learn

## 🚀 Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YourUsername/temple-architecture-ai.git](https://github.com/YourUsername/temple-architecture-ai.git)
   cd temple-architecture-ai
