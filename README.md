# School_District_Analysis

## Overview  

Explain the purpose of this analysis. The purpose of this analysis is well defined (3 pt).
Using Python, Pandas Library, Numpy Library and Jupyter Notebook, an analysis was done on the performances of various school districts. Once completed, it has been revealed that some of the data may be invalid. 9th graders from Thomas High School, a school from the study has been accused of academic misconduct in both math and reading. The scores from this dataset need to be replaced with Nan (a null value) and the analysis needs to be repeated. 


## Results

Below, screenshots are provided detailing how different results were affected:

- District Summary
- School Summary
- Math and reading scores:
   - Relative to other schools
   - By grade
- Scores relative to school:
   - Spending
   - Size
   - Type

### How is the district anaylysis summary affected?


#### District Analysis Original
![DistrictAnalysisOG](https://github.com/Andrewjruble/School_District_Analysis/blob/main/Resources/District_Analysis_Original.png)
#### District Analysis Updated
![DistrictAnalysisUp](https://github.com/Andrewjruble/School_District_Analysis/blob/main/Resources/District_Analysis_Updated.png)


### How is the school summary affected?

#### Original
![SchoolSummaryOG](https://github.com/Andrewjruble/School_District_Analysis/blob/main/Resources/School_Summary_Original.png)


#### Updated
![SchoolSummaryUp](https://github.com/Andrewjruble/School_District_Analysis/blob/main/Resources/School_Summary_Updated.png)

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

#### Original
![topschoolOG](https://github.com/Andrewjruble/School_District_Analysis/blob/main/Resources/TopSchoolsOG.png)

#### Updated
![topSchoolUp](https://github.com/Andrewjruble/School_District_Analysis/blob/main/Resources/TopSchoolsUpdated.png)

### How does replacing the ninth-grade scores affect the following:

#### Math and Reading scores by grade


#### Original
![MathScoresGradeOG](https://github.com/Andrewjruble/School_District_Analysis/blob/main/Resources/MathScoresGradeOriginal.png)


#### Updated
![MathScoresGradeUp](https://github.com/Andrewjruble/School_District_Analysis/blob/main/Resources/Mathscoresgradeupdated.png)


#### Original
![ReadingScoresOG](https://github.com/Andrewjruble/School_District_Analysis/blob/main/Resources/ReadingScoresGradeOriginal.png)


#### Updated
![ReadingScoresUp](https://github.com/Andrewjruble/School_District_Analysis/blob/main/Resources/ReadingScoresGradeUpdated.png)

### Scores by School Spending

#### Original
![ScoresSpendOG](https://github.com/Andrewjruble/School_District_Analysis/blob/main/Resources/Scores_By_Spending_Original.png)


#### Updated
![ScoresspendUP](https://github.com/Andrewjruble/School_District_Analysis/blob/main/Resources/Scores_By_Spending_Updated.png)


### Scores by school size

#### Original
![SchoolSizeOG](https://github.com/Andrewjruble/School_District_Analysis/blob/main/Resources/Scores_School_Size._Original.png)

#### Updated
![School_sizeUp](https://github.com/Andrewjruble/School_District_Analysis/blob/main/Resources/Scores_School_Size.Updated.png)


### Scores by school type

#### Original
![SchooltypeOG](https://github.com/Andrewjruble/School_District_Analysis/blob/main/Resources/Scores_By_School_Type_Original.png)

#### Updated
![SchoolTypeUp](https://github.com/Andrewjruble/School_District_Analysis/blob/main/Resources/Scores_By_School_Type_Updated.png)

### Summary: 

Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.There is a statement summarizing four changes to the school district analysis after reading and math scores have been replaced (5 pt).

- Looking at the distict summary, the percent overall passing lowered around .27%. 
- The overall passing percent at Thomas High School was similar at about .3%. 
- Relative to other schools, Thomas High School did not move above or below a school in any catergory, but it only perform .0004 overall better than it's next contender in the updated version
- Looking at performances based on school spending, the two middle bins ($585-$629, $630-$644) had dastric differences. With quantities big enough to incite more investigation (9% difference in one catergory), it was noticied that an error was made in the code. 
