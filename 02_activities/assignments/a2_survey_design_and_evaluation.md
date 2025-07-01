# Assignment: Questionnaire Design and Sample Evaluation

## Requirements

The goal of this assignment is to practice developing and evaluating sampling materials.

### Part A - Survey Design:

Select one of the scenarios below and design a survey to meet the need(s) outlined in the prompt.

1.	In two to three sentences, describe the purpose of your survey
2.	Describe your target population, sampling frame, sampling units, and overall sampling strategy.
3.	Write a 5-10 question survey to address your chosen scenario below.

##### Scenarios
1.	You work in the Human Resources Department at a large tech company. Over the past few months, the company has been experiencing a high turnover rate across many of its departments, specifically within the entry- and lower-level positions. The company wishes to understand why this turnover is happening, and what changes need to occur to improve employee satisfaction.
2.	You work for a Canadian national political party during a federal election. Throughout the campaign period, your party has seen relatively high approval ratings, but an opposing party is also polling favorably and may still have a chance to win the election. You are one month away from the election and you want to understand what voters want from your party and its leader in order to maintain your lead and eventually win the election.
3.	You are a student researcher in the sociology department at the University of Toronto. You are working on a research project that concerns the relationship between music taste and age. This involves both comparisons between different people of different ages and comparisons of the same individual at different ages during their lifetime. You wish to understand to what extent age influences music taste, specifically as it relates to perceptions of popular music. Your results will be written into an academic paper that you hope to publish.

### Part B - Survey Evaluation:

For the **Canadian General Social Survey on Giving, Volunteering, and Participating, 2018 (cycle 33)**, conducted by Statistics Canada find any and all available documentation for the data gathered and identify and describe the survey features indicated below.

1. Sample type: Multi-stage stratified (two-phase)
2. Sample size: 80,000 individuals (60,000 regular sample, 20,000 oversample)
3. Target population: All persons 15 years of age and older in Canada, excluding residents of the Yukon, Northwest Territories, and Nunavut, full-time residents of institutions, and residents of First Nations reserves
4. Sampling frame: From the first phase, 1 household out of four (systematically selected across Canada).  
5. Survey mode(s): electronic questionnaire (EQ) or computer assisted telephone interviewing (CATI) 
6. Timeline: 2023-09-15 to 2024-03-30
7. Response rate: 40.9% (42.2% for regular sample and 37.1% for oversample)
8. Weights: To adjust for the "rejecting" of a proportion of respondents that are not volunteers, the person weight for respondents that are not 'rejected' and not volunteers is multiplied by an undisclosed factor. For the rest, weights were adjusted so that weighted income distribution of matched the 2022 Canadian Income Survey distribution by province (WGHT_PER). Bootstrap weights were also created.
9. Data processing: Used the Social Survey Processing Environment (SSPE). Edits were performed automatically and manually at various stages, including data verification and flow edits.
10. Cleaning, imputation, etc: For records w/ missing or incorrect information, in a small # of cases, head office completed, corrected deterministically, or imputed from other info on the questionnaire. For almost all cases, all imputations were made using donor imputation, which uses donor records selected through a score function to impute missing values. Recipient records (records with item or partial non-response) were matched with donor records based on shared characteristics, then the donor with the highest score filled in the missing info. If multiple donors had the highest score, one was randomly selected. Mean imputation was used as an alternative when donor imputation could not be used. Imputation was carried out in 4 blocks: 1) imputation of personal income and family income, 2) imputation of variables related to donations, 3) imputation of formal volunteering variables, and 4) imputation of informal volunteering variables
11. Sources of error: Common sources of non-sampling error are imperfect coverage nd non-response. 
12. Limitations, known biases, etc: Persons without good contact info represent a part of the target population that was excluded from the surveyed population - so to the extent that the excluded population differs from the rest of the target population, the results could be biased. Overall, much effort was taken to limit bias.
13. Link to documentation and any additional sources used: https://www23.statcan.gc.ca/imdb/p2SV.pl?Function=getSurvey&amp;SDDS=4430#a1


# Your Changes

## Part A - Survey Design: 

The number of your chosen topic: 1

Describe the purpose of your survey:
```
The purpose of my survey is to understand what is causing the high turnover rate across many of my company's departments, specifically  within the entry- and lower-level positions. I wish to understand why this turnover is happening, and what changes need to occur to improve employee satisfaction.
```

Describe your target population, sampling frame, sampling units, and observational units:
```
Target population: All current and recently-departed (within the last 1 year) employees in the company, across all departments, within entry- and lower-level positions
Sampling frame: HR database with first name, last name, address, and contact information for all individuals in the target population
Sampling units: Each individual employee
Observational units: Each individual employee (same as sampling unit in this csae)
```

Your 5-10 question survey:
```
1. How long did you work (or have been working) for the company? 
    - Less than 6 months
    - 6 months to 1 year
    - 1-2 years
    - 2-3 years
    - 3+ years
2. How satisfied were you with all facets of your employee experience during your time at the company?
    - Very satisfied
    - Satisfied
    - Neither satisfied nor dissatisfied
    - Disatisfied
    - Very dissatisfied
3. For previous employees: What was the primary reason you decided to leave your role? For current employees, what are the primary reasons you might consider leaving your role?
    - Compensation
    - Lack of career development opportunities
    - Work / life balance
    - Work culture / environment
    - Relationship with manager or peers
    - Other reasons (please specify)
4. How would you rate the effectiveness of your manager in supporting your career and development?
    - Excellent
    - Good
    - Fair
    - Poor
5. How satisfied were/are you with opportunities for career growth and advancement?
    - Very satisfied
    - Satisfied
    - Neither satisfied nor dissatisfied
    - Disatisfied
    - Very dissatisfied
6. To what extent did you feel valued and recognized for your contributions?
    - Always
    - Often
    - Sometimes
    - Rarely
    - Never
7. How fair and competitive did/do you find your compensation package?
    - Very fair
    - Somewhat fair
    - Neutral
    - Somewhat unfair
    - Very unfair
8. What changes do you think would most improve employee satisfaction and retention?
    - Open-ended
9. How likely are you to recommend this company as a good place to work to a friend?
    - Very likely
    - Somewhat likely
    - Neutral
    - Somewhat unlikely
    - Very unlikely
10. Any additional feedback you'd like to share?
    - Open-ended

## Part B - Survey Evaluation:

Identify and describe survey features:

```
1. Sample type: Stratified random sampling (current vs. former employees, by department)
2. Sample size: Aiming for 50% of all employees who have left in the past 12 months and 50% of all current employees
3. Target population: All employees in the entry- and lower-level positions across all departments in the company who are either currently employed there or have left the company within the last 12 months
4. Sampling frame: HR database containing first name, last name, employment status, employment duration / tenure, department, and contact information
5. Survey mode(s): Online questionnaire distributed by email, with an option to complete by phone upon request. For current employees, it will go to their work emails. For former employees, it will go to their personal email saved in the HR database
6. Timeline: 6 months
7. Response rate: Anticipated response rate of ~50%
8. Weights: If needed, post-stratification weights will be applied to adjust for responses from disgruntled employees, as well as differential non-response by employment status and department
9. Data processing: Data will be exported from the survey platform (likely Qualtrics or SurveyMonkey) into the analysis environment (Excel, statistical software). Responses will be checked for completeness and consistency.
10. Cleaning, imputation, etc.: Records with partial item non-response (e.g., skipped questions) will be flagged; if missing values are minimal, they will be imputed using mean or mode imputation within strata (current/former employees). Open-ended responses will be reviewed manually for categorization and redaction of identifying information.
11. Sources of error: Potential non-sampling errors include non-response bias, recall bias (particularly among former employees), and social desirability bias
12. Limitations, known biases, etc: Employees who left may differ systematically from those who are currently still employed at the company - their perspectives may not be fully comparable. Current employes may not be fully honest despite confidentiality assurances, due to fear of retribution or retaliation from the company. 
13. Link to documentation and any additional sources used: None
```

## Rubric

-	All required components are present and complete **Complete / Incomplete**
-	Choice of sampling strategy for Part A is justified and related to survey purpose **Complete / Incomplete**
-	Information for Part B is complete and correct **Complete / Incomplete**

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 29/06/2025`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (a2_survey_design_and_evaluation.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/sampling/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via the help channel in Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
