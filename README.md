# School_District_Analysis

## Project Overview
The purpose of this project is to analyze school and student data and report school performance based on key metrics such as School Budget, School Type, Students Passing Rates for Math and Reading subjects. It is to be analyzed how removing Thomas High School 9th grade scores affects these overall key metric results by comparing it with original data results.

## Resources
- Data source: schools_complete.csv, students_complete.csv
- Software: Python 3.7.6, Jupyter notebook 6.4.8

## Results

### **How is the district summary affected?**

**Original district summary:**

![district_summary_original](https://user-images.githubusercontent.com/20058842/176337227-a7e277b0-88ee-4fee-bd41-c98896fcf6a9.png)

**District summary after removing 9th grade scores from Thomas High School:**

![district_summary_modified](https://user-images.githubusercontent.com/20058842/176337372-b0b5d34f-cf0d-4d0f-9ef5-56f16a73d1d5.png)

After removing 9th Grade scores from Thomas High Schools, the changes to the final district results are minimal, almost insignificant to what the original results obtained. If both passing percentages are rounded, the results would be the exact same.


### **How is the school summary affected?**

**Original School Summary**

![school_summary_original](https://user-images.githubusercontent.com/20058842/176337960-73d6e25d-67e7-41d2-8e79-2c2e1fb10a37.png)

**School Summary after removing 9th grade scores from Thomas High School:**

![school_summary_modified](https://user-images.githubusercontent.com/20058842/176337996-ec6931fd-30b6-4816-8f56-277c77f64d94.png)

After removing 9th Grade scores from Thomas High Schools, there are significant changes to the percenatge passing scores for Thomas High School. While original score percentages were both above 90% for both math and reading, scores are now lower 70%. This clearly indicates that the original 9th grade data had very high results compared to other grades from the school which did not average above 70%

### **How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**

The final modified data frame clearly shows how both math and reading now do not pass 70% percentage scores. It went from being the 2nd best overall performing school to the 8th best performing school in the district.

### **How does replacing the ninth-grade scores affect the following:**
- **Math and reading scores by grade**

  There is no real change expect that Thomas High School will now show nan values for 9th graders for both math and reading subject.
  
- **Scores by school spending**

  No changes made. School spending data frame stays the same as original.
  
- **Scores by school size**

  No changes made. School size data frame is the same as original
  
- **Scores by school type**

  No changes made. School type data frame is the same as original
  
## Summary

Removing 9th grade scores from the data set have modified the school summary in a big way since we now have clear data showing that overall Thomas High School is not doing well for Math and Reading. Original 9th grade scores boosted the overall school results making it one of the best performing schools. Minimal changes were reported to the district summary in which after rounding values we would essentially be getting same results from original data frame results. We also now have no data to report for Thomas High School 9th graders, as there data was removed.
