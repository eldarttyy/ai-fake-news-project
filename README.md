# ai-fake-news-project

# Fake News Detection using AI Models

# Fake News Detection: Comparing LLMs and Traditional Machine Learning

## 👥 Group Members
- Eldar Erik Uulu
- [Add other members if applicable]

## 🧠 Project Overview
This project investigates the effectiveness of both Large Language Models (LLMs) and traditional machine learning algorithms in classifying fake news. We implemented and compared:
- A fine-tuned **DistilBERT** model
- A **Logistic Regression** classifier using TF-IDF features
- A **Multinomial Naive Bayes** model

Our goal was to analyze how different models perform on fake news datasets and to identify which provides the most reliable results in real-world scenarios.

---

## 🔍 Models Used

| Model                   | Description                                                      | Libraries Used                         |
|------------------------|------------------------------------------------------------------|----------------------------------------|
| **DistilBERT**         | A smaller, faster version of BERT fine-tuned on fake news data.  | `transformers`, `torch`, `sklearn`     |
| **Logistic Regression**| Baseline traditional model using TF-IDF vectorized inputs.       | `scikit-learn`                         |
| **Naive Bayes**        | Simple probabilistic model with strong performance on text data. | `scikit-learn`                         |

## ✅ What I Learned

- Pre-trained LLMs like DistilBERT significantly outperform older methods in both accuracy and robustness.
- Traditional models are still valuable for fast prototyping and small datasets.
- Evaluation metrics must be complemented with human evaluation (blind testing) for deeper insights.

---

## 💡 Suggestions for Improvement

1. **Include more models**: e.g., RoBERTa, GPT-2 for more nuanced comparison.
2. **Larger dataset**: Use real-time scraping or NewsGuard-rated data for broader evaluation.
3. **Explainability tools**: Integrate SHAP or LIME to interpret model decisions.
4. **Deploy**: Wrap into a simple web app for real-world testing.

---

## 📁 Included Files in Repository
- `FakeNews_Models.ipynb` – Code & analysis
- `poster.pptx` – Visual project summary
- `README.md` – Project overview & credits

### 🛠 Installation
```bash
pip install transformers torch scikit-learn pandas matplotlib


