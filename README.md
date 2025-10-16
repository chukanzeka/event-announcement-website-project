🚀 Building an Event Announcement Website on AWS

https://www.linkedin.com/pulse/building-event-announcement-website-aws-lessons-from-my-chuka-nzeka--qmhxe/?trackingId=l7ft5Ub0ZCJzxeX0o7MZHw%3D%3D

📌 Project Overview
The goal of this project was to create an event announcement website capable of:
•	📧 Allowing users to subscribe to event notifications via email.
•	📅 Displaying a list of upcoming events.
•	📝 Enabling users to create new events through a web form.
•	⚡ Sending real-time alerts (new event notifications) to subscribers.

 🛠️ AWS Services Used
•	Amazon S3 → Used for hosting the frontend and storing event data (events.json).
•	Amazon SNS → Used for sending email notifications and managing subscriptions.
•	AWS Lambda → Used for the backend logic (creating events & managing subscriptions).
•	Amazon API Gateway → Exposed endpoints for frontend ↔ backend communication.
•	IAM Roles & Policies → Controlled secure access between AWS services (S3, SNS, Lambda).

🎉 The Result
The website now:
•	✅ Hosts a static frontend where users can view events, subscribe via email, and create new events.
•	✅ Stores new events in events.json (S3).
•	✅ Triggers SNS via Lambda to send emails to all subscribers whenever a new event is added.
 
Event Announcement Webpage
✨ Next Steps
Once it was working, I wanted a better frontend design. With the help of AI, I redesigned the UI into a brighter, modern card-style layout in just minutes. Uploading the new index.html gave the project a polished, user-friendly look.
I’d love to hear your thoughts — do you prefer the original design or the redesigned version? 
 

