
# Fake News Detection Web App

This is a Fake News Detection application built using **Streamlit** and various machine learning models. The app allows users to input a news article and get predictions on whether the news is real or fake based on several models, including **Logistic Regression**, **Decision Tree**, **Gradient Boosting**, and **Random Forest Classifier**.

## Overview

The goal of this project is to classify news articles as **Fake News** or **Not A Fake News** based on the content of the article. Multiple machine learning models are trained on a dataset consisting of fake and real news articles and the app showcases predictions from each model.

## Features
- **Multiple Model Predictions:** Displays predictions from **Logistic Regression**, **Decision Tree**, **Gradient Boosting**, and **Random Forest**.
- **Text Preprocessing:** The input news article undergoes basic text preprocessing like removing special characters, URLs, etc., to improve model accuracy.
- **Interactive Web Interface:** Built with **Streamlit**, the app allows users to input news text and see predictions in real-time.

## Installation

To run the Fake News Detection app locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/fake-news-detection.git
   cd fake-news-detection
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Ensure you have the trained models (`lr_model.pkl`, `dt_model.pkl`, `gbc_model.pkl`, `rfc_model.pkl`) and `vectorizer.pkl` stored in the project directory.

4. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

## Usage

- After running the Streamlit app, a browser window will open.
- Enter a news article in the provided text box and click **Submit**.
- The app will display predictions from all models on whether the news is **Fake News** or **Not A Fake News**.

## Models Used

The app uses the following machine learning models:
1. **Logistic Regression (LR)**
2. **Decision Tree Classifier (DT)**
3. **Gradient Boosting Classifier (GBC)**
4. **Random Forest Classifier (RFC)**

The models are trained on the Kaggle **Fake News Detection** dataset.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to the Kaggle dataset **Fake News Detection** for providing the data used in training the models.
- Thanks to the **Streamlit** team for the wonderful framework that made building this app easy.

```

---

### **Summary of the README:**
- Describes the project, how to run it, and the dependencies.
- Gives a step-by-step guide to get the app working.
- Lists the models used and acknowledges sources.

This README and the Streamlit code will help you set up the Fake News Detection app for use locally and in GitHub. Let me know if you need further customizations!
