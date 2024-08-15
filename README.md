
# ❤️ Heart Disease Prediction Model

![Heart](https://img.shields.io/badge/Heart%20Disease-Prediction%20Model-red)
![Python](https://img.shields.io/badge/Python-3.x-blue)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📝 Overview

This repository contains a **machine learning model** designed to predict the presence of heart disease based on a variety of clinical features. This tool aims to assist healthcare professionals in assessing the likelihood of heart disease in patients using a reliable, data-driven approach.

## 📊 Dataset

The dataset consists of several key clinical indicators:

| Feature                              | Description                                                                 |
|--------------------------------------|-----------------------------------------------------------------------------|
| **Age**                              | Patient's age                                                               |
| **Sex**                              | Gender (1 = male, 0 = female)                                               |
| **Chest Pain Type**                  | 0 = Typical angina, 1 = Atypical angina, 2 = Non-anginal pain, 3 = Asymptomatic |
| **Resting Blood Pressure**           | Resting blood pressure (mm Hg)                                              |
| **Serum Cholestoral**                | Serum cholesterol level (mg/dl)                                             |
| **Fasting Blood Sugar**              | > 120 mg/dl (1 = true, 0 = false)                                           |
| **Resting Electrocardiographic Results** | 0 = Normal, 1 = ST-T wave abnormality, 2 = Left ventricular hypertrophy     |
| **Maximum Heart Rate Achieved**      | Maximum heart rate achieved during exercise                                 |
| **Exercise Induced Angina**          | Exercise-induced angina (1 = yes, 0 = no)                                   |
| **Oldpeak**                          | ST depression induced by exercise relative to rest                          |
| **Slope of the Peak Exercise ST Segment** | 0 = Upsloping, 1 = Flat, 2 = Downsloping                                    |
| **Number of Major Vessels Colored by Flourosopy** | Number of major vessels (0-3) colored by fluoroscopy                        |
| **Thalassemia (Thal)**               | 0 = Normal, 1 = Fixed defect, 2 = Reversible defect                         |

> **Note:** Sensitive information such as patient names and social security numbers has been replaced with dummy values to protect privacy.

## ⚙️ Model

The model is built using **HeartAI**, and it predicts the likelihood of heart disease based on the provided features. It was trained on a dataset of **512**.

## 🚀 Installation

Follow these steps to set up and run the project locally:

1. **Clone this repository:**
   ```bash
   git clone https://github.com/0xWEBMILK/HeartAI.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd HeartAI
   ```
3. **Install the required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

## 📈 Results

The model achieved the following performance metrics on the test set:

- **Accuracy**: ***0.9805068226120858***
- **Precision**: ***0.9735849056603774***
- **Recall**: ***0.9885057471264368***
- **F1 Score**: ***0.9809885931558935***

> For detailed evaluation metrics, see the [evaluation report](docs/evaluation_report.md).

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. **Fork the repository**
2. **Create a new branch** (`git checkout -b feature-branch`)
3. **Commit your changes** (`git commit -m 'Add new feature'`)
4. **Push to the branch** (`git push origin feature-branch`)
5. **Open a pull request**

Please ensure your code adheres to the project's coding standards and includes appropriate tests.

## 📜 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for more details.

## 🙏 Acknowledgments

- **Dataset**: Provided by [kaggle](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset).
- **Community**: Thanks to the open-source community for tools and resources.

---

*Made with ❤️ by [0xWEBMILK](https://github.com/0xWEBMILK/)*
