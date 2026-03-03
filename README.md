# Medical-Certification-Changes-Analysis

### Project Overview

This project evaluates the impact of two controversial reforms implemented by a medical specialty board in 1990. The goal of the reforms was to enhance the quality of patient care by:

Increasing Certification Stringency: Adding a human-administered oral interview to the initial exam.

Continuous Evaluation: Replacing lifetime certification with a mandatory Maintenance-of-Certification (MOC) exam every five years.

As a consultant, I analyzed historical data (1970–2002) to determine if these changes successfully improved physician adherence to clinical guidelines or if they merely added an unnecessary burden to medical professionals.

### Key Questions

The analysis focuses on answering the following:
* **Pre-1990 Baseline: Did the initial certification exam effectively distinguish between high- and low-performing physicians before the reforms?**
* **Impact of Stringency: Did the 1990 changes make the certification process harder to pass on the first attempt?**
* **MOC Effectiveness: Did the introduction of 5-year re-evaluations improve or stabilize adherence to clinical guidelines over a physician's career?**
* **Policy Justification: Were physicians' complaints about the increased burden justified, or did the board achieve its goal of increasing the quality of care?**


### Data Description

The analysis is based on two primary datasets:

* **Physician Background: Contains residency completion years and board certification years for all physicians certified between 1970 and 2002.**

* **Adherence Evaluations: Annual performance scores (0–100 scale) monitoring how closely physicians' practices align with endorsed clinical guidelines.**

* **Proxy for Success: Based on historical data, physicians obtaining certification in the same year they completed residency are identified as having passed on their first attempt. Those certified in later years are identified as retakers.**


### Tech Stack

* **Python (Pandas, NumPy): Used for data cleaning, melting "wide" format evaluations into "long" tidy data, and feature engineering (e.g., calculating years since certification).**

* **Matplotlib/Seaborn: Used for initial exploratory data analysis and identifying the "sawtooth" pattern in performance.**

* **Power BI: Used to create the final interactive dashboard, utilizing DAX (Data Analysis Expressions) to calculate historical vs. modern pass rates and performance trends.**

![Medical_powerbi](https://github.com/user-attachments/assets/28aa2885-9f6a-4ac8-9cd1-f20d333ae880)
