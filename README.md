# Global Wealth Distribution Analysis of the 2024 Forbes Top 200 Richest Billionaire

## **Introduction**
<img width="1280" height="720" alt="Overview image" src="https://github.com/user-attachments/assets/cb57956d-ffdc-410b-83fd-25c422249b44" />
The Management of my organisation, a Global Financial Research Organisation, assigned me the responsibility of analysing the 2024 Forbes ranking of the World's Top 200 Richest Billionaires as part of a financial research project, with the objective of providing insights into global wealth distribution, geographical representation, industry concentration and demographic characteristics.

## **About Dataset**
The dataset which was obtained from kaggle,captured essential information of the top 200 billionaires, including their net worth, global ranking, names, countries of origin, ages, and industries.[download here](https://www.kaggle.com/datasets/mayankanand2701/top-200-richest-worlds-billionaires-dataset?resource=download)

## **Methodology**
The analysis was conducted using MySQL Server, beginning with database and table creation, followed by data importation and preliminary data cleaning. Subsequently, relevant analytical queries were used to perform calculated metrics involving aggregate functions, group by, where, order by, case when, filtering, and subqueries were applied to generate the required insights.

creating Database
<img width="966" height="896" alt="Overview" src="https://github.com/user-attachments/assets/19dd6480-674d-4710-ae96-11a4862df7ba" />

creating Table
<img width="947" height="894" alt="Creating Table" src="https://github.com/user-attachments/assets/9261f1d1-d21f-430f-98c0-33ebfd003539" />

Data cleaning
<img width="944" height="890" alt="Data cleaning" src="https://github.com/user-attachments/assets/b0f028a6-3944-4b01-85d2-9312f1535697" />

## **Key findings**
The analysis revealed that the 200 billionaires were distributed across 35 countries and 18 industries, with a combined net worth of $6.37 trillion and an average net worth of $31.84 billion. Bernard Arnault and family aged 75 from France, representing the Fashion and Retail industry, ranked first with an estimated net worth of $233 billion. Further analysis showed that 53 billionaires recorded net worth exceeding the overall average of $31.84 billion, highlighting the concentration of substantial wealth among a relatively small proportion of the group.

Total Billionaires
<img width="938" height="891" alt="Total Billioniares" src="https://github.com/user-attachments/assets/a127b489-7d25-423e-b43e-fc5569804dac" />

Total countries
<img width="952" height="885" alt="Total Countries" src="https://github.com/user-attachments/assets/5a396acf-17b1-496c-8e63-8ce2ed5759e9" />

Total industries
<img width="937" height="895" alt="Total Industries" src="https://github.com/user-attachments/assets/9654a198-d7d1-4f6f-b212-0e9b4e6d53fa" />

Total Billionaires net worth
<img width="945" height="886" alt="Total Billionaire Networth" src="https://github.com/user-attachments/assets/4fc02bdd-80ee-425c-86ca-f70b8b5a780c" />

Billionaires with net worth above average net worth
<img width="1068" height="891" alt="networth above average" src="https://github.com/user-attachments/assets/4f94e550-f04d-4b7e-99bf-450d099b19e2" />


The demographic analysis revealed an average billionaire age of 69.38 years, suggesting that the billionaires were predominantly older persons. Further analysis showed that Mark Mateschitz of Austria was the youngest billionaire at 31 years, while Robert Kuok of Malaysia was the oldest at 100 years. Despite the dominance of older individuals, the analysis showed that 16 billionaires below the age of 50 collectively held $508.3 billion in wealth, demonstrating the significant financial influence of younger wealth holders.

oldest billionaire
<img width="940" height="884" alt="Oldest Billioniare" src="https://github.com/user-attachments/assets/3c0261fc-bd31-4692-b39a-e8babac097c1" />

5 youngest billionaires
<img width="936" height="892" alt="5 youngest billionaire" src="https://github.com/user-attachments/assets/54b563d3-7463-4fc6-b0f8-28ea990048c3" />

Average age and networth
<img width="935" height="892" alt="avg age   networth" src="https://github.com/user-attachments/assets/fd7eeeab-c16a-41a6-af8c-81c467fa2232" />

The geographical analysis revealed that the United States dominated the billionaire population, accounting for 79 billionaires with a combined net worth of $3,130.9 billion representing 49.2% of the total wealth held by the 200 billionaires thereby making the United States the leading country in both billionaire representation and aggregate wealth. In contrast, Colombia recorded the lowest country level combined wealth of $10.8 billion by one billionaire. 

Top 5 countries billionaires
<img width="939" height="897" alt="5 most represented country" src="https://github.com/user-attachments/assets/d559438b-caf1-4856-8687-4b7119737498" />

Total net  worth by countries
<img width="983" height="895" alt="combined networth by country a" src="https://github.com/user-attachments/assets/e4c97b10-9a72-4a97-b780-edf91a07c4a1" />

Analysis across the 18 industries identified Technology as the leading industry, with 40 billionaires and a combined net worth of $1,738.8 billion while the Service industry recorded the lowest combined net worth of approximately $13.80 billion by one billionaire. Further analysis revealed that despite Technology having the highest number of billionaires and combined net worth, Telecom recorded the highest average industry net worth of  $102 billion, with just one billionaire. This distinction demonstrates that the industry with the highest combined wealth does not necessarily have the highest average wealth per billionaire.

Total Billionaires by industry
<img width="944" height="893" alt="industry billionaires count" src="https://github.com/user-attachments/assets/d9274d8b-361d-4c32-9891-b4b5222d9d7a" />

Total net worth by Industry
<img width="1186" height="872" alt="industry networth" src="https://github.com/user-attachments/assets/c5ce1d7e-3491-4ebf-b114-0210cb324231" />

Industry with highest average net worth
<img width="949" height="881" alt="highest industry average networth" src="https://github.com/user-attachments/assets/0ae42838-3199-4036-a217-d33cb621ed3f" />

The ranking analysis revealed that 102 billionaires shared rankings across 39 groups of tied positions, while 98 billionaires had unique rankings. Rank 180 recorded the highest frequency, with eight billionaires occupying the same ranking position. Each of these billionaires had an individual net worth of $11.20 billion, giving a combined net worth of $89.60 billion, from four countries and six industries.

Ranking Tie
<img width="980" height="893" alt="rank tie" src="https://github.com/user-attachments/assets/a2e91eb4-eced-47af-a156-c6f2cd01904c" />

## **Limitation**
The dataset did not include gender as a demographic variable. Consequently, the analysis could not establish the gender distribution of the 200 billionaires or determine the proportion of total wealth controlled by male and female billionaires.

## **Conclusion**
Findings from the analysis of the 2024 Forbes Top 200 Richest Billionaires revealed a significant concentration of billionaire wealth in the United States and the Technology industry. The demographic analysis further highlighted the dominance of older individuals in the billionaire population, alongside the growing financial influence of younger billionaires.

However, the absence of gender-disaggregated data limited the assessment of wealth distribution between male and female billionaires. Incorporating gender as an additional demographic variable in future analyses would provide a more comprehensive understanding of global wealth distribution, gender representation, and wealth disparities among the world's wealthiest individuals.

## **Recommendation**
Future wealth distribution dataset should incorporate gender disaggregated data to enable a comprehensive assessment of gender representation and wealth distribution among billionaires. This would provide insights into the gender wealth gap, identify disparities in wealth accumulation, and support evidence-based research on gender equality and economic inclusion.
the data set did not disaggregate by gender hence the percentage of wealth controlled by both gender could not be established
