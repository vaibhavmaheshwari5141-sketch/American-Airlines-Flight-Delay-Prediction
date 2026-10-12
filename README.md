# ✈️ American Airlines Flight Delay Prediction

### Analytics Capstone Project (ANCP)

**Project Title:** An Explainable Machine Learning Framework for Flight Delay Prediction and Operational Decision Support: A Case Study of American Airlines

**Industry:** Aviation / Airline Transportation  
**Company:** American Airlines Group Inc.  
**Business Domain:** Operations Management  
**Technology:** Python, Machine Learning, Explainable AI  
**Methodology:** CRISP-DM  
**Project Status:** D1 – Project Charter

## 1. Project Overview

This project focuses on predicting flight delays at American Airlines using AI and Machine Learning. It aims to identify high-risk flights before departure and provide data-driven insights to support operational efficiency, resource planning, and disruption management.

## 2. Business Problem

American Airlines faces operational challenges caused by flight delays, airport congestion, weather conditions, and scheduling disruptions. According to Cirium's 2025 On-Time Performance Review, the airline recorded an **on-time arrival rate of 76.43%**.

These disruptions affect operational costs, scheduling efficiency, and customer satisfaction.

**Problem Statement:** Can Machine Learning predict American Airlines flights arriving 15 minutes or more late and help operations managers identify high-risk flights before departure?

## 3. Project Objectives

1. Analyse historical flight data to identify major delay-related factors.
2. Develop and compare machine-learning models for flight-delay prediction.
3. Identify high-risk routes, airports, and departure periods.
4. Use Explainable AI to interpret predictions.
5. Support proactive operational planning through a decision-support prototype.

## 4. Dataset

**Dataset Name:** Reporting Carrier On-Time Performance (1987–Present)

**Source:** Bureau of Transportation Statistics (BTS), U.S. Department of Transportation

**Official Dataset Link:**

https://www.transtats.bts.gov/DL_SelectFields.aspx?QO_fu146_anzr=b0-gvzr&gnoyr_VQ=FGJ

**Data Period:** January–December 2025 (planned)  
**Company Filter:** American Airlines (`AA`)  
**Target Variable:** `ArrDel15`

- **0:** Arrival delay less than 15 minutes.
- **1:** Arrival delay of 15 minutes or more.

## 5. Proposed Methodology

The project follows the **CRISP-DM framework**:

1. Business Understanding
2. Data Understanding
3. Data Preparation
4. Machine Learning Modelling
5. Model Evaluation
6. Deployment Planning

**Planned ML Models:**
- Logistic Regression
- Random Forest
- XGBoost

**Evaluation:** Compare ML models with a historical delay-rate baseline using chronological validation, precision, recall, F1-score, and business-oriented delay identification.

## 6. Expected Business Impact

- Early identification of high-risk flights.
- Better operational monitoring and resource prioritisation.
- Improved understanding of flight-delay patterns.
- Data-driven operational decision support.

These are potential benefits that require evaluation, not guaranteed outcomes.

## 7. Project Deliverables

| Milestone | Deliverable |
|---|---|
| D1 | Project Charter |
| D2 | Data Audit and Preparation |
| D3 | Exploratory Data Analysis |
| D4 | ML Modelling |
| D5 | Model Evaluation |
| D6 | Deployment and Monitoring Plan |
| D7 | Draft Report and Presentation |
| E1–E2 | Final Report and Presentation |

## 8. Team Members

| Team Member | Lead Responsibilities |
|---|---|
| Vaibhav  | D1, D4, D7 |
| Anil | D2, D5, E1 |
| Prashansa | D3, D6, E2 |

## 9. References

**Research Paper:** Chakrabarty (2019), *A Data Mining Approach to Flight Arrival Delay Prediction for American Airlines.*

https://arxiv.org/abs/1903.06740

**Industry Report:** Cirium, *2025 On-Time Performance Review.*

https://www.cirium.com/thoughtcloud/most-on-time-airlines-airports-2025-revealed-cirium/

**Consultancy Report:** McKinsey & Company, *How to Modernize Airline Planning.*

https://www.mckinsey.com/industries/travel/our-insights/how-to-modernize-airline-planning

**News Article:** Reuters (2025), *American Airlines Says Technology Issue Affecting Some Systems.*

https://www.reuters.com/business/american-airlines-says-technology-issue-affecting-some-systems-2025-06-27/

---

**Disclaimer:** This is an independent academic capstone project using publicly available data. It is not affiliated with American Airlines. Model results and operational benefits have not yet been established.
