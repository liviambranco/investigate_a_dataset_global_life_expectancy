### Date created
01 Apr 2020

### Project Title
Investigate a Dataset

Investigate the Global Life Expectancy in the Last 50 years
by Livia Mendes

### Project Details
I will conduct data analysis and create a file to share that documents my findings. I will use pandas and NumPy to answer the questions I am most interested in, and create a report sharing the answers.

- Step One - Choose Data Set
- Step Two - Get Organized
- Step Three - Analyze Data
- Step Four - Share Findings
- Step Five - Review

### Description
This project is part of Udacity's Data Analyst Nanodegree.

The purpose of this research is to look at the global population life expectancy in the last 50 years. The datasets used in the analysis were downloaded from gapminder, an organization data collects and translates data about the world into statistics. These databases may be found at Gapminder's website https://www.gapminder.org/data/ . They are:

Life Expectancy: It is the average number of years a newborn will live should the present mortality patterns remain the same.

Life Expectancy Female: It is the average number of years a newborn female will live should the present mortality patterns remain the same.

Life Expectancy Male: It is the average number of years a newborn male will live should the present mortality patterns remain the same.

Government Share of Health Spending: Is the average of health expenditure per citizen that has been subsidized by the government in US Dollars.

Gini Coefficient: It represents the inequality in the society measured by the differences in income. The higher coefficient is, the grater the inequality. It represents how large are the income differences within a society.

GDP Per Capita/Yearly Grow (PPP): It represents the yearly percentage growth rate of Gross Domestic Product (PPP) per capita in terms of purchasing power. This theory compares and measures different currencies among countries in terms of purchasing power. Where, PPP stands for the purchasing power parity (PPP). The GDP per capita is calculated by dividing value of all final goods and services produced by midyear population of the country.

This report intends to see if there is a relation between life expectancy and economic variables. To evaluate if economic or health economic variable, such as, the Government Share of Health Spending, may impact the increase or decrease a population's life expectancy.

The questions this report is looking to answer are:

Female and Male Life Expectancies

In the last 50, which group had the higher average life expectancy, female or male?
What country has the lowest average life expectancy for women?
What country has the highest average life expectancy for women?
What country has the lowest average life expectancy for men?
What country has the highest average life expectancy for men?
General Life Expectancy

What are the bottom 10 countries in average general life expectancy?
What are the top 10 countries in average general life expectancy?
Government Health Spending and General Life Expectancy

Is there a relationship between government health spending and life expectancy? Can government health spending contribute to a higher or lower life expectancy?
What are the top 10 countries in average government health spending?
Are the top 10 countries in average government health spending among the top 10 countries in average life expectancy?
What are the bottom 10 countries in average government health spending?
Are the bottom 10 countries in average government health spending among the bottom 10 countries in average life expectancy?
Gini Coefficient and General Life Expectancy

Is there a relationship between the development index (Gini) and life expectancy? Can a low Gini Index contribute to a higher or lower life expectancy?
What are the top 10 countries in average Gini Coefficient?
Are the top 10 countries in average Gini Coefficient among the top 10 countries in average life expectancy?
What are the bottom 10 countries in average Gini Coefficient?
Are the bottom 10 countries in average Gini Coefficient among the bottom 10 countries in average life expectancy?
GDP Per Capita and General Life Expectancy

Is there a relationship between the GDP per capita and life expectancy? Can a higher GDP per capita contribute to a higher or lower life expectancy?
What are the top 10 countries in average GDP per capita?
Are the top 10 countries GDP within the top 10 countries with the highest life expectancy?
What are the bottom 10 countries in average GDP per capita?
Are the bottom 10 countries GDP within the bottom 10 countries with the lowest life expectancy?

### File used
- life_expectancy.csv
- life_expectancy_f.csv
- life_expectancy_m.csv
- gdp.csv
- gini.csv
- health.csv

### Files
- life_expectancy.csv
- life_expectancy_f.csv
- life_expectancy_m.csv
- gdp.csv
- gini.csv
- health.csv
- investigate_a_Dataset.ipynb
- investigate_a_Dataset.html
- project_details.txt
- readme.md

## Conclusions

**Female and Male Life Expectancies**
We found that overall women tend to live in average 8% more than man.

**General Life Expectancy**
People in the top 10 countries in General Life Expectancy tend to live in average 56% longer than people in the bottom 10 countries.

**Government Health Spending and General Life Expectancy**
With the findings acquired on our exploratory analysis it is possible to conclude that there seems to be a relationship between Government Health Spending and General Life Expectancy. The scatterplots showed that there is a positive correlation between the two variables. The correlation matrix and the comparisons between top and bottom government spending countries versus top and bottom life expectancy countries showed that the amount a government spends in health per person appears to be important and may influence in the life expectancy of a country. However, it is not a determinant variable. Other variables may affect life expectancy more heavily.

**Gini Coefficient and General Life Expectancy**
With the findings acquired on our exploratory analysis it is possible to conclude that there seems to be a faint relationship between the income equality/inequality (Gini coefficient) and General Life Expectancy. The scatterplots showed that there is a linear correlation between the two variables. The correlation matrix and the comparisons between top and bottom Gini coefficient countries versus top and bottom life expectancy countries showed that the income equality may be an important variable for the life improvement of a population, but it seems to have little influence in the life expectancy of a country.

**GDP Per Capita (PPP) and General Life Expectancy**
With the findings acquired on our exploratory analysis it is possible to conclude that there seems to almost no relationship between the parity in purchasing power per capita (GDP - PPP) and General Life Expectancy. The scatterplots showed that there is a positive correlation between the two variables. Similarly, the Gini Index, the correlation matrix and the comparisons between top and bottom GDP PPP countries versus top and bottom life expectancy countries showed that the parity in purchasing power per capita (GDP - PPP) may be an important variable for the life improvement of a population, but it seems to have very little influence in the life expectancy of a country.

### Credits
Udacity (https://www.udacity.com/course/data-analyst-nanodegree--nd002)

Gapminder (https://www.gapminder.org/data/)
