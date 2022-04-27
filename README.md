# PyCitySchool_district_Challenge

The purpose of this school data annalysis:
The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. The school board asked for the data to be removed and analyzed again for a comparison.


How is the district summary affected?
the overall passing percentage was adjusted by 1% as seen below:

[previous average scores](https://user-images.githubusercontent.com/99819387/165402334-7eb0b709-fbb1-4af3-9a2a-f51c8429c648.png)

<img width="699" alt="schools affected" src="https://user-images.githubusercontent.com/99819387/165402357-34dcbd6c-f0ee-4038-910a-67487241080e.png">

How is the school summary affected?
In the original analysis, Thomas High School started with a 91% overall passing percentage to 65% overall passing percentage
<img width="1142" alt="previous oPassing" src="https://user-images.githubusercontent.com/99819387/165403395-7ec120d3-441b-4d0e-9038-fd28ef540e1c.png">
<img width="1142" alt="adjusted Opassin" src="https://user-images.githubusercontent.com/99819387/165403405-6380420e-3aa3-4a51-a762-e6e05db8a44a.png">

How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
The ranking of schools are adjusted, 

in the original analysis, Thomas High School ranked 2nd in the district to the lower half of the school district:
<img width="1142" alt="previous ranking" src="https://user-images.githubusercontent.com/99819387/165405166-8e939a32-1b50-4ee2-a5c6-fd0067adadf5.png">


<img width="1142" alt="adjusted ranking" src="https://user-images.githubusercontent.com/99819387/165405173-23fbb239-bed4-4013-bf44-52f726285973.png">

How does replacing the ninth-grade scores affect the followingng">

Math and reading scores by grade:
Thomas High School had 83.6 math average and 83.7 reading average for the 9th grade tests. Now the scores have been replaced with null values and shows up in Python programming as NaN in the following charts.
<img width="1142" alt="reading adjusted" src="https://user-images.githubusercontent.com/99819387/165645824-9169e1e2-e96d-4719-b2d4-520640534073.png">
<img width="1142" alt="math adjusted" src="https://user-images.githubusercontent.com/99819387/165645849-c778a0e6-0b99-41f9-9f29-cef7c2e7e9e8.png">


Scores by school spending?
Thomas High School falls in the $630-$644/student spending range. However there was very little spending impact by changing the
scores.
<img width="1142" alt="spending adjusted" src="https://user-images.githubusercontent.com/99819387/165646464-4b97d60e-de16-4d33-8668-6383a360fd76.png">

<img width="1142" alt="qspending previous" src="https://user-images.githubusercontent.com/99819387/165646479-622dca88-6c77-43ad-9505-32b98a310947.png">

Scores by school size?
Thomas High School is defined as a medium sized school
<img width="1142" alt="school size" src="https://user-images.githubusercontent.com/99819387/165646683-a02ae1ab-7f38-4c6d-a0a8-a91a43d9369a.png">


Scores by school type
Thomas High School is a charter school type
<img width="1142" alt="school type" src="https://user-images.githubusercontent.com/99819387/165646842-e53f6fcf-e405-4532-93bf-3b7578b542c2.png">


Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

- The passing rate for Thomas High School changed from 91% to 65%.

- Thomas High School's ranking dropped from 2nd to 8th in the district of 15 campuses.

- Data at the grade level will now show as "NaN" in reports for the 9th grade students at Thomas High School

- Thomas High School falls in the charter school type.

