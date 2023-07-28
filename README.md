# AB-test-Hypotesis
Project «A/B Testing, Hypothesis Prioritization». Conducted prioritization of hypotheses for the ICE and RICE frameworks and analysis of the results of the A / B test, built graphs and calculated the statistical significance of differences in conversions and average checks.
### Objective: 
Prioritize hypotheses, launch A/B test, and analyze results.
### Research process:
* Data preprocessing;
* Prioritization of hypotheses using the ICE and RICE methods;
* Comparison of cumulative revenue between groups;
* Comparison of cumulative average order value;
* Graph depicting the relative change in cumulative average order value of Group B compared to Group A;
* Comparison of cumulative average number of orders per visitor;
* Graph depicting the relative change in cumulative average number of orders per visitor of Group B compared to Group A;
* Testing the statistical significance of differences in average order value;
* Testing the statistical significance of differences in average number of orders per visitor.
### Skills and tools:
Python, Pandas, Matplotlib, SciPy, A/B testing, testing of statistical hypotheses
### Examples of visualizing data from a project
![ABtestHypothesis](https://github.com/yumazur/AB-test-Hypothesis/assets/140715941/317b6cf7-4868-412b-96d3-2217d6e3c53b)
### Analysis Results:

Hypothesis Prioritization. It is recommended to base the prioritization of hypotheses on the RICE method results.
The top three hypotheses are:

Add a subscription form to all main pages to collect customer email addresses for email newsletters;
Add product recommendation blocks to the online store website to increase conversion and average order value;
Add two new traffic acquisition channels to attract 30% more users.
A/B Test.

Group B is recognized as the winner of the test, but solely based on the fact that the average number of orders in Group B is higher than in Group A by 16.9%. It is essential to note that, in terms of the average order value, Group B underperforms Group A by 2%.

The unsatisfactory outcome of the experiment can be attributed to incorrect input data. Errors occurred during the division of orders between the groups, with overlapping orders constituting over 15% of the total revenue during the test period. Additionally, the lack of data on unique visitors hinders a proper comparison of the average number of orders for each group.
