# Unlocking HR Insights: Data-driven Decisions
*This Power BI project focuses on HR analytics and aims to provide insights into various aspects of human resources within an organization.*  

### **Authors:**
***Prajwal Koirala (207051)* and *Samin Aryal (207008)***

## Introduction  
The analysis is done for partial fulfillment of Evidence-Based Business Analytics course offered for students enrolled in Bachelor of Business Administration (BBA) at [**Kathmandu University School of Management (KUSOM)**](https://som.ku.edu.np/). For the analysis, a dataset named [*HR Analytics Dataset*](https://www.kaggle.com/datasets/saadharoon27/hr-analytics-dataset) was selected from Kaggle. The dataset consisted of multiple columns with more than 1000 rows. Initally we studied the data and took decision on which columns to include and which to exclude. After the decision was made ***Power query*** was used to clean the data and reach the [desired dataset](https://github.com/koirala99/Pair-Project/blob/main/Working%20file.xlsx). While cleaning undesired columns along will any null values containing rows were excluded. After the data was cleaned, ***Power BI*** was used for preparing [visualization](https://github.com/koirala99/Pair-Project/blob/main/Analytics.pbix) through which insights could be drawn. Through the visualization, insights regarding the characteristics and demographics of the employees were identified. Further we had prepared few questions about the cause of employee attrition and income determinants of employees which were answered through the use of visualizations. Lastly, we have listed the major findings of the analysis which is beneficial for organizaitons to reduce their employee attrition rate. 

## Analysis  
An organization consists of various employees having various backgrounds. Thus, in order to understand the organization one needs to understand the employees. So, first of all we have tried to understand the basic characterstics of the employees present in the dataset.  
![main chart_page-0001](https://github.com/koirala99/Pair-Project/assets/38663887/9c1eb02f-d7e8-458d-9fa5-50e533b4ba6e)    
The Employee distribution as per Gender chart shows that there are 854 males and 569 females working in the company. Likewise majority of the employees are of the age group 26-35 years followed by the age group 36-45 years, 46-55 years, 18-25 years and 55+ years. Similarly most of the employees are working in the Research and Development department (64.93%) followed by Sales department (30.71%) and Human Resources department (4.36%).  

![main chart_page-0002](https://github.com/koirala99/Pair-Project/assets/38663887/f6570ae0-f96b-492a-ae71-e5a67fc3f41d)  
Above chart highlights the distribution of employees as per their role in the organization. We can infer that among the employees most of the employees are working as Sales executives followed by Research Scientist, Laboratory Technician, Manufacturing Director, Healthcare representative and so on.  

![main chart_page-0003](https://github.com/koirala99/Pair-Project/assets/38663887/7f0305f9-dcff-4401-95ce-ddf386cc75b6)   
Most of the employees of the organization i.e. 998 travel rarely for business purposes. Meanwhile 270 employees travel frequently for business purposes while 148 employees have not traveled at all for business purposes. Similarly, most of the employees are educated in Life sciences (41.18%) followed by Medical (31.31%), Marketing (10.89%), Technical degree (9.07%), Other (5.69%) and Human resources (1.83%).  

![main chart_page-0004](https://github.com/koirala99/Pair-Project/assets/38663887/ba6124a8-52e4-47aa-a6fc-a982da372361)  
The employees attrition is at 16.16% meaning that among the total employees 16.16% have left the job.Likewise we can observe that among the employees only about 1/3rd of the employees work overtime. Similarly, most of the employees (721) working in the organization earn upto $5k per month, followed by employees (428) earning between $5k-$10k. 144 employees earn between $10k-$15k with only 130 employees earning more than $15k per month.  

#### Research Questions
The question which we are trying to answer through the analysis includes the followings:  
* Which age group has the highest attrition?
* Does distance from home impact employee attrition rate?
* Does salary determine attrition among employees?
* Do years since the last promotion trigger attrition among employees?
* Does salary increase (%) affect employee attrition?
* Does the education field determine monthly salary?
* Does monthly income determine attrition?

![main chart_page-0005](https://github.com/koirala99/Pair-Project/assets/38663887/b3c109a2-2a6a-4534-b419-af249e549254)   
The highest number of employee attrition in terms of absolute number is seen in the age group 26-35 years. But if we see with a close eye, we can see that the highest rate of employee attrition is seen in the age group 18-25 where almost half of the employees were leaving the job. Likewise we also found that the highest attrition among employees due to distance from home ranges between 0 km and 4km. A second spike in attrition is seen when an employees house is at a distance of 8-10 km and a third spike is seen when the employees house is at a distance of 23-25 km.  

![main chart_page-0006](https://github.com/koirala99/Pair-Project/assets/38663887/f4cf6d5d-9244-4f1c-967d-7863d5ec1531)  
The chart signals that there is a higher case of employee attrition between years 0-4 of an employees recent promotion. As the years since promotion progresses, the attrition rate decreases. This is quite contrary to general understanding in which it is accepted that if employees go without promotion for a long time they tend to leave the organization. We can infer through the bar chart that the owerthe pay the higher the employee attrition rate. As can be seen the highest attrition is seen in the salary slab upto 5k while salary slab above 15k has the lowest attrition signaling that if employees are paid higher they tend to have lower attrition.  

![main chart_page-0007](https://github.com/koirala99/Pair-Project/assets/38663887/0ae00158-f7b8-4ed8-8199-aaa6258fd5d6)   
The employee attrition and monthly income chart shows that on an average the employees who are leaving the organization have below $5000 in monthly income while those staying in the organization have at least $6500 monthly income. Likewise the monthly income as per education field shows that the highest earning field on an average is Marketing ($7353.64), followed by Human Resources ($7275.54), Medical ($6540.83), Life Sciences ($6527.97), Other ($5783.88) and at last Technical degree ($5749.12). Similarly the chart employee attrition and salary hike (%) showed that employees who have an annual salary hike of less than 15% have the highest attrition rate. This further corroborates with the result seen in chart above signaling that lower pay and lower pay growth leads to increased employee attrition.  

## Findings  
The major findings from the analysis are as follows:
* Employees between the age group 26-35 have the highest attrition count in absolute terms while the age group 18-25 has the highest attrition rate.
* Employees living near the organization have the highest attrition rate. 
* Employees that got promoted in the past 4 years have the highest attrition rate. 
* Employees earning in the income slab of Upto 5k have the highest attrition rate while employees earning in the income slab of 15k+ have the lowest attrition rate. 
* On an average, employees earning less than $4500 have the highest attrition rate while employees earning higher than $6500 have reduced attrition. 
* Employees who have yearly salary growth of less than 15% have the highest attrition rate.

## Practical implicaitons
The recommendation














