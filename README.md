# **School_District_Analysis**

### **Purpose**
Based on the school board instructions, the school district analysis needs to be updated without considering the results from the **Thomas High School** (_**THS** from now on_) ninth grade's results due to academic dishonesty.
This is why the following report will highlight the main changes to the original results without the mentioned highschool figures. 
#

## **Final Results**
After some minor adjustments on the analysis, we are now able to compare between the different summaries made during the initial approach in order to understand the school District based on each school's performance, size, budget, etc.

* How is the district summary affected?

Excluding the 461 THS-9th students (1% of total students) had practically no impact in the overall results from the District as shown on the following image.

![District Summary](https://github.com/AxisAngeles/School_District_Analysis/blob/main/Challenge/Resources/SchoolDistrictSummary_new.png)

_District Summary_


* How is the school summary affected?

As expected, the school summary was only affected in the THS row, drastically improving its passing percentages.

![School Summary](https://github.com/AxisAngeles/School_District_Analysis/blob/main/Challenge/Resources/SchoolSummary_changes.png)

_School Summary_
 
* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Based on the above, the new percentages make THS move upward in the School Ranking, reaching a 2nd (_former 8th place_) place in the best performing schools just below the Cabrera High School.


* How does replacing the ninth-grade scores affect the following:
  - Math and reading scores by grade:<br />
  The only impact is that **THS 9th grade has no average score in both math and reading.** 
  - Scores by school spending:<br />
  After the changes, the 2 middle spending ranges ($585-$629 and $630-$644) improved a couple decimals, which makes the **$585-$629 range have the best math and reading scores.**
  - Scores by school size:<br />
  Regarding school sizes, the **changes were marginal** vs the orginal results, thus, small shools still have the best math results.
  - Scores by school type:<br />
  Regarding school type, the **changes were marginal** vs the orginal results, thus, Charter shools still have the best math and reading results.

#
## **APENDIX. Changes Summary**
Four main changes excluding the ninth grade results at Thomas High School:
1. The merged School - Student DataFrame was updated with the NaNs values at THS 9th grade results.
2. The total student count was reduced by 461 students (THS 9th), affecting the passing percentages.
3. The School Summary results were modified to show the new student count, scores and percentages considering only grades 10th - 12th.
4. The School Summary was sorted for a second time to obtain the updated High and Low Performance school lists.
