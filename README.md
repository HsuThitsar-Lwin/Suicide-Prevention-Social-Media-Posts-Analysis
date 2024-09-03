# Suicide Prevention: Analysis of Social Media Posts

This project focuses on identifying and analyzing suicidal language within social media posts, specifically from Reddit. Utilizing a dataset sourced from Kaggle, the project applies machine learning models to classify posts as either "suicide" or "non-suicide." The models used include:

- **Random Forest**
- **Naïve Bayes**
- **Support Vector Machine (SVM)**

In addition to classification, the project employs topic modeling techniques to uncover underlying themes in the data. The topic modeling methods used include:

- **Non-negative Matrix Factorization (NMF)**
- **BERTopic**
- **Latent Dirichlet Allocation (LDA)**

## Features

- **Classification of Suicidal Language:** The machine learning models are trained to identify and classify posts that exhibit suicidal ideation.
- **Topic Modeling:** The topic modeling techniques provide insights into the common themes and discussions related to suicide, helping stakeholders to understand the context of the conversations.
- **Web Application:** A web-based tool is developed to allow users to submit text for analysis. The tool predicts whether the text indicates suicidal ideation and provides relevant resources if necessary.
- **Visual Insights:** The project includes visualizations of the topic distributions, which can be used by NGOs and mental health professionals to craft targeted intervention strategies.

## Dataset

The dataset used in this project was sourced from Kaggle and includes 232,074 Reddit posts. The dataset is balanced with two main classes: "suicide" and "non-suicide." Posts labeled as "suicide" are from the r/SuicideWatch subreddit, while the "non-suicide" posts are from other subreddits, including r/teenagers.

## Goals

The primary goal of this project is to support mental health professionals and NGOs in the early detection and intervention of suicidal ideation by providing:

- **Accurate classification** of suicidal language in social media posts.
- **In-depth analysis** of the topics discussed in these posts to identify trends and areas of concern.
- **Tools and resources** to aid in the timely outreach to individuals at risk.

## Conclusion

By leveraging machine learning and topic modeling, this project aims to make suicide prevention more proactive, offering valuable insights and tools to those working on the front lines of mental health care.

