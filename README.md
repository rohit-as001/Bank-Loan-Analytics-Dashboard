# Bank Loan Analytics Dashboard
### This is Bank Loan Analytics projects


_"Behind Every Loan Application is a Risk, an Opportunity, and a Decision. Make It the Right One."_


## Project Overview
The Bank Loan Analytics Dashboard is a comprehensive data analytics project designed to analyze loan applications, lending performance, borrower behavior, repayment trends, and credit risk using Power BI and Excel.

The objective of this project is to help financial institutions monitor loan portfolio health, identify high-risk lending segments, optimize loan approval strategies, and improve overall financial decision-making through interactive business intelligence dashboards.

Together, these views give banking leadership a 360° picture of their loan portfolio health — from origination to repayment — with the granularity to act on both macro trends and individual risk segments.

This dashboard provides detailed insights into:
- Loan application trends
- Funded vs received loan amounts
- Good loans vs bad loans
- Interest rate analysis
- Debt-to-Income (DTI) ratio analysis
- Loan purpose segmentation
- Home ownership analysis
- State-wise loan applications
- Loan term distribution

The report enables management to evaluate lending performance, assess repayment behavior, reduce credit risk exposure, and improve portfolio profitability.



## Key Metrics Included
  - Total Loan Applications: 38,576
  - Total Funded Amount: $435.8 Million
  - Total Received Amount: $473.1 Million
  - Average Interest Rate: 12.05%
  - Average DTI Ratio: 13.33%
  - Good Loans (% of Total): 86.18% — 33,243 applications
  - Bad Loans (% of Total): 13.82% — 5,333 applications
  - Loan Terms Available: 36 months & 60 months
  - Top Loan Purpose: Debt Consolidation (18.2K applications)
  - Top State by Applications: California (6,894)


 

# Key Insights
1) Portfolio Surplus — Received Exceeds Funded by $37.3M
    - The bank has **funded $435.8M** in loans but **received back $473.1M** — a surplus of **$37.3 Million** representing interest income and fee recovery above principal.
    - This positive spread confirms the portfolio is **generating net revenue**, not just recycling capital.
    - However, the bad loan segment tells the opposite story: **$65.5M was funded to bad loan borrowers, but only $37.3M was recovered** — a net loss of **$28.2M on the bad loan book** alone.
    - **Actionable**: The $28.2M bad loan deficit should be the single most closely watched financial metric. Reducing bad loan exposure by even 2–3 percentage points would translate directly into tens of millions in recovered capital.


2) Bad Loan Exposure — 13.82% is a Red Flag
    - At **13.82% (5,333 loans)**, the bad loan rate represents a material credit risk concentration.
    - Industry benchmark for acceptable non-performing loan (NPL) ratios typically sits between **2–5%** for well-managed retail lending portfolios.
    - The bank's 13.82% rate is **roughly 3x the upper end of healthy benchmarks** — a clear signal that underwriting standards, borrower screening, or collection processes need structural review.
    - Bad loans collectively represent **$65.5M in funded capital** against only **$37.3M recovered** — a recovery rate of approximately **56.9%**, meaning the bank recovers less than **57** cents for every dollar lent to bad borrowers.
    - **Actionable**: Immediate credit policy review is warranted. The bad loan cohort should be analyzed by purpose, state, term length, DTI ratio, and interest rate band to identify the highest-risk approval patterns.


3) Loan Applications — Consistent Monthly Growth Trajectory
    - Applications grew steadily from **2,300 in January** to **4,300 in December** — nearly **doubling** over the course of the year.
    - This upward trajectory indicates strong and growing demand for credit, reflecting either successful marketing, economic conditions driving borrowing needs, or expanded product reach.
    - The growth is **linear and consistent** with no sharp spikes — suggesting organic, sustainable demand growth rather than a campaign-driven or seasonal burst.
    - **Actionable**: With volume nearly doubling year-over-year, the bank must ensure that **underwriting capacity scales proportionally** with application volume. Processing backlogs or staff shortages during peak months could force faster, lower-quality credit decisions — the exact environment where bad loan rates rise.


4) Geographic Concentration — California Dominates, Top 3 States = 33% of Volume
    - **California leads with 6,894 applications**, followed by New York (3,701) and Florida (2,773).
    - The top 3 states account for approximately **34% of all applications** — a significant geographic concentration risk.
    - States like **Georgia (1,355) and Massachusetts (1,310)** represent underpenetrated markets with growth potential.
    - **Actionable**: Geographic concentration in CA, NY, and FL means the portfolio is disproportionately exposed to economic shocks in these states (housing market downturns, job market shifts, regulatory changes). A deliberate **geographic diversification strategy** targeting mid-tier states would reduce systemic risk.


5) Loan Purpose — Debt Consolidation is Overwhelming Primary Driver
    - **Debt Consolidation alone accounts for nearly 47% of all applications** — meaning almost half the loan book is being used by borrowers to pay off existing debts, not invest in assets or generate income.
    - This is a significant risk signal: borrowers using new credit to manage existing debt obligations are inherently **higher-risk profiles** with elevated default probability.
    - **Actionable**: The bank should analyze the **bad loan rate specifically within the Debt Consolidation segment** to determine whether this category is disproportionately contributing to the 13.82% bad loan rate. If so, stricter underwriting criteria or lower credit limits for debt consolidation purposes should be considered.


6) Home Ownership — Renters are the Largest Borrower Segment
    - By home ownership status: **RENT (18,439) > MORTGAGE (17,198) > OWN (2,838)** — renters are the single largest group.
    - Renters — who lack property equity as collateral security — represent a **higher-risk borrower cohort** by conventional lending standards.
    - Mortgage holders (17,198) represent nearly as large a segment and typically indicate more stable, creditworthy borrowers with established repayment histories.
    - **Actionable**: Cross-reference home ownership status with bad loan rates. If renter bad loan rates significantly exceed mortgage-holder rates, the bank may need to apply differentiated interest rates, lower credit limits, or additional income verification requirements for renter applicants.


7) Loan Term — 60-Month Term Dominates at ~73%
    - **60-month (5-year) loans: 28,200 applications (~73%)** vs **36-month loans: 10,300 (~27%).**
    - The heavy preference for longer-term loans indicates borrowers are prioritizing **lower monthly payments over total interest cost** — a pattern associated with borrowers who are already stretched financially.
    - Longer loan terms also mean **the bank's capital is locked for longer**, increasing exposure to economic cycle changes and borrower circumstance shifts over the repayment period.
    - **Actionable**: The bank should monitor bad loan rates by term length. If 60-month loans underperform 36-month loans in recovery rate (which is typical), **offering interest rate incentives for 36-month terms** could improve portfolio quality while reducing long-duration risk.

          

# Business Recommendations (Recommendations for Management)
  - **Strengthen Risk Controls**: Tighten credit checks for high‑DTI borrowers and loans with higher interest rates.
  - **Focus on Debt Consolidation**: Optimize offerings in debt consolidation, the largest loan category, while monitoring repayment behavior.
  - **Improve Recovery Strategies**: Enhance collection processes for charged-off loans to reduce financial losses.
  - **Geographic Targeting**: Expand lending in high‑volume states (CA, NY, FL) with tailored risk models.
  - **Loan Term Optimization**: Promote shorter loan terms (36 months) to reduce long-term risk exposure.
  - **Customer Segmentation**: Use analytics to identify borrower profiles most likely to repay, improving portfolio quality.


1) Priority 1 — Conduct an Urgent Bad Loan Root Cause Analysis
    - At 13.82%, the bad loan rate is dangerously above industry benchmarks. Management must immediately segment the 5,333 bad loans by: loan purpose, state, home ownership status, term length, DTI band, and interest rate tier. This analysis will reveal whether bad loans are concentrated in a specific approval pattern — enabling a targeted policy fix rather than blanket credit tightening that could suppress good loan volume.

2) Priority 2 — Tighten Underwriting for Debt Consolidation Applications
    - With Debt Consolidation representing ~47% of applications and being inherently higher-risk, the bank must apply stricter credit controls to this segment. Recommended measures: lower maximum loan amounts for pure debt consolidation purposes, require verified income documentation (not self-reported), apply a minimum credit score threshold 10–15 points above the standard floor, and implement a maximum DTI cap specifically for this purpose category.

3) Priority 3 — Introduce DTI-Based Risk Tiering
    - The data confirms DTI ratio is a meaningful predictor of repayment outcomes (Fully Paid avg DTI: 13.17% vs Charged Off avg DTI: 14.00%). The bank should formalize DTI-based risk tiers: low risk (DTI <10%), moderate risk (10–15%), elevated risk (15–20%), and high risk (>20%), with differentiated interest rates, credit limits, and collateral requirements for each tier. This makes risk pricing explicit and data-driven.

4) Priority 4 — Scale Underwriting Operations to Match Application Growth
    - Applications nearly doubled from January to December. Without proportional growth in underwriting team capacity, credit review quality will degrade under volume pressure — historically a leading indicator of rising bad loan rates. Management should assess whether current staff headcount, technology infrastructure, and decision timelines are adequate for 4,000+ applications per month and build a hiring or automation plan accordingly.

5) Priority 5 — Develop a Geographic Diversification Strategy
    - With ~34% of applications concentrated in just 3 states (CA, NY, FL), the portfolio carries meaningful geographic risk. The bank should design targeted marketing campaigns for underrepresented but creditworthy markets — states like Georgia, Massachusetts, Virginia, and Pennsylvania already show meaningful application volumes and could be developed with focused outreach, local partnerships, and digital lending channel expansion.

6) Priority 6 — Reassess 60-Month Loan Term Incentive Structure
    - The 73% preference for 60-month terms increases long-duration risk and likely correlates with higher default rates. Introduce a structured interest rate differential that makes 36-month loans meaningfully more attractive (e.g., 50–75 basis points lower rate), and model the revenue impact. Even shifting 15% of 60-month applicants to 36-month terms would materially reduce portfolio duration risk.

7) Priority 7 — Build a Renter-Specific Risk Framework
    - Renters (18,439 applications) outnumber mortgage holders (17,198) and own-home borrowers (2,838 combined). Without property equity as implicit collateral, renter loans carry higher unsecured risk. The bank should analyze renter vs. mortgage-holder default rates and, if the gap is significant, introduce rent-to-income verification requirements, lower maximum loan amounts, or mandatory savings account opening as a commitment signal for renter applicants.

8) Priority 8 — Leverage the $37.3M Portfolio Surplus for Risk Reserve Building
    - The portfolio generates a $37.3M surplus of received over funded amounts. Rather than treating this entirely as profit, management should allocate a portion — aligned with the bad loan rate — into a formal loan loss reserve fund. This builds a financial buffer against future charge-offs, demonstrates prudent risk management to regulators, and reduces earnings volatility during economic downturns.


# Business Value
This dashboard enables banking management to:
- **Monitor portfolio health in real time** — good loan vs. bad loan split, funded vs. recovered amounts
- **Identify credit risk concentration** by purpose, geography, term, and borrower profile
- **Benchmark DTI and interest rate thresholds** against actual default outcomes
- **Track application demand trends** to align underwriting capacity with volume growth
- **Present loan portfolio performance** to board members, regulators, and investors with visual clarity
- **Support credit policy decisions** with data-backed evidence rather than intuition



## Tools & Technologies
- Visualization Tool: Power BI/Excel
- Dataset: Bank Loan Analytics Data
- Data Cleaning & Transformation
- Domain: Banking and Financial Services
- Data Modeling
- KPI Calculation & Measures
- Dual-View Navigation: Summary + Overview toggle buttons for two-page dashboard experience
- KPI Header Cards: Top-line financial metrics — Total Applications, Funded, Received, Interest Rate, DTI



# Why This Project Matters
Bank loan portfolios are the backbone of financial institutions. By analyzing loan applications, repayment behavior, interest rates, and borrower demographics, this project equips management with actionable insights to reduce credit risk, optimize lending strategies, and strengthen financial performance.



## Conclusion
The Bank Loan Analytics Dashboard provides a comprehensive analysis of lending operations, borrower behavior, portfolio quality, and financial performance through interactive business intelligence reporting. The analysis reveals that the institution maintains a strong loan portfolio with over 86% good loans and healthy repayment performance, indicating effective credit risk management practices. Insights from loan purposes, repayment trends, interest rates, and DTI ratios help management identify high-demand lending segments and monitor potential financial risks. The dashboard also highlights the importance of focusing on high-performing markets, improving borrower screening processes, and proactively managing high-risk accounts. By leveraging data-driven insights, financial institutions can optimize loan approval strategies, reduce default rates, improve profitability, and enhance overall portfolio stability. This project demonstrates how analytics can support smarter financial decision-making and strengthen long-term lending performance.


_Good lending isn't about saying yes more — it's about saying yes to the right people, with the right data, at the right time.
_
