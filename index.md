---
layout: default
title: Data Science & Analytics Portfolio
---

# Welcome to Sam C.'s Portfolio

This site showcases my data science and analytics-related academic projects, work projects, and passion projects. My consolidated GitHub repository for these projects can be found [here](https://github.com/samuelco1997/Portfolio), and the links to each can be found below for easier access:

## 🔬 Projects

- [**Predicting Graduation Rates with Regression-type ML Models in Python**](https://github.com/samuelco1997/Portfolio/tree/main/Predicting%20Graduation%20Rates%20with%20Regression-type%20ML%20Models)

For this personal portfolio project, I aimed to create an algorithm that could predict the 4-year graduation rate of higher education institutions using various performance metrics (school composition, enrollment and graduation rates, demographics, test scores, and more). A hyperparameter tuned XGBoost model showed the highest performance (MAE = 4.21, RMSE = 5.70).
<details>
<summary><em>▶ Click to see results</em></summary>
  <p>XGBoost Performance (predictions vs. true values)</p>
  <img src="visuals/graduation_rates_preds_xgboost.png" alt="XGBoost Performance grad" style="width: 300px; height: auto;">
  <img src="visuals/graduation_rates_performance.png" alt="XGBoost Performance grad" style="width: 300px; height: auto;">
</details>


- [**Topic Modeling & Sentiment Analysis of UN speeches in R**](https://github.com/samuelco1997/Portfolio/tree/main/Topic%20Modeling%20and%20Sentiment%20Analysis%20of%20UN%20Speeches%20in%20R)

This project is my final project deliverable for my Text as Data & Computational Linguistics class. I decided to explore how topic modeling and sentiment anlaysis can be applied to UN speeches, as well as how these findings can be validated historically and geographically. I also employed a multivariate fixed-effects regression to analyze the effect of various world metrics on speech sentiment. A R Shiny dashboard with some of my compiled findings can be found [here](https://scohen97.shinyapps.io/tad_app/).
<details>
<summary><em>▶ Click to see results</em></summary>
<!DOCTYPE html>
<html>
<body>
  <iframe src="https://scohen97.shinyapps.io/tad_app/" width="800" height="400"></iframe>
</body>
</html>
</details>

- [**Classifying Election Violence using Random Forests in Python**](https://github.com/samuelco1997/Portfolio/tree/main/Classifying%20Election%20Violence%20using%20ML%20in%20Python)

In this project for my Data Science II class, I created models that could classify the likelihood of instances of electoral violence using random forest algorithms. A random forest model was fit to the data, yielding an accuracy score of 0.85 and a F1 score of 0.78.
<details>
<summary><em>▶ Click to see results</em></summary>
  <p>Random Forest Confusion Matrix and Performance for Conflict Prob.</p>
  <img src="visuals/conflict_rf_confusion_matrix.png" alt="Random Forest Confusion Matrix for Conflict Prob." style="width: 300px; height: auto;">
  <img src="visuals/conflict_rf_performance.png" alt="Random Forest Confusion Matrix for Conflict Prob." style="width: 300px; height: auto;">

</details>


- [**Dog Whistle Detection Classifier with LLMs and Word Embeddings**](https://github.com/samuelco1997/Portfolio/tree/main/Dog%20Whistle%20Detection%20with%20LLM-Generated%20Word%20Embeddings)

For this project in my Neural Networks class, I attempted to create a dog whistle classification system using LLM-generated word embeddings from the DistilBERT transformer, in combination with traditional supervised learning techniques, namely K-Nearest Neighbor and Logistic Regression. Results were promising, with accuracy and F1 scores above 0.90.
<details>
<summary><em>▶ Click to see results</em></summary>
  <p>KNN Embedding Confusion Matrix (100 random obs.)</p>
  <img src="visuals/dw_confusion_matrix.png" alt="KNN Confusion Matrix" style="width: 300px; height: auto;">

</details>


- [**World Health & Happiness Dashboard in Tableau**](https://public.tableau.com/app/profile/sam8656/viz/Worldhealthandhappiness/Dashboard1)

This dashboard is the final product of my Google Data Analytics Certificate coursework. It shows health and happiness metrics across the world, pre-pandemic. My credentials for this certificate can be found [here](https://www.coursera.org/account/accomplishments/professional-cert/9QY9C49T9SJP?utm_source=link&utm_medium=certificate&utm_content=cert_image&utm_campaign=pdf_header_button&utm_product=prof).
<details>
<summary><em>▶ Click to see results</em></summary>
<!DOCTYPE html>
<html>
<body>
  <iframe src="https://public.tableau.com/app/profile/sam8656/viz/Worldhealthandhappiness/Dashboard1" width="800" height="400"></iframe>
</body>
</html>
</details>


---
More information on my background, credentials, and accomplishments can be found on my [LinkedIn](https://www.linkedin.com/in/samuel-cohen-b5878b163/) profile. 

<style>
details {
  margin-bottom: 1.5em;
}

details summary {
  font-weight: normal;
  color: #0056b3;
  cursor: pointer;
  margin-top: 0.5em;
}

details summary:hover {
  color: #007bff;
  text-decoration: underline;
}

details[open] {
  padding: 0.5em;
  background-color: #f9f9f9;
  border-left: 4px solid #ccc;
}
</style>

