# Smoking-Behavior-Analysis-In-the-Uk

⚠️ Disclaimer: The project is based on a dataset available in the public domain for educational purposes only.

##  Introduction

Tobacco use remains one of the leading preventable causes of death globally, with substantial social, economic, and health implications. Despite declining smoking rates in many developed countries, a significant portion of the population continues to smoke—posing ongoing challenges for public health systems.
This project explores a real-world dataset containing demographic and lifestyle information from individuals in the United Kingdom. By analyzing variables such as age, gender, education level, and income, the project aims to uncover key patterns and associations that influence smoking behavior.
Through detailed exploratory data analysis (EDA) and visualizations, this study identifies the segments of the population most at risk, highlights socioeconomic and behavioral correlations, and lays the groundwork for future development of AI-powered predictive models and targeted public health interventions.
Ultimately, the goal is to demonstrate how data science can drive smarter, more effective decisions in the realm of health and wellness

##  Probem Statement
Despite widespread awareness campaigns and public health policies, smoking remains a persistent health risk in the United Kingdom, particularly among certain demographic and socioeconomic groups. The lack of granular, data-driven insights into who smokes, why they smoke, and how behavioral patterns vary across different populations limits the effectiveness of targeted intervention strategies.


##  Methodology
This project employs a structured data science approach to analyze smoking behavior using a real-world demographic dataset from the United Kingdom. The methodology involves the following key steps:

1. Data Collection & Loading
The dataset, originally sourced from a publicly available health and lifestyle survey, was imported in .csv format.
Initial exploration confirmed the presence of relevant features such as age, gender, highest_qualification, income, region, and the target variable smoke.

2. Data Cleaning & Preparation
Missing values in numerical fields (amt_weekends, amt_weekdays) were handled using conditional filtering.
Data types were converted where necessary (e.g., numeric conversion for cigarette consumption). Categorical columns were stripped of whitespace and normalized for consistency.

3. Exploratory Data Analysis (EDA)
- Visualizations were created using matplotlib and seaborn to understand: Distribution of smokers vs non-smokers
- Age patterns across smoking status
- Influence of education level and gender
- Weekly vs weekend smoking behavior
- Statistical summaries provided quantitative context for each chart.

4. Insight Extraction
- EDA results were used to derive key patterns in smoking behavior.
- Each visualization was interpreted to highlight risks, disparities, or trends based on subgroup characteristics.

5. Reporting
Results were compiled into a clear, structured report including charts, insights, and recommendations.
The format closely follows professional data science communication standards, suitable for GitHub, academic presentations, or stakeholder briefings.
This methodology ensures transparency, reproducibility, and relevance, forming a strong foundation for future predictive modeling or policy simulation tools.

## Tools and Technology 

| Tool / Technology                | Purpose                                                                    |
| -----------------------------| -------------------------------------------------------------------------- |
| Python 3.8+                  | Primary programming language for analysis                                  |
| Pandas                       | Data manipulation and wrangling                                            |
| NumPy                        | Numerical operations and array handling                                    |
| Matplotlib                   | Plotting and basic charting                                                |
| Seaborn                      | Advanced data visualizations with built-in statistical features            |
| Jupyter Notebook             | Interactive development environment for combining code, visuals, and notes |

## Key Insights

-25% of the population are current smokers.

-Smokers are predominantly in the 30–45 age range.

-Individuals with no qualifications or only GCSE/O-levels have the highest smoking rates.

-Smoking patterns are relatively even between males and females in the dataset.

-Smokers consume an average of: 16.4 cigarettes on weekends, 13.8 cigarettes on weekdays

-Non-smokers are typically older, especially above 50.

<img width="3200" height="2000" alt="smoking_behavior_snapshot" src="https://github.com/user-attachments/assets/bada8fb1-f087-4b11-8cd4-09876f920f2a" />
<img width="4000" height="2400" alt="merged_smoking_insights" src="https://github.com/user-attachments/assets/1bcf26ba-c15b-4db2-b887-cd947d7aea5a" />


