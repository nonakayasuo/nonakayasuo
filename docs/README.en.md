---
layout: default
title: Resume — Yasuo Nonaka
description: Full-stack engineer, Tokyo — English resume.
---
<!-- Jekyll: front matter によりページとしてビルドされる。言語リンクは GitHub 表示でも効くよう絶対 URL -->
<!-- div 内は Kramdown が Markdown 解釈しないため HTML でリンク -->
<div class="web-only">
  <p>English | <a href="https://nonakayasuo.github.io/nonakayasuo/">日本語</a></p>
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

---

## Professional summary

I am a full-stack engineer with over seven years of experience, centered on Python and TypeScript. I work across the stack from frontend (Next.js, Vue.js, React) and backend (FastAPI, Flask) through cloud infrastructure design and operations, primarily on AWS.

Most recently, as Tech Lead on an AI SaaS engagement for a large manufacturer, I led design and development of a RAG system using LangChain, LangGraph, and MCP. As a freelancer I have also contributed to mobile apps (Flutter / iOS), web applications, and data platform builds.

I focus on applying AI, shaping architecture, and supporting engineering teams—taking work from PoC through production operations.

---

## Self-introduction

I am a full-stack engineer who can own delivery from frontend and backend through cloud infrastructure and AI agent development. With Python and TypeScript as my core stack and over seven years of experience, I have recently led RAG system design and development as Tech Lead using LangChain, LangGraph, and MCP.

On the technical side, I design and operate infrastructure on AWS (EC2, Lambda, ECS, CDK, and more) and Google Cloud (Cloud Run, GKE), implement frontends with Next.js, AngularJS, and Vue.js, and build backends with FastAPI and Flask. I actively adopt modern AI development tools such as Cursor and Claude Code.

In my work I try to anticipate technical issues by looking at project-wide architecture, not only individual requirements. As Tech Lead I support teammates through technical guidance, code review, and design decisions to improve quality and productivity.

I keep learning in AI, blockchain, design, and adjacent areas, and aim to choose the right technologies and deliver end-to-end solutions for business problems.

---

## What I want to do next

As a full-stack engineer and Tech Lead I have led technical delivery for web applications, SaaS products, and internal DX initiatives. I still find engineering rewarding, and I want to use technology not only as an implementation tool but in ways that connect more deeply to **business decisions**.

In particular, I want to work in a media or content company, understand market needs and business strategy, maximize product value from a technical perspective, and help drive business growth directly.

I plan to apply my experience in application development and AI adoption, together with full-stack depth, to take stronger business-side ownership of outcomes and to keep tying technology to the core of the business.

---

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

### AI

Cursor, Claude Code, LangChain, LangGraph, LangSmith, MCP, Agent Skills, Azure OpenAI API, OpenAI API

### Other tools

Datadog, Docker, SQLAlchemy, Sentry, RSpec, Terraform

## Work experience (detailed)

---

#### Internal DX promotion &amp; integrated platform development (Adixie Inc.)

<table>
  <thead>
    <tr><th>Period</th><th>Details</th></tr>
  </thead>
  <tbody>
    <tr>
      <td>Sep 2025 –<br>present</td>
      <td>
        <b>Employment type:</b> Full-time employee<br><br>
        <b>Team:</b> Engineering: 3 / Total: 10<br>
        <b>Stakeholders:</b> Internal departments (management, IT, HR, accounting, etc.)<br><br>
        <b>Languages &amp; frameworks:</b><br>
        ・Frontend: TypeScript + Next.js<br>
        ・Backend: TypeScript + Node.js (GraphQL / REST)<br>
        ・ORM: Prisma<br><br>
        <b>Infrastructure:</b><br>
        ・AWS (ECS Fargate, Aurora Serverless v2, Lambda, API Gateway, ECR, CloudWatch, S3, Amplify)<br>
        ・IaC: Terraform<br>
        <b>RDB:</b> PostgreSQL (Aurora Serverless v2)<br>
        <b>Protocols:</b> GraphQL, REST<br><br>
        <b>Tools:</b> GitHub, GitHub Actions, Docker, Cursor, Claude Code, MCP, Prisma, Docusaurus<br><br>
        <b>Summary:</b><br>
        Led planning, design, and construction of an integrated internal platform "ADiXi Sandbox" as PdM / PL. Built a monorepo-based platform that unifies infrastructure, shared modules, and multiple internal-facing business APIs under one repository for centralized management and deployment.<br><br>
        <b>Role:</b><br>
        ・Project management: Requirements definition, task management, team coordination, and stakeholder alignment as PdM / PL<br>
        ・Architecture design: Designed monorepo + Git Submodules multi-repository structure connecting satellite and hub repositories<br>
        ・Infrastructure: Drove IaC with Terraform on AWS. Optimized costs with Aurora Serverless v2 zero-scale configuration and built container deployment on ECS Fargate<br>
        ・CI/CD pipeline: Automated deployments via GitHub Actions with dev / prod environment separation and DB migration automation<br>
        ・API design: Designed hybrid GraphQL / REST API (Entity API) for master data, attendance reconciliation, billing, and payroll<br>
        ・SaaS integration: Designed data sync engines and adapters for external SaaS (PORTERS, Bakuraku, SmartHR)<br>
        ・AI agent platform: Designed and implemented MCP (Model Context Protocol) servers and Agent Skills for cross-functional AI agent capabilities<br>
        ・Documentation: Built unified specification and API documentation site with Docusaurus<br><br>
        <b>Outcomes:</b><br>
        ・Designed and built an integrated platform from scratch to consolidate multiple business APIs, driving internal DX<br>
        ・Optimized infrastructure costs through Terraform IaC and Aurora Serverless v2 zero-scale configuration<br>
        ・Established automated dev / prod deployment pipeline with GitHub Actions CI/CD<br>
        ・Built an AI agent platform using MCP / Agent Skills, enabling cross-functional AI utilization
      </td>
    </tr>
  </tbody>
</table>

---

#### AI SaaS development for a major manufacturing client (Adixie Inc.)

<table>
  <thead>
    <tr><th>Period</th><th>Details</th></tr>
  </thead>
  <tbody>
    <tr>
      <td>Mar 2025 –<br>present</td>
      <td>
        <b>Employment type:</b> Full-time employee<br><br>
        <b>Team:</b> Engineering: 8 / Total: 12<br>
        <b>Stakeholders:</b> Several client companies<br><br>
        <b>Languages &amp; frameworks:</b><br>
        ・Frontend: TypeScript + Next.js<br>
        ・Backend: Python + FastAPI<br><br>
        <b>Infrastructure:</b> AWS, PostgreSQL (pgvector)<br>
        <b>Protocols:</b> REST<br><br>
        <b>Tools:</b> GitHub, Notion, Cursor, MCP (PostgreSQL, etc.), Docker, LangChain, LangGraph, LangSmith, OpenAI API, Azure OpenAI API, Claude Code, SQLAlchemy<br><br>
        <b>Summary:</b><br>
        Led development of a RAG system over internal and design documents for an AI SaaS engagement targeting large manufacturers, as Tech Lead.<br><br>
        <b>Role:</b><br>
        ・Architecture: Owned end-to-end design of the RAG stack: FastAPI backend, pipeline from PDF ingestion through embedding and search, and PostgreSQL/pgvector for scalable document search.<br>
        ・Frontend: Single-handedly implemented core Next.js UI—interactive chat with AI agents and search result visualization—and integration with backend APIs.<br>
        ・AI agents: Built multi-step reasoning with LangGraph, prompt engineering for manufacturing terminology and context, and validation from ontology level through graph search—delivering hybrid search combining vector, graph, and agents.<br>
        ・Domain modeling: Designed domain-specific agents and a multi-agent split of work; tuned chunking strategy to balance context retention and retrieval quality.<br><br>
        <b>Outcomes:</b><br>
        ・Delivered a production-oriented hybrid search system by owning ontology design through accuracy evaluation against real client workflows and terminology.<br>
        ・Multi-agent design (domain routing, coordination, reflection) enabled complex operational queries that a single agent could not handle.<br>
        ・Established a continuous prompt-improvement loop so the team could keep raising search quality.
      </td>
    </tr>
  </tbody>
</table>

---

#### Mobile app for a used-car dealership (Freelance)

<table>
  <thead>
    <tr><th>Period</th><th>Details</th></tr>
  </thead>
  <tbody>
    <tr>
      <td>Dec 2024 –<br>Feb 2025</td>
      <td>
        <b>Employment type:</b> Freelance (3 months)<br><br>
        <b>Team:</b> Engineering: 2 / Total: 4<br>
        <b>Stakeholders:</b> 1 client company<br><br>
        <b>Languages &amp; frameworks:</b><br>
        ・Mobile: Dart + Flutter<br>
        ・Backend: Python + FastAPI<br>
        ・Web: TypeScript + Next.js<br><br>
        <b>Infrastructure (AWS):</b> API Gateway, EC2, S3, CloudFormation, CDK, Lambda, RDS, ECR, CloudWatch, SQS<br>
        <b>RDB:</b> MySQL<br>
        <b>Protocols:</b> REST<br><br>
        <b>Tools:</b> GitHub, Backlog, Terraform, Sentry<br>
        <b>Platform:</b> iOS<br><br>
        <b>Summary:</b><br>
        Full-stack delivery from Flutter iOS app through greenfield AWS infrastructure for API migration.<br><br>
        <b>Role:</b><br>
        ・iOS / Flutter: End-to-end design and implementation with direct user feedback, focusing on intuitive UX.<br>
        ・Infrastructure: Built and operated AWS from scratch for migrated APIs; IaC with CloudFormation and CDK.<br>
        ・Collaboration: Worked closely with PO, SM, and developers in Scrum.<br><br>
        <b>Outcomes:</b><br>
        ・Covered mobile development and new AWS infrastructure as part of the Scrum team.<br>
        ・Enabled new API operations via greenfield AWS services.<br>
        ・Helped keep the project moving through tight cross-functional collaboration.
      </td>
    </tr>
  </tbody>
</table>

---

#### Corporate 1-on-1 web application (Freelance)

<table>
  <thead>
    <tr><th>Period</th><th>Details</th></tr>
  </thead>
  <tbody>
    <tr>
      <td>Mar 1, 2024 –<br>Nov 30, 2024</td>
      <td>
        <b>Employment type:</b> Freelance<br><br>
        <b>Team:</b> CTO ×1, Tech lead ×1, Engineers ×8 (10 total)<br>
        <b>Stakeholders:</b> 1 client company<br><br>
        <b>Languages &amp; frameworks:</b><br>
        ・Frontend: TypeScript + AngularJS / HTML + SCSS + Tailwind CSS<br>
        ・Backend: Python + FastAPI / Ruby on Rails<br><br>
        <b>Infrastructure:</b> AWS<br>
        <b>Protocols:</b> REST, GraphQL<br><br>
        <b>Tools:</b> GitHub, Sentry, AWS CloudWatch, Notion<br><br>
        <b>Summary:</b><br>
        Built and maintained a web app supporting corporate 1-on-1 meetings—new features, UI/UX, and ops—as a full-stack engineer.<br><br>
        <b>Role:</b><br>
        ・Frontend: TypeScript + AngularJS for new features and improvements.<br>
        ・UI/UX: Tailwind CSS and SCSS for a consistent design system.<br>
        ・Backend: Primarily Python + FastAPI for new work; Rails for legacy maintenance.<br>
        ・Operations: CloudWatch for logs, Sentry for errors—fast incident response.<br><br>
        <b>Outcomes:</b><br>
        ・Improved UX through new features and UI work.<br>
        ・Reduced effort and increased consistency via the design system.<br>
        ・Stable operations through combined monitoring.<br>
        ・Strengthened full-stack ownership from frontend through backend and ops.<br>
        ・Automation around logs and errors improved efficiency and response time.
      </td>
    </tr>
  </tbody>
</table>

---

#### Sales-facing AI web app (Freelance)

<table>
  <thead>
    <tr><th>Period</th><th>Details</th></tr>
  </thead>
  <tbody>
    <tr>
      <td>Jan 2024 –<br>Aug 31, 2024</td>
      <td>
        <b>Employment type:</b> Freelance<br><br>
        <b>Team:</b> PM ×1, Engineers ×2<br>
        <b>Stakeholders:</b> 1 client company<br><br>
        <b>Languages &amp; frameworks:</b><br>
        ・Frontend: TypeScript + Next.js<br>
        ・Backend: Python<br><br>
        <b>Infrastructure:</b> Firebase, GCP<br>
        <b>Protocols:</b> REST<br><br>
        <b>Tools:</b> GitHub, Tailwind CSS, LangChain (temperature, agents, etc.), Notion<br><br>
        <b>Summary:</b><br>
        Application for sales users to generate prompts from product, manufacturer, and customer data—from PoC through production.<br><br>
        <b>Role:</b><br>
        ・Frontend: TypeScript + Next.js features.<br>
        ・Backend: Firebase SDK + Python for data handling and prompt generation.<br>
        ・Prompting: LangChain tuning (temperature, agents) for better outputs.<br>
        ・Financial data: Extracted data from EDINET (XBRL) and computed metrics (e.g. revenue, operating profit) using accounting knowledge.<br>
        ・Operations: Owned path from PoC to production.<br><br>
        <b>Outcomes:</b><br>
        ・Delivered an AI prompt app tailored to sales workflows.<br>
        ・Improved response quality via LangChain tuning.<br>
        ・Consistent UI with Tailwind.<br>
        ・Better accuracy on financial extraction and KPI calculation using EDINET and accounting input.<br>
        ・Shipped end-to-end in a small team, exceeding client expectations.
      </td>
    </tr>
  </tbody>
</table>

---

#### Manufacturing web application (Freelance)

<table>
  <thead>
    <tr><th>Period</th><th>Details</th></tr>
  </thead>
  <tbody>
    <tr>
      <td>May 2023 –<br>Feb 28, 2024</td>
      <td>
        <b>Employment type:</b> Freelance<br><br>
        <b>Team:</b> Tech leads ×2, Engineers ×10<br>
        <b>Stakeholders:</b> 1 client company<br><br>
        <b>Languages &amp; frameworks:</b> TypeScript, Nuxt.js 3, Pinia, React.js<br><br>
        <b>Infrastructure:</b> AWS<br>
        <b>Protocols:</b> REST, GraphQL<br><br>
        <b>Tools:</b> GitHub, Tailwind CSS, Hasura, Sentry, Datadog, Notion<br><br>
        <b>Summary:</b><br>
        AI-enabled web app for manufacturing: efficient frontend–backend integration, stability in production, and React rewrite of a legacy app.<br><br>
        <b>Role:</b><br>
        ・Frontend: TypeScript + Nuxt 3 + Pinia, UX-focused features.<br>
        ・Rewrite: Migrated legacy UI to React for maintainability and extensibility.<br>
        ・Styling: Tailwind for consistent, efficient UI.<br>
        ・Data: Hasura + GraphQL for efficient reads/writes.<br>
        ・Reliability: Sentry + Datadog from detection through handling.<br><br>
        <b>Outcomes:</b><br>
        ・Shipped on Nuxt 3 with a modern toolchain.<br>
        ・Flexible, consistent UI with Tailwind.<br>
        ・Faster, more flexible data access via Hasura + GraphQL.<br>
        ・Reduced tech debt and improved maintainability with the React migration.<br>
        ・Stronger stability and faster troubleshooting with observability.<br>
        ・Broadened frontend and operations skill set.
      </td>
    </tr>
  </tbody>
</table>

---

#### Traveler-focused B2C web application (Freelance)

<table>
  <thead>
    <tr><th>Period</th><th>Details</th></tr>
  </thead>
  <tbody>
    <tr>
      <td>Oct 1, 2021 –<br>Dec 31, 2022</td>
      <td>
        <b>Employment type:</b> Freelance<br><br>
        <b>Team:</b> PO ×1, Tech lead ×1, Engineers ×3<br>
        <b>Stakeholders:</b> 1 client company<br><br>
        <b>Languages &amp; frameworks:</b><br>
        ・Frontend: TypeScript + Vue.js<br>
        ・Backend: PHP + Laravel<br><br>
        <b>Infrastructure (AWS):</b> CloudFront, CloudWatch, CodePipeline, EC2, S3, CodeBuild, RDS<br>
        <b>Protocols:</b> REST, GraphQL<br><br>
        <b>Tools:</b> GitHub, Pusher, SCSS, Notion<br><br>
        <b>Summary:</b><br>
        New chat features and enhancements for a B2C travel web app, plus real-time comms and CI/CD.<br><br>
        <b>Role:</b><br>
        ・Chat (new): TypeScript + Vue.js frontend and UI.<br>
        ・Backend: Laravel with JWT-based auth.<br>
        ・CI/CD: CodeBuild + CodePipeline for build, test, deploy.<br>
        ・Realtime: Pusher across frontend and backend.<br>
        ・Enhancements: Additional features on an existing education-oriented web product.<br><br>
        <b>Outcomes:</b><br>
        ・Designed and shipped chat with realtime UX improvements.<br>
        ・CI/CD improved deploy speed and reliability.<br>
        ・Stable realtime behavior after research, design, and implementation.<br>
        ・Full-stack growth across frontend and backend.<br>
        ・Increased value of the existing product through new capabilities.
      </td>
    </tr>
  </tbody>
</table>

---

#### PoC development for new AI-powered applications (IDH Inc.)

<table>
  <thead>
    <tr><th>Period</th><th>Details</th></tr>
  </thead>
  <tbody>
    <tr>
      <td>Aug 1, 2020 –<br>Sep 30, 2021</td>
      <td>
        <b>Employment type:</b> Full-time employee<br><br>
        <b>Team:</b> PM ×1, Lead ×1, Engineers ×5<br>
        <b>Stakeholders:</b> 1 client company<br><br>
        <b>Languages &amp; frameworks:</b><br>
        ・Frontend: TypeScript + Vue.js<br>
        ・Backend: Python + Flask / FastAPI<br><br>
        <b>Infrastructure:</b> MySQL, SQLite<br>
        <b>Protocols:</b> REST<br><br>
        <b>Tools:</b> GitLab, Docker, Pytest<br><br>
        <b>Summary:</b><br>
        Two PoC applications:<br>
        ・Money-laundering audit app: TypeScript + Vue.js + Flask<br>
        ・Speech recognition &amp; captioning app: TypeScript + Vue.js + FastAPI<br><br>
        <b>Role:</b><br>
        ・Screen and functional design in the design phase.<br>
        ・Full-stack development with Vue.js and Flask/FastAPI.<br>
        ・Backend APIs and logic; tests with Pytest.<br>
        ・Audio/video speech recognition and text output through delivery.<br><br>
        <b>Outcomes:</b><br>
        ・Delivered two AI PoCs with client handoff.<br>
        ・Improved backend quality and reliability with Pytest.<br>
        ・Owned design through implementation, including architecture documentation.<br>
        ・Efficient frontend–backend integration within a tight timeline.
      </td>
    </tr>
  </tbody>
</table>

---

#### Mobile app UI development (IDH Inc.)

<table>
  <thead>
    <tr><th>Period</th><th>Details</th></tr>
  </thead>
  <tbody>
    <tr>
      <td>Jan 1, 2021 –<br>Jul 31, 2021</td>
      <td>
        <b>Employment type:</b> Full-time employee<br><br>
        <b>Team:</b> PO ×1, Scrum Masters ×4, Engineers ×12<br>
        <b>Stakeholders:</b> 1 client company<br><br>
        <b>Languages &amp; frameworks:</b> JavaScript, React.js, Gatsby, Jest, TestCafe<br><br>
        <b>Infrastructure:</b> Firebase Realtime Database, GCP (GKE)<br>
        <b>Protocols:</b> REST<br><br>
        <b>Tools:</b> GitLab, Docker, Kubernetes, Jira, nginx<br><br>
        <b>Summary:</b><br>
        Design, build, and operate a mobile-oriented experience using React and GCP in a cloud-native style.<br><br>
        <b>Role:</b><br>
        ・Frontend with React.js + Gatsby.<br>
        ・Design docs and feature design from requirements.<br>
        ・CI/CD from dev through release.<br>
        ・Jest unit tests and TestCafe E2E tests.<br><br>
        <b>Outcomes:</b><br>
        ・Shipped the app on React + GCP on an aggressive timeline.<br>
        ・CI/CD reduced effort from development to release.<br>
        ・Tests improved quality.<br>
        ・Architecture diagrams and requirements docs streamlined design.
      </td>
    </tr>
  </tbody>
</table>

---

#### Data platform construction (IDH Inc.)

<table>
  <thead>
    <tr><th>Period</th><th>Details</th></tr>
  </thead>
  <tbody>
    <tr>
      <td>Mar 1, 2019 –<br>Dec 31, 2020</td>
      <td>
        <b>Employment type:</b> Full-time employee<br><br>
        <b>Team:</b> PO ×1, Scrum Master ×1, Tech lead ×1, Engineers ×6<br>
        <b>Stakeholders:</b> 1 client company<br><br>
        <b>Languages &amp; frameworks:</b> Python, Pytest, Boto3<br><br>
        <b>Infrastructure (AWS):</b> EC2, S3, Lambda, RDS, DynamoDB, Batch, Glue, ECR, EMR, CloudWatch, Athena<br>
        <b>Protocols:</b> REST<br><br>
        <b>Tools:</b> GitHub, Jira, Presto, Docker<br><br>
        <b>Summary:</b><br>
        Built an analytics platform to process and aggregate large-scale game telemetry for analysis—ETL development and operations.<br><br>
        <b>Role:</b><br>
        ・Python applications for design, new development, operations, and maintenance.<br>
        ・Unit tests with Pytest.<br>
        ・Backend automation against AWS with Boto3.<br>
        ・Used EC2, S3, Lambda, RDS, DynamoDB, Batch, Glue, and related services for the data platform.<br><br>
        <b>Team context:</b><br>
        ・Scrum with rapid feature delivery and fixes.<br>
        ・Very large data volumes required cost-performance tuning and scalable design.<br>
        ・Operations needed quick incident response and new requirements.<br><br>
        <b>Outcomes:</b><br>
        ・Data pipelines processed large volumes more efficiently than before.<br>
        ・Tests improved quality and sped up fixes.<br>
        ・AWS design choices improved cost-performance.<br>
        ・Flexible delivery on new requirements built client trust.
      </td>
    </tr>
  </tbody>
</table>

---

#### B2C investment application (TecoTec Inc.)

<table>
  <thead>
    <tr><th>Period</th><th>Details</th></tr>
  </thead>
  <tbody>
    <tr>
      <td>Sep 1, 2018 –<br>Feb 28, 2019</td>
      <td>
        <b>Employment type:</b> Full-time employee<br><br>
        <b>Team:</b> PM ×1, Engineers ×4<br>
        <b>Stakeholders:</b> 1 client company<br><br>
        <b>Languages &amp; frameworks:</b> Python<br><br>
        <b>Infrastructure (AWS):</b> Lambda, S3, RDS<br>
        <b>Protocols:</b> REST<br><br>
        <b>Tools:</b> GitLab, Jupyter Notebook, Redmine<br><br>
        <b>Summary:</b><br>
        Collected, analyzed, and visualized user investment data; generated individualized performance and market trend reports.<br><br>
        <b>Role:</b><br>
        ・End-to-end flow from ingestion through analysis, visualization, and delivery.<br>
        ・Analysis in Python with numpy/pandas.<br>
        ・Charts and reports with matplotlib/seaborn.<br>
        ・REST APIs for processed results.<br>
        ・Automated, customized user reports.<br><br>
        <b>Outcomes:</b><br>
        ・Reporting improved satisfaction by surfacing performance clearly.<br>
        ・Python workflows shortened development time.<br>
        ・APIs enabled timely data and higher product value.<br>
        ・Visualization strengthened trust and insight for the client.
      </td>
    </tr>
  </tbody>
</table>

---

#### Credit card credit-management support (FUJISOFT Inc.)

<table>
  <thead>
    <tr><th>Period</th><th>Details</th></tr>
  </thead>
  <tbody>
    <tr>
      <td>Jun 1, 2018 –<br>Jul 31, 2018</td>
      <td>
        <b>Employment type:</b> Full-time employee<br><br>
        <b>Team:</b> PM ×1, Engineers ×3 (4 total)<br>
        <b>Stakeholders:</b> 1 client company<br><br>
        <b>Languages &amp; frameworks:</b> VBA<br><br>
        <b>Infrastructure:</b> N/A<br>
        <b>Protocols:</b> N/A<br><br>
        <b>Tools:</b> Excel<br><br>
        <b>Summary:</b><br>
        Supported credit operations: requirements-phase assistance, efficiency tooling, documentation, and project support.<br><br>
        <b>Team context:</b><br>
        ・Documentation and coordination during requirements.<br>
        ・VBA tools to speed PM work.<br>
        ・Materials and progress tracking to improve information sharing.<br><br>
        <b>Role:</b><br>
        ・Requirements support: Organized and managed related documents.<br>
        ・Efficiency tools: VBA tools for PM workflows and document automation.<br>
        ・Reporting: Data aggregation, materials, and progress tracking.<br><br>
        <b>Outcomes:</b><br>
        ・Smoother requirements phase through structured documentation.<br>
        ・Faster daily PM work via VBA tooling.<br>
        ・Better visibility and sharing through materials and progress tracking.<br>
        ・Foundational knowledge of credit operations and the value of documentation and tooling.
      </td>
    </tr>
  </tbody>
</table>

---

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
