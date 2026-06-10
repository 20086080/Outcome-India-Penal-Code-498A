# Outcome-India-Penal-Code-498A
## Project Overview

This Power BI dashboard analyses the judicial outcomes of cases registered under Section 498A of the Indian Penal Code (IPC), which addresses cruelty by a husband or his relatives towards a married woman.

Section 498A cases represent one of the largest categories of crimes recorded against women in India and have been the subject of significant public, legal, and academic debate. Questions are frequently raised regarding conviction rates, acquittals, case pendency, trial duration, and the broader impact of prolonged legal proceedings on families.

Using National Crime Records Bureau (NCRB) data, this dashboard provides a longitudinal analysis of case registrations, court outcomes, conviction trends, acquittal rates, and pending trials to help users better understand how these cases progress through the criminal justice system.

## Problem Statement

Section 498A cases occupy a unique position within India's criminal justice system due to their volume, social significance, and potential impact on family relationships. While the law was introduced to protect women from cruelty and domestic abuse, concerns have also been raised regarding lengthy investigations, prolonged trials, low conviction rates, and the consequences of unresolved cases for both complainants and accused persons.

This project seeks to explore the available NCRB data to answer key questions such as:

How have Section 498A case volumes changed over time?
What proportion of cases result in conviction, acquittal, or other outcomes?
Are judicial backlogs increasing or decreasing?
How long do cases remain within the justice system?
What trends can be observed across states and over multiple years?

The objective is not to determine guilt, innocence, or the prevalence of false complaints, but rather to provide a data-driven view of how Section 498A cases move through the criminal justice process and what outcomes are ultimately recorded.

## Tools Used

- Power BI
- Excel
- DAX

## Business Questions Answered

### Core Business Questions

- How have crime trends changed over time?
- What are the conviction rates?
- How large is the trial backlog?
- What proportion of cases remain pending?
- How effective is the criminal justice system at disposing of IPC 498-A cases?
- Are case disposal rates improving or declining over time?
- How do new cases compare with resolved cases each year?
- Is the backlog growing faster than cases are being resolved?

### Judicial Outcome Questions

- What are the most common outcomes of IPC 498-A cases?
- What proportion of cases result in conviction versus acquittal?
- How frequently are cases withdrawn, compromised, or discharged?
- How many cases are disposed of without proceeding to trial?
- Has the conviction rate changed over time?
= Have acquittal rates increased or decreased over time?

### Trial Efficiency Questions

- How long do IPC 498-A cases remain in the judicial system?
- What percentage of cases exceed one year in duration?
- Are trial completion rates improving over time?
- Is the proportion of cases disposed without trial increasing or decreasing?

### Trend and Performance Questions

- What year-on-year changes are occurring in case registrations?
- What year-on-year changes are occurring in trial completions?
- What year-on-year changes are occurring in case disposals?
- Are improvements in case disposal keeping pace with incoming caseloads?
- Which years demonstrate the strongest or weakest judicial performance?

### Policy and Governance Questions

- Does the data indicate a persistent backlog problem within IPC 498-A cases?
- Are judicial outcomes dominated by convictions, acquittals, or non-trial resolutions?
- Do observed trends suggest increasing efficiency or continuing pressure on the justice system?
- What evidence exists to support policy interventions aimed at reducing case backlogs and trial duration?

## Data Source

National Crime Records Bureau (NCRB)

## Challenges & Limitations

### Data Discovery and Extraction

The National Crime Records Bureau (NCRB) publishes its annual reports as large documents containing hundreds of statistical tables. Each report includes more than 300 tables covering a wide range of crime categories, judicial outcomes, and administrative statistics.

One of the primary challenges of this project was identifying and extracting the specific tables relevant to IPC Section 498A (Cruelty by Husband or Relatives). This required a detailed review of multiple annual reports to locate consistent data sources, verify definitions, and ensure that comparable metrics were collected across all years included in the analysis.

This data discovery process represented a significant portion of the project effort before cleaning, modelling, and dashboard development could begin.

### Data Preparation and Longitudinal Analysis

The dashboard analyses more than two decades of NCRB data. During data preparation, several structural differences between annual reports required standardisation before meaningful trend analysis could be performed.

Maintaining consistency across years required careful validation of definitions, calculations, and reporting categories to ensure comparability over time. Particular attention was given to ensuring that trends reflected genuine changes in reported outcomes rather than differences in reporting formats or data structures.

### Dashboard Design and Dynamic Insights

Presenting complex judicial statistics in an accessible format required balancing analytical depth with usability. Particular attention was given to visual clarity, trend identification, and the communication of key findings through interactive visualisations.

An additional challenge was the development of dynamic DAX-driven narrative insights that automatically update based on user selections while remaining concise, readable, and analytically meaningful.

### Dataset Limitations

NCRB data reports judicial outcomes such as convictions, acquittals, discharges, and pending cases. However, the dataset does not directly identify whether a complaint was genuine, false, malicious, or withdrawn. As a result, the dashboard focuses on recorded judicial outcomes rather than attempting to infer case validity.

The NCRB dataset also provides annual snapshots rather than individual case histories. This limits the ability to measure exact trial durations for specific cases and instead requires the use of aggregate indicators such as pending investigations and pending trials when analysing case progression through the justice system.

### Geographic Granularity

The NCRB dataset does not provide IPC Section 498A judicial outcomes at a sufficiently granular geographic level. While state-level case registration statistics are available, detailed outcome measures such as convictions, acquittals, discharges, and pending trials are not consistently reported by state, district, or metropolitan versus non-metropolitan regions.

As a result, this analysis is limited to national-level trends and cannot determine whether judicial outcomes differ across states, regions, or levels of urbanisation. Such differences may exist due to variations in demographics, socio-economic conditions, legal practices, reporting behaviour, education levels, or cultural factors, but these relationships cannot be evaluated using the available NCRB data.

Consequently, the findings presented in this dashboard should be interpreted as national trends rather than evidence of patterns within specific geographic or cultural groups.

## Key Insights

(To be completed)

## Dashboard Preview

(To be completed)

## Author

Monisha Sikka
