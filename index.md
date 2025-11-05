## Portfolio

---

### Projects

# Predicting Arteriovenous Fistula Failure in Hemodialysis Patients
<img src="images/AVF_FAILURE_RISK_DASHBOARD.png?raw=true"/>

This machine learning system predicts arteriovenous fistula failure in dialysis patients 30 treatments in advance, enabling proactive clinical intervention. Built with Python and Random Forest classifier, achieving 90% AUC-ROC and 88% recall. The interactive Streamlit dashboard demonstrates how clinicians would monitor high-risk patients, view hemodynamic trends, and prioritize interventions. Developed using clinically realistic synthetic data (156K treatment records) with feature engineering capturing temporal patterns in blood flow, venous pressure, and dialysis adequacy metrics. Projected impact: ~$1M in avoided emergency costs per 1,000 patients annually through early detection and preventive treatment.

[Live Demo](https://avf-failure-prediction.streamlit.app/)

[View Code](https://github.com/jasonodom44/avf_failure_prediction)

# Credit Risk Modeling - Predicting Loan Defaults

Built XGBoost classifier on 1.35 million Lending Club loans achieving 0.72 AUC-ROC and 53% recall, enabling banks to proactively identify high-risk borrowers before default. Optimized decision threshold from 0.5 to 0.25 using precision-recall analysis, balancing false negatives (missed defaults = direct loss) versus false positives (rejected good loans = opportunity cost). Model's top predictors (loan grade, interest rate, debt ratios) align with financial domain knowledge, validating it learned actual risk factors rather than spurious correlations. Projected impact: $238M in avoided losses annually for a $500M loan portfolio through early intervention.

[View Code](https://github.com/jasonodom44/credit-risk-modeling)

# Payroll Automation for Mental Health Facility with Google Sheets/Apps Script
<img src="images/Bookkeeping.jpg?raw=true"/>

This Google Sheets-based payroll automation system streamlines compensation calculations and reporting for clinicians at a mental health facility.  Using Google Apps Script, it automates data import from Simple Practice, calculates clinician payments based on factors like weight class and payment source, generates personalized pay reports, and automates email delivery. The system improves efficiency, transparency, and scalability, reducing payroll processing time from hours to minutes.

[Medium Link](https://medium.com/@jasonodom44/automating-payroll-processing-for-a-mental-health-clinic-5f4742cde1e4)
