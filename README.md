# notification-centralization-tool
This is a simple tool used to centralize my personal notifications from different sources

Have you ever felt tired from having to constantly check for new announcements made by the teachers at different sources (such as facebook groups, faculty portals, Google Classroom, Microsoft Team…etc)?
Well I certain have!!!
That’s why I’m making a simple tool to help me check for notifications every day. Now I did try to search online for an easy solution of copying and pasting the codes, and I came across [this](https://www.geeksforgeeks.org/python-script-to-monitor-website-changes/) article. However, just knowing if the website is changed by hashing the entire website is not what I aim for, since you would still need to manually check for what the new announcement is, so I thought I might just make my own version.

-------------------------------------------------------
1.	The idea

The idea is that once the website (e.g the faculty portal)  got changed in the “Announcement” section, the tool should be able to detect that and take the content of the newly added announcement and dump it into an output of sorts.

-------------------------------------------------------
2.	The methods


I will use Python as the main language for 2 reasons. Firstly, this is a personal project that I do not have much time to invest in so using Python with its large number of usable libraries would greatly reduce the time I need to develop a simple working program. Secondly, I have just learned Python by myself, so I would like to use this project to learn more about the programming language.

-------------------------------------------------------
3.	What next?


Scanning for a new announcement on a website is only the beginning. What I want to do next is to get latest news from the following source:
-	Facebook groups
-	Gmail
-	Microsoft Teams
-	Google classroom
-	Discord channels
-	…
The output of the tool currently could be just a .txt file or some other simple methods. However, in the future, I would want the output to be:
-	Discord bot
-	Gmail
-	…
