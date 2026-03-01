Project Overview - The Fake Real News ML Project is a machine learning application built in Python that predicts whether a news article is real or fake. The model is trained on labeled news datasets and makes predictions using pre-trained machine learning models. This project also includes a Python interface (app.py) to interact with the model.

Project Objective - The goal of this project is to build a reliable classification system that can help identify misinformation and reduce the spread of fake news using data-driven approaches.

Repository Structure - 
├── Athenura final.ipynb       # Notebook with project development / experiments
├── Fake.csv                   # Dataset of fake news entries
├── True.csv                   # Dataset of real news entries
├── Practice.ipynb             # Another notebook file (practice or analysis)
├── app.py                     # Main Python application for predictions
├── fake_news_model.pkl        # Saved ML model for detecting fake news
├── svm_model.pkl              # Support Vector Machine model
├── w2v_model.pkl              # Word2Vec based model
├── word2vec_model.pkl         # Another Word2Vec / embedding model
├── requirements.txt           # Python packages required for project
└── README.md                  # Project description (this file)

Technologies & Tools- Python
                      Scikit-learn
                      Pandas & NumPy
                      Word2Vec (Text Embeddings)
                      Support Vector Machine (SVM)
                      Jupyter Notebook

Dataset - The model is trained using two labeled datasets:
          True.csv – Contains real news articles
          Fake.csv – Contains fake news articles


Methodology - Data Cleaning & Text Preprocessing
              Tokenization and Feature Extraction
              Word Embedding using Word2Vec
              Model Training using SVM
              Model Evaluation & Saving (.pkl files)
              Deployment through a Python application (app.py)

How to Run the Project - pip install -r requirements.txt
                         python app.py 

Highlights -  Implementation of NLP techniques for text classification
              Use of machine learning algorithms for supervised learning
              Multiple trained models saved for reuse

This project demonstrates strong understanding of Machine Learning, NLP, and model deployment in Python and can be extended further into a web-based application using frameworks like Flask or Streamlit.
<img width="1914" height="855" alt="image" src="https://github.com/user-attachments/assets/a43a5441-d629-48f0-b818-42e217e26872" />
<img width="1576" height="654" alt="image" src="https://github.com/user-attachments/assets/d81b7988-54f6-4254-bbce-e1b182d6cbe7" />

              Practical real-world application of ML in misinformation detection

