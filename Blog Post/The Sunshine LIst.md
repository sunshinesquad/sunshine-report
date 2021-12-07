# Equity Stands in The Shadows of The Sunshine List

---

## About Us

This report and the accompanying analysis has been developed by Douglas Conley, Reese Dominguez, Alexander Sawatsky, Joshua Trower. All analyses can be found on [GitHub](https://github.com/sunshinesquad/sunshine-report)

---
## Acknowledgements

This project was submitted as the final course project for CSCI 2000U “Scientific Data Analysis” during Fall 2021. The authors certify that the work in [this repository](https://github.com/sunshinesquad/sunshine-report) is original and that all appropriate resources are rightfully cited.

---

## Limitations

We are fully aware that the use of datasets to predict the gender and race of a person is imprecise. There are many first names that are unisex, and there are many last names belonging to people of many racial identities. We hope our naive approach gives at least some insight to racial and gender representation, and use non-confident language throughout this article to reflect this.

---
## Introduction

For the past 24 years, the Ontario Government has been reporting on the salaries of government employees who earn more than $100,000. The intention of publishing this list of employees, commonly referred to as the "Sunshine List", is to act as an accountability measure to the public. Each year that this data is published, a great deal of attention is given to the increased number of employees who are earning $100,000 or more. One of the more common criticisms of this data set is that it does not account for inflation. 

A more pressing criticism of this data set is that, despite the passing of the Anti-Racism Act of 2017 ([https://www.ontario.ca/laws/statute/17a15](https://www.ontario.ca/laws/statute/17a15)) no data is currently available to explore issues of equity with respect to the highest paid employees in the province. This project seeks to gain greater insight not only into the historical trends of the Sunshine List, but to also consider the extent to which there is equitable representation in these jobs for female and for racialized employees.

The data used for this exploration includes Sunshine List files from 1996 to 2020, Population statistics for Ontario over this same period, a Name file that includes probabilities of Gender, and a Name file that includes probabilities of racial identity. Although the use of names and probabilities of Gender and Racial Identity are not precise and inherently inexact, it does provide interesting insights into inequity, at least until the Ontario government requires the inclusion of gender and racial identity in the compilation of the Sunshine List.

---
## Discussion

As can be seen in the following graph, the number of provincial employees who earn $100,000 or more has increased every year. From 4,501 people in 1996 and 205,000 people in 2020. This represents an increase of $4,393.916 across the average salaries over the past 24 years.

_Graph 1: Number of Provincial Employees on the Sunshine List from 1996 to 2020_
![[Pasted image 20211206234450.png]]

Although the largest increase in people being added to the Sunshine list occured in 2020, this did not correspond to an increase in the average salary. As can be seen in the following graph, the largest increase in average salary occured from 1999 to 2001 but most recently, in 2020, the average salary decreased. The difference in average salary from 1996 When considering this decline, it would be worth noting the impact that COVID may have had.

_Graph 2: Average Salary on the Sunshine List from 1996 to 2020_
![[Pasted image 20211206234547.png]]

More starkly, when the average salaries are considered across quartiles, we can see that the highest 25% of employees earn, on average, such significantly larger salaries that the other three quartiles are compressed together. Although this highest range of earners has greater variability over the 24 years, it is interesting to note that during 2020 and the introduction of COVID, their salaries did not drop, unlike the overall average highlighted above.

_Graph 3: Average Salaries by Quartiles from 1996 to 2020_
![[Pasted image 20211206234558.png]]

Although the percentage of women in the province has remained fairly stable around 50.6% over the past 25 years, the following graph highlights that women clearly have not had the same representation on the Sunshine list.

_Graph 4: Number of Men and Women on the Sunshine List from 1996 to 2020_
![[Pasted image 20211206234604.png]]

While the number of both men and women on the list has been increasing over the past 24 years, women continue to be under-represented. 

Perhaps more alarming, when considered from the perspective of racial identity, as infered from names, there is greater representation of employees who identify as white than of any other group. 

_Graph 5: Number of Employees by Racial Identity from 1996 to 2020_
![[Pasted image 20211206234616.png]]

---
## Conclusion

Although the sunshine list is particularly sunny for the highest earners (highest quartile), and has been spreading the light for more employees, the sun is just beginning to rise for women and racialized employees who are continuing to try to reach those higher paid jobs.