# company-analysis-research-design
A look into the research design and data collection process for companies across 10 years (Compustat data), with a closer look at the advertising, development, and market performance measures of these companies.

All the companies selected were consolidated, domestic, still active, produced monetary reports in US dollars, and included businesses operating in sectors other than financial services.

A total of 80,687 observations were collected. Almost all variables had missing values. To lower the risk of compromising those missing values and to prevent bias in later analyses, new binary variables for six measures were created (advertising expenses, R&D expenses, income, sales, market value, and goodwill) to indicate either the presence or absence of company reporting.

Next, the sample was further narrowed by filtering for company size. On average, the companies reported just over 13,000 employees. Therefore, only companies with over 2,000 employees were focused on for further analysis, or large-sized businesses, according to a classification by the Small Business Administration (SBA). All variables were renamed for clarity, and variables deemed unnecessary were deleted (e.g., variables indicating the data format for download and the population source). The sample resulted in 2,189 observations.

This analysis hoped to determine differences and nuances across the industries by seeing whether the explorations produced any notable patterns or correlations. To do this, a new variable was created to represent the company’s industry by using its Standard Industrial Classification (SIC) code. 10 industry categories were used in the initial classification. After removing missing values that would have impeded further analyses, this was further narrowed down to six remaining focal industries: manufacturing, wholesale, retail, transportation/communications/electric, finance/insurance/real estate, and services.

Data provided by Compustat databases very likely only reflects companies that have attained status on a global level. While this does reflect bias in industry representation for the research, the four omitted industry categories were determined to have relatively less significance from a marketing performance perspective.
 
Six new variables were created to represent advertising measures. The first variable produced a fractional representation of expenditure from the company’s assets. This was further categorized with a second, binary variable to classify an emphasis on either marketing expenditures (denoted by a value of “1”) or R&D expenditures (denoted by a value of “0”). Next, a variable was created to represent the company’s Tobin’s Q value, which measures whether it is relatively overvalued or undervalued (calculated by the ratio of its market value to its assets’ replacement cost). Next, a variable was calculated to represent the company’s return on assets (ROA), which measures how profitable the company is in relation to its total assets. Lastly, two variables were created to represent advertising and R&D intensity, respectively.

A last variable was created to potentially aid in further classification steps during later analyses. Due to the large amount of missing data in the expenditure (advertising and R&D) and strategic emphasis variables, a new binary variable was created to classify the presence of the company’s expenditure and strategic emphasis information (denoted by a “1”) and the absence of both types of information (denoted by a “0”).
