# Retrieving-Processing-and-Visualizing-Email--Honors-Capstone-Project
For this project, I retrieved a large set of email data from the web, and then I stored it in a database. I ran gmane.py, a python script, to retrieve email data and then store it into a database called content.sqlite. 

Next, I clean up the email data in content.sqlite by running gmodel.py, which normalizes the email data into structured tables and sends the data into the database index.sqlite.

I then run the gbasic.py to calculate histogram data on the retrieved email messages. I computed the top 25 email list participants and the top 25 email list organizations.

Next, I showcase the most common words used in the retrieved email through gword.py and visualize it with gword.htm.

At the very end,  I produce a timeline visualization of the emails retrieved through running the gline.py and visualize it with gline.htm.
