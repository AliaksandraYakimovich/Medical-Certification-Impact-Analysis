# <b>Medical-Certification-Impact-Analysis</b>

### <b>Project Overview</b>

This project evaluates the impact of two controversial reforms implemented by a medical specialty board in 1990. The goal of the reforms was to enhance the quality of patient care by:

Increasing Certification Stringency: Adding a human-administered oral interview to the initial exam.

Continuous Evaluation: Replacing lifetime certification with a mandatory Maintenance-of-Certification (MOC) exam every five years.

As a consultant, I analyzed historical data (1970–2002) to determine if these changes successfully improved physician adherence to clinical guidelines or if they merely added an unnecessary burden to medical professionals.

### <b>Key Questions</b>

The analysis focuses on answering the following:
* **Pre-1990 Baseline: Did the initial certification exam effectively distinguish between high- and low-performing physicians before the reforms?**
* **Impact of Stringency: Did the 1990 changes make the certification process harder to pass on the first attempt?**
* **MOC Effectiveness: Did the introduction of 5-year re-evaluations improve or stabilize adherence to clinical guidelines over a physician's career?**
* **Policy Justification: Were physicians' complaints about the increased burden justified, or did the board achieve its goal of increasing the quality of care?**

## <b>Key Insights</b>

* **MOC Effectiveness Confirmed:** The "sawtooth" pattern in the line chart proves that mandatory Maintenance-of-Certification (MOC) exams successfully mitigate knowledge decay. Performance dips as physicians approach the 5-year mark, followed by a significant rebound immediately after recertification.
* **Higher Standard, Lower Pass Rate:** Following the introduction of the oral exam (Pre-1990 vs Post-1990), the "Modern Pass Rate" dropped to **65.93%**, compared to the historical **94.86%**. This confirms the certification process became significantly more stringent.
* **Validation of Reform:** While the new exams are difficult, they effectively filter for quality. Post-1990, even those who initially struggle to pass maintain a high average adherence score (~69), suggesting the reforms successfully removed "low quality" from the practice.
* **Valid Proxy:** Passing the exam on the first attempt was a valid proxy for quality, with a consistent 10-point gap in adherence before 1990.

<img width="1276" height="716" alt="bi_report" src="https://github.com/user-attachments/assets/23886ea2-b26a-44a1-acfd-3e3162ad1891" />


### <b>Data Description</b>

The analysis is based on two primary datasets:

* **Physician Background: Contains residency completion years and board certification years for all physicians certified between 1970 and 2002.**

* **Adherence Evaluations: Annual performance scores (0–100 scale) monitoring how closely physicians' practices align with endorsed clinical guidelines.**

* **Proxy for Success: Based on historical data, physicians obtaining certification in the same year they completed residency are identified as having passed on their first attempt. Those certified in later years are identified as retakers.**


### <b>Tech Stack</b>

* **Python (Pandas, NumPy): Used for data cleaning, melting "wide" format evaluations into "long" tidy data, and feature engineering (e.g., calculating years since certification).**

* **Matplotlib/Seaborn: Used for initial exploratory data analysis and identifying the "sawtooth" pattern in performance.**

* **Power BI: Used to create the final interactive dashboard, utilizing DAX (Data Analysis Expressions) to calculate historical vs. modern pass rates and performance trends.**


