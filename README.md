
---

# **Drug Recommendation System Based on Sentiment Analysis of Drug Reviews Using Machine Learning**

### **Presented by:**
- A. Amulya (20J21A0501)
- A. Sai Kiran (20J21A0503)
- K. Chandra Siddartha (20J21A0531)
- K. Sai Manu (20J21A0537)

### **Guided by:**
- Dr. T. Prabhakaran, Professor & HOD, Department of CSE

---

## **Overview**
This repository contains the code and resources for a **Drug Recommendation System** that leverages **Sentiment Analysis** on drug reviews using **Machine Learning** algorithms. The aim is to build a model that processes patient reviews to provide personalized drug recommendations. By analyzing patient sentiment, this system helps optimize healthcare decision-making.

---

## **Table of Contents**
1. [Abstract](#abstract)
2. [Proposed System](#proposed-system)
3. [Technologies Used](#technologies-used)
4. [System Architecture](#system-architecture)
5. [Algorithms](#algorithms)
6. [Evaluation Metrics](#evaluation-metrics)
7. [Results](#results)
8. [How to Run the Project](#how-to-run-the-project)
9. [Conclusion](#conclusion)

---

## **Abstract**
The **Drug Recommendation System** uses machine learning techniques to analyze sentiment from drug reviews, providing insights that help recommend medications to patients based on their sentiments. It uses models such as **Logistic Regression**, **Collaborative Filtering**, and **Support Vector Classifiers** to predict positive, neutral, or negative reviews, assisting in optimizing personalized drug recommendations.

### **Objective:**
To leverage sentiment analysis and machine learning to provide reliable drug recommendations based on user reviews, enhancing decision-making in healthcare.

---

## **Proposed System**
The system:
- Analyzes drug reviews to predict sentiments (positive, neutral, or negative).
- Recommends drugs based on sentiment analysis using **Collaborative Filtering** and **Content-Based Filtering** techniques.
- Uses metrics like precision, recall, F1-score, and accuracy to evaluate the model’s performance.

### **Advantages:**
- **Personalized Recommendations**: Tailored drug suggestions based on patient reviews.
- **Sentiment-Driven**: Enhances recommendations by incorporating user sentiment about drugs.
- **User Feedback Integration**: Incorporates customer feedback, leading to more accurate recommendations.

---

## **Technologies Used**
- **Languages**: Python
- **Libraries**: 
  - Natural Language Processing: **NLTK, Word2Vec**
  - Machine Learning: **Scikit-learn, TensorFlow**
  - Data Handling: **Pandas, NumPy**
  - Evaluation: **Precision, Recall, F1-score, AUC**
  
- **Tools**: 
  - Jupyter Notebook
  - Git for version control

---

## **System Architecture**
The architecture includes:
1. **Data Preprocessing**: Cleaning drug reviews (removing HTML tags, stopwords, etc.).
2. **Sentiment Analysis**: Applying NLP techniques like Bag of Words (BoW), TF-IDF, and Word2Vec to extract sentiments.
3. **Model Building**: Using classifiers like Naive Bayes, Logistic Regression, and Support Vector Classifiers (SVC) for sentiment classification.
4. **Recommendation**: Recommending drugs based on collaborative filtering and content-based filtering.

---

## **Algorithms**
- **Logistic Regression**: Classifies drug reviews into positive, neutral, or negative sentiments. If classification accuracy is above 80%, the dataset is considered valid.
- **Collaborative Filtering**:
  - **User-based Filtering**: Recommends drugs similar users have reviewed positively.
  - **Item-based Filtering**: Suggests drugs similar to those previously reviewed by the user.
- **Content-Based Filtering**: Recommends drugs based on their features (class, side effects, etc.) and the user’s history.
- **Linear Support Vector Classifier (SVC)**: Classifies reviews using a hyperplane for binary classification.
- **Decision Trees**: Hierarchically splits data based on features for classification.

---

## **Evaluation Metrics**
The system's performance is measured using:
- **Accuracy**: Overall correctness of the model.
- **Precision**: Correct positive predictions out of total positive predictions.
- **Recall**: Correctly predicted positives out of all actual positives.
- **F1-score**: Harmonic mean of precision and recall.
- **AUC (Area Under the Curve)**: Measures the model’s ability to distinguish between classes.

---

## **Results**
The **Linear SVC** model using **TF-IDF** achieved the highest accuracy of **93%**, while the **Decision Tree** model using **Word2Vec** performed at **78%**. The model’s effectiveness was evaluated based on how accurately it predicted sentiment and provided useful drug recommendations.

---

## **How to Run the Project**
1. **Clone the repository**:
   ```bash
   git clone https://github.com/Chandra-Siddartha/DRUG-RECOMMENDATION-SYSTEM-BASED-ON-SENTIMENT-ANALYSIS-OF-DRUG-REVIEWS-USING-MACHINE-LEARNING.git
   ```
2. **Navigate to the directory**:
   ```bash
   cd drug-recommendation-system
   ```
3. **Install required libraries**:
   ```bash
   pip install -r requirements.txt
   ```
4. **Run the Jupyter Notebook**:
   ```bash
   jupyter notebook
   ```
5. **Execute the project** and analyze results in the notebook interface.

---

## **Conclusion**
The system successfully demonstrates the potential of using sentiment analysis for drug recommendations. The **Linear SVC** model outperforms others, proving its robustness for sentiment classification. Future work will focus on improving the system by integrating more advanced machine learning techniques and exploring oversampling methods to balance the dataset.

---

Let me know if you need any modifications or additional details!
