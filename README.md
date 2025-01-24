# Unlocking the Secrets to Crowdfunding Success

## Project Overview

This project investigates the factors associated with the success of crowdfunding campaigns. Using a dataset of 5,000 campaigns from a U.S.-based platform, we explore how engagement metrics (e.g., comments) and goal-setting strategies impact the amount of funds collected. 

The study is grounded in **Signaling Theory**, which suggests that certain campaign characteristics can signal credibility and trustworthiness to potential backers, driving success.

## Hypotheses

1. **H1:** There is a positive and significant relationship between the number of comments and the funds collected. Campaigns with more comments signal higher engagement and credibility, leading to increased funding.

2. **H2:** The funding goal moderates the relationship between comments and funds collected. Higher goals amplify the effect of comments, while lower goals require less evidence of engagement to achieve success.

## Data & Methodology

- **Dataset:** 5,000 crowdfunding campaigns
- **Key Variables:**
  - **Dependent:** `collected_funds` - Total funds collected (in USD)
  - **Independent:** `comments_count` - Number of backer comments
  - **Moderator:** `goal` - Funding goal set by the campaign
  - **Controls:** 
    - `pitch_size` - Word count of the campaign pitch
    - `campaign_quality` - Composite score reflecting quality indicators like images, videos, and perks
- **Analytical Techniques:** Linear regression models (OLS), moderating effect analysis, and assumption checks (e.g., normality, multicollinearity, and heteroskedasticity).

## Results

- **H1:** Supported. A positive and significant relationship exists between the number of comments and funds collected.
- **H2:** Supported. The funding goal moderates the relationship, with higher goals requiring more engagement to drive success. However, extremely high goals diminish the reliance on comments.

## Insights

1. Engagement (e.g., comments) is a crucial driver of crowdfunding success.
2. Campaign strategies should adapt based on funding goals. Higher goals require stronger evidence of credibility and backer involvement.
3. Statistical assumptions, such as normality and homoscedasticity, require attention to improve the robustness of the findings.

## Files in the Repository

- `analysis_code.qmd`: R code for data cleaning, regression analysis, and visualization.
- `data.xlsx`: Sample dataset (sanitized version for privacy).
- `presentation.pdf`: Summary of findings.

## Key Takeaways for Practitioners

- Leverage comments and updates to build trust and drive engagement.
- Set funding goals strategically, aligning with the expected level of backer interaction.
- Analyze campaign data for insights into what drives success in your specific niche.

## Authors

- **Thao Nghi Le Thai (me)**
- **Bao Nhi Tang**

## Acknowledgments

This project was developed as part of the course **BE603: Data Analytics III**. We are grateful for the support and feedback from our instructors and peers.
