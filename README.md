# STAT 184 Repository
Introduction: 
This repository contains data and code for analyzing U.S. Armed Forces data. The goal of this activity was to explore the structure of military personnel data, including categories like Pay Grade, Branch, Rank Title, and Sex. In this assignment, I created 2 CSV files from the original dataset: group_data (sorted by Pay Grade) and individual_data (sorted by individual records). These datasets reveal insights into the distribution of U.S. armed forces across various categories.

Implementation:
For this activity, I used R to analyze the U.S. Armed Forces data. I first cleaned and processed the data to ensure accuracy, then implemented functions to sort and manipulate the data. Key operations included filtering, summarizing, and integrating the data based on specific characteristics like Pay Grade, Rank Title, and Sex. One issue I encountered while working through the assignment. was handling missing values. I handled this by implementing a command that checks if Branch and Pay Grade exist in Ranks. If one or the other was not found, then I would return NA. Below is the corresponding code:

![image](https://github.com/user-attachments/assets/fca5e5ac-dbdf-476f-bf17-d3efe8612827)

Results/Conclusion:
The analysis revealed essential insights into the distribution of U.S. Armed Forces personnel. For instance, visualizing the data showed that certain branches have higher concentrations of personnel in specific pay grades. Plots generated through ggplot2 provided a clear view of these trends. This activity not only improved my data cleaning and visualization skills, but also furthered my understanding of the structure of military data. Moving forward, I can apply similar techniques to other datasets for more in-depth analysis.

Sample Output for group_data (in the form of a newly written CSV file):
![image](https://github.com/user-attachments/assets/18ba755c-778f-484e-bb7b-1b1f401f7f04)

Contact:
For any questions or feedback, feel free to contact me at mmk6577@psu.edu.
