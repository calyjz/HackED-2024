# HackED-2024: Caleb's All-Seeing Eye
Hi there! This is a discord content moderation bot called **Caleb's All-Seeing Eye**, developed for the hackathon HackED 2023. 
This bot uses models to detect and flag hate speech, harmful content, and misinformation.
## Approach
Hate Speech and Harmful Content  
Caleb's All-Seeing Eye integrates OpenAI's moderation API to flag for hate speech. Any messages that are flagged will appear in the #bot-flags channel for moderators to review. Here, the moderators are able to delete the message, timeout the user for 60s, 5m, 10m, 1h, 1d or 1w, kick the user, or ban the user.   
Misinformation  
To combat misinformation in discord servers, we've integrated Google's fact checker API. To fact check a message, first click the three dots associated with that message. On mobile, users will need to hold down the message. Afterwards, navigate to apps -> fact check. After running this command, Caleb's All-Seeing Eye will send a list of relevant news articles related to the content in the initial message, allowing users to quickly access verified information and make informed decisions about the content of the message.
## Implementation
This bot utilized Javascript, OpenAI API, Google Fact Check API, and Discord.js and was coded in under 16 hours. 


Built By The New Anonymous,  
Ben, Caleb, Caly, Jeffery, Jeremy