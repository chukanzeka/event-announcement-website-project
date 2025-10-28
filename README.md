🚀 Building an Event Announcement Website on AWS

📖 LinkedIn Article - https://www.linkedin.com/pulse/building-event-announcement-website-aws-lessons-from-my-chuka-nzeka--qmhxe/?trackingId=l7ft5Ub0ZCJzxeX0o7MZHw%3D%3D
---

📌 Project Overview -

The goal of this project was to create a simple, scalable Event Announcement Website that enables users to:

📧 Subscribe to event notifications via email

📅 View a list of upcoming events

📝 Create new events through a web form

⚡ Receive real-time alerts when new events are added
---

🛠️ AWS Services Used -

Amazon S3:	Hosts the static frontend and stores event data (events.json).

Amazon SNS:	Manages email notifications and subscriber lists.

AWS Lambda:	Handles backend logic (creating events, triggering notifications).

Amazon API Gateway:	Exposes RESTful endpoints for frontend ↔ backend communication.

IAM Roles & Policies:	Enforces secure access between AWS resources.
---

🎉 The Result -

✅ Fully Functional Website:
Users can view, subscribe, and create events directly from the frontend.

✅ Event Storage:
New events are saved automatically to S3 (events.json).

✅ Real-Time Notifications:
Each new event triggers SNS via Lambda, sending alert emails to all subscribers.
---

✨ Frontend Redesign -

After achieving full functionality, I wanted a cleaner, more modern UI.
With the help of AI, the design was transformed into a brighter, card-style layout — improving readability and visual appeal.

💬 Feedback

I’d love to hear your thoughts:

Do you prefer the original design or the AI-redesigned version?
---

Author: Chuka Nzeka


Project Type: AWS Cloud / Serverless / Frontend Integration


