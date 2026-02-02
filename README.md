# Automobiles — Exploratory Data Analysis for Executive Fleet Selection

This project presents a comprehensive **exploratory data analysis (EDA)** of an automobiles dataset, framed around a realistic business task: recommending **environmentally responsible executive vehicles** that balance cost, fuel efficiency, and performance.

The analysis combines structured data cleaning, statistical exploration, and visualisation to support **data-driven decision-making**. Particular emphasis is placed on transparency of assumptions, interpretation of relationships between variables, and clear communication of findings.

![Illustration of a range of cars arranged in a horseshoe formation with a city skyline in the background](chevy_range_2025.jpg)

---

## What’s in this repository

- **Jupyter Notebook:** full exploratory analysis (`Automobiles_Capstone_Project.ipynb`)  
- **Report:** formal written analysis and recommendations (`EDA_report_Automobile_Dataset.pdf`)  
- **Images:** visualisations and reviewer feedback  
- **Source data:** automobile dataset (`automobile.txt`)  
- **Requirements:** Python dependencies (`requirements.txt`)  

---

## Project Context

The dataset contains information on 205 vehicles across 26 attributes, including price, fuel efficiency, engine specifications, dimensions, and categorical variables such as manufacturer and body style. No accompanying metadata was provided, requiring careful interpretation and explicit handling of assumptions.

The task was framed as an executive fleet selection exercise, with a company policy focused on **reducing environmental impact and operating costs** while retaining suitable performance and status characteristics for senior management vehicles.

---

## Approach Overview

The analysis followed a structured exploratory workflow:

- Data inspection and cleaning, including identification and treatment of non-standard missing values  
- Conversion and validation of numerical and categorical features  
- Univariate and multivariate visualisation  
- Correlation analysis to identify dependent and independent relationships  
- Investigation of trade-offs between price, fuel efficiency, engine size, and performance  
- Synthesis of findings into an evidence-based recommendation  

---

## Key Insights / Findings

- **Price and fuel efficiency** exhibit a strong inverse relationship: higher-priced vehicles tend to have lower fuel efficiency.  
- **City and highway MPG** show an almost perfectly linear relationship within this dataset, warranting caution around overfitting.  
- **Engine size and horsepower** are strongly positively correlated with price and negatively correlated with fuel efficiency.  
- **Honda and Chevrolet** emerge as manufacturers offering the most fuel-efficient vehicles within the dataset, though sample size limitations are explicitly acknowledged.  
- Body style analysis highlights trade-offs between engine size, performance expectations, and fuel efficiency.  

These findings were consistently supported across histograms, scatterplots, boxplots, KDE plots, and correlation heatmaps.

---

## Resulting Recommendation

Based on fuel efficiency, cost considerations, and driving characteristics suitable for long-distance executive use, the analysis supports the selection of **sedan models from the upper ranges of Chevrolet and Honda**.

This recommendation balances environmental considerations with performance and acknowledges the role of executive vehicles as both functional and symbolic assets.

---

## Endorsement

Reviewer feedback highlighted the **depth and quality of the analysis**, with particular praise for:

- Thoughtful and well-documented **data cleaning decisions**, including handling of non-standard missing values  
- Effective use of **advanced visualisations** to explore relationships between variables  
- Clear analytical reasoning that went beyond surface-level exploration  
- A structured, professional approach that reflects real-world analytical practice  

<sub>[View full reviewer feedback](capstone%20automobiles.jpg)</sub>

---

## Skills Demonstrated

**Analysis**
- Exploratory data analysis  
- Correlation and relationship interpretation  
- Handling incomplete and ambiguous datasets  

**Visualisation**
- Histograms, boxplots, scatterplots, KDE plots  
- Correlation heatmaps and grouped comparisons  

**Interpretation**
- Trade-off analysis between cost, efficiency, and performance  
- Evidence-based recommendation development  

**Tools**
- Python  
- pandas  
- NumPy  
- matplotlib / seaborn  
- Jupyter Notebook  

---

## Requirements

Install the required Python packages with: `pip install -r requirements.txt`

---

## Why this project belongs in my portfolio
This project demonstrates my ability to approach an open-ended, real-world problem with discipline, clarity, and analytical rigour.

Rather than treating exploratory analysis as an informal exercise, the work emphasises careful data handling, explicit assumptions, and structured reasoning. It reflects how exploratory data analysis supports decision-making in professional contexts and forms a strong foundation for more advanced modelling work later in my portfolio.
