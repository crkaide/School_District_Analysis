# School District Analysis

## Overview & purpose

The client, a city school district (represented by data scientist Maria), has requested an analysis of standardized testing data for its stakeholders.  The client wishes to study its original datasets (reading and math scores for the 15 institutions in its purview) for insights regarding performance trends, as well as to assess the impact on the integrity of the report of the removal of scores for an entire segment of the population (Thomas High School, 9th grade).  Results of this analysis will inform institution and district decisions regarding budget and add'l priorities.  As in all educational circumstances, FERPA restrictions must be respected when reporting data at a level that would make students identifiable; however, records need not be removed for the purpose of reporting summary data where individuals are not identifiable and the reported n is greater than 5 (per State Board of Education).  Therefore, FERPA restrictions had no impact on what's reported here. 

## Results

### District summary

* When code is refactored to exclude the potentially problematic population (Thomas High School, 9th grade), the following changes are observed:
1. The average math score decreases from 79.0 to 78.9.
2. The % passing math decreases from 75 to 74.8.
3. The % passing reading decreases from 86 to 85.7.
4. The % overall passing decreases from 65 to 46.9.
5. **Refactoring the code to exclude Thomas/9th causes no statistically significant changes to the district summary data. 

***Original***

![https://github.com/crkaide/School_District_Analysis/blob/main/Report_Screen_Shots/r_1_1_district_summary_original.png?raw=true](https://github.com/crkaide/School_District_Analysis/blob/main/Report_Screen_Shots/r_1_1_district_summary_original.png?raw=true)

***Refactored***

![https://github.com/crkaide/School_District_Analysis/blob/main/Report_Screen_Shots/r_1_2_district_summary_new.png?raw=true](https://github.com/crkaide/School_District_Analysis/blob/main/Report_Screen_Shots/r_1_2_district_summary_new.png?raw=true)

### School summary

***Original***

![https://github.com/crkaide/School_District_Analysis/blob/main/Report_Screen_Shots/r_2_1_per_school_summary_original.png?raw=true](https://github.com/crkaide/School_District_Analysis/blob/main/Report_Screen_Shots/r_2_1_per_school_summary_original.png?raw=true)

***Refactored***

![https://github.com/crkaide/School_District_Analysis/blob/main/Report_Screen_Shots/r_2_2_per_school_summary_new.png?raw=true](https://github.com/crkaide/School_District_Analysis/blob/main/Report_Screen_Shots/r_2_2_per_school_summary_new.png?raw=true)

### Performance relative to other schools (top & bottom)

***Original Top 5***

![https://github.com/crkaide/School_District_Analysis/blob/main/Report_Screen_Shots/r_3_1_top_five_original.png?raw=true](https://github.com/crkaide/School_District_Analysis/blob/main/Report_Screen_Shots/r_3_1_top_five_original.png?raw=true)

***Refactored Top 5***

![https://github.com/crkaide/School_District_Analysis/blob/main/Report_Screen_Shots/r_3_2_top_five_new.png?raw=true](https://github.com/crkaide/School_District_Analysis/blob/main/Report_Screen_Shots/r_3_2_top_five_new.png?raw=true)

***Original Bottom 5***

![https://github.com/crkaide/School_District_Analysis/blob/main/Report_Screen_Shots/r_4_1_bottom_five_original.png?raw=true](https://github.com/crkaide/School_District_Analysis/blob/main/Report_Screen_Shots/r_4_1_bottom_five_original.png?raw=true)

***Refactored Bottom 5***

![https://github.com/crkaide/School_District_Analysis/blob/main/Report_Screen_Shots/r_4_2_bottom_five_new.png?raw=true](https://github.com/crkaide/School_District_Analysis/blob/main/Report_Screen_Shots/r_4_2_bottom_five_new.png?raw=true)

### Grade summary

#### Math

***Original***

![https://github.com/crkaide/School_District_Analysis/blob/main/Report_Screen_Shots/r_5_1_math_scores_by_grade_original.png?raw=true](https://github.com/crkaide/School_District_Analysis/blob/main/Report_Screen_Shots/r_5_1_math_scores_by_grade_original.png?raw=true)

***Refactored***

![https://github.com/crkaide/School_District_Analysis/blob/main/Report_Screen_Shots/r_5_2_math_scores_by_grade_new.png?raw=true](https://github.com/crkaide/School_District_Analysis/blob/main/Report_Screen_Shots/r_5_2_math_scores_by_grade_new.png?raw=true)

#### Reading

***Original***

![https://github.com/crkaide/School_District_Analysis/blob/main/Report_Screen_Shots/r_6_1_reading_scores_by_grade_original.png?raw=true](https://github.com/crkaide/School_District_Analysis/blob/main/Report_Screen_Shots/r_6_1_reading_scores_by_grade_original.png?raw=true)

***Refactored***

![https://github.com/crkaide/School_District_Analysis/blob/main/Report_Screen_Shots/r_6_2_reading_scores_by_grade_new.png?raw=true](https://github.com/crkaide/School_District_Analysis/blob/main/Report_Screen_Shots/r_6_2_reading_scores_by_grade_new.png?raw=true)

### Spending summary

***Original***

![https://github.com/crkaide/School_District_Analysis/blob/main/Report_Screen_Shots/r_7_1_spending_summary_original.png?raw=true](https://github.com/crkaide/School_District_Analysis/blob/main/Report_Screen_Shots/r_7_1_spending_summary_original.png?raw=true)

***Refactored***

![https://github.com/crkaide/School_District_Analysis/blob/main/Report_Screen_Shots/r_7_2_spending_summary_new.png?raw=true](https://github.com/crkaide/School_District_Analysis/blob/main/Report_Screen_Shots/r_7_2_spending_summary_new.png?raw=true)

### Size summary

***Original***

![https://github.com/crkaide/School_District_Analysis/blob/main/Report_Screen_Shots/r_8_1_size_summary_original.png?raw=true](https://github.com/crkaide/School_District_Analysis/blob/main/Report_Screen_Shots/r_8_1_size_summary_original.png?raw=true)

***Refactored***

![https://github.com/crkaide/School_District_Analysis/blob/main/Report_Screen_Shots/r_8_2_size_summary_new.png?raw=true](https://github.com/crkaide/School_District_Analysis/blob/main/Report_Screen_Shots/r_8_2_size_summary_new.png?raw=true)

### Type summary

***Original***

![https://github.com/crkaide/School_District_Analysis/blob/main/Report_Screen_Shots/r_9_1_type_summary_original.png?raw=true](https://github.com/crkaide/School_District_Analysis/blob/main/Report_Screen_Shots/r_9_1_type_summary_original.png?raw=true)

***Refactored***

![https://github.com/crkaide/School_District_Analysis/blob/main/Report_Screen_Shots/r_9_2_type_summary_new.png?raw=true](https://github.com/crkaide/School_District_Analysis/blob/main/Report_Screen_Shots/r_9_2_type_summary_new.png?raw=true)
