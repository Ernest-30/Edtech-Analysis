# Edtech-Analysis

## Overview
In this analysis, we leveraged the power of Power BI to gain valuable insights and extract meaningful information from various datasets related to lead management and sales performance. The analysis focused on providing a comprehensive view of the lead journey, team performance, Lead source performance and watched demo report.

## About the Dataset
The dataset contains a month’s data of Edtech Business sales report. The dataset contains the details of the leads in various stages of the customer acquisition flow. The timeline covered is January to February 2022.

#### Customer Acquisition Key Stages:

Lead - Awareness - Consideration - Conversion

Dataset provided contains:
- Basic details of leads
- Hierarchy structure of sales managers and their assigned leads
- Lead interaction details
- Demo watched details of leads
- Reason for not being interested

1.	lead_basic_details: Contains details of the leads.

2.	sales_managers_assigned_leads_details: Contains the details of the senior and junior sales managers and their assigned leads.
- Each senior sales manager is assigned to 4 junior sales managers.
- Each junior sales manager is assigned few leads in each cycle (a cycle is approximately a week).

3.	leads_interaction_details: Contains the details of call interactions of junior sales managers with the leads.
  - A lead can drop out at any stage of the flow. If there is no call by the junior sales manager to the lead after a certain stage then the lead is considered as dropped at that stage.

4.	leads_demo_watched_details: Contains the details of the demo session watched by the leads.

5.	leads_reasons_for_no_interest: Contains the details of the reasons given by the leads for their lack of interest.


## Business Task

Identify the right metrics and run an analysis that will help the;

a. Business team to understand the lead's journey and stages with scope for improvement

b. Business heads to understand their team performance

c. Managers to understand their target areas

d. Build the best suitable dashboard presenting your insights.

## Analysis
The analysis was done using Microsoft Power BI.

### Steps

- Data Import: I imported the raw data which was in CSV file format into Microsoft Power BI.

- Data Cleaning: I cleaned the data to ensure accuracy and consistency this included standardizing the formats, and correcting errors.

- Data Transformation: I transformed the data to make it suitable for analysis. This transformation includes calculations, aggregations, and filtering operations. I also created new columns required for the analysis.

- Data Visualization: I visualized the analyzed data using the various in charts and graphs available in Microsoft Power BI. I also created a dashboard using the insights from the analyzed data.

### Leads Demography:
The Leads Demography report provides a breakdown of leads based on various attributes such as age, gender, current city, current education, and parent occupation. These visualizations will offer valuable insights into the target audience, and will help the business team tailor their sales strategies and messaging to cater to specific demographics. Understanding the demographic distribution of leads will empower the team to make informed decisions on how to best engage and convert potential customers.

![image](https://github.com/Ernest-30/Edtech-Analysis/assets/123366282/57caa140-2c97-43e5-b603-cd79c3503ddb)

From the analysis above, the following insights was uncovered;

- Gender: Females represent the majority of leads generated, accounting for a significant 55.28% of the total leads, which amounts to approximately 199              leads.

- Age_Group: Among the various age groups, the bracket of 16 - 18 years stands out with the highest number of leads generated, comprising a total of 109                leads.

- Current_city: The city of Hyderabad emerges as the dominant lead generator, contributing a substantial 77 leads, making it the city with the most leads.

- Current_education: Among different education levels, B.tech stands out as the primary source of leads, contributing to 139 leads, indicating its                              popularity among the target audience.

- Parent's_occupation: The occupation of government employee holds the top spot in generating leads, with an impressive 128 leads attributed to this                              category.

- Lead_source: Social media emerges as the most effective lead source, generating 87 leads, showcasing its significant impact in attracting potential                      customers.


### Team Performance Analysis:
To provide insights into team performance, I designed a dashboard that showcased individual team members' activities and outcomes. This dashboard allowed Business heads to compare individual team member performance, identifying top performers and areas where additional support might be required. Metrics such as the number of calls made, leads funnel,conversions and response rates will help the Business heads understand how each team member was contributing to the overall success of the sales team.

![image](https://github.com/Ernest-30/Edtech-Analysis/assets/123366282/6dc05030-afa3-49fd-a5d2-70bbf5e9c67f)

From the analysis above, the following insights was uncovered;

- Total Leads: The total leads generated is 358 leads

- Converted Leads: The total converted leads are 64 leads

- Conversion rate: The overall conversion rate is 18%

- Leads Distribution per Jnr_sm and Snr_sm : The Jnr_sm that received the highest number of lead was JNR1001MG with a total of 34 leads while the Snr_sm      that received the highest number of leads is SNR503MG with a total of 98 leads

- Converted leads per Jnr_sm : The Jnr_sm that converted the highest number of leads was JNR1016MG with a total of 8 leads converted out of 27 leads         received

- Top Jnr_sm (Conversion rate): The Jnr_sm with the highest conversion rate is JNR1002MG with a conversion rate of 35%

- Top Snr_sm (Conversion rate) : The Snr_sm with the highest conversion rate is SNR501MG with a conversion rate of 24%

- Response rate per Jnr_sm : The Jnr_sm with the highest response rate is JNR1002MG with a response rate of 2.75%

- Successful calls per Jnr_sm : The Jnr_sm with the highest number of successful calls is JNR1016MG with a total of 26 successful calls.

- Calls to conversion ratio: The overall calls to conversion ratio is 2.89 while the Jnr_sm with the best call to conversion ratio is JNR1002MG with a     ratio of 2.9


### Lead Source Performance:
The Lead Source Performance report provides a comprehensive analysis of lead generation sources. By analyzing the performance of different lead sources, the business team will gain valuable insights into which sources were most effective in generating high-quality leads. The report showcased metrics such as lead volume per lead source, conversion rates per lead source, and lead source distribution across various segments like; age_group, current location, gender etc. Armed with this information, the team will be able to optimize their marketing and lead generation efforts, focusing on the sources that yielded the best results. This approach will help to allocate resources efficiently and maximize return on investment (ROI).

![image](https://github.com/Ernest-30/Edtech-Analysis/assets/123366282/9d5570eb-0189-4956-9f8e-305a686d15f4)

From the analysis above, the following insights were uncovered;

#### Lead distribution by Lead source
- The lead source that generated the most leads is social media with a total of 87 leads generated making it the top performaing leads source in terms of lead genration, on the other hand the least performing lead source is website with a total of 58 leads generated.

- In terms of conversion, the top performing lead source is email marketing with a conversion rate of 26%, while the least performing lead source is Website with a conversion rate of 10%

#### Lead source distribution and Conversion per Gender  
- The social media lead source accounts for the most leads from the female gender with a total of 61 leads, while the SEO lead source accounts for the most male leads with a total of 38 leads. The lead source with the least number of leads from the female gender is website with a total of 31 leads, while for male genders it is social media with a total of 26 leads.

-  The female gender accounts for 25% each of the converted leads of both the SEO and social media lead source making them the top performing lead source in terms of conversion rate for female leads, while the lead source with the least conversion for female leads are user referrals and webiste with conversion rate of 16% each. The male gender accounts for 29% of the converted leads from the email marketing lead source making it the top performing lead source in terms of conversion rate for male leads, while the least performing lead source in terms of conversion rate for male leads is Website with a conversion rate of 4%.

#### Lead source distribution and Conversion per City  
-  The social media lead source recorded the highest number of leads generated per city with a total of 35 leads generated in Hyderabad while the website recorded the lowest number of leads generated in a city with a total of 2 leads generated in Mumbai and Bengaluru respectively. SEO also recorded very low leads generation in Bengaluru with a total of 2 leads.

- The highest conversion rate recorded was in Bengaluru where SEO has about 50% conversion rate making it the top lead source in terms of conversion rate accross all the Cities. This rank is also shared with website which also recorded a conversion rate of 50% in Bengaluru. Some lead sources did not record any conversion at all accross some of the Cities as well;
- Email marketing recorded 0% conversion rate in Mumbai.
- Both SEO and social media recorded 0% conversion rate in Chennai.
- User referrals recorded 0% conversion rate in Chennai, Hyderabad, Kochi and Mumbai.
- Website recorded 0% conversion rate in Mumbai.

#### Lead source distribution and Conversion per Age Group  
-  The social media lead source recorded the highest number of leads generated per age group with a total of 34 leads generated from 22 - 24 age group while user referral recorded the lowest number of leads generated per age group with a total of 4 leads generated from  25+ age group.

-  The highest conversion rate recorded was for 25+ age group where email marketing has about 40% conversion rate making it the top lead source in terms of conversion rate accross all the age groups. Some lead sources did not record any conversion at all accross some of the age groups;

- Social media and user referrals recorded 0% conversion rate each for the 25+ age group.

- Website recorded 0% conversion rate for both the 16 - 18 and 25+ age groups respectively.


### Watched Demo Report:
The Watched Demo Report offers a detailed analysis of leads who watched product demos. It includes metrics such as the percentage of the demo session watched, number of leads that watched the demo accross different segments, languages preferred, and reasons for not showing interest in the demo. By understanding how leads engage with the demo content, the business team will gain insights into the effectiveness of their product demonstrations. The report highlights opportunities to improve demo content, address language preferences, and understand the reasons for disinterest. Armed with this information, the team will tailor demos to better resonate with potential customers, increasing the likelihood of conversions.

![image](https://github.com/Ernest-30/Edtech-Analysis/assets/123366282/b1097b75-6776-4f34-93ad-78d5484dbf25)

From the analysis above, the following insights were uncovered;

- A total of 194 leads watched the demo.

- The most preferred language for the leads that watched the demo is English language, which accounts for 57.73% of the total leads that watched the demo, this is a total of 112 leads. The least preferred language is Hindi accounting for only about 10.31% of the total leads that watched the demo, this is a total of 20 leads.

- The top reason for leads not interested in the demo is 'Wants offline Classes' with a total of 56 leads.

- The top reason for leads not interested to consider is 'Can't afford' with a total of 31 leads.  

- The top reason for leads not interested to convert is 'Can't afford' with a total of 19 leads.

- Leads with current education as B.tech recorded the highest number of watched demo with a total of 70 leads who watched the demo, while the least category for this segment are leads with current education as 'Intermediate completed' with just 3 leads.

- Leads within the age group of 19 - 21 recorded the highest number of watched demo with a total of 60 leads who watched the demo, while the least category for this segment are leads within the age group of 25+ with just 23 leads.  

- Leads with parent occupation as Government employee recorded the highest number of watched demo with a total of 67 leads who watched the demo, while the least category for this segment are leads with parent occupation as Doctor with just 2 leads.

- Leads from the female gender recorded the highest number of watched demo with a total of 112 leads who watched the demo this is about 57.73% of the total leads that watched the demo, while leads from the male gender accounted for only 82 leads which is about 42.27% of the total leads that watched the demo.

- Leads with current city as Hyderabad recorded the highest number of watched demo with a total of 43 leads who watched the demo, while the least category for this segment are leads with current city as Mumbai with just 19 leads.


## Visualization

The overall dashboard was created using Microsoft Power BI. The Dashboard consists of 4 different tabs;
- Leads demography
- Team performance
- Lead source performance
- Watched demo report
  
Click [HERE](https://github.com/Ernest-30/Edtech-Analysis/blob/main/Edtech%20Dashboard.pbix) to download and view the full interactive dashboard.


## Conclusions

- The team can focus on female leads, aged 16-18 years, with a current education in B.tech, whose parents are government employees. Social media can be a key lead source to further engage potential customers.

- The team can recognize the most successful junior and senior sales managers based on the number of leads received, conversions, and response rates. They can also learn from the JNR1002MG junior sales manager, who has the highest conversion rate and the most successful calls.

- Social media stands out as the most effective lead source with the highest number of leads generated. However, email marketing has the highest conversion rate, making it a potential focus for future campaigns. The team can also target leads from Bengaluru and the 25+ age group, as both segments have the highest conversion rates.

- The team can improve demo sessions by addressing language preferences, especially English, which is the most preferred language. Additionally, they can address concerns raised by leads who are not interested in the demo, such as wanting offline classes or financial constraints.

## Recommendations

Based on the analysis conducted, the following recommendations are suggested to improve the lead generation and conversion process:

1. Target Female Leads: As females represent the majority of leads generated, the business team should focus on tailoring marketing efforts and messaging to resonate with this demographic. Understanding their preferences and pain points can lead to more effective lead engagement.

2. Engage the 16-18 Age Group: The age group of 16-18 years shows the highest number of generated leads. Targeted campaigns and content that appeal to this age group's interests and needs can significantly improve lead engagement.

3. Leverage Social Media: Social media is the most effective lead source, generating the highest number of leads. The business team should allocate resources to maximize its potential. Engaging potential customers through social media platforms can yield valuable leads.

4. Optimize Email Marketing: While social media generates the most leads, email marketing shows the highest conversion rate. The team should invest in well-crafted email campaigns to nurture leads and drive conversions.

5. Address Language Preferences: English is the most preferred language for watching demo sessions. The business team should ensure that demo content is available in multiple languages, catering to the diverse audience's preferences.

6. Understand and Address Objections: Pay attention to the reasons leads provide for not showing interest in the demo. Identifying common objections, such as cost concerns or offline class preferences, allows the team to address these issues effectively in future marketing and sales efforts.

7. Recognize Top Performers: Acknowledge and reward top-performing junior and senior sales managers, such as JNR1002MG and SNR501MG, who have demonstrated high conversion rates and successful call ratios. Encourage knowledge sharing and best practices among the sales team.

8. Optimize Lead Distribution: Review the distribution of leads among junior and senior sales managers. Ensure an equitable allocation of leads to maximize performance and minimize bottlenecks.

9. Analyze Demographic Performance: Continue analyzing demographic data to uncover potential opportunities for specific marketing and sales strategies. Tailoring campaigns to specific demographic segments can improve lead engagement and conversion rates.

10. Continuous Improvement: Encourage a data-driven approach to decision-making and emphasize continuous improvement in all aspects of lead generation and conversion. Regularly review performance metrics and adjust strategies based on insights from data analysis.

By implementing these recommendations, the business team can enhance lead generation and conversion, leading to increased sales, improved team performance, and overall business growth.
