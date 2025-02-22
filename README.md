# Missing keywords in your resume from the job description. 
# Why?
While I was applying for jobs every day, I would verify if my resume was a good fit for each position. Then I would compare my resume with the job description, but this process was often quite time-consuming. Thus, as a data engineer, I aimed to streamline this issue and developed a concept to automate it.

# How?
I provide all the keywords as input along with my resume in a text file format, which is more convenient for PySpark to process. The text file will be transformed into an RDD, and then we will evaluate the count of keywords by examining the file line by line. This will yield a percentage score and highlight any missing skills.

# Future Development

Integrate the current code with AI , AWS cloud and Apache Airflow.
Resume Match Score with PySpark is an AI-driven pipeline that automates job description (JD) processing and resume analysis to provide missing keywords. The project leverages AWS S3, Lambda, Apache Airflow, and NLP to optimize Applicant Tracking Systems (ATS) and enhance resume alignment with job postings.

# Features

Automated JD Processing: Designed an NLP-driven pipeline that extracts and processes job descriptions via AWS S3, Lambda, and Apache Airflow, reducing manual effort by 80%.

AI-Based Matching Algorithm: Utilizes Natural Language Processing (NLP) to extract key skills, experience, and role requirements from job descriptions and compare them with resumes to generate an accurate match score.

ATS Optimization & Notifications: Automatically delivers personalized job fit scores, missing skill insights, and keyword recommendations through email notifications, improving resume alignment with job postings.


 For one file we can easily process using python , but in terms of developing further I have implemented in Pyspark.
