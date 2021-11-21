# School District Analysis

## Overview of Project

### Purpose
The school board has notified us that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. The purpose of this project is to replace the ninth grade math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once the math and reading scores have been replaced, we would repeat the school district analysis and see how these changes affected the overall analysis.

## Results
### How is the district summary affected?
Old District Summary:
![image](https://user-images.githubusercontent.com/92401000/142738766-a7a2a5c4-34a0-4e23-901e-1eaf40025944.png)

New District Summary:
![image](https://user-images.githubusercontent.com/92401000/142738808-b9a38194-a530-48aa-8650-49a6ead99e84.png)

The new district summary had a lower percentage in % passing math (-0.2%), lower percentage in % passing reading (-0.3%), and lower percentage in % overall passing (-0.1%).

### How is the school summary affected?
Old School Summary:
![image](https://user-images.githubusercontent.com/92401000/142738980-9e6f998a-1eb1-496c-9d1f-2d51ddba812c.png)

New School Summary:
![image](https://user-images.githubusercontent.com/92401000/142739007-a6338910-3092-4f40-96ef-6b9be5b67f7d.png)

All the other schools stats stayed the same besides Thomas High School. The new % Passing Math for Thomas High School decreased by (-0.08%), % Passing Reading decreased by (-0.29%), and % Overall Passing decreased by (-0.32%).

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Removing the ninth graders' math and reading scores decreased Thomas High School's % Passing Math, % Passing Reading, and % Overall Passing by (-0.08%), (-0.29%), and (-0.32%) respectively.

### How does replacing the ninth-grade scores affect the following:
#### Math and reading scores by grade

Old Math Scores by Grade:

![image](https://user-images.githubusercontent.com/92401000/142739628-34469f3d-e6e4-45e5-8a5c-b4464dbfce31.png)

Old Reading Scores by Grade:

![image](https://user-images.githubusercontent.com/92401000/142739645-97ad367c-a366-4c08-89ab-d286a45b5e54.png)

New Math Scores by Grade:

![image](https://user-images.githubusercontent.com/92401000/142739680-93256da1-da81-4903-baa8-b91d1c20e1e4.png)

New Reading Scores by Grade:

![image](https://user-images.githubusercontent.com/92401000/142739701-4833ad2b-212d-4876-99c7-2b53d9354396.png)

There was no changes to the other 14 school's math or reading scores. The only change was Thomas High School's math and reading scores for ninth grade. The math scores for Thomas High School ninth grade changed from 83.6 to "nan" and the reading scores for changed from 83.7 to "nan".

#### Scores by school spending

![image](https://user-images.githubusercontent.com/92401000/142745727-4e7bb8a7-fc69-43ca-a582-859fbf07da09.png)

Replacing the ninth-grade scores had no affect on school spending based on scores.

#### Scores by school size

![image](https://user-images.githubusercontent.com/92401000/142745840-7351242b-53b0-4c7c-b9b8-2010980f8bce.png)

Replacing the ninth-grade scores had no affect on scores by school size.

#### Scores by school type

![image](https://user-images.githubusercontent.com/92401000/142745867-02ac7b4e-cdba-450e-8569-73d5030d0f2e.png)

Replacing the ninth-grade scores had no affect on scores by school type.

## Summary

After reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs the new district summary had a lower percentage in % passing math (-0.2%), lower percentage in % passing reading (-0.3%), and lower percentage in % overall passing (-0.1%). Also, in the school summary the new % Passing Math for Thomas High School decreased by (-0.08%), % Passing Reading decreased by (-0.29%), and % Overall Passing decreased by (-0.32%). In the new math and reading scores by grade, the math scores for Thomas High School ninth grade changed from 83.6 to "nan" and the reading scores for changed from 83.7 to "nan".
