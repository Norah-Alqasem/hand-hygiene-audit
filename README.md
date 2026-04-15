#  Hand Hygiene Compliance Analytics & Automated ETL Pipeline

![Infection Control](https://img.shields.io/badge/Domain-Infection%20Control-blue)
![Data Analytics](https://img.shields.io/badge/Focus-Data%20Analytics%20%26%20BI-success)
![Automated Workflow](https://img.shields.io/badge/Status-Fully%20Automated-brightgreen)

##  Project Overview
The **Hand Hygiene Audit System** is an end-to-end automated data solution designed to monitor, track, and analyze hand hygiene compliance within healthcare facilities. In the realm of Infection Control, accurate and timely data is critical for patient safety. 

This repository highlights the **Data Analytics, ETL architecture, and Business Intelligence** aspects of the project, built in collaboration with [@Manar501](https://github.com/Manar501). It showcases how raw observational data is automatically extracted, transformed, and loaded into an interactive Power BI dashboard to empower healthcare professionals with real-time, actionable insights.

##  System Architecture & Workflow

To eliminate manual data entry and reduce reporting delays, we implemented a robust, fully automated workflow:

1. **Data Collection:** Infection control practitioners record daily observations via customized mobile forms.
2. **Automated ETL Pipeline:** A scheduled Python script securely connects to the data source API, extracts the latest records, cleans the data, and standardizes it using `pandas`.
3. **Data Modeling & Visualization:** The cleaned dataset is ingested into Power BI, where custom DAX measures calculate critical compliance KPIs, categorized by worker types and hospital departments.
4. **Automated Refresh:** The entire system runs on a schedule, ensuring decision-makers always have access to the latest compliance metrics without any manual intervention.

##  Key Features & Analytics
* **Compliance KPIs:** Dynamic calculation of hand hygiene compliance rates based on WHO guidelines.
* **Granular Filtering:** Interactive Power BI dashboards allowing users to drill down by department, role (e.g., Physician, Nurse), and specific hand hygiene moments.
* **Worker Type Categorization:** Automated mapping of unstructured job titles into standardized healthcare worker categories using Power Query.
* **Zero-Touch Automation:** Daily script execution using Windows Task Scheduler integrated with Power BI Gateway for seamless online updates.

##  Tools and Technology

| Tool | Purpose |
| :--- | :--- |
| **SmartSheet** | Data collection — mobile forms with dropdown validation |
| **SmartSheet API** | Automated data extraction via Python |
| **Python 3.13** | ETL script — extraction, cleaning, transformation |
| **pandas** | Data manipulation and transformation library |
| **Power BI Desktop** | Dashboard design, DAX measures, Power Query transformations |
| **Power BI Service** | Online dashboard publishing and sharing |
| **Power BI Gateway** | Automated scheduled refresh |
| **Power Query** | Worker type categorization and data shaping |
| **DAX** | Custom measures for compliance KPIs and dynamic filtering |
| **Windows Task Scheduler** | Daily automated script execution |
| **GitHub** | Version control and project documentation |

##  Collaboration & Main Repository
This analytical pipeline is part of a broader collaborative effort to digitize healthcare quality metrics. 
🔗 **You can view the main project repository and my colleague's contributions here:** [Hand Hygiene Audit by Manar501](https://github.com/Manar501/hand-hygiene-audit)

## Authors
- **Manar** — [GitHub Profile](https://github.com/Manar501)
- **Norah** — [GitHub Profile](https://github.com/Norah-Alqasem)

---

## Links
- **Power BI Dashboard**: [View the live dashboard](https://seuedu-my.sharepoint.com/personal/s200088111_seu_edu_sa/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fs200088111_seu_edu_sa%2FDocuments%2FHH%20Report.pbix&parent=%2Fpersonal%2Fs200088111_seu_edu_sa%2FDocuments&ga=1)
