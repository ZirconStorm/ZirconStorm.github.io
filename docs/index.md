# Bernard (Bernie) Fay

## Education
* Iowa State University - 3.98 GPA, Class of 2022
    * Software Engineering, B.S. with Honors
    * Data Science, B.S.

## Relevant Coursework
* I E 312 - Optimization
* I E 483 - Data Mining
* COM S 311 - Introduction to the Design and Analysis of Algorithms
* COM S 363 - Introduction to Database Management Systems
* STAT 347 - Probability and Statistical Theory for Data Science
* DS 202 - 	Data Acquisition and Exploratory Data Analysis
* DS 303 - Concepts and Applications of Machine Learning 

## Projects
### AWS Data Pipeline
I assisted in developing a pipeline for the storage of personally identifiable information (PID) for one of my internships. The pipeline had to be able to receive data at any time without prior notification. The data being transferred could include various forms of PID and other highly senseitive information that needed to be encrypted before it could be stored. Additionally, the data needed to be transformed and cleaned so that it would be ready to use by data analysts. Additionally the unencrypted form needed to be accessible in case it was requested by the analysts, but only with human intervention to ensure sensitive was not accessed without reason. As a result, the primary tbale that would be queried from only contaimned an encrypted reference to the actual encrypted data in another table. That way, should the primary table be decrypted, no sensitive information would viewable to the analysts. A rough sketch of the process can be found below: