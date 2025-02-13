# Public Opinion Extraction

## 📌 Project Overview
This project focuses on extracting public opinions on smart cities using **Latent Dirichlet Allocation (LDA)** for topic modelling. We utilize Twitter data as a primary dataset, collected using **Twint**, to analyze discussions and identify prevalent themes in smart city discourse.

## 👨‍💻 Tech Stack & Libraries
- **Programming Language**: Python
- **Libraries Used**:
  - `numpy`, `pandas` (Data handling & manipulation)
  - `twint` (Data scraping from Twitter)
  - `nltk`, `sastrawi` (Text preprocessing & NLP tasks)
  - `sklearn` (Vectorization & Model Evaluation)

## 📊 Dataset
- **Source**: Twitter (Scraped using `twint`)
- **Keywords**: "smart city"
- **Language**: Indonesian (`id`)
- **Limit**: 500 tweets
- **Storage Format**: CSV (`dataset.csv`)

## 🔧 Project Workflow
1. **Data Collection**: Scraping tweets with `twint` based on defined keywords and filters.
2. **Preprocessing**:
   - Cleaning tweets (removing punctuation, special characters, etc.).
   - Stopwords removal & slang words normalization (`kamus_alay.csv`, `slang_words.txt`).
   - Tokenization, stemming, and lemmatization (`nltk`, `sastrawi`).
3. **Feature Engineering**:
   - TF-IDF Vectorization (`sklearn`).
   - LDA Topic Modeling to extract meaningful topics.

## 📂 Project Structure
```
📁 Public-Opinion-Extraction
├── 🏋️‍♂️ LDA - Smart City.ipynb        # Exploratory Data Analysis & LDA modeling
├── 📊 dataset.csv                   # Raw dataset scraped from Twitter
├── 🎯 data_clean.xlsx                # Cleaned dataset
├── 🛠 data_preprocess.xlsx           # Preprocessed dataset
├── 🤖 kamus_alay.csv                 # Slang words mapping
├── 📜 slang_words.txt                # Slang words dictionary
```

## 🚀 Getting Started
### 1️⃣ Installation
Clone the repository and install dependencies:
```bash
# Clone the repository
git clone https://github.com/mrzlsyf/Public-Opinion-Extraction.git
cd Public-Opinion-Extraction
```
### 2️⃣ Run the Project
Ensure you have the dataset (`dataset.csv`) available, open the Jupyter Notebook:
```sh
jupyter notebook
```
Load and run the `LDA - Smart City.ipynb` file.

## 📈 Results & Findings
- Extracted **n** key topics from the dataset.
- Identified main concerns and public sentiment towards smart city initiatives.
- Provided insights for urban policymakers and smart city developers.

## 📌 Future Improvements
- Increase dataset size for better generalization.
- Implement sentiment analysis alongside topic modelling.
- Develop a dashboard for real-time monitoring of public opinion.

## 🤝 Contributing 
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch (`feature-branch`).
3. Commit your changes and push to your fork.
4. Open a pull request with a clear description of your modifications.

✨ Feel free to fork, contribute, or reach out! 💫
---
> _"Understanding public opinion is the key to building smarter cities."_
