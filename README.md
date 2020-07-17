
<h1 align="center"> Healthcare Fraud Analysis </h1>

<p align="center">✨ 🍰 ✨</p>

![Python](https://img.shields.io/badge/Python-v3%2B-blue)
[![HitCount](http://hits.dwyl.com/hastagAB/Healthcare-Fraud-Analysis.svg)](http://hits.dwyl.com/hastagAB/Healthcare-Fraud-Analysis)
![License](https://img.shields.io/github/license/hastagAB/Healthcare-Fraud-Analysis)
![Repo Size](https://img.shields.io/github/repo-size/hastagAB/Healthcare-Fraud-Analysis)


# Description :earth_asia:

Medicare Fraud Claims is perhaps the most serious issue confronting the healthcare industry. According to the government, the total Medicare spending increased exponentially due to frauds in Medicare claims. Healthcare fraud is an organized crime which involves peers of providers, physicians, beneficiaries acting together to make fraud claims.

Thorough examination of Medicare information/data has yielded numerous doctors & physicians who are involved in one way or another.Insurance companies are the most vulnerable institutions impacted due to these bad practices. Due to this reason, insurance companies increased their insurance premiums and as result healthcare is becoming costly matter day by day.

This project will help in building tool that can be offered to insurance providers, health care providers, patients, pharmacy, and doctors and will enable Pulseinsights gain credibility in the industry, combat the increasing costs of healthcare, and costly impact of fraud.


# Common types of frauds by providers :bangbang:

- Billing for services that were not provided.
- Duplicate submission of a claim for the same service.
- Misrepresenting the service provided.
- Charging for a more complex or expensive service than was actually provided.
- Billing for a covered service when the service actually provided was not covered.

# Dataset description :file_folder:

The dataset is a part of [CMS.gov dataset](https://www.cms.gov/Research-Statistics-Data-and-Systems/Statistics-Trends-and-Reports/Medicare-Provider-Charge-Data/Part-D-Prescriber) divided and categorized in a [kaggle dataset](https://www.kaggle.com/rohitrox/healthcare-provider-fraud-detection-analysis)

The dataset consists of:

- **Inpatient Data**

    - This data provides insights about the claims filed for those patients who are admitted in the hospitals. It also provides additional details like their admission and discharge dates and admit d diagnosis code.

- **Outpatient Data**

    - This data provides details about the claims filed for those patients who visit hospitals and not admitted in it.

- **Beneficiary Details Data**

    - This data contains beneficiary KYC details like health conditions,regioregion they belong to etc.
    

# Solution Notebooks 💡

The Solutiion consists of two python notebooks.

- [analysis.ipynb](https://github.com/hastagAB/Healthcare-Fraud-Analysis/blob/master/src/analysis.ipynb)

This notebook contains all the Exploratory data analysis regarding the dataset to better analyze, understand and get insights from it.
This notebook contains following notable insights:

    - fraudulent & non-fraudulent data distribution
    - Inpatient & Outpatient Procedure and Diagnosis Distribution
    - Common Procedures & Diagnosis of Inpatinets and Outpatients (Potential fradulent encounters)
    - States having the highest number of potential frauds
    - age distribution for the probable fradulent activites
    - Cost Distribution
    - Correlation Matrix 

- [models.ipynb](https://github.com/hastagAB/Healthcare-Fraud-Analysis/blob/master/src/models.ipynb)

This notebook conatins the creation of a master dataframe and then creating and testing various models.
These models are:

    - Decision Tree
    - Random Forest
    - Naive Bayes
    - Logistic Regression
    
## License :bookmark_tabs:

This repository is licensed under the terms of [LGPL-2.1](/LICENSE). Check the [LICENSE](/LICENSE) file for more details.
