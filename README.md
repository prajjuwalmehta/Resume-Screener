# Resume-Screener
Introduction
This project is a Resume Screening project which is used for screening a candidate’s resume using python language and tell whether the candidate is fit for a job or not 
Writing a resume is not a trivial task, especially when it comes to the right selection of keywords. People spend hours writing and formatting the perfect resume hoping it to be read by a talent acquisition professional and, eventually, help them land a job interview. Unfortunately, around 75% of resumes submitted are never seen by a human eye.
Due to the high number of applicants and resumes submissions to job postings, manual resumes screening processes become tedious, ineffective and time consuming for talent acquisition professionals. Therefore, standardized automated screening methods are necessary to categorize qualified from unqualified candidates based on their background, education and professional experience faster, with more efficiency and more accurate results to streamline hiring processes.
In this project we will be making a Resume Screening model in which the user can upload any resume and our model will tell the percentage of how much the submitted resume is matching with the job description or the user can also check the various workfields  that the resume is fit for.
 
 

Context

This project has been done as a part of my course for B.tech-CSE at Graphic Era University,Dehradun

Problem statement

To create a project ” Resume Screening based on Job Description using Python”  to show the percentage of how much the candidate’s resume matches with given job description.


motivation
The brief motivation behind this project is to provide the users with  an automated Resume Screener which will be used to tell whether a candidate is eligible for a certain job or not with more efficiency and more accuracy

Tools used

To accomplish this project following tools were used:
Operating System : Windows 10
IDE used: Spyder(anacoda3)
Language used: Python 
Libraries used:
●	PyPDF2:- PyPDF2 is a free and open source pure-python PDF library capable of splitting, merging, cropping, and transforming the pages of PDF files. It can also add custom data, viewing options, and passwords to PDF files. PyPDF2 can retrieve text and metadata from PDFs as well.
●	re:- A regular expression is a special sequence of characters that helps you match or find other strings or sets of strings, using a specialized syntax held in a pattern. Regular expressions are widely used in UNIX world.
●	string:-the string library contains a number of methods to process strings in Python
●	Pandas:-Pandas is an open-source library that is made mainly for working with relational or labeled data both easily and intuitively. It provides various data structures and operations for manipulating numerical data and time series. This library is built on top of the NumPy library. Pandas is fast and it has high performance & productivity for users.
●	Matplotlib:- Matplotlib is a comprehensive library for creating static, animated, and interactive visualizations in Python. Matplotlib makes easy things easy and hard things possible.
●	docx2txt:- A pure python-based utility to extract text and images from docx files.
●	CountVectorizer from sklearn.feature_extraction.text:- Convert a collection of text documents to a matrix of token counts.
●	cosine_similarity from sklearn.metrics.pairwise:- Compute cosine similarity between samples in X and Y.

 
 

Methodology
This project not only help me in gathering information about new technologies but also made me realize the use of programming in real life.
Now let’s start with the various steps used in completing this project.

First we have to install all the libraries which are required for our project and then import then into our project
Then we have to read the pdf  file and extract all the text from the file
Then we have to clean the extracted text by converting all the string to lower case ,removing all the numbers and punctuations
Then we have to create a dictionary with industrial and system engineering key terms by area the key terms included in each area of this dictionary were obtained through a research of the most common key terms included in industrial and system engineering job postings.
Now we have to calculate the scores for each area and stored the result in a data frame. Using this data frame we have created a piechart with the help of this  pie chart we can determine the highest expertise level in an industrial and system engineer’s resume out of the six concentration area


After this we have to take Job description in the form of text document and extract text from it .Now we have to find similarity between the resume and job  description using Cosine Similarity.
At last we have to find match percentage .This will tell by how much percentage the resume matches with the job description.


Conclusion
The project was completed successfully, I got to learn so many new things while working on this project. It helped me learn how to work with different python libraries and data in the form of PDFs and docs and also helped me in learning the implementation of various concepts. I have also gone through many possible applications of artificial intelligence and text mining on resume screening programs. Real Applicant Tracking Systems are quite more complex and advanced than the program built in here; they not only scan resumes content but their format too. It is crucial for candidates to know how resume screening systems work to beat them and get their resumes to be viewed by a talent acquisition professional.
