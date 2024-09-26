## AI Bootcamp Module 18: 
# Neural Network Challenge
The objective of this challenge was to creat a neural-network that can assess the level of loan risk for student loans. The following are the results of my findings based on the challenge.
1. Describe the data that you would need to collect to build a recommendation system to recommend student loan options for students. Explain why this data would be relevant and appropriate.

To build a recommendation system for student loan options, we would need to collect the following data:

- Student's financial information: income, savings, existing debts
- Academic information: GPA, major, expected graduation date
- Loan details: interest rates, repayment terms, loan amounts
- Career prospects: expected salary after graduation, job placement rates
- Historical loan performance data: repayment rates, default rates

This data is relevant and appropriate because it provides a view of the student's financial situation, academic performance, and future earning potential. It allows the system to match students with loan options that they are likely to qualify for and be able to repay.

2. Based on the data you chose to use in this recommendation system, would your model be using collaborative filtering, content-based filtering, or context-based filtering? Justify why the data you selected would be suitable for your choice of filtering method.

The model would primarily use content-based filtering, with elements of context-based filtering when regarding career prospects. Content-based filtering is suitable because we're using specific attributes of the student (financial situation, academic performance) and the loans (interest rates, terms) to make recommendations. The system would match loan features to student profiles.

3. Describe two real-world challenges that you would take into consideration while building a recommendation system for student loans. Explain why these challenges would be of concern for a student loan recommendation system.

Two real-world challenges to consider are:

a) Data privacy and security: Handling sensitive financial and personal information requires robust security measures to protect against data breaches and ensure compliance with regulations like FERPA in the US.

b) Ethical considerations: The system must avoid bias and ensure fair recommendations across all demographic groups. It should also consider the long-term financial impact on students, avoiding recommendations that could lead to excessive debt burdens.