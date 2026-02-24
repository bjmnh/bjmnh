# Benjamin Hanson

Computer Science graduate and Software Developer with experience creating responsive full stack web applications that implement SQL/NoSQL databases, user authentication, cloud functions, API integrations (Stripe, Claude/Gemini, N8N) and security best practices across various cloud platforms (GCP, AWS, Supabase). 

I stay up to date with the latest news on current AI assisted coding techniques and put them into practice to maximize leverage without compromising code quality and security (though I believe  there is a lot of hype/overengineering going on at the moment). 

Currently working on freelance technical AI training studies, personal projects, and in the process of obtaining CompTIA Security+ Certification.

<p align="center">
  <img src="https://raw.githubusercontent.com/8bithemant/8bithemant/master/svg/dev/languages/python.svg" alt="python" style="vertical-align:top; margin:4px">
  <img src="https://raw.githubusercontent.com/8bithemant/8bithemant/master/svg/dev/languages/js.svg" alt="js" style="vertical-align:top; margin:4px">
  <img src="https://raw.githubusercontent.com/8bithemant/8bithemant/master/svg/dev/languages/csharp.svg" alt="csharp" style="vertical-align:top; margin:4px">
  <img src="https://raw.githubusercontent.com/8bithemant/8bithemant/master/svg/dev/frameworks/react.svg" alt="react" style="vertical-align:top; margin:4px">
  <img src="https://raw.githubusercontent.com/8bithemant/8bithemant/master/svg/dev/tools/bash.svg" alt="bash" style="vertical-align:top; margin:4px">
  <img src="https://raw.githubusercontent.com/8bithemant/8bithemant/master/svg/dev/tools/visualstudio_code.svg" alt="vscode" style="vertical-align:top; margin:4px">
  <img src="https://raw.githubusercontent.com/8bithemant/8bithemant/master/svg/dev/services/gcp.svg" alt="gcp" style="vertical-align:top; margin:4px">
  <img src="https://raw.githubusercontent.com/8bithemant/8bithemant/master/svg/dev/services/aws.svg" alt="aws" style="vertical-align:top; margin:4px">
</p>

- 🔗 Connect with me on [LinkedIn](https://www.linkedin.com/in/ben-wh)

---

## My Projects

Here are some projects I am proud of:

## Legal-Ease | Legislative Impact Analyzer (Capstone)
<img width="1915" height="955" alt="Screenshot of the Legal-Ease application dashboard" src="https://github.com/user-attachments/assets/e2a09211-f135-4e36-8e85-2e17e22d9fdf" />

---

This web application features a React.js frontend that interacts with a Google Firebase backend to present up to date information on federal legislation and offer integrated tools including AI analysis (powered by Gemini) to identify the potential impacts on federal law. It utilizes Cloud Functions and a NoSQL database (Firestore) to collect and cache current bill data fetched directly from CongressAPI. The frontend is optimized for user experience and is feature rich, including the ability to track and be notified about changes to relevant legislation. Try it out yourself! Feel free to use a dummy email to sign up as I have disabled email verification.

I created this application over the course of my senior year as my capstone project. I was assigned to this project that had been submitted to the university by an external client and I was responsible for interviewing him and translating his requests into user stories and eventually working features. Much of the project was completed manually but as AI assisted IDEs like Cursor and Windsurf were rolled out that year, I took the opportunity to learn how to utilize them. This project taught me that the most impactful documentation particularly during AI assisted development is the exact format of data that is being sent and received by API and function calls. This was my first real full stack application so it was a learning experience start to finish, and it went through lots of trial and error to arrive at where it is today.


**Tech Stack:** React, Node.js, Firebase (Auth & Firestore), Gemini API, Congress API

[Live Demo](https://legal-ese.netlify.app/)

---

## ChatInsights | AI Conversation Data Visualization Tool (Hackathon)
<img width="1548" height="934" alt="Screenshot of the ChatInsights project UI" src="https://github.com/user-attachments/assets/7aa98739-6974-4604-8efc-9f8cbca8ccf4" />

---

This hackathon project takes your exported AI conversation data (from Anthropic, OpenAI, or Google) and performs detailed AI powered analysis, converting it into an entertaining and insightful experience where you can explore what you have revealed about yourself from your conversations. The application offers a basic report and a premium report. Feel free to try out with your own data or just check out the sample report on the website!

Bolt.ai hosted this hackathon and challenged participants to utilize their platform to supercharge frontend development and create a novel software product offering. You can read more about my development process in the devlog below.

**Tech Stack:** React, Node.js, Express, Supabase, TailwindCSS, Gemini API, Stripe API

[Live Demo](https://chatinsights.online/) | [Devpost](https://devpost.com/software/chatinsights) | [Source Code](https://github.com/bjmnh/ChatInsights)

---

## Celey | Scalable AI Video Generation Platform
<img width="1916" height="935" alt="Screenshot of the Celey video generation dashboard" src="https://github.com/user-attachments/assets/2e4bdc53-f715-4c5a-91ad-72cac61cb670" />
<img width="1914" height="932" alt="Screenshot of the Celey video generation dashboard" src="https://github.com/user-attachments/assets/de877aba-c303-47f7-bdd4-91bb606f66e7" />

---


Celey is a video generation platform that transforms static photos into high-fidelity, animated celebration videos to show at birthday parties, celebrations, or family group chats. The application leverages cutting-edge generative video models (supporting Runway and Luma) through a custom-built asynchronous processing pipeline designed to handle long-running AI tasks. Users can choose from a library of themed templates or provide custom prompts to dictate the AI's creative direction. To ensure a professional-grade user experience, I integrated a robust credit-based subscription system and a secure media delivery pipeline. It is still in development but you can try it out with free credits by creating an account. 

I developed this project with the purpose of learning how to build a production-ready SaaS architecture on AWS. The biggest technical challenge was moving away from simple synchronous API calls which I learned would time out before video generation completed and instead I implemented a decoupled architecture using AWS SQS to queue jobs and AWS Lambda to handle the interfacing with Video AI APIs. Videos are securely stored in S3 and served globally via CloudFront CDN. This project helped me to familiarize myself with the AWS environment and practice developing event-driven architecture.

**Tech Stack:** Next.js, TypeScript, Supabase (Auth & Postgres), AWS (Lambda, SQS, S3, CloudFront), Stripe API

[Live Demo](https://celey.netlify.app/)

---

## Split the Room | Party Game
<img width="1890" height="923" alt="SplitTheRoom Frontpage" src="https://github.com/user-attachments/assets/b72c7131-f569-4fd4-92ea-5cfc7063d7ec" />

---

This is a fan recreation of the Jackbox Game of the same name. The game is split into two phases where players create dilemmas and then vote on each others'. The objective is for players to create dilemmas that half the other players would accept and half would reject. You are rewarded more points the closer you are to 50/50. You can try it out now for free (if you have at least 2 people).

**Tech Stack:** React, Node.js, Firebase (Firestore)

[Live Demo](https://splitroom.netlify.app/)





