# 2C-E-commerce-product-reviews
# Sentiment Analysis of Code-Mixed Telugu–English E-commerce Product Reviews

## 📌 Project Overview

This project focuses on performing sentiment analysis on code-mixed Telugu–English e-commerce product reviews using Deep Learning techniques.

The system classifies customer reviews into three sentiment categories:
- **Positive**
- **Negative**
- **Mixed**

Since Telugu words are written using English characters and combined with English words, traditional English sentiment analysis models may struggle to understand the reviews.

We implement and compare three Recurrent Neural Network architectures: SimpleRNN, LSTM, and GRU.

## 🎯 Objectives

- Perform sentiment analysis on Telugu–English code-mixed reviews.
- Preprocess and tokenize textual data.
- Implement SimpleRNN, LSTM, and GRU models.
- Compare model performance using evaluation metrics.
- Analyze model predictions using confusion matrices and classification reports.

## 📂 Dataset Details

| Attribute | Description |
|---|---|
| Dataset | Code-Mixed Product Reviews |
| Total Reviews | 2,000 |
| Languages | Romanised Telugu + English |
| Classes | Positive, Negative, Mixed |
| Categories | Electronics, Fashion, Home Appliances |
| Training Data | 1,600 |
| Testing Data | 400 |

**Note:** The dataset contains synthetic example reviews, not real customer reviews.

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook / Google Colab

## ⚙️ Project Workflow

1. Dataset loading
2. Text preprocessing
3. Tokenization
4. Sequence padding
5. Train-test splitting
6. Model building
7. Model training
8. Model evaluation
9. Performance comparison
10. Sentiment prediction

## 🧠 Models Implemented

### 1. SimpleRNN
A basic recurrent neural network used for sequential text classification.

### 2. LSTM
Long Short-Term Memory networks use gates to capture long-term dependencies.

### 3. GRU
Gated Recurrent Units provide a simplified gated architecture for sequence learning.

## 📊 Model Performance

| Model | Test Accuracy | Macro F1 |
|---|---:|---:|
| SimpleRNN | 88.75% | 0.89 |
| LSTM | 33.50% | 0.17 |
| GRU | 33.25% | 0.17 |

**Best Performing Model:** SimpleRNN

SimpleRNN achieved the highest test accuracy and macro F1-score in our experiments.

## 📈 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- Training and Validation Accuracy
- Training and Validation Loss

## 🚀 How to Run the Project

**Step 1: Clone the repository**

```bash
git clone https://github.com/your-username/your-repository-name.git
```

**Step 2: Open the project folder**

```bash
cd your-repository-name
```

**Step 3: Install dependencies**

```bash
pip install numpy pandas matplotlib scikit-learn tensorflow
```

**Step 4: Open Jupyter Notebook**

```bash
jupyter notebook
```

**Step 5:** Open the project notebook and run all cells.

## 📁 Project Structure

```text
Sentiment-Analysis/
│
├── DL_T10_2C_2000_code_mixed_product_reviews.csv
├── DL_T10_2C.ipynb
├── README.md
└── report.pdf
```

*Update the filenames according to the files uploaded to your repository.*

## ⚠️ Limitations

- The dataset contains synthetic reviews.
- LSTM and GRU did not achieve satisfactory performance.
- IMDB transfer learning was not implemented.
- CPU inference time for 10,000 reviews was not measured.
- Sequence-length comparison experiments were not completed.

## 🔮 Future Enhancements

- Use real-world Telugu–English customer reviews.
- Improve model performance through hyperparameter tuning.
- Implement transfer learning using pretrained models.
- Experiment with Bidirectional LSTM and GRU.
- Improve text preprocessing and spelling normalization.
- Optimize inference speed.

