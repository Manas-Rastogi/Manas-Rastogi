<div align="center">

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=1000&color=64B5F6&center=true&vCenter=true&width=700&lines=Java+%26+Python+Backend+Engineer;Spring+Boot+%7C+FastAPI+%7C+Microservices;REST+APIs+%7C+AI+Integrations+%7C+Automation;Building+Systems+That+Scale)](https://git.io/typing-svg)

### Manas Rastogi
Backend Engineer building event-driven microservices with Spring Boot, RabbitMQ and Docker, and AI-powered automation with Python, FastAPI and Groq.
Currently seeking **Backend Engineering Internship / Java Backend Developer** roles.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/manas-rastogi-181426329)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=flat-square&logo=firefox&logoColor=white)](https://manas-rastogi-dev.netlify.app)
[![Gmail](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:manasrastogi64@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Manas-Rastogi)

</div>

---

## About Me

I design and ship backend systems end-to-end — authentication, APIs, service-to-service messaging, AI-powered data pipelines and deployment — with a focus on clean service boundaries and secure-by-default design. My recent work spans animal-rescue logistics, healthcare resource matching, civic-tech automation and startup lead research, all built as independently deployable services.

- 🔧 Currently building distributed systems with **Spring Boot**
- 🐍 Building AI-powered automation with **Python**, **FastAPI**, **Groq** and **Tavily**
- 📨 Comfortable designing event-driven flows with **RabbitMQ**
- 🔐 Security-first: **JWT**, **OAuth2**, **Spring Security**, role-based access control
- 🗄️ Work across both relational (**MySQL**) and document (**MongoDB**) data models
- 🐳 Containerize services with **Docker**; currently learning **AWS** and **Kafka**
- 📍 Based in Bareilly, UP, India — open to remote and relocation

---

## Tech Stack

**Languages**
![Java](https://img.shields.io/badge/Java_17-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

**Backend & Frameworks**
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=flat-square&logo=hibernate&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white)

**AI & External APIs**
![Groq](https://img.shields.io/badge/Groq_API-F55036?style=flat-square)
![Tavily](https://img.shields.io/badge/Tavily_API-4F46E5?style=flat-square)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)

**Databases & Messaging**
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)

**DevOps & Tooling**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger_OpenAPI-85EA2D?style=flat-square&logo=swagger&logoColor=black)

**Currently Learning**
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)

---

## Featured Projects

### StartlyAI — AI-Powered Startup Research Platform
Automates the discovery of newly funded startups and collects company and employee information. A scheduler runs every 7 hours, Tavily searches the web for funding news, and Groq AI converts the unstructured results into structured JSON. The system skips startups that were already researched to save API calls, then runs a second stage to find founders, CTOs and public professional contacts, stored in separate MongoDB collections. Built with a layered architecture (routes, services, repositories) using constructor injection and FastAPI `Depends()`.

`Python` `FastAPI` `MongoDB` `Tavily API` `Groq AI` `Scheduler`

**[View Repository →](https://github.com/Manas-Rastogi/Startly-AI)**

---

### CarePaws — Microservices Platform for Animal Rescue Coordination
Connects citizens, NGOs, and municipal teams to route stray-animal rescue requests in real time. Built as 6 independently deployable Spring Boot services communicating over RabbitMQ, with JWT-based authentication, role-based access control, and a geo-aware engine that assigns incidents to the nearest available rescuer.

`Spring Boot` `RabbitMQ` `MongoDB` `Docker` `JWT / RBAC`

**[View Repository →](https://github.com/Manas-Rastogi/CarePaws-Microservices-Project)**

---

### CivicInsight — AI-Powered Political Office Management System
Digitizes political and civic offices by automating citizen grievance intake, classification, and workload-balanced routing to officials. Uses Ollama with Llama 3 for on-device grievance classification, Google OAuth2 for one-click citizen login, and a location-aware routing engine backed by real-time dashboards for office staff.

`Java` `Spring Boot` `Ollama / Llama 3` `Google OAuth2` `MongoDB`

**[View Repository →](https://github.com/Manas-Rastogi/CivicInsight-Backend)**

---

### HealthTracker — Hemophilia Patient Care Platform
Backend system connecting hemophilia patients with nearby NGOs and hospitals for coordinated treatment. Includes an automated factor-dosage calculation engine, geo-based matching between patients and available resources, and role-secured access via Spring Security for patients, hospitals, and NGO staff.

`Spring Boot` `MongoDB` `Spring Security`

**[View Repository →](https://github.com/Manas-Rastogi/HealthTracker-Backend)**

---

### RecruitMate — Recruitment Management System
Full applicant-lifecycle backend for enterprise hiring workflows — job postings, resume upload and parsing, application tracking, and an admin panel for managing candidates through the hiring pipeline. JWT-based auth with role separation between admins and applicants.

`Spring Boot` `JWT` `MySQL`

**[View Repository →](https://github.com/Manas-Rastogi/RecruitMate)**

---

## GitHub Stats

<div align="center">

<img height="165em" src="https://github-readme-stats.vercel.app/api?username=Manas-Rastogi&show_icons=true&theme=github_dark&hide_border=true&count_private=true&include_all_commits=true&title_color=64b5f6&icon_color=64b5f6&text_color=c9d1d9&bg_color=0d1117"/>
<img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Manas-Rastogi&layout=compact&theme=github_dark&hide_border=true&title_color=64b5f6&text_color=c9d1d9&bg_color=0d1117"/>

</div>

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=Manas-Rastogi&theme=darkhub&no-frame=true&no-bg=true&column=4&margin-w=15&margin-h=15&title=Commits,Repositories,PullRequest,Stars"/>

</div>

---

## Let's Connect

Open to full-time roles, internships, and freelance backend work.

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/manas-rastogi-181426329)
[![Email](https://img.shields.io/badge/Email_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:manasrastogi64@gmail.com)
