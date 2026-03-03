# BOOTCAMP-EDA-STUDY
## EDA STUDY FROM BOOTCAMP CLASS (GROUP 5)
## Onat, Minseo and Mauurya worked on this

**Task Overview**

We were given loan application data from a consumer finance company and tasked with using EDA to identify patterns that indicate a client's likelihood of defaulting. The goal was to help the company make smarter lending decisions — approving reliable borrowers while flagging or adjusting terms for riskier ones.

We worked across two datasets: `application_data.csv` for current applicant profiles and `previous_application.csv` for historical loan behaviour.

---

**Key Findings**

**From Application Data (Current Applicants)**
- Lower education and higher region ratings are the strongest demographic predictors of default
- Unemployed and maternity leave applicants default at dramatically higher rates (35–40%), while pensioners and state servants are among the safest
- Owning a car, but not necessarily property, is associated with a meaningfully lower default rate

**From Previous Application Data (Historical Behaviour)**
- Cash loan applicants historically receive 9–13% more credit than they apply for, regardless of yield group — this upselling increases repayment burden and may contribute to future default
- Consumer loans are treated more cautiously by the bank, with most yield groups receiving less than requested, suggesting the bank already perceives higher risk in this segment
- Application volume peaks sharply between 10am and 12pm, with Saturday at 11 am being the single busiest slot — high-volume windows may warrant additional review scrutiny to avoid rushed approvals
