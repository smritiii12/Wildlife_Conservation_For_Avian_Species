# 🐦 Wildlife Conservation for Avian Species using Deep Learning

# 📖 Introduction

Wildlife conservation has become increasingly important due to the rapid decline in endangered avian species caused by habitat destruction, climate change, environmental imbalance, and human activities. Traditional wildlife monitoring methods are often time-consuming, expensive, and highly dependent on manual observation.

Recent advancements in Artificial Intelligence and Deep Learning provide opportunities to automate species identification and improve wildlife monitoring systems. Image classification techniques using Convolutional Neural Networks (CNNs) can help researchers identify bird species more efficiently and accurately from camera trap or wildlife image datasets.

This project presents a Deep Learning based avian species classification system using CNN and MobileNetV2 Transfer Learning techniques for identifying endangered bird species.

---

# ❗ Problem Statement

Manual identification and monitoring of avian species require significant human effort and expertise, making wildlife conservation processes slow and inefficient. Existing monitoring systems often struggle with classification accuracy, scalability, and real-time analysis.

The objective of this project is to develop an intelligent and automated image classification system capable of accurately recognizing avian species using Deep Learning techniques.

---

# 🔍 Research Gap

Several traditional machine learning approaches have been used for wildlife species classification; however, many of them suffer from:

- Lower classification accuracy
- Limited scalability
- Poor feature extraction capability
- High dependency on handcrafted features
- Difficulty handling large image datasets

This project addresses these limitations by applying Transfer Learning using MobileNetV2, which improves feature extraction and significantly enhances classification performance.

---

# 🎯 Objectives

- Develop an automated avian species classification system
- Apply Deep Learning techniques for wildlife conservation
- Improve image classification accuracy using Transfer Learning
- Reduce dependency on manual species identification
- Support intelligent wildlife monitoring systems
- Build a scalable AI-based conservation solution

---

# 🦜 Species Included

- Great Indian Bustard
- Hornbill
- Heron
- Vulture
- Albatross

---

# 🛠️ Technologies & Tools Used

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| TensorFlow / Keras | Deep Learning framework |
| OpenCV | Image preprocessing |
| Scikit-learn | Evaluation metrics |
| Google Colab | Training environment |
| CNN | Image classification |
| MobileNetV2 | Transfer Learning |

---

# ⚙️ Methodology

## 1. Data Collection
The dataset consists of avian species images collected from publicly available wildlife datasets.

## 2. Image Preprocessing
Preprocessing techniques included:
- Image resizing
- Grayscale conversion
- Normalization
- Data augmentation

## 3. Model Development

### Basic CNN
A baseline CNN architecture was implemented for initial classification.

### Optimized CNN
Additional convolution layers, dropout, and normalization techniques were applied for performance improvement.

### MobileNetV2 Transfer Learning
Transfer Learning with MobileNetV2 was used to achieve higher accuracy and better feature extraction.

---

# 📊 Model Performance

| Model | Accuracy |
|---|---|
| Basic CNN | 54.66% |
| Optimized CNN | 55.75% |
| MobileNetV2 | 93.82% |

---

# 🚀 Key Features

✅ Deep Learning based avian species classification  
✅ Transfer Learning implementation  
✅ Wildlife conservation support system  
✅ Automated image classification  
✅ High accuracy prediction model  
✅ Real-world AI application  

---

# 📂 Repository Structure

```text
Wildlife_Conservation_For_Avian_Species/
│
├── notebooks/
├── reports/
├── presentation/
├── assets/
├── dataset/
├── models/
├── README.md
└── requirements.txt
```

---

# ▶️ How to Run

```bash
git clone https://github.com/smritiii12/Wildlife_Conservation_For_Avian_Species.git
```

```bash
pip install -r requirements.txt
```

```bash
jupyter notebook
```

Open:

```text
avian_species_classification.ipynb
```

---

# 📚 Documentation Included

- Research Paper
- Final Project Report
- Project Presentation
- Model Evaluation Results

---

# 🌱 Future Scope

- Real-time wildlife monitoring
- Flask/Streamlit deployment
- Additional endangered species support
- Camera trap integration
- Cloud-based monitoring systems

---

# 👩‍💻 Author

Smriti Kumari

---

# 📜 License

This project is intended for academic and research purposes.
