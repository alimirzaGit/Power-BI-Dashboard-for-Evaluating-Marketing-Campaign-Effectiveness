# Power BI Dashboard for Evaluating Marketing Campaign Effectiveness
<br/>

## Project Introduction

The project's requirement was to create a dashboard for a client – a fitness club based in Toronto. Project deliverables included the dashboard (the Power BI file is attached), a project presentation, and a detailed report documenting the business problem, analytics questions, data processing tasks, data analysis, insights, and recommendations.

*Please note that the identities of the client and its members, along with other data, have been anonymized for confidentiality.*

<br/>

## Business Problem

The client aimed to evaluate the profitability of three marketing campaigns and required a dashboard solution for a comprehensive comparison of revenue and costs associated with each campaign. Additionally, the client expressed the need for a detailed breakdown of campaign revenues and costs attributed to individual members, aiming to determine customer profitability.

<br/>

## Analytics Questions

1. What were the advertising revenues and costs, both overall and attributed to individual members, for each campaign?
2. What key metrics should be used to evaluate the effectiveness of advertising campaigns?
3. Among the advertising campaigns, which one demonstrated the highest cost-effectiveness?
4. What are the demographic characteristics of the club members?

<br/>

## Data Preprocessing

Python was used for data preprocessing to alleviate processing load on Power BI, thereby enhancing overall efficiency. Data was extracted from client’s servers through APIs, followed by data cleaning that involved tasks such as removing duplicates, handling missing values, and standardizing formats. Subsequently, data was transformed by merging data tables via joins and by performing manipulations for calculating key performance indicators (KPIs), such as the percentage of leads converted. The processed data was then loaded into Power BI to create a dashboard, which was the required data product.

<br/>

## Solution Implementation

The dashboard, as depicted in the figure below, consists of four interactive dynamic visuals that produce customized information based on the user’s selection. For example, selecting Campaign A in the column chart triggers a corresponding shift in the horizontal bar chart, revealing the geographic distribution specific to members targeted by that campaign. These capabilities not only address the analytics questions mentioned earlier but also empower users to conduct ad-hoc queries.

![Dashboard Image](https://github.com/alimirzaGit/Power-BI-Dashboard-for-Evaluating-Marketing-Campaign-Effectiveness/blob/main/Dashboard%20Image.png?raw=true)
<p align="center"><strong>Power BI Dashboard for Evaluating Marketing Campaign Effectiveness</strong></p>

<br/>

## Description of the Visuals

1. **"Revenue, Cost, and Profit by Campaign" Column Chart (Top-Left):** Compares the performance of different campaigns, visually breaking down profits to help users distinguish effective campaigns from non-effective ones.

2. **"Members by City, Gender, Age, and Membership Type" Bar Chart (Top-Right):** Offers drill-down capabilities to provide various demographic details on members, including location, gender, age, and membership type. This chart allows users to explore membership distribution patterns, potentially revealing demographic characteristics that contribute to higher income for the company.

3. **"Campaign KPIs" Table Visual (Center):** Showcases KPIs for each campaign. Metrics such as return on investment (ROI), lead conversion percentage, and cost per lead conversion, among others, enable users to evaluate campaign performance in greater detail.

4. **"Revenue and Cost by Member" Table Visual (Bottom):** Displays the revenues and advertising costs attributed to individual members. This visual aids users in assessing customer profitability and provides quick and convenient access to members’ personal information.

<br/>

## Analysis, Insights, and Recommendations

*Note: For conciseness, this section presents a summary of a few selected findings.*

Our analysis identified Campaign A as the sole profitable initiative among the three. This campaign generated the highest revenue at the least cost, thereby producing the most profit and return on investment (ROI). An intriguing anomaly emerged as Campaign A recorded the highest lead conversions despite having the fewest leads. We recommend an investigation into the reasons behind this higher conversion rate, which may unveil the success factors underlying membership sign-ups.

Demographic insights revealed that a substantial 59% of members reside in the Scarborough area, which is near the club. Commuting distance and time appear to be decisive factors for membership sign-ups. We advise the club to focus on local advertising in areas accessible within a 30-minute commute. Furthermore, targeting younger audiences and their parents, particularly school-going children in the local vicinity, could establish a base of loyal customer families. Research suggests that brand exposure in childhood fosters brand association and loyalty into adulthood (Ruiz, 2021), potentially securing recurring revenues for the business in the future.

<br/>

## Reference

[Ruiz, S. (2021, January). The effects of childhood nostalgia on brand loyalty. ResearchGate.](https://www.researchgate.net/publication/348391614_THE_EFFECTS_OF_CHILDHOOD_NOSTALGIA_ON_BRAND_LOYALTY)

<br/>

## Acknowledgments

The project was part of a Capstone course within the Business Insights and Analytics post-graduate program at Humber College. The project team consisted of the following members:

- [Ali Mirza](https://www.linkedin.com/in/m-ali-mirza) - Github: https://github.com/alimirzaGit
- [Andres Ramirez](https://www.linkedin.com/in/andr%C3%A9s-ram%C3%ADrez)
- [Gizelle Lao](https://www.linkedin.com/in/gizellelao) - Github: https://github.com/GizelleL
- [Rafael Muniz](https://www.linkedin.com/in/rafaelfma) - Github: https://github.com/rafael-muniz
- [Trung Le](https://www.linkedin.com/in/trung-le-analyst) - Github: https://github.com/LETRUNGK2
