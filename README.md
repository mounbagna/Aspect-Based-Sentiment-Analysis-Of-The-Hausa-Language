# Hausa Aspect-Based Sentiment Analysis (Hausa-ABSA)

This repository presents a research project on **Aspect-Based Sentiment Analysis (ABSA)** for the **Hausa language**. The goal is to detect sentiments related to specific aspects or topics within text data written in Hausa. This work contributes to natural language processing (NLP) research in underrepresented African languages and addresses the unique linguistic challenges of Hausa.

## 🔍 What is ABSA?

Aspect-Based Sentiment Analysis goes beyond traditional sentiment analysis by:
- Identifying **aspects** or **topics** within the text.
- Determining the **sentiment polarity** (positive, neutral, negative) associated with each aspect.

## 📁 Project Structure

├── ABSA.ipynb # Main notebook containing data preprocessing, model training, testing, and evaluation

├── hesac_dataset/ # Hausa ABSA dataset (text and labeled data)

│ └── hesac.xlsx

├── stopwords/ # Stopword list for the Hausa language

│ └── stopwords.txt

└── README.md # Project documentation


## 📦 Dataset

- The dataset is located in the `hesac_dataset/` folder.
- It contains English comments and Hausa sentences annotated for **aspects** and their corresponding **sentiment polarities**.
- Preprocessing includes tokenization, removal of stopwords (see `stopwords/stopwords.txt`), and formatting for model input.

## 🧠 Models

This project uses two approaches for ABSA:

### 1. BiLSTM (Bidirectional LSTM)
- A sequence-based deep learning model.
- Trained from scratch using the Hausa dataset.
- Handles both aspect extraction and sentiment classification.

### 2. HauBERT (Hausa BERT)
- A pre-trained BERT model fine-tuned for token classification and sentiment classification.
- Based on multilingual BERT or domain-adapted Hausa models.

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/mounbagna/ABSA.git
   cd ABSA
