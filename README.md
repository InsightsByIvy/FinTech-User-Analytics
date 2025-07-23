# FinTech-User-Analytics
Comprehensive fintech user analytics: Insights, segmentation, profiling, and predictive risk modelling.

## Table of Content 
- [Project Overview](#ProjectOverview)
- [Business Context & Problem Statement]()
- [Objectives](#Objectives)
- [Hypotheses](#Hypotheses)
- [Dataset](#Dataset)
- [Project Structure](#ProjectStructure)
- [How To Use This Project](#HowToUseThisProject)
- [Methodology](#Methodology)
- [Machine Learning Approach](#MachineLearningApproach)
- [Visualisation](#Visualisation)
- [Key Findings & Insights](#KeyFindings&Insights)
- [Future Improvements](#FutureImprovements)
- [Learning Outcomes & Reflection]()
- [Ethical Considerations](#EthicalConsiderations)
- [Technologies Used / Main Data Analysis Libraries]()
- [Credits](#Credits)
- [Acknowledgements](#Acknowledgements)

## Project Overview

FinTech User Analytics is an end-to-end data solution designed to uncover behavioural and engagement insights from simulated fintech user data. This project identifies churn patterns, product adoption drivers (such as credit card interest), and engagement trends across mobile platforms. By leveraging data on user activity, financial behaviour, and platform preferences, it provides business-ready insights and predictive models to support decision-making in customer retention, product personalisation, and digital experience optimisation.

## Business Context & Problem Statement

In today’s fast-moving fintech landscape, companies face intense competition for user acquisition and retention. Understanding how users interact with financial products and digital platforms is essential for building loyalty, increasing engagement, and driving sustainable growth. Modern fintech platforms must analyse behavioural trends and engagement patterns to:
 * Reduce customer acquisition costs
 * Improve user retention and lifetime value
 * Optimise product features and offerings
 * Personalise the user experience across channels
 * Mitigate risk through behavioral and financial profiling

This project leverages simulated fintech user data to:
 * Detect and predict churn behaviour
 * Drive adoption of financial products (e.g., credit cards, loans)
 * Tailor engagement strategies across mobile and web users
 * Analyse the impact of referrals, rewards, and app usage
 * Segment users for targeted outreach and product recommendations

Solution:
This project delivers an interactive analytics platform that analyses user behaviour, financial engagement, and product adoption trends. Through visualisations and machine learning models, it surfaces actionable insights for business strategy and operational decision-making.

## Objectives

 * Segment fintech users based on demographic, behavioural, and financial attributes to uncover distinct user personas
 * Identify high-risk churn segments and high-value loyal users using engagement and transaction data
 * Analyse key drivers of loyalty, including app usage patterns, referral behaviour, and reward incentives
 * Predict user retention likelihood to support targeted marketing and feature personalisation strategies
 * Provide actionable insights for product teams to optimise onboarding, referral flows, and feature adoption
 * Visualise engagement and loyalty trends via interactive dashboards for strategic business decision-making

 ## Hypotheses

FinTech users can be segmented into distinct personas based on behavioural patterns. These personas display significantly different levels of engagement, retention, and financial value, making them actionable for business strategy.
This project investigates whether distinct FinTech user behaviours can be used to classify users into personas that help explain differences in engagement, churn, and product interest. 
These insights can be used by fintech platforms to inform product design, marketing, and retention strategies.

**Key Hypotheses**:
 1. Users who earn higher rewards are less likely to churn. 

     **Validation:**  Compare churn rates across reward levels using visual analytics and churn prediction models (e.g., logistic regression or decision trees).

2. Users referred by others show stronger retention and greater interest in financial products.

    **Validation:** Segment referred vs. non-referred users and evaluate retention indicators, product uptake (e.g., credit card interest), and average engagement scores.

3. App users (especially on mobile) demonstrate higher engagement than web-only users.

    **Validation:** Analyse engagement metrics across different user types (app_user, web_user, ios_user, android_user) using clustering and descriptive comparison.

## Dataset

## Project Structure

<pre>📦 FinTech_User_Analytics
├── 📁 Data
│    └── 📁 Cleaned
│        └── 📄 cleaned_data.csv 
│    └── 📁 Raw
│        └── 📄 Fintech_user.csv                   
├── 📁 Notebooks
│   ├── 📄 01_initial_inspection.ipynb         
│   ├── 📄 02_data_cleaning.ipynb            
│   └── 📄 03_hypothesis_testing.ipynb         
├── 📁 Images
├── 📄 .gitignore                              # Specifies files/folders Git should ignore
├── 📄 README.md                               # Project overview
├── 📄 requirements.txt                        # Dependencies
└── 📄 Tableau_Dashboard.twbx                  # Packaged dashboard (if used)
</pre>


## How To Use This Project

This project is designed to be accessible and valuable for a range of users:

**For Business Users**

 * **Goal:** Understand key user segments and what drives engagement, churn, and product adoption.
 * **How to Use:** Explore the Tableau dashboard to view KPIs, user persona rankings, and loyalty trends.
 * **Value:** Support strategic decisions on product offerings, referral systems, and retention campaigns.

**For Product Teams**

 * **Goal:** Identify high-value user behaviours and optimise onboarding or referral flows.
 * **How to Use:** Use the dashboard filters to analyse app vs. web users, platform preferences (iOS/Android), and referral impacts.
 * **Value:** Improve user experience and product-market fit based on behavioural insights.

**For Analysts**

 * **Goal:** Dive deep into behavioural data and modelling logic.
 * **How to Use:** Navigate the notebooks/folder to follow data preparation, feature engineering, and ML development steps.
 * **Value:** Extend the analysis or apply the framework to new fintech user datasets.


## Methodology

This project follows a structured data science approach to extract user insights, build behavioural profiles, and identify key engagement patterns within a fintech platform.

 * **Data Collection & Preparation**: Imported the dataset, handled missing values, and cleaned data for consistency.

 * **Exploratory Data Analysis (EDA)**: Investigated distributions of key variables and relationships between user demographics, behaviour, and engagement.

 * **Visualisation**: Developed an interactive dashboard to present insights tailored for business and product stakeholders.


## Visualisation

## Key Findings & Insights

## Future Improvements

## Learning Outcomes and Reflection

## Ethical Considerations

## Technologies Used

## Credits

 - [Kaggle](https://www.kaggle.com/datasets/niketdheeryan/fintech-users-data): For providing the FinTech Users Dataset
 - [Canva](https://www.canva.com/design/DAGtbZPuH18/A0jzAFmy08rXnbawqq0WXA/edit) is used for project Image
 - Variety of [AI](https://chatgpt.com/?model=auto) Tools were used to suggest and debug codes
 - [Seaborn](https://seaborn.pydata.org/) documentation was reviewed for visualisation
