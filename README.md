# seek_job_application_organizer_automation
This repo contains a notebook created using python selenium to automate the process of keeping a record of the seek.com weblink in an organized manner to facilitate following up with the jobs that the user applied for.

Overall process is as follows
=============================
1.) Connect to the chrome webdriver
2.) Get the weblink correcponds to the relevant job advert from the seek.co
3.) Identify the xpath elements in the webpage for the necessary information that needed to be collected (ex: job title, company, etc.)
4.) Get the whole text in to a string so that the text can be later analyzed using NLP to predict text features in future
5.) Create a dictionary with the above details
6.) Append the dictionary to a running CSV file that contains previosly extracted job application details

