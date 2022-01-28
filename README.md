# Performance evaluation of Terapixel rendering in Cloud (Super)computing

**Introduction**

Photo-realistic terapixel visualization is computationally costly, and there have been no such visualization of urban digital twins to date, with the few terapixel visualizations that do exist focus on space rather than earth. The objective of the project was to visualize the data the collected from the IoT device by urban observatory of the Newcastle. Terapixel images provide an intuitive and open way for stakeholders to present information sets, enabling audiences to interactively search big data across multiple scales. 

***
In our project we have used matplotlib and seaborn for data visualization. The platform we used for the project is google colab notebook. Pandas and numpy for data cleansing and data exploration. 

**Dataset**
 
The dataset was collected from application checkpoint and system metric output from the production of a terapixel image during a run using 1024 GPU nodes. The data shows the performance of the GPU card, performance timing of the render application and the details of each image during rendering.

The dataset in our projects:
•	Application-checkpoints.csv
•	gpu.csv
•	task-x-y.csv

**Code**

The TerpixelEvalution_B21047209_SATISH_PILLA.IPNYB file contains the source code for the entire project. For every line of the code there is clear instruction of why were are running the particular code block.

Table of contents:

1) Introduction

2) Importing all necessary libraries

3) Uploading all the TeraScope files 
   
   The TeraScope files can be uploaded by using files.upload() command or you can simple go to files and upload your files.

4) Data Preprocessing
   
5) Exploratory Data Analysis

6) Conclusion and Future works

7) Learnings

8) Reference  


**Abstract**

B210472095_SATISH_PILLA_CLOUD_COMPUTING_ABSTRACT.pdf contains the abstract of the project.

**Report**

B210472095_SATISH_PILLA_CLOUD_COMPUTING_REPORT.pdf is the overall report of the project. The report is organized as follows:

1 Introduction	

2 Business Understanding	

 2.1 Background	

 2.2 Objective	

 2.3 Tools & Methodologies	

3 Description of Data	

4 Data Preprocessing	

5 Exploratory Data Analysis	

 5.1 Which event type dominate the task run times	

 5.2 predicting which event type dominates the task run times for each jobId.

 5.3 Which level dominates the task run time.	

 5.4 Correlation between attributes of GPU dataset	
  
  5.4.1 Correlation between percent utilization of the GPU (core) and percent utilization of the memory	

  5.4.2 Correlation between temperature and percent utilization of the GPU (core) and percent utilization of the memory	
  
  5.4.3 Correlation between Power drawn and remaining attributes	

5.5 Analyzing GPU Hardware performance by plotting box plot	
  
  5.5.1 Power Consumption range	

5.6 Correlation Between Render time and Power Drawn	

6 Conclusion, Results and Future Work	

6.1 Future Work	

7 Learning	

8 Reference	


<<<<<<< HEAD
=======

>>>>>>> 1351bf5e1fbccc8132b83d95b3b08f4ffc18ad56
