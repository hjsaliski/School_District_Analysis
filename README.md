# School_District_Analysis
**1) Overview/ Purpose:**
  
   The purpose of this analysis was to be able to find/ locate specific elements in multiple CSV files and manipulate them to answer specific questions that we had based on the information in each specific file. During the module we spent our time summarizing school spending, average scores for math and reading, school size, and scores by school type. In the challenege we were to expand on this knowledge and seperate the students scores that were only in 9th grade at Thomas High School, re-run the school district analysis and compare how much the information was changed due to changing information in our databases. We showed how much Thomas high school's % overall passing grades were increased once the 9th grade was nulled and how that later affected the whole district summary report. 
   
   **Results**
   
   The district summary was affected because we changed the number of students that were being calculated in the math and reading percentages for each school. After we nulled the ninth grade reading and math scores we then found a new percentage from the total students that were left to count and found new passing math, passing reading and overall passing percentages for the school district. This changed the numbers by only a few percentage points closer to 0.5-1% but can still cause larger results the more information we have. We called the new total number of students "new_student_count" and made our predictions for the school district based on this number. 
<img width="887" alt="Screen Shot 2022-04-16 at 19 41 30" src="https://user-images.githubusercontent.com/102257486/163696678-cbb553fe-eb09-4e73-a371-3ce00a3bdae1.png">
<img width="909" alt="Screen Shot 2022-04-16 at 19 41 57" src="https://user-images.githubusercontent.com/102257486/163696681-0b9bc98e-07de-4698-8e59-d02cce410756.png">
<img width="887" alt="Screen Shot 2022-04-16 at 19 41 03" src="https://user-images.githubusercontent.com/102257486/163696684-46730597-f259-4d0a-827c-0a3bcabe4289.png">

  The school summary was affected because after we nulled the ninth grade reading and math scores we had to change the school summary percentage grades for Thomas High School. These final percentage grades were skewed because of the incorrect input the ninth grade had on the reading and math. Once we changed the overall grades to only reflect 10-12th graders at Thomas High School the average scores went up by quite a bit. Increasing from around an overall passing grade of 65% to almost 91%. 
  
Before

<img width="836" alt="Screen Shot 2022-04-16 at 19 50 50" src="https://user-images.githubusercontent.com/102257486/163696881-06b7507e-779e-40c1-ad2a-0619c45850a5.png">

After

<img width="797" alt="Screen Shot 2022-04-16 at 19 51 23" src="https://user-images.githubusercontent.com/102257486/163696883-0e0170fc-edaf-4361-8e06-8f285619d675.png">

Replacing the scores has affected Thomas High School's performance against the other schools in a very positive way. Because of this their overall passing percentage has increased and actually gave them a spot at second place in the top 5 performing schools list. Before changing the grades Thomas High School was right in the middle when it came to how well they performed compared to the other schools in this data frame.

Replacing ninth grade scores affected the math and reading scored by grade because the total number of students that are now being calculated for this grade has been decreased since we got rid of ninth graders scores at thomas high school. For this analysis breakdown we seperated the grades by school names along with their average math and reading grades. So particularly, while getting rid of 9th grade scores at Thomas high school increased the overall passing percentage of Thomas high schools grades, for each grade seperately it did not affect the other grades as much since we took those averages based on class size and not overall school size. When looking for 10th grade average math score we took the math scores from only the 10th grade and made calculations based on 10th grade student size at Thomas high school and not for the entire school. 

Replacing the ninth grade math and reading scores for thomas high schoool affected the scores by school spending because the data frame here was shwoing whether or not school spending affected the scores of each grade. After analysis we did not find that school spending affected the grades of thomas high school even after the ninth grade scores were reset.

This graph was showing us the comparison of average school scores by how large the school population was. After we got rid of the ninth grade scores this definitely had a shift because thomas high school would now have fewer students and because of the shift up in grade averages after getting rid of the ninth grade, the data frame will show that fewer population schoools had a better grade point average. This is especcially true for thomas high school. But getting rid of the ninth grade definitely had an impact on scores by scool size because this shifted the school averages higher with lower population schools

Dropping the ninth grade thomas high schoool scores did not have much of an affect on the school scores by school type. Besides a possible increase in average scores for the overall district that Thomas high school is in, the overall scores by school type stayed pretty much the same. The only affect that dropping the ninth grade scores would have done is increase the average score for thomas high school and therefore increasing the average score a little bit due to which district thomas high school was in. 

**Summary**

So four changes that we really saw when changing the ninth grade Thomas High school scores could have been the math and reading scores by grade definitely because we are now missing averages for the ninth grade. We can see that the district summary has changed and Thomas High school is now in the second highest position because of the increase in averages due to dropping the ninth grade. We can see that the scores by school size has been affected because now especilly with thomas high school we have a lower population school with a much higher overall passing average. 
