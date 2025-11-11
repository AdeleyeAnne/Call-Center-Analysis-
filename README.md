# Call-Center-Analysis-
This project reinforces the power of data in transforming customer experience through through measurable and actionable insights 
 
## 📉Business Overview

This analysis evaluates customer interactions across four main channels — Call Center, Chatbot, Email, and Web — from multiple U.S. locations (Baltimore/MD, Chicago/IL, Denver/CO, and Los Angeles/CA).

The dataset includes metrics such as Total Calls, Average Call Duration, Customer Satisfaction (CSAT), Response Category, and Sentiment, with the goal of understanding how service delivery and customer perception differ across channels and regions.

### 💻Project Dashboard

[Dashboard Preview](https://1drv.ms/i/c/ce35d0d4c398a5c7/IQBIshqCNPqqT7VxfP3zqXE6ATL3Gttc27QrBr7h922lLbg?e=81l0BH)

## 📔Statement of the Problem

The organization’s customer service department manages multiple communication channels — Call Center, Chatbot, Email, and Web — across several states. However, despite consistent call volume, customer satisfaction levels vary, and some response categories exceed service level agreements (SLAs).

There is a need to analyze call volume, response efficiency, satisfaction trends, and channel performance to identify improvement areas and enhance overall customer experience.

### 📚Dataset Description 

The dataset contains information scraped from online for the purpose of learning 

#### Dataset Columns

(ID, Customer Name, Sentiment, CSAT Score, Call Timestamp, Reason, City, State, Channel, Response Time, Call Duration (Minutes), Call Center)

  ### 📠Analysis Focus: 
  Tasks focus on Average call period, Average satisfaction ratings, Response, and sentiment insights
  
  ### 💻Tools Used
- Ms Excel (for Data Analysis cleaning)
  - For data collection
  - For data cleaning
- Pivot Table and chart (for analysis and Dashboard Visualization)


### 🔍Data cleaning and modeling 
- Data was Transformed into Power query
- Data cleaning and formating
- Data filtering
- Removing duplicates values
- Loaded to power pivot fir modeling
- Generate a date table
- Connect date table to query
  

### 📊New Calculated Created using DAX 

1. Total Call = Count (Call centerID)
2. Total Call for all channels 
   = Calculate (Count ( call center id), call center["channel"] = Call center.
 = Chatbot
= web
= Email
3. Average satisfaction call= Average (Calk center [CSAT Score]
4. Same for all channel
   
- These calculated columns played a vital role in deriving actionable insights
  
### 📋Business Objectives

1. Evaluate overall customer satisfaction and identify performance gaps.
2. Compare efficiency across communication channels and regional call centers.
3. Assess how SLA compliance impacts satisfaction levels.
4. Identify major reasons for customer inquiries.
5. Recommend data-driven actions to improve service delivery and optimize customer support channels.

### 📝Performance Overview 

* Total  Calls 70.
* Average call duration of 26.26 minutes
* Average satisfaction score of 5.33 out of 10.

Across channels,
* Call Center emerged as the strongest performer. It handled 33% of total calls, maintaining a relatively short average call duration of 24.22 minutes.
*  Highest satisfaction score 5.70.
  The Web channel followed closely by 24%  with an average satisfaction score of 5.41

* The Email channel performed moderately well, with 11% of total calls, a slightly higher duration (27.88 minutes), and a satisfaction score of 5.50 

* Chatbot channel underperformed. Despite handling 31% of total calls, it recorded the lowest satisfaction score (4.82) and the longest average call duration (29.14 minutes).

Calls handled within SLA averaged 24 minutes and recorded the highest satisfaction score of 6,  calls handled above SLA took an average of 36 minutes and saw satisfaction drop to 3.

Regionally, results varied significantly.

Baltimore (MD) and Los Angeles (CA) had the highest number of interactions but also showed higher negative sentiment, suggesting service inconsistency or heavy call load.

Chicago (IL) and Denver (CO) displayed fewer calls and mixed feedback, but generally more balanced performance.
Interestingly, Los Angeles showed both extremes — a high number of “Very Positive” and “Very Negative” responses — signaling inconsistency in service quality within the same location.

In terms of customer intent, Billing Questions (50%) dominated all call reasons, followed by Payments (12) and Service Outages (8)
The weekday analysis showed that Monday (15 calls) and Wednesday (12 calls) recorded the highest call activity, likely linked to billing cycles or service follow-ups at the start and middle of the week.
   
### ✅Summary of Insights

- Customer satisfaction is directly tied to response timeliness and SLA compliance.
- Call Center remains the most reliable and satisfying service channel.
- Chatbot shows inefficiency — longer durations, lower satisfaction, and likely customer frustration.
- Billing-related queries represent the majority of calls, signaling a systemic issue that could be automated or clarified.
- Regional performance varies widely, highlighting the need for standardization.
- Peak call days (Monday and Wednesday) may require better staffing or scheduling adjustments.

## 📌Recommendations

✅ Reinforce SLA Discipline:
Monitor and enforce response targets — calls handled within SLA clearly produce higher satisfaction outcomes.

✅ Improve Billing Clarity:
Redesign billing communication, offer FAQs, or implement self-service portals to reduce repetitive billing-related calls.

✅ Standardize Regional Training:
Establish unified customer service procedures across all call centers to minimize sentiment and satisfaction gaps.

✅ Optimize Scheduling:
Allocate more agents during high-call days (Mondays and Wednesdays) to reduce waiting time and improve response consistency.

### 📝Conclusion

This comprehensive call center analysis highlights that service speed, consistency, and human interaction are the strongest contributors to customer satisfaction.
While traditional call centers remain effective, there’s significant opportunity to improve automation through better chatbot design and enhanced SLA adherence.

By applying these insights, the organization will streamline its support operations, reduce handling times, and ensure customers consistently receive timely, high-quality service — ultimately improving satisfaction and loyalty.


   
 ### 📂Data Analysis ( Files Included)
  - view Analysis here [Excel workbook](https://1drv.ms/x/c/ce35d0d4c398a5c7/IQDFDRuTiQFJR6LohIgId29DAQAnKMhtE1luP1Es4xdSwCg?e=PrbcD2)
