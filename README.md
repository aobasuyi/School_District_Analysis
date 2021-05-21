# School_District_Analysis
Performing analysis on school district exam data

## Overview of the school district analysis
A chief data scientist for the city school district will be assisted with analyzing the school district exam data to showcase trends in school performance. The results of the analysis will assist the school board and superintendent in making decisions regarding the school budgets and in setting priorities at the school and the district level. Preliminary results showed evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered.<br />

You have been given the following tasks to complete the school district exam analysis. <br />

1. Replace the ninth-grade reading and math scores for Thomas High School.
2. Repeat the school district analysis.
    - Generate the School District Summary 
    - Generate the School Summary 
    - High and Low Performing Schools
    - Average Math and Reading Scores by Grade
    - Group Scores by School Spending per Student
    - Group Scores by School Size
    - Group Scores by School Type

## Resources
- Data Source: This analysis was performed using the [schools_complete.csv](https://github.com/aobasuyi/School_District_Analysis/blob/main/Resources/schools_complete.csv),[students_complete.csv](https://github.com/aobasuyi/School_District_Analysis/blob/main/Resources/students_complete.csv) datasets.
- Software: Python 3.7.6 :: Anaconda, Inc., conda 4.10.1, Visual Studio Code, 1.56

## School District Results

- **Replace Ninth-Grade Reading and Math Scores code**
The *loc* method was used to select all the reading and math scores from the ninth grade at Thomas High School and replaced with NaNs (codes and figure below). <br />

**District summary results**
- The school district summary provided a high-level snapshot of the district's key metrics. Thomas High school (THS) ninth graders comprise of 461 students out of tha 39,170 students in the district. Removing the grades of Thomas High school (THS) ninth graders had minimal impact on the district's key metrics
!(image)

**School summary results**
- **Performance relative to other schools**
The percentage of THS students who passed who passed Math, Reading were:
- Before replacing the grades of ninth graders:
    - Math = 66.91
    - Reading = 69.66
    - Math and Reading = 65.07
- After replacing the grades of ninth graders: 
    - Math = 93.19
    - Reading = 97.02
    - Math and Reading = 90.63
- Replacing Thomas High School (THS) ninth graders’ math and reading scores improved the passing percentage and the school performance, moving the school from a low performing to the second highest performing school in the district.
!(image), !(image), !(image)

- **The impact of replacing THS ninth grades on the following**   
**Math and Reading Scores by grade**
- Replacing THS ninth graders scores kept the average by grades at about 83% for for Math and 84% for Reading

- **Scores by school spending**
THS falls within the spending range of $630 per student. The school outperformed other students within the same spending range per student after ninth graders scores were replaced

- **Scores school size**
THS falls within the medium range school size. The school performed similarly to schools of the same size.

- **Scores by school type**
THS is a charter school. The Math and Reading scores of THS students were similar to those in Charter schools

## Summary
Four changes in the updated school district analysis after the reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs include:
1. Thomas High School (THS) passing percentage Math and Reading scores from an average of 65% to average of 95%.
2. The school performance improved from a low performing school to become the second highest performing school in the district.
3. The avearge scores by grades were among the highest in the district
4. The school outperformed other schools within the same spending range per student.
5. The school performed similary to other schools within same school size and type