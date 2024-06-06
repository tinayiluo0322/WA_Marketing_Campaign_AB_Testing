# WA Marketing Campaign AB Testing

## Project Description

This repository contains a project focused on decision-making from A/B testing, utilizing a nuanced approach that goes beyond the traditional binary decision-making framework. Instead of merely determining whether to reject the null hypothesis of no effect, we consider both statistical significance and practical significance. The project involves a detailed analysis of an A/B test to provide a holistic understanding of the test results, employing Frequentist statistical methods, Monte Carlo simulations, and a touch on Bayesian analysis.

## Key Concepts

### Traditional A/B Testing Approach
Most A/B tests emphasize a binary decision-making approach:
- **Reject the null hypothesis** if the test shows statistical significance.
- **Deploy the change** if the null hypothesis is rejected; otherwise, maintain the status quo.

### Enhanced Decision-Making Approach
This project incorporates additional layers of analysis:
- **Statistical Significance:** Determine if the null hypothesis of no effect can be rejected.
- **Practical Significance:** Assess whether the estimated effect size is large enough to justify deployment.
- **Alternative Hypotheses:** Evaluate statistical significance concerning a null hypothesis where the effect size is less than the threshold for practical significance.

## Project Objectives

1. **Frequentist Analysis:** Analyze A/B test data using traditional statistical methods, but interpret the results as probability distributions for potential effects if deployed broadly.
2. **Monte Carlo Simulations:** Utilize probability distributions to conduct Monte Carlo simulations, analyzing the likelihood of different outcomes.
3. **Bayesian Context:** Discuss how this approach relates to Bayesian statistical analysis.

## Exercise Context

### Data Source
The data for these exercises is a modified version from [IBM Watson Analytics](https://www.kaggle.com/datasets/chebotinaa/fast-food-marketing-campaign-ab-test) for a marketing A/B test conducted in Washington State. The context involves a fast-food chain deciding whether to run a new marketing campaign to promote a new menu item. Weekly sales data were recorded for four weeks.

### Dataset Variables
- `MarketID`: Unique identifier for the market.
- `MarketSize`: Size of the market area by sales.
- `LocationID`: Unique identifier for the store location.
- `AgeOfStore`: Age of the store in years.
- `Promotion`: Indicates if the location received the promotion (treated).
- `week`: One of four weeks when the promotions were run.
- `SalesInThousands`: Sales amount for a specific `LocationID`, `Promotion`, and `week`.

### Analytical Approach
- **Data Cleaning and Preparation:** Handling missing values and preparing the dataset for analysis.
- **Exploratory Data Analysis (EDA):** Visualizing and understanding sales patterns.
- **Statistical Analysis:** Applying hypothesis testing and interpreting results as probability distributions.
- **Monte Carlo Simulations:** Using simulations to predict the likelihood of various outcomes.
- **Results Interpretation:** Assessing both statistical and practical significance to guide decision-making.

## Conclusion

This project provides a comprehensive framework for decision-making from A/B testing, emphasizing both statistical and practical significance. By leveraging Frequentist methods, Monte Carlo simulations, and Bayesian insights, the project offers a sophisticated approach to interpreting A/B test results and making informed business decisions.
