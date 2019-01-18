# Data Synthesis

This project will be to develop GAN-based-methods to help synthesize rare business data.

To check-out the repo:

```
git clone https://github.com/sriharshams/data_synthesis.git
```

## Main Idea

Most businesses own tabular data, structured in the form of records in a database. These can be timeseries, customer transactions, or product informations. Many Data Scientists all over the world are working on extracting Insights from this type of data. 


Most of the crucial tasks that can be solved with this data, such as fraud detection, funnel analysis, and churn prediction, suffer from a common problem: [imbalanced data](https://www.svds.com/learning-imbalanced-classes/). This is a well known issue throughout the machine learning and data science fields,and methods have been explored to tackle it. Solving it is a huge need, as losses due to fraud are routinely estimated to be in the billions of dollars annually for example. This initiative, attempts to do just that.


## Project description
One of the method that works best for images, text, and audio is data augmentation, usually done by tweaking images and audio samples, or paraphrasing text. This is much harder for tabular data, because it requires generating realistic data that is useful, fits real world constraints, and follows our distribution. This project will be to develop GAN-based-methods to help synthesize rare data, such as realistic fraud examples in [Kaggle's Credit Card Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud).
