<div align="center">

# Hi, I'm Satyam Singh 👋

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1200&color=2F81F7&center=true&vCenter=true&width=600&lines=Fresher+Backend+Developer;Learning+Java+%26+Spring+Boot+every+day;Building+REST+APIs%2C+one+project+at+a+time;Open+to+internships+%26+SDE-1+roles" alt="Fresher backend developer, learning Java and Spring Boot" />

**Computer Engineering graduate · Java & Spring Boot learner · I learn by building real projects**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Satyam_Singh-0A66C2?style=flat-square)](https://www.linkedin.com/in/satyam-singh-05b369376/)
[![LeetCode](https://img.shields.io/badge/LeetCode-silently__code-FFA116?style=flat-square&logo=leetcode&logoColor=white)](https://leetcode.com/u/silently_code/)
[![Email](https://img.shields.io/badge/Email-satyam.singh261103%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:satyam.singh261103@gmail.com)

</div>

---

## 🙋 About me

I'm a **Computer Engineering graduate** and a **fresher** learning backend development with **Java and Spring Boot**.
The way I learn best is by building something real: write the code, deploy it, break it, read the error, fix it, and write down what I learned.

- 🌱 **Learning now:** Spring Security, testing with JUnit 5 & Mockito, SQL, Docker
- 🛠️ **Building:** small but complete backend projects that are deployed and documented
- 🎯 **Looking for:** my first role as a Java backend / software developer (internship or SDE-1)
- 🤝 **Always happy to get:** code reviews and feedback; I learn a lot from them

### What I try to do in every project

- Keep the code simple and readable, with clear names
- Validate input and return clear error messages, not stack traces
- Keep secrets out of Git (environment variables only)
- Write tests for the main logic
- Write a README that explains how to run it
- Deploy it, so anyone can try it

---

## 🛠️ Tech I use

**Backend (my main focus)**

<img src="https://skillicons.dev/icons?i=java,spring,hibernate,postgres,mysql,redis,maven" alt="Java, Spring Boot, Hibernate, PostgreSQL, MySQL, Redis, Maven" />

`Spring Security` `JWT` `Spring Data JPA` `REST APIs` `JUnit 5` `Mockito`

**Tools & deployment**

<img src="https://skillicons.dev/icons?i=git,github,docker,postman,idea,vscode,vercel" alt="Git, GitHub, Docker, Postman, IntelliJ IDEA, VS Code, Vercel" />

`Render` `Neon (serverless PostgreSQL)`

**Frontend & JavaScript (enough to build full-stack projects)**

<img src="https://skillicons.dev/icons?i=html,css,js,ts,react,nextjs,tailwind,nodejs,express,mongodb" alt="HTML, CSS, JavaScript, TypeScript, React, Next.js, Tailwind CSS, Node.js, Express, MongoDB" />

---

## 📌 Projects

### 🥗 NutriScan: scan a food label, get a clear health verdict

`Java 21` `Spring Boot 4` `Spring Security + JWT` `PostgreSQL (Neon)` `Redis` `Docker` `Next.js`

Scan a barcode or search a packaged food, and NutriScan explains it in plain English: sugar, salt and fat levels, allergy and diet alerts, a veg / non-veg mark, and healthier alternatives.

- REST API with JWT login, BCrypt passwords, input validation, and one global exception handler, so every error has the same JSON shape
- Gets product data from Open Food Facts first, with an AI fallback; caches results with Caffeine and rate-limits guests with Redis
- 61 automated tests (unit + MockMvc) and a Dockerfile; API on Render, database on Neon, frontend on Vercel
- **What I learned:** stateless authentication, designing clean error responses, and configuring an app only through environment variables

[Code](https://github.com/silent-coder-dev/nutriscan) · [Live demo](https://nutriscan-web-pi.vercel.app)

### 🎫 SupportDesk CRM: customer support ticket system

`Java 21` `Spring Boot` `Spring Security` `Spring Data JPA` `MySQL` `Thymeleaf` `Docker`

A helpdesk app where customers raise support tickets and agents track and resolve them.

- Optimistic locking (`@Version`), so two agents can't overwrite each other's changes on the same ticket
- Role-based access with Spring Security, and email updates over Gmail SMTP when a ticket changes
- Detects duplicate tickets and follow-ups, and pushes live SLA updates to the page with Server-Sent Events
- **What I learned:** I started with SQLite, hit connection timeouts when many writes happened at once, and moved to MySQL. That's how I learned how databases handle locking.

[Code](https://github.com/silent-coder-dev/support-desk-crm) · [Live demo](https://support-desk-crm-qs00.onrender.com/tickets)

### 🤖 AI Resume Studio

`Next.js` `TypeScript` `Tailwind CSS` `Zustand` `Google Gemini API`

A resume editor that imports your existing PDF resume, proofreads it with AI, and compares it with a job description, without inventing skills you don't have.

- Reorder resume sections (for example, Projects before Experience, which helps freshers)
- Export the finished resume as a PDF
- **What I learned:** working with an AI API, and managing a large form's state cleanly

[Code](https://github.com/silent-coder-dev/ai-resume-builder) · [Live demo](https://ai-resume-builder-silent.vercel.app)

### 🧰 Smaller projects

| Project | What it does | Built with |
| --- | --- | --- |
| [Student Vault Desktop](https://github.com/silent-coder-dev/student-vault-desktop) | Desktop app to add, view, update and delete student records, with photos | Java Swing, JDBC, MySQL |
| [Online Diary](https://github.com/silent-coder-dev/Dairy) | Diary web app with full CRUD for text, image and video entries | TypeScript |
| [Weather Website](https://github.com/silent-coder-dev/Weather_Website) | Live weather for any city, with a matching background photo | HTML, CSS, JavaScript, OpenWeather API |

> The Render free tier puts servers to sleep, so the first request to a live demo can take about a minute.

---

## 🧭 My learning path

I'm a fresher, so this list keeps changing.

| ✅ Used in my projects | 🔄 Learning now | 🎯 Next on my list |
| --- | --- | --- |
| Core Java: OOP, collections, exceptions | Spring Security in more depth | System design basics |
| REST APIs with Spring Boot | Better tests with JUnit 5 & Mockito | Microservices with Spring Cloud |
| Spring Data JPA / Hibernate | SQL: joins, indexes, transactions | Messaging with Kafka |
| PostgreSQL & MySQL | Caching with Redis | AWS basics (EC2, S3, RDS) |
| JWT login with BCrypt passwords | Java multithreading | CI/CD with GitHub Actions |
| Docker, deploying on Render & Vercel | DSA on LeetCode | |

---

## 🧩 DSA practice

I solve problems on LeetCode to build problem-solving habits: **200+ solved so far**, mostly Easy and Medium.

`Arrays` `Strings` `Hashing` `Linked Lists` `Stack` `Queue` `Binary Search` `Recursion` `Sorting` `Trees` `Graphs` `Dynamic Programming`

<a href="https://leetcode.com/u/silently_code/"><img src="https://leetcard.jacoblin.cool/silently_code?theme=dark&font=Fira%20Code" alt="LeetCode stats for silently_code" /></a>

---

## 📊 GitHub stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=silent-coder-dev&show_icons=true&hide_rank=true&theme=tokyonight&hide_border=true" alt="GitHub stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=silent-coder-dev&layout=compact&theme=tokyonight&hide_border=true" alt="Most used languages" />

<img src="https://streak-stats.demolab.com?user=silent-coder-dev&theme=tokyonight&hide_border=true" alt="GitHub contribution streak" />

</div>

---

<div align="center">

I'm still learning, so feedback on my code is always welcome.<br>
Open an issue on any repo, or message me on [LinkedIn](https://www.linkedin.com/in/satyam-singh-05b369376/).

<br>

<img src="https://komarev.com/ghpvc/?username=silent-coder-dev&style=flat-square&color=2F81F7&label=Profile+views" alt="Profile views" />

</div>
