# Study project: the mobile app users behaviour analysis

## Project task
In this project we need to analyse user event log containing conducted A/A/B testing. The project manager wants to change fonts in our application, the decision will be made after testing. Users were divided in 3 groups: 2 control groups with old fonts and 1 challenger group with new fonts. We need to decide which font is better.  

## Data
* Table `logs_exp` - contains events of users included in A/A/B testing.

## Used libraries
*pandas*, *seaborn*, *plotly*, *matplotlib*.

## Project completion status - ✔️ Completed

In this project, we studied the user event log of mobile app. An A/A/B testing analysis was performed, on which base the decision regarding new app fonts using was made.

After analysing experiment itself and researching hypothesis, we have calculated the statistical significance between the proportions of different events in different experiment groups. Our test did not show any statistical difference between our groups. That is why we can conclude that new fonts implementing does not affect the user conversion in any way.  
