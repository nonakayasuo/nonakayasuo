---
layout: default
title: Resume
---
<!-- front matter により Jekyll が HTML に変換（README.en.html） -->
<div class="web-only">

English | [日本語]({{ site.baseurl }}/)

</div>

# Resume

## Basic Information

| Field           | Details                                                                                    |
| --------------- | ------------------------------------------------------------------------------------------ |
| Name            | Yasuo Nonaka                                                                               |
| Date of Birth   | July 1993                                                                                  |
| Location        | Tokyo, Japan                                                                               |
| Education       | Ritsumeikan University Graduate School, Business Administration (MA)                       |
| Certifications  | Ordinary Driver’s License, Securities Analyst (Japan), Level 2 Bookkeeping (Japan)         |

## Areas of Interest

- Full-stack engineering (frontend, backend, cloud infrastructure design and development)
- Technical leadership and problem-solving aligned with overall project direction
- Web application architecture and end-to-end solution delivery
- Learning and applying new technologies (AI, blockchain, design tools, etc.)

## Skills

### Development methodologies

Agile (Scrum), prototyping, MVC

### Languages

- Python: 6 years  
- TypeScript: 5.5 years  
- Dart: a few months  
- PHP: a few months  
- Ruby: a few months  

### Frameworks and libraries

FastAPI, Flask, React.JS, Next.js, Vue.JS, AngularJS, Laravel, Ruby on Rails, Flutter

### Communication protocols

GraphQL, gRPC, REST

### RDB

MySQL, PostgreSQL (pgvector)

### Cloud

#### AWS: 5 years

API Gateway, Bedrock, CDK, CloudFormation, CloudFront, CodeBuild, CodePipeline, EC2, ECS, S3, Lambda, RDS, DynamoDB, Batch, Glue, ECR, EMR, CloudWatch, Athena, SES, SQS

#### Google Cloud: 2 years

Cloud Build, Cloud Pub/Sub, Cloud Run, GKE

### SaaS/PaaS

CircleCI, Firebase, Firestore, GitHub, GitHub Actions

## AI

Cursor, Claude Code, LangChain, LangGraph, LangSmith, MCP, Agent Skills, Azure OpenAI API, OpenAI API

### Other tools

Datadog, Docker, SQLAlchemy, Sentry, RSpec, Terraform

## Work experience (detailed)

#### AI SaaS development for a major manufacturing client

**Employment type:** Full-time employee  

**Period:** Mar 2025 – present  

**Team**

- Engineering: 8  
- Total: 12  

**Stakeholders**

- Several client companies  

**Languages & frameworks**

- Frontend: TypeScript + Next.js  
- Backend: Python + FastAPI  

**Infrastructure**

- AWS  
- PostgreSQL (pgvector)  

**Protocols**

- REST  

**Tools**

GitHub, Notion, Cursor, MCP (PostgreSQL, etc.), Docker, LangChain, LangGraph, LangSmith, OpenAI API, Azure OpenAI API, Claude Code, SQLAlchemy  

**Summary**

Led development of a RAG system over internal and design documents for an AI SaaS engagement targeting large manufacturers, as Tech Lead.

**Role**

- **Architecture:** Owned end-to-end design of the RAG stack: FastAPI backend, pipeline from PDF ingestion through embedding and search, and PostgreSQL/pgvector for scalable document search.  
- **Frontend:** Single-handedly implemented core Next.js UI—interactive chat with AI agents and search result visualization—and integration with backend APIs.  
- **AI agents:** Built multi-step reasoning with LangGraph, prompt engineering for manufacturing terminology and context, and validation from ontology level through graph search—delivering hybrid search combining vector, graph, and agents.  
- **Domain modeling:** Designed domain-specific agents and a multi-agent split of work; tuned chunking strategy to balance context retention and retrieval quality.  

**Outcomes**

- Delivered a production-oriented hybrid search system by owning ontology design through accuracy evaluation against real client workflows and terminology.  
- Multi-agent design (domain routing, coordination, reflection) enabled complex operational queries that a single agent could not handle.  
- Established a continuous prompt-improvement loop so the team could keep raising search quality.  

#### Mobile app for a used-car dealership

**Employment type:** Freelance  

**Period:** Dec 2024 – Feb 2025 (3 months)  

**Team**

- Engineering: 2  
- Total: 4  

**Stakeholders**

- 1 client company  

**Languages & frameworks**

- Mobile: Dart + Flutter  
- Backend: Python + FastAPI  
- Web: TypeScript + Next.js  

**Infrastructure (AWS)**

API Gateway, EC2, S3, CloudFormation, CDK, Lambda, RDS, ECR, CloudWatch, SQS  

**RDB**

MySQL  

**Protocols**

REST  

**Tools**

GitHub, Backlog, Terraform, Sentry  

**Platform**

iOS  

**Summary**

Full-stack delivery from Flutter iOS app through greenfield AWS infrastructure for API migration.

**Role**

- **iOS / Flutter:** End-to-end design and implementation with direct user feedback, focusing on intuitive UX.  
- **Infrastructure:** Built and operated AWS from scratch for migrated APIs; IaC with CloudFormation and CDK.  
- **Collaboration:** Worked closely with PO, SM, and developers in Scrum.  

**Outcomes**

- Covered mobile development and new AWS infrastructure as part of the Scrum team.  
- Enabled new API operations via greenfield AWS services.  
- Helped keep the project moving through tight cross-functional collaboration.  

#### Corporate 1-on-1 web application

**Employment type:** Freelance  

**Period:** Mar 1, 2024 – Nov 30, 2024  

**Team**

CTO ×1, Tech lead ×1, Engineers ×8 (10 total)  

**Stakeholders**

1 client company  

**Languages & frameworks**

- Frontend: TypeScript + AngularJS / HTML + SCSS + Tailwind CSS  
- Backend: Python + FastAPI / Ruby on Rails  

**Infrastructure**

AWS  

**Protocols**

REST, GraphQL  

**Tools**

GitHub, Sentry, AWS CloudWatch, Notion  

**Summary**

Built and maintained a web app supporting corporate 1-on-1 meetings—new features, UI/UX, and ops—as a full-stack engineer.

**Role**

- **Frontend:** TypeScript + AngularJS for new features and improvements.  
- **UI/UX:** Tailwind CSS and SCSS for a consistent design system.  
- **Backend:** Primarily Python + FastAPI for new work; Rails for legacy maintenance.  
- **Operations:** CloudWatch for logs, Sentry for errors—fast incident response.  

**Outcomes**

- Improved UX through new features and UI work.  
- Reduced effort and increased consistency via the design system.  
- Stable operations through combined monitoring.  
- Strengthened full-stack ownership from frontend through backend and ops.  
- Automation around logs and errors improved efficiency and response time.  

#### Sales-facing AI web app (side project)

**Employment type:** Freelance  

**Period:** Jan 2024 – Aug 31, 2024  

**Team**

PM ×1, Engineers ×2  

**Stakeholders**

1 client company  

**Languages & frameworks**

- Frontend: TypeScript + Next.js  
- Backend: Python  

**Infrastructure**

Firebase, GCP  

**Protocols**

REST  

**Tools**

GitHub, Tailwind CSS, LangChain (temperature, agents, etc.), Notion  

**Summary**

Application for sales users to generate prompts from product, manufacturer, and customer data—from PoC through production.

**Role**

- **Frontend:** TypeScript + Next.js features.  
- **Backend:** Firebase SDK + Python for data handling and prompt generation.  
- **Prompting:** LangChain tuning (temperature, agents) for better outputs.  
- **Financial data:** Extracted data from EDINET (XBRL) and computed metrics (e.g. revenue, operating profit) using accounting knowledge.  
- **Operations:** Owned path from PoC to production.  

**Outcomes**

- Delivered an AI prompt app tailored to sales workflows.  
- Improved response quality via LangChain tuning.  
- Consistent UI with Tailwind.  
- Better accuracy on financial extraction and KPI calculation using EDINET and accounting input.  
- Shipped end-to-end in a small team, exceeding client expectations.  

#### Manufacturing web application

**Employment type:** Freelance  

**Period:** May 2023 – Feb 28, 2024  

**Team**

Tech leads ×2, Engineers ×10  

**Stakeholders**

1 client company  

**Languages & frameworks**

TypeScript, Nuxt.js 3, Pinia, React.js  

**Infrastructure**

AWS  

**Protocols**

REST, GraphQL  

**Tools**

GitHub, Tailwind CSS, Hasura, Sentry, Datadog, Notion  

**Summary**

AI-enabled web app for manufacturing: efficient frontend–backend integration, stability in production, and React rewrite of a legacy app.

**Role**

- **Frontend:** TypeScript + Nuxt 3 + Pinia, UX-focused features.  
- **Rewrite:** Migrated legacy UI to React for maintainability and extensibility.  
- **Styling:** Tailwind for consistent, efficient UI.  
- **Data:** Hasura + GraphQL for efficient reads/writes.  
- **Reliability:** Sentry + Datadog from detection through handling.  

**Outcomes**

- Shipped on Nuxt 3 with a modern toolchain.  
- Flexible, consistent UI with Tailwind.  
- Faster, more flexible data access via Hasura + GraphQL.  
- Reduced tech debt and improved maintainability with the React migration.  
- Stronger stability and faster troubleshooting with observability.  
- Broadened frontend and operations skill set.  

#### Traveler-focused B2C web application

**Employment type:** Freelance  

**Period:** Oct 1, 2021 – Dec 31, 2022  

**Team**

PO ×1, Tech lead ×1, Engineers ×3  

**Stakeholders**

1 client company  

**Languages & frameworks**

- Frontend: TypeScript + Vue.js  
- Backend: PHP + Laravel  

**Infrastructure (AWS)**

CloudFront, CloudWatch, CodePipeline, EC2, S3, CodeBuild, RDS  

**Protocols**

REST, GraphQL  

**Tools**

GitHub, Pusher, SCSS, Notion  

**Summary**

New chat features and enhancements for a B2C travel web app, plus real-time comms and CI/CD.

**Role**

- **Chat (new):** TypeScript + Vue.js frontend and UI.  
- **Backend:** Laravel with JWT-based auth.  
- **CI/CD:** CodeBuild + CodePipeline for build, test, deploy.  
- **Realtime:** Pusher across frontend and backend.  
- **Enhancements:** Additional features on an existing education-oriented web product.  

**Outcomes**

- Designed and shipped chat with realtime UX improvements.  
- CI/CD improved deploy speed and reliability.  
- Stable realtime behavior after research, design, and implementation.  
- Full-stack growth across frontend and backend.  
- Increased value of the existing product through new capabilities.  

#### PoC development for new AI-powered applications

**Employment type:** Full-time employee  

**Period:** Aug 1, 2020 – Sep 30, 2021  

**Team**

PM ×1, Lead ×1, Engineers ×5  

**Stakeholders**

1 client company  

**Languages & frameworks**

- Frontend: TypeScript + Vue.js  
- Backend: Python + Flask / FastAPI  

**Infrastructure**

MySQL, SQLite  

**Protocols**

REST  

**Tools**

GitLab, Docker, Pytest  

**Summary**

Two PoC applications:

- Money-laundering audit app: TypeScript + Vue.js + Flask  
- Speech recognition & captioning app: TypeScript + Vue.js + FastAPI  

**Role**

- Screen and functional design in the design phase.  
- Full-stack development with Vue.js and Flask/FastAPI.  
- Backend APIs and logic; tests with Pytest.  
- Audio/video speech recognition and text output through delivery.  

**Outcomes**

- Delivered two AI PoCs with client handoff.  
- Improved backend quality and reliability with Pytest.  
- Owned design through implementation, including architecture documentation.  
- Efficient frontend–backend integration within a tight timeline.  

#### Mobile app UI development

**Employment type:** Full-time employee  

**Period:** Jan 1, 2021 – Jul 31, 2021  

**Team**

PO ×1, Scrum Masters ×4, Engineers ×12  

**Stakeholders**

1 client company  

**Languages & frameworks**

JavaScript, React.js, Gatsby, Jest, TestCafe  

**Infrastructure**

Firebase Realtime Database, GCP (GKE)  

**Protocols**

REST  

**Tools**

GitLab, Docker, Kubernetes, Jira, nginx  

**Summary**

Design, build, and operate a mobile-oriented experience using React and GCP in a cloud-native style.

**Role**

- Frontend with React.js + Gatsby.  
- Design docs and feature design from requirements.  
- CI/CD from dev through release.  
- Jest unit tests and TestCafe E2E tests.  

**Outcomes**

- Shipped the app on React + GCP on an aggressive timeline.  
- CI/CD reduced effort from development to release.  
- Tests improved quality.  
- Architecture diagrams and requirements docs streamlined design.  

#### Data platform construction

**Employment type:** Full-time employee  

**Period:** Mar 1, 2019 – Dec 31, 2020  

**Team**

PO ×1, Scrum Master ×1, Tech lead ×1, Engineers ×6  

**Stakeholders**

1 client company  

**Languages & frameworks**

Python, Pytest, Boto3  

**Infrastructure (AWS)**

EC2, S3, Lambda, RDS, DynamoDB, Batch, Glue, ECR, EMR, CloudWatch, Athena  

**Protocols**

REST  

**Tools**

GitHub, Jira, Presto, Docker  

**Summary**

Built an analytics platform to process and aggregate large-scale game telemetry for analysis—ETL development and operations.

**Role**

- Python applications for design, new development, operations, and maintenance.  
- Unit tests with Pytest.  
- Backend automation against AWS with Boto3.  
- Used EC2, S3, Lambda, RDS, DynamoDB, Batch, Glue, and related services for the data platform.  

**Team context**

- Scrum with rapid feature delivery and fixes.  
- Very large data volumes required cost-performance tuning and scalable design.  
- Operations needed quick incident response and new requirements.  

**Outcomes**

- Data pipelines processed large volumes more efficiently than before.  
- Tests improved quality and sped up fixes.  
- AWS design choices improved cost-performance.  
- Flexible delivery on new requirements built client trust.  

#### B2C investment application

**Employment type:** Full-time employee  

**Period:** Sep 1, 2018 – Feb 28, 2019  

**Team**

PM ×1, Engineers ×4  

**Stakeholders**

1 client company  

**Languages & frameworks**

Python  

**Infrastructure (AWS)**

Lambda, S3, RDS  

**Protocols**

REST  

**Tools**

GitLab, Jupyter Notebook, Redmine  

**Summary**

Collected, analyzed, and visualized user investment data; generated individualized performance and market trend reports.

**Role**

- End-to-end flow from ingestion through analysis, visualization, and delivery.  
- Analysis in Python with numpy/pandas.  
- Charts and reports with matplotlib/seaborn.  
- REST APIs for processed results.  
- Automated, customized user reports.  

**Outcomes**

- Reporting improved satisfaction by surfacing performance clearly.  
- Python workflows shortened development time.  
- APIs enabled timely data and higher product value.  
- Visualization strengthened trust and insight for the client.  

#### Credit card credit-management support

**Employment type:** Full-time employee  

**Period:** Jun 1, 2018 – Jul 31, 2018

**Team**

PM ×1, Engineers ×3 (4 total)

**Stakeholders**

1 client company

**Languages & frameworks**

VBA

**Infrastructure**

N/A

**Protocols**

N/A

**Tools**

Excel

**Summary**

Supported credit operations: requirements-phase assistance, efficiency tooling, documentation, and project support.

**Team context**

- Documentation and coordination during requirements.  
- VBA tools to speed PM work.  
- Materials and progress tracking to improve information sharing.  

**Role**

- **Requirements support:** Organized and managed related documents.  
- **Efficiency tools:** VBA tools for PM workflows and document automation.  
- **Reporting:** Data aggregation, materials, and progress tracking.  

**Outcomes**

- Smoother requirements phase through structured documentation.  
- Faster daily PM work via VBA tooling.  
- Better visibility and sharing through materials and progress tracking.  
- Foundational knowledge of credit operations and the value of documentation and tooling.  

## Hobbies

- Reading (about 300–400 books per year)  
- Music (on the order of 1,500 tracks listened to in 2025)  
- Travel (47 prefectures in Japan; 32 countries/regions)  
- Shogi (~2-dan level)  
- Language learning (English, Chinese, Spanish)  
- Dance (hip-hop, K-pop, house, popping)  
- Running  
- Violin  
- Acoustic guitar  
- Saxophone  
- Visiting museums and art galleries  
