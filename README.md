# Hi, I'm Jiajun Zheng

M.S. Software Engineering Systems student at Northeastern University, seeking software engineering jobs in full-stack development and AI applications.

I build full-stack products and AI agent systems with React, TypeScript, Java, Spring Boot, PostgreSQL, LangGraph, and modern cloud/database tooling.

## Portfolio

[View my portfolio](https://jiajun-portfolio.vercel.app)

## Featured Projects

---

### RunbookAgent

An AI-powered AIOps platform that automates incident diagnosis through multi-agent collaboration and turns resolutions into reusable runbooks.

#### Key Features

- Built a polyglot microservice system with Spring Boot, FastAPI, React, Redis Streams, pgvector, and LangGraph.
- Implemented an incident-response pipeline for triage, evidence collection, root-cause diagnosis, remediation planning, and runbook generation.
- Designed live-streamed reasoning so on-call engineers can follow agent decisions in real time.
- Used Redis Streams to support durable event-driven workflow updates across backend services.
- Integrated pgvector-based semantic retrieval to help agents reuse historical incident knowledge.

#### Tech Stack

- **Frontend:** React 18, TypeScript
- **Backend:** Spring Boot 3, FastAPI
- **AI / Agent Framework:** LangGraph
- **Database:** PostgreSQL, pgvector
- **Messaging / Streaming:** Redis Streams
- **Deployment:** Docker Compose
- **Architecture:** Microservices, Multi-Agent System, Event-driven Architecture, RAG

#### Links

- **GitHub:** [RunbookAgent](https://github.com/jjMurphy1012/Runbook_agent)

---

### Job Matching AI

An automated multi-step AI career agent that helps users upload resumes, configure job preferences, search for matching opportunities, score job compatibility, and generate personalized cover letters.

#### Key Features

- Built an interactive full-stack dashboard using React and TypeScript, allowing users to upload PDF resumes, configure job preferences, and monitor autonomous job-matching tasks in real time.
- Used the OpenAI GPT-5 API and LangGraph to orchestrate stateful AI workflows for resume parsing, LinkedIn search, compatibility scoring, and personalized cover letter generation.
- Developed an asynchronous FastAPI backend integrated with the LinkedIn API and APScheduler to support scheduled job-matching workflows.
- Implemented automated daily email notifications using SendGrid to deliver personalized job recommendations to users.
- Employed PostgreSQL with pgvector to manage a RAG pipeline for resume and job matching, enabling semantic comparison between user profiles and job descriptions.
- Designed an adaptive threshold algorithm that dynamically adjusts match-score requirements to ensure users receive 10 personalized job recommendations per day.
- Deployed containerized services with Docker to Railway, exposing REST APIs and async task queuing to support concurrent multi-user agent workflows.

#### Tech Stack

- **Frontend:** React, TypeScript
- **Backend:** FastAPI, Python
- **AI / Agent Framework:** OpenAI GPT-5 API, LangGraph
- **Database:** PostgreSQL, pgvector
- **Scheduling / Automation:** APScheduler, SendGrid
- **External API:** LinkedIn API
- **Deployment:** Docker, Railway
- **Architecture:** Full-stack Application, RAG Pipeline, Async Task Queue, Agent Workflow

#### Links

- **GitHub:** [Job Matching AI](https://github.com/jjMurphy1012/jobMatchAI.git)
- **Live Demo:** [welcoming-mindfulness-production-e40c.up.railway.app](https://welcoming-mindfulness-production-e40c.up.railway.app)

---

### Online Order

A full-stack food ordering application with secure authentication, restaurant menu browsing, order management, PostgreSQL persistence, and AWS deployment.

#### Key Features

- Built RESTful backend APIs using Spring Boot to support user authentication, menu browsing, cart management, and order processing.
- Developed a React frontend for customers to browse food items, place orders, and interact with the application through a responsive user interface.
- Integrated PostgreSQL for persistent storage of users, orders, menu items, and application data.
- Implemented Spring Security authentication and authorization to protect user sessions and backend resources.
- Deployed the application using AWS services including RDS, ECR, and App Runner.

#### Tech Stack

- **Frontend:** React
- **Backend:** Spring Boot, Java
- **Security:** Spring Security
- **Database:** PostgreSQL, AWS RDS
- **Deployment:** AWS ECR, AWS App Runner
- **Architecture:** Full-stack Web Application, REST API

#### Links

- **GitHub:** [Online Order](https://github.com/jjMurphy1012/OnlineOrder)

---

### miniSpotify

An Android music streaming client built with Kotlin, Jetpack Compose, MVVM, and the Repository Pattern. It supports playlist browsing, playback controls, favorites, and offline persistence.

#### Key Features

- Built a native Android music streaming client using Kotlin and Jetpack Compose.
- Implemented playlist browsing, music playback controls, favorites, and offline persistence.
- Used MVVM architecture and the Repository Pattern to separate UI, business logic, and data access.
- Integrated Retrofit and OkHttp for network communication with remote music APIs.
- Used Room database for local persistence and offline data storage.
- Applied Hilt for dependency injection and Coil for efficient image loading.

#### Tech Stack

- **Mobile:** Kotlin, Jetpack Compose
- **Architecture:** MVVM, Repository Pattern
- **Networking:** Retrofit, OkHttp
- **Database:** Room
- **Dependency Injection:** Hilt
- **Image Loading:** Coil
- **Architecture Type:** Native Android Application

#### Links

- **GitHub:** [miniSpotify](https://github.com/jjMurphy1012/miniSpotify)

---

## Tech Stack

### Languages

Java, TypeScript, JavaScript, Go, SQL

### Frontend / Mobile

React, React Native, Expo, Jetpack Compose

### Backend

Spring Boot, Spring Security, NestJS, FastAPI, Node.js

### Databases / Search

PostgreSQL, MongoDB, Redis, Elasticsearch, pgvector

### AI / Agent Systems

LangGraph, LangChain, RAG, OpenAI API

### Cloud / DevOps

Docker, AWS, GCP, GitHub Actions

## Contact

- **Portfolio:** [jiajun-portfolio.vercel.app](https://jiajun-portfolio.vercel.app)
- **LinkedIn:** [linkedin.com/in/jiajun-zheng1012](https://linkedin.com/in/jiajun-zheng1012)
- **GitHub:** [github.com/jjMurphy1012](https://github.com/jjMurphy1012)
- **Email:** [zheng.jiaju@northeastern.edu](mailto:zheng.jiaju@northeastern.edu)
