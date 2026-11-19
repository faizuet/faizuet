<div align="center">

<img src="profile-image.png" width="100%" alt="Muhammad Faiz, Backend Software Developer at NexVolt Solutions"/>

<br/>

**Backend and Cloud Engineer**

Python · FastAPI · AWS · Linux · Docker

Peshawar, Pakistan · Open to remote, onsite, and relocation

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/muhammad-faiz-backend)
[![Email](https://img.shields.io/badge/Email-0F2C59?style=flat&logo=gmail&logoColor=white)](mailto:faizuet7@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-1D4ED8?style=flat&logo=github&logoColor=white)](https://github.com/faizuet)

<br/>

[About](#about) · [Skills](#skills) · [Experience](#experience) · [Projects](#projects) · [GitHub](#github) · [Learning](#learning) · [Contact](#contact)

</div>

---

<a id="about"></a>

## About

I am a backend and cloud engineer at **NexVolt Solutions** in Peshawar. Most of my work is Python APIs, PostgreSQL, and the AWS and Linux hosts those APIs run on.

Before this role I interned on backend services at **Wanclouds Inc.** in Islamabad and, earlier, at **Go Jins** as a remote Python backend intern.

I am currently working on AWS infrastructure and [ImagifyAI](#imagifyai), and I am learning Kubernetes and system design alongside that work.

---

<a id="skills"></a>

## Skills

| Area | Technologies |
| --- | --- |
| Backend | Python, FastAPI, Flask, REST APIs, Pydantic |
| Data | PostgreSQL, MySQL, Redis, SQLAlchemy, SQL |
| Cloud | AWS EC2, RDS, S3, VPC, CloudFront, security groups |
| Delivery | Docker, CI/CD, Linux administration, Nginx, TLS, DNS |
| Background work | Celery, Redis |
| Applied ML | TensorFlow, FastAPI model serving, Gemini API |

<div align="center">

<br/>

<img src="https://skillicons.dev/icons?i=python,fastapi,flask,postgres,mysql,redis,aws,docker,linux,nginx,git,tensorflow&theme=light" alt="Python, FastAPI, Flask, PostgreSQL, MySQL, Redis, AWS, Docker, Linux, Nginx, Git, TensorFlow"/>

</div>

Kubernetes and Terraform are in progress. They are listed under [Learning](#learning), not as current strengths.

---

<a id="experience"></a>

## Experience

<table>
<tr>
<td width="28%" valign="top">
<b>Nov 2025 - Present</b><br/>
<sub>Peshawar, Pakistan</sub>
</td>
<td width="72%" valign="top">

<strong>Backend Software Engineer</strong>
<br/>
NexVolt Solutions

<br/>

I work on backend services from the API through to the AWS hosts they run on.

<ul>
<li>Deploy and maintain applications on EC2, RDS, S3, VPC, and CloudFront, including security groups.</li>
<li>Build FastAPI services backed by PostgreSQL.</li>
<li>Package services with Docker and run deployments through CI/CD.</li>
<li>Configure Nginx as a reverse proxy, along with TLS, DNS, and host firewall rules.</li>
<li>Operate Linux servers: logs, process health, and infrastructure fixes.</li>
<li>Run background work with Celery and Redis.</li>
<li>Implement authentication with JWT and OAuth2.</li>
</ul>

Python · FastAPI · PostgreSQL · AWS · Docker · Nginx · Linux · Celery · Redis

</td>
</tr>
<tr>
<td width="28%" valign="top">
<br/>
<b>Jun 2025 - Sep 2025</b><br/>
<sub>Islamabad, Pakistan</sub>
</td>
<td width="72%" valign="top">
<br/>

<strong>Backend Engineering Intern</strong>
<br/>
Wanclouds Inc.

<br/>

Internship on backend services inside a cloud product team.

<ul>
<li>Built services with FastAPI and Flask.</li>
<li>Designed MySQL schemas and wrote Alembic migrations.</li>
<li>Added auth middleware, Pydantic validation, and structured error handling.</li>
<li>Queued background work with Celery and Redis.</li>
</ul>

FastAPI · Flask · MySQL · Alembic · Celery · Redis

</td>
</tr>
<tr>
<td width="28%" valign="top">
<br/>
<b>Jun 2024 - Sep 2024</b><br/>
<sub>Remote</sub>
</td>
<td width="72%" valign="top">
<br/>

<strong>Python Backend Intern</strong>
<br/>
Go Jins

<br/>

First backend internship, on user-facing APIs.

<ul>
<li>Built REST endpoints for core product flows.</li>
<li>Added JWT authentication and authorization checks.</li>
<li>Designed SQL schemas and wrote the queries behind those endpoints.</li>
<li>Integrated third-party APIs, with validation and error handling.</li>
</ul>

Python · REST · JWT · SQL

</td>
</tr>
</table>

---

<a id="projects"></a>

## Projects

<a id="imagifyai"></a>

### ImagifyAI

Async image-generation backend. The API accepts work, stores application data in PostgreSQL, and processes jobs off the request path.

**Repository:** [faizuet/genwalls](https://github.com/faizuet/genwalls)

- FastAPI service with PostgreSQL
- Background jobs with Celery and Redis
- JWT and OAuth2 authentication
- AWS layout using EC2, RDS, S3, and CloudFront
- Docker image for the service

FastAPI · PostgreSQL · Redis · Celery · Docker · AWS

<a id="looks-lab"></a>

### Looks Lab

Wellness backend that stores user sessions and returns recommendations from Google Gemini. It covers areas such as skincare, haircare, fitness, and diet.

**Repository:** [faizuet/looks-lab-backend](https://github.com/faizuet/looks-lab-backend)

- FastAPI with SQLAlchemy 2.0 async and asyncpg
- Anonymous onboarding, with the session linked to an account after sign-in
- Google and Apple sign-in, plus JWT refresh tokens
- Stripe subscriptions, trials, and webhooks
- S3 for stored files

FastAPI · PostgreSQL · Gemini · Stripe · AWS S3

<a id="cartrack-api"></a>

### CarTrack API

Vehicle-tracking API split into routes, services, and schemas, with authentication and a containerized deploy.

**Repository:** [faizuet/cartrack-api](https://github.com/faizuet/cartrack-api)

- FastAPI and PostgreSQL
- JWT access and refresh tokens, with role-based access
- Docker Compose for the app stack
- Nginx as the reverse proxy

FastAPI · PostgreSQL · Docker · Nginx

<a id="livercare-ai"></a>

### LiverCare AI

Image-classification pipeline for liver steatosis on ultrasound images. A TensorFlow CNN is trained on a prepared image set and exposed through a FastAPI endpoint.

**Repository:** [faizuet/livercare-ai](https://github.com/faizuet/livercare-ai)

- Image preprocessing and augmentation before training
- CNN classifier in TensorFlow
- FastAPI endpoint for inference

FastAPI · TensorFlow · NumPy · Pandas

---

<a id="github"></a>

## GitHub

<div align="center">

<a href="https://github.com/faizuet?tab=repositories">
  <img src="https://github-readme-stats.vercel.app/api?username=faizuet&show_icons=true&include_all_commits=true&hide_border=true&bg_color=f8fafc&title_color=0F2C59&text_color=334155&icon_color=1D4ED8" height="165" alt="GitHub statistics for faizuet"/>
</a>
&nbsp;
<a href="https://github.com/faizuet?tab=repositories">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=faizuet&langs_count=6&layout=compact&hide_border=true&bg_color=f8fafc&title_color=0F2C59&text_color=334155&hide=Jupyter%20Notebook,Roff" height="165" alt="Most used languages for faizuet"/>
</a>

</div>

---

<a id="learning"></a>

## Learning

| Focus | What I am working toward |
| --- | --- |
| Kubernetes | Run multi-service applications with container orchestration, beyond single-host Docker Compose. |
| System design | Practice designing backends that stay understandable as traffic and data grow. |
| Terraform | Describe AWS infrastructure in code so environments can be recreated instead of rebuilt by hand. |

---

<a id="contact"></a>

## Contact

I am open to backend and cloud engineering roles, remote or onsite, including relocation.

| | |
| --- | --- |
| LinkedIn | [muhammad-faiz-backend](https://linkedin.com/in/muhammad-faiz-backend) |
| Email | [faizuet7@gmail.com](mailto:faizuet7@gmail.com) |
| GitHub | [faizuet](https://github.com/faizuet) |
