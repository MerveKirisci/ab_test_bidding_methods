# AB_Test_Bidding_Methods

![alt text](https://www.invespcro.com/blog/images/blog-images/creating-successful-ab-test.jpg)

## Business Problem

Facebook recently introduced a new type of bidding, 'average bidding', as an alternative to the current bidding type called 'maximum bidding'.

One of our clients, bombabomba.com, decided to test this new feature and would like to run an A/B test to see if the average bid converts more than the maximum bid.

The A/B test has been going on for 1 month and now bombaomba.com is waiting for you to review the results of this A/B test. The ultimate success criterion for Bombabomba.com is Purchase. Therefore, the focus should be on the Purchase metric for statistical testing.

## Dataset Story

In this data set, which includes the website information of a company, information such as the number of advertisements that users see and click, as well as earnings information is also included here. There are two separate data sets, the control and test groups. These datasets are on separate sheets of ab_testing.xlsx excel. Maximum Bid was applied for the Control group, Average Bid was applied for the Test group.


Finally, in this project I analyzed the confidence interval using sms.DescrStatsW. I examined behaviors such as hypothesis-building, normality assumption (Shapiro-Wilks Test) measures, and variance homogeneity. Considering the p_value obtained as a result of the test, interpret whether there is a statistically significant difference between the purchasing averages of the control and test groups. Since we cannot reject the assumption hypotheses, the process will continue with the Parametric test.
