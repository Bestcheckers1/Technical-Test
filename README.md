# Technical-Test
Analysis of Agent Self-Assessment Program

This Jupyter Notebook, Technical Test - Business Analyst.ipynb, contains a statistical analysis of a new agent self-assessment program. The primary goal is to test the hypothesis that encouraging agents to be more self-aware of their behaviors will lead to an improvement in their CSAT (Customer Satisfaction) scores.

Analysis Objectives
The notebook is structured around five key objectives, with a final section for conclusions and recommendations:

Impact Assessment: Compares CSAT scores before and after the self-assessment form was introduced on March 8, 2024. It uses a Mann-Whitney U test to determine if there's a significant difference.

Behavioral Trends: Analyzes whether there's a positive trend in agent self-audit scores over time. This is done using a regression analysis.

Tenure vs. Proficiency: Investigates the relationship between an agent's tenure and their self-audit scores using a Spearman correlation.

Self-Perception vs. Reality: Assesses how well agents' self-perceived CSAT scores correlate with the actual CSAT scores they receive.

Pre vs. Post Comparison: A direct statistical comparison of CSAT performance before and after the form's introduction.

Recommendations: Based on the statistical findings, this section provides actionable recommendations to improve agent performance.

Key Findings
The analysis reveals that the self-assessment program in its current form is not effectively driving agent improvement. The core issue is a significant disconnect between what agents perceive as good performance and the actual CSAT scores from customers.

How to Use
To run this notebook, ensure you have the necessary Python libraries installed, including pandas, numpy, scipy, matplotlib, seaborn, and statsmodels. The notebook should be in the same directory as the csat_data.csv and self_audit_data.csv files. You can execute each cell sequentially to reproduce the analysis.
