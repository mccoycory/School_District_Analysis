# School District Analysis
Module 4 - Class Work 
## Overview 

The school board was suspicious that the 9th graders at Thomas High School cheated on their exams. It was our task to determine if there was an cheating within the 9th grade class and if so how where did the cheating occur. We will acomplish this by re running the anaylsis performed in the module without the Thomas High School 9th graders. 

## Results 

The school board sent us over two over csv files with school and student data. With any good data project, we had to merge and clean the data using the python np function. This function allowed us to quickly idenfity empty cells and replace those cells. Once we had a clean data set, we were able to use the panda function and create dataframes for quick analysis. Furthermore, using the groupby function it was easy to assign variables and perform analysis. 

We performed analysis by getting average math and reading scores by school, school type, school size, and by school funding. This would allow us to determine if different factors resulted in better testing scores.

Secondly, we performed the same analysis by taking out the 9th graders at Thomas High School. If the results changed from our base case of results, we could infer that cheating had occured. If there was no change in the data, we could infer there was no cheating at Thomas High School. 

Below are some screenshots of the dataframe results. 

![District Summary](https://github.com/mccoycory/School_District_Analysis/blob/main/Resources/School%20District%20Summary.png)

1[District Summary without 9th Grade at Thomas High School](https://github.com/mccoycory/School_District_Analysis/blob/main/Resources/School%20District%20Summary.png)

![Top 5 Performing Schools](https://github.com/mccoycory/School_District_Analysis/blob/main/Resources/Top%20Performing%20Schools.png)

![Bottom Performing Schools](https://github.com/mccoycory/School_District_Analysis/blob/main/Resources/Bottom%20Performing%20School.png)

![Average Math Scores per School](https://github.com/mccoycory/School_District_Analysis/blob/main/Resources/Average%20Math%20scores%20by%20school.png)

![Average Reading Scores per School](https://github.com/mccoycory/School_District_Analysis/blob/main/Resources/Average%20Reading%20scores%20by%20school.png)

![Average Scores by School Size](https://github.com/mccoycory/School_District_Analysis/blob/main/Resources/Average%20scores%20by%20size.png)

![Average Score by School Funding](https://github.com/mccoycory/School_District_Analysis/blob/main/Resources/Average%20Scores%20by%20spending.png)

![Average Score by School Type](https://github.com/mccoycory/School_District_Analysis/blob/main/Resources/Average%20score%20by%20school%20type.png)

## Summary 

After the anaylsis was permed without the 9th graders in Thomas High School, the data set did not change very much. Therefore, it can be infered that Thomas High School 9th grade students did not cheat on their exams. However, it is important to recognize that the sub set of the 9th graders at Thomas High School is very small over a 40,000 plus data set. I think some additional stats other than mean would help identify outliners within the data set.  



