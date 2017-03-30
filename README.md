# kaggle_h1b

Data Exploration based on data from Kaggle https://www.kaggle.com/nsharan/h-1b-visa

The columns in the dataset include:

UPDATE: Credit: Jagan Gurumurthy

The CASE_STATUS field denotes the status of the application after LCA processing. Certified applications are filed with USCIS for H-1B approval. 
CASE_STATUS: CERTIFIED does not mean the applicant got his/her H-1B visa approved, it just means that he/she is eligible to file an H-1B. For more details on this update, read this discussion.

CASE_STATUS: Status associated with the last significant event or decision. Valid values include “Certified,” “Certified-Withdrawn,” Denied,” and “Withdrawn”.
EMPLOYER_NAME: Name of employer submitting labor condition application.
SOC_NAME: Occupational name associated with the SOC_CODE. SOC_CODE is the occupational code associated with the job being requested for temporary labor condition, as classified by the Standard Occupational Classification (SOC) System.
JOB_TITLE: Title of the job
FULL_TIME_POSITION: Y = Full Time Position; N = Part Time Position
PREVAILING_WAGE: Prevailing Wage for the job being requested for temporary labor condition. The wage is listed at annual scale in USD. The prevailing wage for a job position is defined as the average wage paid to similarly employed workers in the requested occupation in the area of intended employment. The prevailing wage is based on the employer’s minimum requirements for the position.
YEAR: Year in which the H-1B visa petition was filed
WORKSITE: City and State information of the foreign worker's intended area of employment
lon: longitude of the Worksite
lat: latitude of the Worksite