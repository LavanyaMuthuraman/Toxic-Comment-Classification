# Jigsaw-Toxic-Comment-Classification

---
![toxic2](https://user-images.githubusercontent.com/109660074/230200129-f6ded7bb-e6d6-4400-918a-fae5b16a112a.jpg)
---

### **Description:**

The work carried out in this notebook focused on the [Jigsaw Toxic Comment Classification Challenge](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge) hosted on [Kaggle](https://www.kaggle.com/). The task consists of a **Multilabel text classification** problem where a given toxic comment, needs to be classified into one or more categories out of the following list:
- `toxic`
- `severe_toxic`
- `obscene`
- `threat`
- `insult`
- `identity_hate`

For instance, if the comment is `toxic` and `obscene`, then for both those headers the value will be `1` and for the others it will be `0`.

- I've used the [Jigsaw toxic data](https://www.kaggle.com/competitions/jigsaw-toxic-comment-classification-challenge/data) prived by the competition
- I've referring only to the following csv files from the data dump: `train.csv`, `test.csv`, `test_labels.csv`

In summary, The toxic comment challenge dataset represents a challenging task for text classification due to the high level of toxicity in the comments and the imbalanced class ratio. In this notebook, we have explored three models for this task: **a baseline model, a GloVe model, and a BERT model.** The results show that BERT outperformed the other models in most of the categories, especially in the rare labels, such as threat and identity hate. The study also revealed that the performance of all three models was similar in toxic and severe toxic categories.

The study highlights the effectiveness of BERT in multi-label text classification, especially in imbalanced datasets. Addressing the imbalanced data issue and exploring more advanced transformer models could improve the performance further more.
