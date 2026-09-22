# Student Performance Findings

## Overview

This report summarizes the five visualizations created from the 1,000-student performance dataset. Scores are measured on a 0-100 scale. The charts describe patterns in this sample; they do not prove that gender, lunch type, or test preparation caused the observed differences.

## V1 - Gender boxplots

**Main takeaway:** the gender pattern is different for math and reading.

Figure V1 compares the score distributions for female and male students. The median math score is **65.0** for female students and **69.0** for male students. Reading shows the opposite pattern: the female median is **73.0**, compared with **66.0** for male students. Reading scores are generally higher than math scores for both groups. The boxes and whiskers also show that there is noticeable variation within each gender, not just a difference between the medians. The gender difference appears more noticeable for reading than for math. These are descriptive group comparisons, so they should not be interpreted as evidence that gender causes score differences.

## V2 - Test preparation and math

**Main takeaway:** students who completed test preparation had the higher average math score.

Students who did not complete the course averaged **64.08** points in math. Students who completed it averaged **69.70** points, a difference of **5.62 points**. The error bars show approximate 95% confidence intervals based on the standard error of each group mean. In this dataset, the completed group therefore performed better on average. The result is consistent with test preparation being associated with stronger math performance. However, this is observational data, so it cannot show that the course alone produced the improvement. Prior achievement, motivation, or other differences between the groups could also help explain the gap.

## V3 - Lunch type and average performance

**Main takeaway:** the standard-lunch group has higher average scores across all four measures.

The overall average score is **70.84** for students receiving standard lunch and **62.20** for students receiving free or reduced lunch. That is an **8.64-point** difference in the overall average. The same direction appears for math, reading, and writing, so the pattern is not driven by one subject alone. The grouped bars make both the lunch comparison and the subject comparison easy to see. Lunch type may be connected to broader socioeconomic conditions, so it is better treated as an indicator than as a direct cause. The chart describes an association in this sample and should not be used to make conclusions about individual students.

## V4 - Subject correlations

**Main takeaway:** students who do well in one subject generally do well in the others, especially in reading and writing.

The heatmap shows positive relationships among all three subjects. Math and reading have a correlation of **0.82**, math and writing have a correlation of **0.80**, and reading and writing have the strongest relationship at **0.95**. These values indicate that higher scores in one subject tend to occur alongside higher scores in another. The especially strong reading-writing relationship is reasonable because those skills are closely related. Correlation measures linear association, not cause and effect. It also does not tell us whether the relationships would remain the same after controlling for preparation, lunch, or other student characteristics. Overall, the subjects appear to be measuring related aspects of academic performance.

## V5 - Math versus reading by test preparation

**Main takeaway:** math and reading move together strongly, while the two preparation groups have very similar trend-line slopes.

The overall correlation between math and reading is **0.82**, which indicates a strong positive association. The fitted slope is **0.861** for students who did not complete test preparation and **0.840** for students who did. The completed-group slope is therefore only **0.021 lower** than the no-preparation slope. Both lines rise, meaning students with higher reading scores generally also have higher math scores. The legend includes the number of students in each group so the comparison is transparent. The nearly parallel lines suggest that preparation is more clearly associated with a higher level of math performance than with a major change in the math-reading relationship. Because the groups were not randomly assigned, the slope comparison should still be interpreted cautiously.