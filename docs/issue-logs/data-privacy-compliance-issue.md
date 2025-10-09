# Data Privacy Compliance Issue

## Priority
High

## Assigned To
- Software Engineer
- Legal Analyst

## Reported By
Reported by the Legal Analyst whilst reviewing the backend data handling process to ensure compliance with Australian Privacy Principles.

## Date Reported
9/18/2025 10:34

## Date Resloved
9/22/2025 14:00

## Description
Sensitive personal data stored in the production database without encryption at rest.

## Comments
- Issue is identified: Found during backend validation under Work Package 3.1.3.1 – Develop Service Backend. 
- Analysis is done: Legal Analyst reviewed compliance against APP 11 (Data Security) and identified a breach risk. 
- Decision is made: On 18 Sep 12:00 Project Manager, Legal Analyst and Software Engineer decided to apply AES-256 encryption and restrict access. 
- Result is documented: Security update recorded in Jira (linked to WP 3.1.3.1). 

## Resolution
Encryption implemented and validated through Snyk security scan (0 critical vulnerabilities).
