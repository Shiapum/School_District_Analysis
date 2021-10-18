# School District Analysis
## Overview of Project
### Purpose
Replace the math and reading scores for Thomas High School while keeping the rest of the data intact. Then, repeat the school district analysis.

### Background
The school board notified Maria and her supervisor that the previous analysis shows evidence of academic dishonesty from Thomas High School ninth graders. Although the school board is aware of this, they want to uphold the state-testing standards. 

## Results
### Analysis
- How is the district summary affected?

We can see that the average math and reading scores are practically the same. 

The previous district summary was:
![image](https://user-images.githubusercontent.com/21972342/137664432-40dba13d-c504-49e0-93e1-8a3a252a4a0d.png)

After removing the 9th graders form Thomas High School, the distric summary is:
![image](https://user-images.githubusercontent.com/21972342/137664494-ac9ac4f2-71fa-476b-bc81-75a46c9ba67f.png)

- How is the school summary affected?

We can see that the Thomas High School summary changed like follows: 
- Passing math number of students percentage decreased 0.09%,
- Passing reading number of students percentage decreased 0.29%,
- And, the ovarall passing percentage decreased 0.31%

Before replacing ninth graders school summary:
![image](https://user-images.githubusercontent.com/21972342/137665277-ff3edc44-e3a5-4300-be32-e515e7959c41.png)

After replacing ninth graders school summary:
![image](https://user-images.githubusercontent.com/21972342/137665300-e1d8e123-d876-4ca8-81ff-ce8fac15e84f.png)

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Thomas High School is still performing as the second best school in the district.

Before replacing ninth graders:
![image](https://user-images.githubusercontent.com/21972342/137665825-09984e28-2e97-46d1-b994-860c0f44f182.png)
After replacing ninth graders:
![image](https://user-images.githubusercontent.com/21972342/137665855-a1ac53cc-e162-4aa9-87cc-165c494bb365.png)

- How does replacing the ninth-grade scores affect the following:
    -  Math and reading scores by grade
       
       We can see in Thomas High School that the 9th graders, for both math and reading scores, change to nan. This is due, there is no data for those students. This scores doesn't affect other schools. 
       
        Previous math scores by grade:
       
        ![image](https://user-images.githubusercontent.com/21972342/137666942-48efbc2c-c24c-424e-b2a4-1e4abb0dc4dc.png)
       
        Previous reading scores by grade:
       
        ![image](https://user-images.githubusercontent.com/21972342/137666983-b9e5e8ac-9d16-45b1-86fa-c2ecad35e48d.png)

        New math scores by grade:
       
        ![image](https://user-images.githubusercontent.com/21972342/137667134-fa3de68e-aef3-4d2f-b1a3-1982ef8a48e2.png)

        New reading scores by grade:
       
       ![image](https://user-images.githubusercontent.com/21972342/137667164-cd0bdcf5-4dcc-4b0e-b24b-cc6baa7bbeb2.png)

    -  Scores by school spending

        Thomas High School belongs to the $630 to $645 bin. Removing the 9th graders from the analysis didn't change the outcome. 
       
        ![image](https://user-images.githubusercontent.com/21972342/137667463-4e1b42bf-0d4f-419b-a0a3-c8733027db16.png)

        Previous scores by school spending:
       
        ![image](https://user-images.githubusercontent.com/21972342/137667246-a1e697a3-b991-4dc4-96fb-d92dd4fa914b.png)
       
        New scores by school spending:
       
       ![image](https://user-images.githubusercontent.com/21972342/137667275-0def7082-6626-45dc-8b5d-694df9fda0ad.png)

    -  Scores by school size

        Similar to the school spending, removing the Thomas High School 9th grader students from the analysis doesn't change the outcome.
        
        Previous scores by school size:
        
        ![image](https://user-images.githubusercontent.com/21972342/137667776-d7e51eb6-0e85-4ab7-b0f1-a7e07b79198a.png)
        
        New scores by school size:
        
        ![image](https://user-images.githubusercontent.com/21972342/137667804-518f30a1-dcf5-4f2e-964f-eaa65b08b086.png)

    -  Scores by school type
        
        Sames as before, removing the Thomas High School 9th grader students from the analysis doesn't change the outcome.
        
        Previous scores by school type:
        
        ![image](https://user-images.githubusercontent.com/21972342/137668025-64eb9274-649d-4042-9554-0905e14d99cb.png)

        New scores by school type:
        
        ![image](https://user-images.githubusercontent.com/21972342/137668039-06787d40-42a1-4013-a465-73040f7f0fcf.png)

### Summary
The results show that removing the 9th graders from the calculation didn't change the results of the analysis. Thomas High 9th grade students are 461, while the total students in Thomas High are 1,635. And the total number of students in the district are 39,170. 
Meaning: 
- The Thomas High 9th grader population is small compared to the district level calculations, so removing them from the calculations, didn't have much of an impact.
- The scores for Thomas High 10th to 12th graders are a little lower compared to 9th graders, because the averages decreased. But, they are still good enough to keep Thomas High as a high performer school. 
