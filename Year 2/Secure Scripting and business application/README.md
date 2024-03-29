# Secure Scripting and Business Application

This module's assignment was based around "insecure code". The task I was given was to improve code which was given to us. 
Below is an example of the insecure code I had to improve.

# Script 1
![image](https://github.com/Cameron-Skerritt/University-Projects/assets/122690042/1d6bd4c0-dd74-4ca5-8591-a25cdfdf6916)

In this script, the main vulnerability is that we pass raw "SQL", this is troublesome as attackers could inject their own malicious sql code.

# Script 3
![image](https://github.com/Cameron-Skerritt/University-Projects/assets/122690042/0315d3ee-3252-4eab-81b4-129606572fca)

In this script, we break GDPR regulations by not prompting the user to agree / disagree with the terms & conditions.
Additionally, we do not ask for their ask to ensure they can use the app.

With these consideraitons in mind, the script I made improved upon this, however, I could not make my own database due to time constraints.
So, with this in mind, this is an adapatation of what the code would act like if it was linked to a database.

To solve these issues, I made Secure_Script.py, this encompases all the concerns and fixes them accordingly.

# Python War Game
This game was created as an assignment based on a brief which had criteria that I had to hit.
The criteria asked for:
- Player Names
- Round Limit
- Score Keeping
- Special Cards
- Save & Load feature
- Challenge: Custom rules or feature

This program took over a week to code & debug, I eventually got it working, the hardest part was coding the "war" function (when two players draw the same cards). That function took me around 3~ days to make it fully work. 
