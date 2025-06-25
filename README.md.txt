# 🧠 Marketing Analytics: Predicting Campaign Response (SPSS Project)

This project was submitted for the Marketing Analytics (MANM533) module at the University of Surrey. It involved building predictive models to identify customers likely to respond positively to a savings campaign using IBM SPSS Statistics.

## 🎯 Objective

To apply statistical analysis and predictive modeling to campaign and demographic data in order to:
- Understand customer patterns
- Predict campaign responses
- Propose a targeted marketing strategy

## 📂 Datasets

Two raw datasets in `.sav` format were merged using `CustID`:
- `all_campaign.sav`: Contact method, call duration, and campaign response
- `all_personal.sav`: Age, job, marital status, education, loan details, etc.

## 📊 Project Workflow

### Task 1: Data Preparation
- Merged campaign and personal datasets
- Checked for missing values and outliers
- Conducted exploratory data analysis (EDA)
- Visualized one numerical and one categorical variable
- Binned a numerical variable using equal interval and equal frequency methods
- Split dataset into 70% training and 30% testing

### Task 2: Model Building
- **Logistic Regression**: Identified significant predictors of positive response
- **Decision Tree**: Analyzed main splits and response patterns
- Compared both models using ROC curve and AUC metrics

### Task 3: Campaign Recommendation
- Identified high-likelihood responders
- Suggested marketing channels and customer segments based on model results

## ⚙️ Tools Used

- **IBM SPSS Statistics**: Data prep, modeling, and analysis
- **Microsoft Word/Excel**: Report writing and formatting

## 🗂 Folder Structure

- `/data`: Original `.sav` datasets
- `/outputs`: Model summaries, charts, binning results, and ROC curves
- `/report`: Final submitted report (PDF)

---

© 2025 Taimoor Ali — Submitted for academic purposes only.
