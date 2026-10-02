<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B1120,100:2563EB&height=220&section=header&text=Mohd%20Haris%20Khan&fontColor=ffffff&fontSize=42&animation=fadeIn&fontAlignY=38&desc=Software%20Engineer%20%7C%20Full-Stack%20MERN%20%7C%20Java&descAlignY=58&descSize=18"/>

<img src="https://readme-typing-svg.demolab.com?font=Poppins&weight=600&size=24&pause=1200&color=60A5FA&center=true&vCenter=true&width=850&lines=Software+Engineer;Full-Stack+Developer+%7C+MERN;Java+%2B+Data+Structures;Currently+building+ErrorLens"/>

<br><br>

<a href="mailto:mohdhariskhan15@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/mohdhariskhan/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://leetcode.com/u/hariskhan01613/"><img src="https://img.shields.io/badge/LeetCode-100%2B%20solved-FFA116?style=for-the-badge&logo=leetcode&logoColor=black"/></a>
<a href="https://my-portfolio-one-eta-82.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-2563EB?style=for-the-badge&logo=vercel&logoColor=white"/></a>

<br><br>

<img src="https://img.shields.io/badge/Open%20to%20Work-Software%20Engineer%20%7C%20Full--Stack%20%7C%20Java-16A34A?style=flat-square"/>

</div>

---

## 👋 About Me

B.Tech Computer Science graduate (2026) from NIET, Greater Noida. I build full-stack web applications with the **MERN stack** and solve data structures and algorithms problems in **Java** (100+ LeetCode problems so far).

I built and deployed the **Job Application Tracker** (below) end to end, and I'm now working on **ErrorLens**, a bigger project to deepen my backend skills: APIs, testing, Docker and LLM integration.

I'm looking for a **Software Engineer / Associate Software Engineer / Full-Stack Developer** role where I can ship features, learn from code reviews and grow quickly.

---

## 🛠️ Tech Stack

**Languages**
<br>
<img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
<img src="https://img.shields.io/badge/SQL-Basics-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>

**Frontend**
<br>
<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
<img src="https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white"/>

**Backend & Database**
<br>
<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white"/>
<img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white"/>

**Tools**
<br>
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
<img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white"/>
<img src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white"/>

**Core concepts:** Data Structures & Algorithms · Object-Oriented Programming · REST APIs · JWT Authentication · DBMS

---

## 🚀 Projects

### 📋 Job Application Tracker
A full-stack app to track job applications by company, role, status and follow-up date, with each user's data kept private.

- 🔐 JWT authentication and protected routes (users only see their own data)
- ✅ Input validation and error handling on the REST API endpoints
- 🔄 Create, update, filter, sort and delete applications
- 📊 Status views: Applied, Interview, Offer, Rejected
- 📱 Responsive dashboard
- ☁️ Deployed live with MongoDB Atlas

**Tech:** `React` `Node.js` `Express.js` `MongoDB` `Mongoose` `JWT`

🔗 [**Live Demo**](https://job-application-tracker-one-zeta.vercel.app/) (first load may take a moment if the server is asleep) · 💻 [**Source Code**](https://github.com/hariskhan1613/job-application-tracker)

---

### 🔍 ErrorLens: AI-Assisted Error Monitoring for Node.js Apps
![Status](https://img.shields.io/badge/Status-In%20Progress-F59E0B?style=flat-square)

A mini error-monitoring tool: a small SDK captures errors from a Node.js app, an API groups duplicate errors into issues, and an LLM suggests a likely cause and fix. I'm building it from scratch to learn backend engineering properly, and I plan to run it on my own Job Application Tracker.

**Planned architecture**

```mermaid
flowchart LR
  A[Node app + ErrorLens SDK] -->|batched events| B[Ingestion API]
  B --> C[Fingerprint and group errors]
  C --> D[(MongoDB)]
  C --> E[LLM triage]
  D --> F[React dashboard]
  E --> F
```

**What I'm building**
- [ ] Ingestion API with API-key auth and request validation
- [ ] Error fingerprinting and grouping
- [ ] npm SDK with batching and retry
- [ ] React dashboard with issue list and charts
- [ ] LLM-based triage with caching and validation
- [ ] Tests, Docker and CI

**Planned stack:** `Node.js` `Express.js` `TypeScript` `MongoDB` `React` `Jest`

💻 Source code: coming soon (will be linked here once the first milestone is pushed)

---

## 📚 Currently Learning

| Area | Focus |
|---|---|
| ⚙️ Backend | TypeScript, API design, validation, authentication |
| 🧪 Quality | Testing with Jest and Supertest |
| 🐳 DevOps | Docker, GitHub Actions |
| 🗄️ Databases | MongoDB indexing and aggregation |
| 🤖 AI | Integrating LLM APIs into applications |
| 🧠 Problem solving | Data structures and algorithms in Java |

---

## 📊 GitHub Analytics

<div align="center">

<img height="180" src="https://github-readme-stats-pearl-omega.vercel.app/api?username=hariskhan1613&show_icons=true&hide_border=true&theme=tokyonight&rank_icon=github&include_all_commits=true"/>

<img height="180" src="https://streak-stats.demolab.com?user=hariskhan1613&theme=tokyonight&hide_border=true"/>

</div>

<br>

<div align="center">

<img height="180" src="https://github-readme-stats-pearl-omega.vercel.app/api/top-langs/?username=hariskhan1613&layout=compact&hide_border=true&theme=tokyonight&langs_count=8"/>

</div>

---

## 🏅 Certifications

- Object-Oriented Programming in Java (Coursera)
- Java Programming: Arrays, Lists, and Structured Data (Coursera)
- Database Management Systems (Infosys Springboard)
- Python for Data Science, AI & Development (IBM / Coursera)

---

## 🎓 Education

**B.Tech in Computer Science and Engineering**
Noida Institute of Engineering and Technology (NIET), Greater Noida · 2022 – 2026

---

## 📫 Let's Connect

<div align="center">

<a href="mailto:mohdhariskhan15@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/mohdhariskhan/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://leetcode.com/u/hariskhan01613/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black"/></a>

<br>

> *Build with purpose. Solve with logic. Keep learning.*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2563EB,100:0B1120&height=120&section=footer"/>

</div>
