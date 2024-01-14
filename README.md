# Findings and Analysis

## Overview
This sample dataset is a survey record of a company collected anonymously.
The employees were asked to share their opinions on the diversity culture of
the company. Below are some of my observations.

## Analysis
I started my analysis by calculating a Top two box score for the company
overall, which turned out to be 72.32%. This indicates that more
than 70% of the employees perceive the company’s diversity culture positively. However, as we will see further in the report there are
improvements needed in some areas.

If we look at the score for each question asked we see the results below.

- Leadership makes an effort to create a space that is welcoming for all: 84.25%
- COMPANY as an organization values diversity: 83.90%
- Leadership understands diversity is critical to our future success: 78.77%
- I feel supported in my career growth and development at COMPANY: 78.77%
- I feel COMPANY respects my work and personal life balance: 73.29%
- I feel comfortable sharing all parts of my identity with my colleagues: 72.60%
- I feel comfortable to share my opinion without fear of negative consequences:
71.58%
- I feel my unique background and identity (i.e. my differences) are valued at
COMPANY: 70.89%
- COMPANY as an organization represents a diverse group of people (e.g., race,
gender identity, age, disability, sexual identity, education, religion, etc.): 70.21%
- People from all backgrounds and with a range of identities have equitable
opportunities to advance their careers at COMPANY: 67.47%
- The process for career advancement/promotion is transparent to all employees:
43.84%
  
1. The results indicate that more than half of the employees do not
feel that their career advancement/promotion is a transparent process.
Similarly, around 40% of employees do not perceive that the company
values diversity and people from all backgrounds have equitable
opportunities to progress in their careers. We will see more details on this in
our statistical test.
2. As you can see from the table women are less agreeable than
men overall in this survey. It's not a significant difference but it's still
something to take note of here.
3.In the Statistical test section, The task was to find
significant differences between the subgroups of Race/Ethnicity and
Roles. For the first part In my exploratory data analysis, I found that the
distribution of the roles and their responses was not normal and
therefore I decided to go for the Kruskal-Wallis test. The chi-square test is a
more popular option given the dataset with many categories and
fulfilling assumptions for the Kruskal-Wallis test. It was the best option.
Chi-square test of independence described in the previous response
can help determine if there's a significant association between the
employee's role and their responses. However, it doesn't directly
compare specific roles to each other.
In my test results, I did not find any statistically significant differences in
responses among the different roles for any of the questions. In all
cases, the p-value was greater than 0.05, which is the common
threshold for determining statistical significance. Therefore, we can not
reject the null hypothesis and assume there is little to no correlation
between different roles and their survey responses.
4. In the second part I tested subgroups of Ethnicity - White People vs
Indigenous and People of Color. Again I used the Kruskal-Wallis test for
this scenario.
Note: There is not enough data for Black people in the provided dataset,
therefore I decided to not include them in the test for a more accurate
results.
In many instances, the p-value less than 0.05 suggests a significant
difference between the groups. The smaller the p-value, the stronger
the evidence that we should reject the null hypothesis.
- "COMPANY as an organization values diversity": p = 0.00496
- "Leadership understands diversity is critical to our future success": p =
0.00242
- "I feel comfortable sharing all parts of my identity with my colleagues": p
= 0.0487
- "People from all backgrounds and with a range of identities have
equitable opportunities to advance their careers at COMPANY": p =
0.02607
According to these results, there is an indication that some employees with
certain backgrounds feel that the company doesn't value diversity, the leadership
does not fully understand the importance of diversity thus resulting in
preferential treatment to some.
5. Many employees do not feel comfortable sharing all parts of their
identity including their Sexual Identity, Ethnicity and gender
