# Project: Optimizing Bank Marketing Strategies through Logistic Regression Analysis
### Project Overview and Object
Analyzed data from a Portuguese bank using logistic regression to identify key factors influencing clients' term deposit decisions. Highlighted the impact of demographic, financial, and marketing-campaign-related variables on term deposit subscriptions. Enhanced client targeting by analyzing how various factors influenced deposit decisions, summarized positioning strategies, and proposed improved telemarketing campaign ideas and promotion methods to increase subscription rates and strengthen client relationships.
### Problem Statement 
Do specific aspects of the phone campaign, such as call duration, frequency of contacts, and timing of calls, or demographic, financial factors significantly impact consumer decisions 
to subscribe a term deposit? 
### Data Description
Dataset Name: Bank Marketing

Source: Moro,S., Rita,P., and Cortez,P.. (2012). Bank Marketing. UCI Machine Learning Repository. https://doi.org/10.24432/C5K306.

Content Overview:
- Customer Demographics: Age, Job, Marital Status, Education
- Financial Background: Default, Balance, Housing Loan, Personal Loan
- Campaign-Related Variables: Contact, Day, Month, Duration, Campaign, Pdays, Previous, Poutcome
- Target Variable (“y”) – Client Subscribe 

### Tool
- Python - Data Exploration, Data Cleaning, Feature Selection, Modeling
### Recommandation Summary:
#### 1. Targeting: Identifying Customer Groups for Marketing Efforts. 
#### Based on the analysis of demographic and financial factors, this term deposit marketing campaign should focus on the following customer groups:

- Retired Individuals and Students: Specifically, target clients aged below 30 or above 60, as they are more likely to be risk-averse compared to other age groups and occupations.

- Single or Divorced Clients: These individuals are often more financially independent, with spare funds available for deposits or investments.

- Well-Educated Clients: Focus on clients with secondary or tertiary education levels, as they are more likely to have an awareness of personal financial management.

- Clients with Positive Yearly Balances: 1)Adquet Positive Balance: These clients have sufficient funds for term deposits and are likely loyal customers of the bank. They are not extremly high balance group, as high balance group is more likely to invest higher risk financial product. 2)Near-Zero Balance: Represents non-frequent users or those with limited investment funds. These clients may require more engagement to convert. 3)Negative Balance: Frequent users but with financial constraints, indicating insufficient funds for investment.

- Clients with Minimal Financial Burdens: Clients with fewer financial obligations, such as housing or personal loans, are more likely to have disposable income available for term deposits.


#### 2. Positioning: 
#### From targeting analysis, we known the characteristics of the client attracted by our current term deposit product. The bank could tailor the current deposit product base on the target customers' needs.

- Highlight the benefit of term deposit - Safety: Comparing to other investment, like security or mutual funds, term deposit offers lower risk. Prospective clients of term deposit focus on safety. For example, retired people and students view safety as a more important factor comparing to return(interest). The product should be tailored to emphasize the low-risk nature of term deposit. 

- Adjustable term and amount: Under the broad defination of term deposit product, the bank should offer several different combination of terms and amount. For students, they may prefer small amount and shorter term; for retired, they may prefer higher amount; for single and divorced client, they may have long term financial goal. Such a product setting covers broader clients.

#### 3. Promotion:
#### Long-term tele-marketing strategies, between campaigns:

1. Customer Relationship Expansion: For prospective clients in the customer pool who have not been contacted before, initiate contact to build a relationship and include them in the next campaign. Historical data shows that previous campaign contact—whether the outcome was success, failure, or ambiguous—significantly increases the likelihood of subscription in future campaigns.

2. Previous Success: Clients who subscribed during a previous campaign are highly likely to subscribe again, regardless of the time passes. To maintain a long-term relationship and maintain loyalty, the bank could promot through offering loyalty rewards, such as higher interest rates, gift incentives, or credit rewards. Additionaly, the bank could simplify the reinvestment process through automatic renewals or user-friendly online options, to make the term deposit product as a consistent investment option with repeat subscriptions easily to be achieved.

3. Previous Failure: Following up within 100 days after a failed campaign increases the probability of success in next campaign. Promotion strategies include time-limited offers (e.g “Act within the next 90 days to secure our exclusive term deposit rate.), customized solutions (address the reasons of the previous failure and tailoring offers to meet client needs.)

4. Ambiguous Previous Outcome ("Other"):For clients with ambiguous previous campaign outcomes, follow up within 200 days, because success rates are higher during this timeframe. Promotion strategies are similar as the ones for previous failure (periodic follow-ups, time-limited promotions, and customized solutions)


#### Short-term, within the campaign:

1. Optimal Number of Contacts: Analysis of last_contact_month shows that previous contacts within the campaign help customers better understand the product, and a certain number of contacts is needed to support decision-making. However, insights from current_campaign_contacts indicate that clients who do not make a decision after a certain number of contacts are more likely to refuse the subscription. The bank should avoid excessive repeat contact to prevent wasting bank resources and annoying clients, focus on meaningful, high-quality interactions rather than  frequency.

2. Increase Contact Duration: A higher last_contact_duration_minute has a positive impact on the likelihood of subscription. During future contact, the customer team should carefully review the client’s background, including demographics and financial history, to better understand their investment needs. Communicate a tailored message that resonates with the client’s goals to bring up interest and engage them in longer, more meaningful conversations. For example, highlight safe, short-term, low-amount, a more flexible term deposit option different from traditional term deposit product for students, that align with their financial situation.

