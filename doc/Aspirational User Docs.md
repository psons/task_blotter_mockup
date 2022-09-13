# Task Blotter UI
## Day planning view
Given a prioritized colection of endeavors,
which are prioritized collections of stories
which are prioritized collections of tasks,

Allow the user to see the tasks drawn from the endeavors in prioritized order with the flexability to 
 - manipulate the number of tasks drawn from an endeavor :ndev_tasks
 - manipulate the total number of tasks drawn for the day sprint :day_tasks
 :- with the consequence that endeavors below the highest contribute tasks to the day sprint if the day_tasks is larger than the sum of the ndev_tasks dor all higher endeavors.
 :- with the consequence that large :ndev_tasks for the top endeavor causes focus on that endeavor

### the assumption is that that he task user will focus on highest priority, but may work collaboratively blocked briefly or need to keep additional endeavors active during the day.

