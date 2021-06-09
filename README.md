# Data Science for job hunting in Data Science
In my current job hunting in Data Science, I found the video https://www.youtube.com/watch?v=Y5ZbzTryBZY from the channel "Self-made millennial", about job searching, interviews... There, Madeline Mann described a "high intensity" strategy for job searching.

The main goal of this strategy is to make as many personal interactions with colleagues as possible, in order to get advice about the role, position, and industry, and focus on some companies as a target, looking for interactions with employees of those companies, in a more or less random way, to get information about the "target" department, the managers or supervisors of that department, and get information about possible roles or opportunities.

At the end, all this is just a problem of information processing, so I plan to chop all this strategy into different steps and apply a programmatic or analytical approach to each of them. 

## 1-General Interactions
Here, the basic idea is to have as many interactions as possible with people to get information that can be valuable in our job hunting. The original video speaks about to tell random people about your job hunting, but in the current pandemic situation, I am going to simplify this task, so for this interactions will be "Sending email to Data scientifics around the UK and maybe other places in the world, and analyise those emails"

Possibly, a SQLite Db will be created to add a bit of SQL magic into the project 

For this, I need to:

-Create a Database of those people, with their name, email, and, if known, role and company.

-Write a number of templates, to ask information that can be helpful in the future.

-Create a python script to automatically pick one of the templates, complete with the data from the database, send it by email, and register what templeted was sent to who. 

-Check received messages to see any answer to my emails. We can use this data to check with templates work better, and apply a sentiment analysis to the body of the answers.
