# SouthStyle Food Sales Factors Analysis

I used Excel to perform a correlation analysis and regression analysis to identify variables affecting sales and create a formula to forecast sales for a food manufacturer. 

## Executive Summary:

A fictional food manufacturer based in South-Carolina called SouthStyle Food specializes in selling sausages and southern-style processed foods. After 40 years of successful sales in the South, SouthStyle Food is expanding to new locations on a national scale. They have hired a marketing research agency to identify variables that could affect sales in new regions. This firm has identified the following five factors influencing sales: Number of dealers, Population (in 000s), Market potential (in 000s), Number of popular brands, and Number of stores (in 00s). My contribution to the project was to identify the most important factors affecting sales and to create a formula for SouthStyle Food to be able to forecast sales for new areas. 

I performed a correlation analysis in Excel to determine the following order of significance for the five identified variables. 

#### Most Influential Factors: 
1) Number of dealers
2) Population (in 000s)
3) Market potential (in 000s)
4) Number of popular brands
5) Number of stores (in 00s)

After, I performed a series of regression analyses in Excel and created the following statistically significant, predictive formula for SouthStyle Food to use to forecast sales in potential locations. 

#### Best Fit Formula to Predict Sales:
Sales = 0.570883089 * # of dealers - 0.668575163 * # of popular brands + 0.203846491 * Population (in 000s)

## Project Requirements:

- Produce a list of variables affecting sales ordered by greatest significance.
- Create a formula to predict future sales.
   
## Methodology:

1. Use Excel to perform a correlation analysis with the provided data.
   
2. Use Excel to perform and refine a statistically significant regression analysis.
   
3. Use the results of the final regression analysis to produce a formula forecasting sales.
   
## Skills:

#### Excel: 
correlation analysis, regression analysis, data analysis toolpak, general formatting, reports

## Results and Recommendations: 

Using a correlation analysis in Excel, I compared the above variables with the sales variable to identify the factors most strongly correlated with sales. This produced numerical values between -1 and 1 that show how closely the variables are correlated. Factors with the strongest relationships have values closer to 1 for positive correlations and values closer to -1 for negative correlations. If values are near 0, this indicates the variables are not correlated. All of the variables in this analysis have a strong positive correlation with sales, except number of popular brands which has a strong negative correlation, meaning a higher number of popular brands typically yields lower overall sales. I used the results of the correlation analysis to produce a ranking of variables correlating to sales for SouthStyle Food. This will allow them to identify ideal potential locations to maximize future sales. 

#### Most Influential Factors: 
1) Number of dealers
2) Population (in 000s)
3) Market potential (in 000s)
4) Number of popular brands
5) Number of stores (in 00s)

Then, I performed several regression analyses in Excel, refining them each time to produce sufficiently low p-values and increase the significance of my predictive formula. I was able to create a statistically significant formula to predict sales using the following variables: sales, number of dealers, number of popular brands, and population (in 000s). This formula has a high adjusted R Square score of 0.95712497622086, meaning 95.7% of variance in sales is a result of the variables used in the analysis. It also has an extremely Significance F value of 9.26020674643806E-30, which indicates the model as a whole is statistically meaningful with a reliable relationship. Finally, the very low p-values for each of the x variables indicates the model is statistically significant and yields valuable insights. I used this regression analysis and the coefficients it provided for each variable to produce a formula to predict sales.  

#### Best Fit Formula to Predict Sales: 
Sales = 0.570883089 * # of dealers - 0.668575163 * # of popular brands + 0.203846491 * Population (in 000s)

Along with the results of the analyses, I created a report in Excel to professionally present my results to stakeholders from SouthStyle Food. 

## Next Steps: 
1) I could produce focused sales forecasts for different regions of the United States.
2) The sales forecasts could be used to inform profit models for potential new locations. 
