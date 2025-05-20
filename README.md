# 👋 Hi, I'm Maysam Gamini

🎯 I've been  
- **Staff Software Engineer Team Lead**
- **Principal Chaos Engineering (SRE) Team Lead**
- **Principal Platform Engineer Team Lead**
- **Cloud Architect**

I'm a hands-on SRE and Staff software engineer with over a decade of experience designing and operating fault-tolerant, scalable, and observable distributed systems across AWS, Azure, and GCP. I lead resilience engineering and chaos experimentation efforts to proactively detect and eliminate reliability risks—boosting uptime, reducing incident rates, and empowering engineering teams to move fast and safely. Advocate for code excellence and robust system architecture with 10+ years of experience. Expert in Test Driven Design, clean architecture, SOLID pa􀆩erns, refactoring, and code reviews to deliver maintainable, high-performance microservices, API gateways, and event-driven pipelines. Partner with stakeholders to translate requirements into secure, resilient systems with built-in CI/CD, observability, logging, and exception
handling and mentoring teams to uphold coding standards and drive continuous improvement.

---

## 🛠️ Core Expertise

- **Languages Agnostic & Frameworks:** Python, C#, .NET Core, ASP.NET, Bash, Java, GoLang
- **Cloud Platforms:** AWS (EKS, Lambda, EC2), Azure (AKS, App Services), GCP (GKE, Compute Engine)
- **Chaos & Resilience Engineering:** Gremlin, AWS FIS, Azure Chaos Studio, GCP Chaos Toolkit, SLO/SLI/Error Budgets
- **Monitoring & Observability:** Prometheus, Grafana, OpenTelemetry, ELK, Azure Monitor, Application Insights
- **Infrastructure & DevOps:** Terraform, Helm, Docker, Kubernetes, GitHub Actions, Jenkins, Azure DevOps
- **Architectural Patterns:** Microservices, DDD, Event-Driven Design, Circuit Breakers, Bulkheads

---

## 👨‍💻 Work Experience

### 🎰 Aristocrat Technologies — *Austin, TX*  
**Staff Software Engineer / Principal Chaos Engineer (2021 – Present)**  
Aristocrat Gaming is a global leader in casino technology, operating land based slot machines on its modern platform and a diverse online portfolio, powered by acquisitions such as NeoGames (iGaming/iLottery on Azure), Plarium (mobile/online games on AWS/Azure), Big Fish Games and Product Madness (social casino on AWS/Azure), and Roxor (real money gaming on GCP). These services run on a hybrid, multi cloud infrastructure serving millions of players worldwide, under strict uptime and regulatory requirements.
Time Allocation per Sprint / Responsibilities / Tasks / Achievements
Coding: 70–100% • Architecture & Design: 10–40% • Mentorship & Leadership: 5–20% • DevOps & Infrastructure: 5–30% • Incident Response & Production Support: 0–20% • Code review 10-25%
•	Spec writing, and POC creation, accelerating requirements validation and reducing chance of reworks.
•	Led design, development, and maintenance of a large scale, event driven codebase microservices (serving 100+ games) across accounting, compliance, protocol, and hardware domains. 
•	The Robot: designed and implemented a lightweight stress runner that integrated with an OpenTelemetry Agent personalized to mimic actual gameplay at high speed, collects metrics and sends them to CMAP.
•	Implemented Flux Redux and Stateless workflows—cutting game round defects from 40 to 5 defects per month (88%↓) and improving state transition reliability. 
•	High throughput IPC C#↔C++ messaging via gRPC .protos—reducing average inter process call latency from 50 ms to 35 ms (30%↓).
•	Patent pending candidate for invented a thread safe High Throughput DSA.
•	Architected and implemented Domain Driven Design microservices and RESTful APIs with OAuth2/OpenID Connect, built plugin-based systems, enabling rapid feature development.
•	Adding >1000 unit tests; Improving Test Coverage from 45% to 80% across microservices and platform.
•	Defined API management via AWS API Gateway, Azure API Management, implementing routing, LB, auth, rate limits, caching, transformations, monitoring, and third party integrations to halve error rates.
•	Engineered asynchronous inter service communications with Kafka, boosting throughput by (25%↑) and cutting failure rates from 4.0% to 2.8% (30%↓).
•	Refactored native code into OS agnostic modules for hardware support, improving system interoperability.
•	Built CI/CD pipelines with GitHub Actions, integrated SonarQube quality gates, canary/blue green deployments, and automated rollbacks, reducing average pipeline runtimes from ~27 to 10 minutes (≈ 63%↓) and boosting deployment success from 60% to 98%.
•	Optimized data layers for low latency, high availability with SQL/NoSQL stores, Redis caching, RabbitMQ messaging, and distributed systems patterns.
•	Designed and deployed CMAP (Centralized Monitoring & Alerting Platform) using OpenTelemetry, Terraform, and AWS EKS (Helm charts, autoscaling, rolling upgrades) to achieve 99.9% availability.
•	Embedded observability with AWS CloudWatch, Azure Monitor, and Grafana Mimir—reducing mean time to detection from 20 to 5 minutes (75%↓) and mean time to recovery from 50 to 30 minutes (40%↓).
•	Built structured logging (Serilog → CloudWatch) and global exception handling middleware—reducing production incidents from 20 to 13 per month (35%↓) and improving error diagnosis speed by 50%.
•	Mentored and led engineers through Agile ceremonies, breaking down epics, managing cross team dependencies and risk, and aligning deliverables with product and business goals.


### 🧪 Food Chain ID Group — *Fairfield, IA*  
**Senior Software Engineer / Cloud Engineer / DevOps Manager (2017 – 2021)**  
FoodChain ID’s flagship SaaS platforms—InSYTE Traceability and SupplyTrak Compliance—deliver end to end supply chain visibility and regulatory compliance for the food industry. Originally built on legacy, on premises stack (stateful ASP.NET apps backed by SQL Server), the solution suffered from high technical debt, manual release processes, and zero horizontal scalability. To support rapid customer growth and improve reliability, I led the full-stack migration to Azure—modernizing architecture with Infrastructure as Code, automated CI/CD pipelines, and scalable services.

Time Allocation per Sprint / Responsibilities / Tasks / Achievements:
Coding: 80–100% Architecture & Design: 10–20% Mentorship & Leadership: 5–15% DevOps & Infrastructure: 30–100% Incident Response & Production Support: 20–50% Code review ~10%
•	Enhanced and maintained EF Core database first models codebase, adding new features and fixing defects. 
•	Increased unit test coverage from 50% to 80% ahead of the Azure migration, enabling safe refactoring.
•	Refactored a large, stateful ASP.NET monolith with DDD into containerized microservices on Azure App Service, enabling horizontal scaling and 99.95% uptime.
•	Continuous resolving technical debt, slashing code complexity and shrinking the debt backlog by 50%.
•	Migrated on prem SQL Server → Azure SQL via Azure Database Migration Service with geo replication.
•	Implemented Live data ingestion using Azure Data Factory and DMS incremental pipelines. 
•	Designed multi tenant SaaS architecture across Dev, DevTest, Test, Staging, and Production, Reduced release lead time from 1 hour of manual steps to 10 minutes via automated pipelines (≈ 83%↓) 
•	Implemented Azure API Management and Application Gateway for routing, OAuth2/OpenID Connect, rate limiting, and caching, halving API error rates.
•	Built Azure DevOps pipelines with automated build, test, canary deployments, approvals, and rollbacks—scaling deployment cadence from monthly to weekly (4×↑) and raising deployment success to 98%.
•	Embedded Application Insights and Log Analytics, distributed tracing with global exception handling middleware—reducing production incidents by 35% and improving mean time to diagnosis by 50%.
•	Applied tagging, budget alerts, and reserved instances, resulted in 38% YOY Azure spend reduction.
•	Drove architecture & design reviews and fostered a collaborative code review culture, improving sprint velocity by 25% and quality metrics across teams.
•	Established monthly release calendars, release notes, and blameless rollback processes—cutting coordination overhead by 40%. Integrated audit trails, GDPR/CCPA controls, and zero trust policies for 100% regulatory compliance.


## 🏆Education background
Master of Science in Computer Science [USA – MIU (IOWA)]
Bachelor of Science in Information Technology Engineering [Iran – IUT (ISF)]

---

## 🏆 Achievements

- 🥇 **Innovation Award Winner** at Aristocrat for transforming company-wide reliability practices
- 📉 Reduced critical incident rate by 30% YoY
- 📈 Increased automated resilience test coverage from 55% to 75% of critical services
- 💰 Saved an estimated $1.2M in potential downtime via proactive chaos testing

---

## 🌐 Find Me Online

- 💼 [LinkedIn](https://linkedin.com/in/maysamgamini)
- 💻 [GitHub](https://github.com/maysamgamini)
- 🌍 [dwiseowl.dev](https://dwiseowl.dev)
- 📧 m.gamini@gmail.com

---

> ⚠️ **Disclaimer: Only U.S.-based positions are listed here; additional global experience can be provided**
