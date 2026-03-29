# fake-news-detection-ml
Fake News Detection using Machine Learning

## 📂 Dataset
This project uses multiple datasets:

- Initial dataset (collected from publicly available GitHub sources)
  
- Fake and Real News Dataset (Kaggle):  https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset
  
- Custom dataset created for real-world testing,consisting of short and medium-length statements with balanced real and fake news samples to improve model generalization.

# 📰 Fake News Detection using Machine Learning

## 📌 Project Overview

This project focuses on detecting fake news using machine learning techniques. The goal is to classify news articles as **Real** or **Fake** based on their textual content.

Multiple models were implemented and compared to understand the impact of datasets and generalization in real-world scenarios.

---

## 🚀 Features

* Text preprocessing and cleaning
* TF-IDF vectorization
* Multiple ML models implementation
* Comparative analysis of models
* Real-world testing with custom dataset

---

## 🧠 Models Used

* Logistic Regression
* Naive Bayes
* Support Vector Machine (SVM)

---

## 📊 Results

| Model               | Dataset    | Accuracy | Observation         |
| ------------------- | ---------- | -------- | ------------------- |
| Logistic Regression | Initial    | 60%      | Poor, biased        |
| Naive Bayes         | Improved   | 65%      | Slight better       |
| SVM                 | Structured | 99%      | Overfitting         |
| Naive Bayes         | Custom     | 83%      | Best generalization |

---

## 📂 Dataset

* Initial small dataset
* Structured dataset (Kaggle)
* Custom dataset created for better real-world testing

---

## ⚙️ Tech Stack

* Python
* Scikit-learn
* Pandas
* Google Colab

---

## ▶️ How to Run

1. Clone the repository
2. Install required libraries
3. Run the notebook in Google Colab or Jupyter

---

## 📈 Key Learnings

* High accuracy does not always mean good performance
* Dataset quality plays a crucial role
* Generalization is more important than overfitting

---

## 📄 Research Paper

A detailed research paper is included in this repository explaining methodology, results, and analysis.

---

## 🙌 Acknowledgment

* Kaggle datasets
* Scikit-learn documentation
* Online ML resources

---

## 👩‍💻 Author

**Himanshi Jain**

---

⭐ If you like this project, feel free to star the repository!
