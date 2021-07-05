# Overview

## Purpose
The purpose of conducting the school analysis was to assist Maria and her supervisor replace the ninth grade math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once the math and reading scores are replaced, create a school district analysis to compare with the previoous school district analysis with unaffected reading and math scores from Thomas High School students. 

# Results

## How Was The District Summary Affected
### School District Analysis - Unaffected
The school district analysis had different average math and reading scores and percentages for the 15 schools within the district, before the ninth grade math and reading scores from Thomas High School were replaced with NaNs. 

Per image below, one can see that the following information:

* Average math score was 79.0
* Average reading score was 81.9
* Passing math percentage was 75%
* Passing reading percentage was 86%
* Overall passing percentage was 65%

![Screen Shot 2021-07-04 at 4 33 43 PM](https://user-images.githubusercontent.com/82562823/124402524-9af06780-dce5-11eb-9da7-d51cc735ae3f.png)

### School District Analysis - Affected
Once the scores of Thomas High's ninth graders were replaced, the math and reading scores and percentages, along with the overall passing percentage changed. 

Per image below, one can notice there were certain differences when running the school district analysis without the Thomas High's ninth grade math and reading scores.

* Previously: Average math score was 79.0 - Currently: 78.9 = 0.1 point difference
* Previously: Average reading score was 81.9 - Currently: 81.9 = no difference
* Previously: Passing math percentage was 75% - Currently: 74.8% = 0.2 point difference
* Passing reading percentage was 86% - Currently: 85.7% = 0.3 point difference
* Overall passing percentage was 65% - Currently: 64.9% = 0.1 point difference

<img width="824" alt="Screen Shot 2021-07-04 at 4 49 20 PM" src="https://user-images.githubusercontent.com/82562823/124402932-2f5bc980-dce8-11eb-9ffb-af9a6b149d07.png">

# How Was The School Summary Affected

## What Happened When Scores Were Replaced In Relation to Thomas High Schools's Peformance to Other Schools:

A significant difference that occurred when Thomas High's ninth grade scores were replaced, was the ranking of the schools in the school district. 

The top schools before the grades were changed are listed in the image below.

<img width="919" alt="Screen Shot 2021-07-04 at 11 33 06 PM" src="https://user-images.githubusercontent.com/82562823/124427395-30a8e880-dd20-11eb-88f8-e3b09564078a.png">

Thomas High was previously not in the top five schools until the ninth grade scores were replaced. 

<img width="919" alt="Screen Shot 2021-07-04 at 11 34 10 PM" src="https://user-images.githubusercontent.com/82562823/124427522-5635f200-dd20-11eb-9fc6-e363522d58c0.png">

### When The Ninth Grade Scores Were Replaced

* Math and reading scores by grade in Thomas High School:

	* Before the ninth grade scores were replaced, the passing math (66.9%), reading (69.6%) and overall percentage (65.1%) were lower in comparison to the results after replacement.

	<img width="824" alt="Screen Shot 2021-07-04 at 5 47 27 PM" src="https://user-images.githubusercontent.com/82562823/124404470-e740a500-dcef-11eb-971d-cf4addbaeec5.png">
	
	* After the ninth grade scores were replaced, the passing math (93.8%), reading (97.0%), and overall percentage (90.5%), the  scores of the rest of the 10th-12th students in Thomas High appear higher. 
	
	<img width="824" alt="Screen Shot 2021-07-04 at 5 48 34 PM" src="https://user-images.githubusercontent.com/82562823/124404499-0f300880-dcf0-11eb-93a1-abc10aadec12.png">

* Scores by school spending
	* Before the ninth grade scores were replaced, Thomas High's average math, and reading scores, passing math, reading and overall percentages were higher in the school summary. 
	
![Screen Shot 2021-07-04 at 10 12 15 PM](https://user-images.githubusercontent.com/82562823/124420767-e4a47680-dd14-11eb-88e3-518b4b29f790.png)

* After the ninth grade scores were replaced, Thomas High's average scores and percentages decreased compared to before the replacement, however the spending bin ($630-644) remains the same.

	
<img width="824" alt="Screen Shot 2021-07-04 at 10 10 57 PM" src="https://user-images.githubusercontent.com/82562823/124420648-b6bf3200-dd14-11eb-9951-24dfec0c6163.png">

Furthermore, if one analyzes the spending range per student, the average math and reading scores, and passing math, reading and overall passing percentage increases when Thomas High's ninth grade scores are replaced.

Before replacement:

<img width="919" alt="Screen Shot 2021-07-04 at 11 52 58 PM" src="https://user-images.githubusercontent.com/82562823/124429626-f725ac80-dd22-11eb-955a-395f3da9769b.png">

After replacement: 

<img width="919" alt="Screen Shot 2021-07-04 at 11 53 31 PM" src="https://user-images.githubusercontent.com/82562823/124429705-0a387c80-dd23-11eb-90d7-066423d24c63.png">
	
* Scores by school size
Changing the ninth grade scores did not affect the size of Thomas High School. Thomas High is in the Medium sized category (1000-2000) with 1635 students in total. Without the ninth grade class, the student count in Thomas High is 1174. However, if one inspects the size summary dataframe one may notice that the medium school category has increased math and reading scores and math, reading and overall percentage. 

Before replacement:

<img width="919" alt="Screen Shot 2021-07-05 at 12 30 34 AM" src="https://user-images.githubusercontent.com/82562823/124434003-37d3f480-dd28-11eb-8e85-557e5d428036.png">

After replacement: 

<img width="919" alt="Screen Shot 2021-07-05 at 12 31 30 AM" src="https://user-images.githubusercontent.com/82562823/124434116-589c4a00-dd28-11eb-9843-aaeb4592f3c5.png">


* Scores by school type
Thomas High School is in the Charter category. After the ninth grade scores were replaced, the overall average math and reading scores, and average math, reading and overall passing percentages increased. 

Before replacement: 

<img width="919" alt="Screen Shot 2021-07-04 at 11 56 55 PM" src="https://user-images.githubusercontent.com/82562823/124430044-83d06a80-dd23-11eb-939c-c261bc24c1d6.png">

After replacement: 

<img width="919" alt="Screen Shot 2021-07-04 at 11 57 32 PM" src="https://user-images.githubusercontent.com/82562823/124430107-99de2b00-dd23-11eb-8b36-aa9e71041563.png">

# Summary

The four changes in the updated school district analysis after the reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs are listed below:
1. The average math and reading scores, and passing math, reading and overall percentages increased within Thomas High School. 
2. The average math and reading scores, and passing math, reading and overall percentages increased within the school district.
3. The charter category in the school district analysis saw an increase in scores and percentages. 
4. The Medium school category also saw an increase in scores and percentages. 
