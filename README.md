# Table of Content
* [1.0 Executive Summary](https://github.com/skddedm/Commercial-Portfolio-Analysis/blob/main/README.md#10-executive-summary)
* [2.0 Methodology](https://github.com/skddedm/Commercial-Portfolio-Analysis/blob/main/README.md#20-methodology)
* [3.0 Project Outcomes](https://github.com/skddedm/Commercial-Portfolio-Analysis/blob/main/README.md#30-project-outcomes)
* [4.0 Risk Metrics](https://github.com/skddedm/Commercial-Portfolio-Analysis/blob/main/README.md#40-risk-metrics)
* [5.0 Strategy Recommendation](https://github.com/skddedm/Commercial-Portfolio-Analysis/blob/main/README.md#50-strategy-recommendation)
* [6.0 Future Project Continuity](https://github.com/skddedm/Commercial-Portfolio-Analysis/blob/main/README.md#60-future-project-continuity)

# 1.0 Executive Summary
The commercial loan portfolio book is critical in driving income and value to the operation of the bank into the foreseeable
future. An imaginary bank - Assurance Bank was used in this project.

### 1.1 Problem Statement:
The bank could not claim possession of the collateral of of a recently defaulted customer due to imperfect collateral registration
into the bank’s custody.

### 1.2 Project Objective:
The objective of this project analyzes the bank’s commercial loan portfolio quality, risk and growth factors. The key
determinants are:
* Credit worthiness of customer entry into the portfolio
* Loan processing TAT analysis
* Portfolio industry distribution
* Overdraft utilization and portfolio growth
* Interest income generation
* Non-performance risk tracking
* Collateral management (perfection and monitoring)

### 1.3 Project Scope:
* The commercial overdraft portfolio is the focus
* All customers operate within the province of Alberta
* 7300 commercial overdraft customers make up the portfolio since 2009 and 2026
* 797 new commercial overdrafts was approved in Q1 2026
* The portfolio was spread among 8 industry sectors
* Overdraft interest ranges from 11% to 21% based on the industry requirements
* All newly onboarded customers in Q1 2026 have 12 months overdraft tenor from the date of approval
* Approved TAT for loan processing is 15 days
* Credit score breakdown used in analysis is as follows:
  760 and above: Excellent
  729 - 759: Very Good
  660 - 728: Good
  560 - 659: Fair
  559 and below: Poor

### 1.4 Tools Deployed:
* Power query
* Power BI

### 1.5 Summary Project Findings:
The commercial overdraft portfolio is well balanced with income generation, utilization, growth and diversity across the 8
industries of lending but heavily strong on performance and collateral monitoring. It shows 0% overdue overdraft and 100%
collateral monitoring. However, it contains 5.21% poorly credit-rated customers, 36% delayed processing and 0.6% collateral
not perfected with exposed values at risks of $53.84m, $314.39m and $5.91m respectively. A risk metrics determined the impact
of the 3 weaknesses identified. The poorly credit-rated customers and delayed processing times are HIGH risk and the collateral
not perfected are MEDIUM risk. Strategies have been recommended to reduce these risk levels to an estimated LOW.

# 2.0 Methodology
The following methods were deployed:
* 4 tables were created under the following names: customer_list, overdraft_origination, overdraft_utilization,
overdraft_income
* The various key indicators defined in the objective statement were analyzed using Power Query
* Interactive dashboards summary was created using Power BI
* Risk analysis was performed to determine the likelihood and impact of the weaknesses that exist in the portfolio
* Recommendations to be considered were suggested to aid resolve weaknesses discovered after the data analysis.

### 2.1 Data Cleaning Process
* Duplicated customer IDs with customer name deleted
* Date format converted properly
* New columns added: overdraft utilization was converted from amount used to percentage utilized

### 2.2 Data Limitations
* Value Allocation Assumptions: Overdraft amounts, interest income, utilization rate were estimated rather than direct
attribution, affecting precision.
* Limited Time Horizon: Analysis based on a single period (FY2026) may not capture seasonality or long-term trends
over a range of years
* Exclusion of External Factors: Market conditions, competitors’ pricing and macroeconomics impacts were not fully
incorporated.

### 2.3 Overdraft Lifecycle
The following diagrams summarizes the overdraft life cycle adopted by the bank
<img width="969" height="288" alt="image" src="https://github.com/user-attachments/assets/f16b5448-38e6-43ef-8395-246af7475189" />

# 3.0 Project Outcomes
Based on the project objective, the following key performance areas were discovered:
<img width="1305" height="725" alt="image" src="https://github.com/user-attachments/assets/decfa104-cf6b-4e76-a37e-e941c9e85675" />

### 3.1 Strengths
* The number of customers and overdraft exposure are fairly distributed across the 8 industries without concentration risk
* Average overdraft utilization ranges between 1% and 70% over the first quarter of 2026.
* The overdraft earned incomes of $3m, 7m and 23m over the first quarter of 2026
* The portfolio experiences 0% overdue balances
* 100 of the collateral have been monitored within Q1 2026

### 3.2 Weaknesses
* 5.21% of customers rated poor on credit score
* 36% of the overdrafts were approved beyond the 15 day processing TAT
* 0.6% of the collateral are yet to be fully and legally perfected

### 3.3 Details of Key Performance Areas Identified
#### 3.3.1 Credit worthiness of customer entry into the portfolio
5.21% of customers rated poor on credit score. Even though this segment is small, it presents higher risk clients within the
portfolio, presenting an opportunity for targeted monitoring and risk-based pricing to protect returns. Additionally, evidence of
exceptional approval is required from authorized persons with justification supporting reasons for granting credit to customer
who perform poorly with credit behaviour. Without these actions, $53.84m and 49 customers are highly are risk.
<img width="500" height="273" alt="image" src="https://github.com/user-attachments/assets/b821bbf9-77ce-4fd8-8784-46a0c880455b" />

#### 3.3.2 Loan processing TAT analysis
36% of the overdraft were approved beyond the 15 day processing TAT. It represents delays and operational inefficiencies in credit processing may impact client satisfaction and speed-to-market indicating a need for process optimization. 
<img width="511" height="283" alt="image" src="https://github.com/user-attachments/assets/af7564cd-515f-4197-b542-78575a70f4eb" />

#### 3.3.3 Portfolio industry distribution
The credit portfolio is evenly distributed across 8 industries. It is well-diversified, reducing sector-specific shocks and enhancing overall portfolio stability. 
<img width="476" height="273" alt="image" src="https://github.com/user-attachments/assets/d980190f-0d50-4e95-b639-a128032f5076" />

#### 3.3.4 Overdraft utilization and portfolio growth
Average overdraft utilization ranges between 1% and 70% over the first quarter of 2026. It shows that clients are actively using their facilities indicating income generation for the bank and healthy engagement of customers while maintaining room for future lending and liquidity management. The utilization grows the overdraft book balance.
<img width="520" height="102" alt="image" src="https://github.com/user-attachments/assets/ae9232d4-9654-4999-82b2-316a3e161420" />

#### 3.3.5 Interest income generation
The overdraft earned incomes of $3m, 7m and 23m over three months of Q1 2026. This shows a strong income growth over Q1 suggesting increased overdraft utilization and effective pricing of overdraft facilities.
<img width="517" height="107" alt="image" src="https://github.com/user-attachments/assets/e6486820-5f83-4803-b554-15522d54a2e5" />

#### 3.3.6 Non-performance risk tracking
The portfolio experiences 0% defaults showing strong quality, reflecting prudent underwriting and effective risk monitoring processes. 

#### 3.3.7 Collateral management (perfection and monitoring)
There exist a minor gap in legal perfection of collateral. Even though minimal, it exposes the bank to legal and recovery risk, requiring immediate remediation to ensure enforceability of security. Additionally, the bank has maintained strong collateral oversight, ensuring risk is continuously mitigated and security positions remains valid in custody. 
<img width="371" height="153" alt="image" src="https://github.com/user-attachments/assets/4ab5db59-ed43-4656-80ca-81fb8f3b91f2" />

<img width="375" height="155" alt="image" src="https://github.com/user-attachments/assets/f4a342b1-1743-4990-833f-6b91558aa8e3" />

# 4.0 Risk Metrics
The risk metrics is defined by the risk level rating, likelihood rating and impact rating. 

### 4.1 Risk Level
Risk level rating is defined by the likelihood rating and impact rating of each risk area.

| Risk Level | Rating    |
|------------|-----------|
|Low Risk	   |2 and below|
|Medium Risk |3 - 4      |
|High Risk   |5 and above|

### 4.2 Likelihood
Defined as the possibility of the risk area occurring. The number of the affected overdraft expressed as a percentage of the total number of overdraft appr4vals defines the likelihood.
|Likelihood   |Percentage         |Rating|
|-------------|-------------------|------|
|Unlikely     |Less than 5%       |1     |
|Likely       |Between 6% and 40% |2     |
|Very Likely  |Higher than 40%    |3     |

### 4.3 Impact
Defined as the overdraft amount value that can be affected in relation to the expressed likelihood. 
|Impact Severity |Financial Impacted               |Rating      |Investigation and Resolution Timeline|
|----------------|---------------------------------|------------|-------------------------------------|
|Minor           |Less than $5,000,000             |1           |Up to 2 months                       |
|Serious         |Between $5,000,001 and $8,000,000|2           |Up to 1 month                        |
|Major           |Higher than $8,000,000           |3           |Up to 1 week                         |

### 4.4 Commercial Portfolio Risk Assessment Summary
The three weaknesses identified have been assessed in the table below:
|Risk Category                 |Likelihood Rating |Financial Impact Severity  | Risk Rating (likelihood rating + financial impact rating)|Risk Level|
|------------------------------|------------------|---------------------------|----------------------------------------------------------|----------|
|Poor customer credit score    |2                 |3                          |5                                                         |High      |
|OD Approved beyond 15days TAT |2                 |3                          |5                                                         |High      |
|Collateral yet to be perfected|1                 |2                          |3                                                         |Medium    |

# 5.0 Strategy Recommendation
The following strategies have been recommended to aid resolve the identified weaknesses with the commercial portfolio of Assurance Bank in Alberta.
|Identified Weaknesses         |Recommendation                                                                                                             |
|------------------------------|---------------------------------------------------------------------------------------------------------------------------|
|Poor customer credit score    |* Adjust interest rates and exposure limits for lower-rated customers to compensate for higher risk                        |
|                              |* Track financial performance, utilization, and repayment behavior more frequently to detect early signs of deterioration  |
|------------------------------|* Enforce stricter covenants and require more frequent financial reporting to maintain tighter control                     |
|OD Approved beyond 15days     |* Establish real-time dashboards to track processing timelines by analyst and stage                                        |
|                              |* Implement workflow automation for document verification, checklist tracking, and approvals                               |
|------------------------------|* Create a fast-track approval process for low-risk customers to reduce processing time and improve client experience      |
|Collateral yet to be perfected|* Develop a centralized database to monitor collateral documentation status and perfection stages across the portfolio     |
|                              |* Set up alerts for pending or overdue collateral perfection                                                               |
|                              |* Perform quarterly audits on collateral records to ensure all securities are legally enforceable and properly documented  |
                    
# 6.0 Future Project Continuity
* Integrate live portfolio data
* Build a web-based dashboard using Power BI embedded
