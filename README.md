# Resume-Refiner-AI-Agent
<img width="278" height="360" alt="image" src="https://github.com/user-attachments/assets/ad2f7b3a-1a4d-4b2e-aeec-23ee9a252b8e" />

## Overview
This project is an AI-powered Resume Refiner built in n8n. It takes a user-submitted resume and job posting, processes them using OpenAI, and returns tailored suggestions via email.
## Building the Agent
<img width="1158" height="467" alt="image" src="https://github.com/user-attachments/assets/bb37e86b-b8c7-4bc5-8ee4-5aff469d1df0" />

### What approach did you take to design your agent? 
- I started with the end in mind. I focused first on what I wanted the user to receive, which was a clear, useful email with personalized resume edits. That helped me reverse engineer the steps the workflow needed to take to achieve my goal.
- Secondly, I built and tested in small chunks. I added and tested each piece as I went to catch issues early.
- Thirdly, I focused on clarity over complexity. I kept the nodes in the workflow clean and grouped by purpose. If I ever go back to change something later, it is easy to follow.
## Trobleshooting
### What issues did you encounter and how did you resolve them?
- AI suggested experiences the user didn’t have. To Fix, I updated the prompt so AI would not invent or add content that isn’t already in the resume. I only wanted AI to rephrase and enhance existing material.
- "Insufficient quota detected"
<img width="324" height="87" alt="image" src="https://github.com/user-attachments/assets/7a4320f1-1ceb-44ca-a604-582f04074b85" />
    - My OpenAI account did not have enough credits or capacity to fulfill my initial request.  To fix, I needed to increase my usage limit to test various categories .
## Optimization
### What might you improve or add in future iterations?
- Multi-job support
  - It would be helpful if users could paste in several job descriptions at once and get a comparison report showing how their resume stacks up to each one.
