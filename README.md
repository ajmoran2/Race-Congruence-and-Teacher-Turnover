# Race-Congruence-and-Teacher-Turnover
This repository is intended to provide a replication template for my Race Congruence and Teacher Turnover paper.  This paper used exclusively publicly available data so all data is included, as downloaded from the internet.  I have also included a range of do-files that will reproduce the analysis, tables, and figures included in this paper. 

Do-files are numbered in the order that they should be run, which is listed below:
  1. rc_dataupload - this file will upload all files downloaded from the internet into Stata. School-level files are downloaded directly from [Urban Institutes Education Data Portal](https://educationdata.urban.org/documentation/schools.html). Teacher-level files are downloaded from the [Pennsylvania Department of Education Data Site](https://www.education.pa.gov/DataAndReporting/ProfSupPers/Pages/ProfPersIndStaff.aspx). FAIR WARNING: this file takes a long time to run and is a little finicky while interacting with the Data Portal site.
  2. rc_datacleaning - this file cleans and merges all the school-level and teacher-level files into one main analytic file.  There are decisions that are made about how to treat teachers will multiple assignments in this file that are specific to my purpose for this paper so be cautious if deciding to use this file for other reasons.
  3. rc_analysis - this file contains all of the analysis and table/figure creation for my paper

If issues arise with any of the downloads or do-files, please reach out to me at amoran2@fsu.edu.  NB: this is my email while I am a PhD student. I graduate(d) in the spring of 2025, so if you are accessing this after that time, that email might not work anymore.  If so, please try alexjmoran005@gmail.com.  
