# ECO-202---Research
All data are stored in Data folder.
+ Grade from Quercus: 2020-12-23T0914_Grades-ECO202Y5_Y_All_Sections.csv
+ Zoom data: ECO202_data.7z

Data analysis is performed in data_analysis.ipynb. Details can be found in that file. Please open data_analysis.ipynb for the code + plots/results.

Overview of results:
+ Watchers' grades are significantly higher in both Tests: 4 points in Test 1 and 6 points in Test 2
+ Treatment effect (of watching) is insignificant: Diff-in-Diff regression on sample of students who didn't watch videos before Test 1.

Update on Result: Jan 12 2021
+ Create time series graph for number of views/viewers in total and by Lectures
+ In time series graphs: Red lines are date of Exams, Gray lines are date of the Lectures
+ Students seem to watch the videos days after the lecture and few days before the exam date
+ Distribution for 4 types of students:
  + Type 1: Watch none: 133
  + Type 2: Watch Test 1 but not 2: 14
  + Type 3: Watch Test 2 but not 1: 86
  + Type 4: Watch both: 84
