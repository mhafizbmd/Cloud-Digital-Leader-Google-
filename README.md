# Cloud Digital Leader

---

These are my own notes written on Notion.
Every single information was taken from a mixture of Google Cloud SKills Boost, and additional information were taken from LinkedIn Learning and KodeKloud (Yes, I am a subscriber).
I practiced the quiz from CloudSkillsBoost, Google's own mock exam and the 4 Practice Exams available on LinkedIn Learning.

## 🗂️ Table of Contents

1. [Deployment Models](#-deployment-models)  
   1. [On-premises (Traditional Way)](#-traditional-way)  
   2. [Private Cloud](#private-cloud)  
   3. [Public Cloud](#public-cloud)  
   4. [Hybrid Cloud](#hybrid-cloud)  
   5. [Multicloud](#multicloud)  

2. [Cloud Service Models](#-cloud-service-models)  
   1. [Infrastructure as a Service (IaaS)](#1-infrastructure-as-a-service-ias)  
   2. [Platform as a Service (PaaS)](#2-platform-as-a-service-paas)  
   3. [Software as a Service (SaaS)](#3-software-as-a-service-saas)  

3. [Hybrid & Multicloud Drivers](#-hybrid--multicloud-drivers)  

4. [Benefits of Cloud Computing over Traditional](#-benefits-of-cloud-computing-over-traditional)  

5. [Digital Transformation](#-digital-transformation)  
   1. [Transformation Cloud Basis](#transformation-cloud-basis)  
   2. [Hybrid Cloud (again)](#-hybrid-cloud-again)  
   3. [Multicloud (again)](#-multicloud-again)  
   4. [Hybrid & Multicloud Drivers (again)](#-hybrid--multicloud-drivers-again)  

6. [Key Concepts](#-key-concepts)  
   1. [Abstraction](#abstraction)  
   2. [Shared Responsibility Model](#shared-responsibility-model)  

7. [Data Services](#-data-services)  
   1. [Relational (SQL)](#1-relational-sql)  
   2. [Non-Relational (NoSQL)](#2-non-relational-nosql)  
   3. [Data Warehouse](#data-warehouse)  
   4. [Data Lake](#data-lake)  
   5. [Data Types by Source](#data-types-by-source)  
   6. [Data Governance](#data-governance)  
   7. [Storage Class](#storage-class)  
   8. [Datastream](#datastream)  
   9. [Structured/Semi-structured Workloads](#structuredsemi-structured-workloads)  
   10. [Streaming Analytics](#streaming-analytics)  
   11. [Data Pipeline](#data-pipeline)  
   12. [Dataproc](#dataproc)  
   13. [Looker](#looker)  
   14. [Data Value Chain](#data-value-chain)  

8. [AI & ML](#-ai--ml)  
   1. [AI vs ML](#ai-vs-ml)  
   2. [High-quality Data for ML](#high-quality-data-for-ml)  
   3. [Generative AI](#generative-ai)  
   4. [Google Cloud ML Models](#google-cloud-ml-models)  
   5. [Considerations When Selecting AI/ML Solutions](#considerations-when-selecting-aiml-solutions)  
   6. [Google AI Principles](#google-ai-principles)  

9. [Cloud Migration Terms](#-cloud-migration-terms)  
   1. [Workload](#workload)  
   2. [Retired](#retired)  
   3. [Retained](#retained)  
   4. [Rehosted (Lift and Shift)](#rehosted-lift-and-shift)  
   5. [Replatform (Move and Improve)](#replatform-move-and-improve)  
   6. [Refactored](#refactored)  
   7. [Reimagined](#reimagined)  

10. [Vertex AI](#-vertex-ai)  
    1. [Key Vertex AI Services](#key-vertex-ai-services)  
    2. [TensorFlow](#tensorflow)  

11. [Google API](#-google-api)  
    1. [Vision API](#vision-api)  
    2. [Natural Language API](#natural-language-api)  
    3. [Translation API](#translation-api)  
    4. [Speech-to-Text API](#speech-to-text-api)  
    5. [Text-to-Speech API](#text-to-speech-api)  
    6. [Video Intelligence API](#video-intelligence-api)  

12. [Google AI Solutions](#-google-ai-solutions)  
    1. [Contact Center AI](#contact-center-ai)  
    2. [Document AI](#document-ai)  
    3. [Discovery AI](#discovery-ai)  
    4. [Recommendations AI](#recommendations-ai)  

13. [Compute Options](#-compute-options)  
    1. [VM-based Compute Options](#vm-based-compute-options)  
        - [Compute Engine](#compute-engine)  
        - [Google Cloud VMware Engine](#google-cloud-vmware-engine)  
        - [Bare Metal Solution](#bare-metal-solution)  
    2. [Container-based Compute Option](#container-based-compute-option)  
        - [Google Kubernetes Engine (GKE)](#google-kubernetes-engine-gke)  
    3. [Serverless Computing Options](#serverless-computing-options)  
        - [App Engine](#app-engine)  
        - [Cloud Run](#cloud-run)  
        - [Cloud Functions](#cloud-functions)  

14. [Patterns for Modernizing Applications](#-patterns-for-modernizing-applications)  

15. [Developing Cloud-Native Applications](#-developing-cloud-native-applications)  

16. [Legacy System Challenges](#-legacy-system-challenges)  

17. [API (Application Programming Interface)](#-api-application-programming-interface)  

18. [API Management](#-api-management)  

19. [Apigee](#-apigee-google-cloud-api-platform)  

20. [Cloud Security Model](#-cloud-security-model)  
    1. [Privileged Access Security Model](#privileged-access-security-model)  
    2. [Least Privilege Security Principle](#least-privilege-security-principle)  
    3. [Zero-Trust Architecture](#zero-trust-architecture)  

21. [How Organizations Can Protect Itself from Cyber Threats](#-how-organizations-can-protect-itself-from-cyber-threats)  
    1. [Security by Default](#security-by-default)  
    2. [Security Posture](#security-posture)  
    3. [Cyber Resilience](#cyber-resilience)  

22. [Security Measures to Protect Cloud Resources](#-security-measures-to-protect-cloud-resources)  
    1. [Firewall](#firewall)  
    2. [Encryption](#encryption)  
    3. [Decryption](#decryption)  

23. [CIA Triad](#-cia-triad)  

24. [Artifact Registry](#-artifact-registry)  

25. [Traditional On-Premises Security vs Cloud Security](#-traditional-on-premises-security-vs-cloud-security)  

26. [Cybersecurity Threats](#-cybersecurity-threats)  

27. [Google Data Center](#-google-data-center)  

28. [Encryption](#-encryption)  

29. [Identity](#-identity)  

30. [Identity and Access Management (IAM)](#-identity-and-access-management-iam)  

31. [Network Security](#-network-security)  

32. [Security Command Center (SCC)](#-security-command-center-scc)  

33. [Google Cloud Trust Principles](#-google-cloud-trust-principles)  

34. [Data Sovereignty & Data Residency](#-data-sovereignty--data-residency)  

35. [Compliance Resource Center](#-compliance-resource-center)  

36. [Transparency Reports](#-transparency-reports)  

37. [Google Cloud Pricing Calculator](#-google-cloud-pricing-calculator)  

38. [Roles in Managing Cloud Costs](#-roles-in-managing-cloud-costs)  
    1. [People](#people)  
    2. [Process](#process)  
    3. [Technology](#technology)  

39. [Cloud Financial Best Practice](#-cloud-financial-best-practice)  
    1. [Identify who manages cloud costs](#identify-who-manages-cloud-costs)  
    2. [Understand invoices versus cost management tools](#understand-invoices-versus-cost-management-tools)  
    3. [Use Google Cloud’s cost management tools](#use-google-clouds-cost-management-tools)  

40. [Google Cloud Resource Hierarchy](#-google-cloud-resource-hierarchy)  
    1. [Organization](#organization)  
    2. [Folders](#folders)  
    3. [Projects](#projects)  
    4. [Resources](#resources)  

41. [Four Golden Signals (SRE Monitoring)](#-four-golden-signals-sre-monitoring)  
    1. [Latency](#latency)  
    2. [Traffic](#traffic)  
    3. [Errors](#errors)  
    4. [Saturation](#saturation)  

42. [Replication](#-replication)  

43. [Site Reliability Engineer](#-site-reliability-engineer)  

44. [Google Cloud Customer Care Support Levels](#-google-cloud-customer-care-support-levels)  

45. [Google Cloud Observability Tools](#-google-cloud-observability-tools)  

46. [Google's 2030 Goal](#-googles-2030-goal)  

47. [ISO 14001](#-iso-14001)  

48. [Google Cloud Console Mobile App](#-google-cloud-console-mobile-app)  

49. [Database Migration Service](#-database-migration-service)  

50. [Google Cloud Anthos](#-google-cloud-anthos)  

51. [Google Cloud Operations](#-google-cloud-operations)  

52. [AI Platform Notebooks](#-ai-platform-notebooks)  

53. [Cloud Source Repositories](#-cloud-source-repositories)  

54. [Managed Instance Group](#-managed-instance-group)  

55. [GCP Zones](#-how-many-zones-are-present-in-a-gcp)  

56. [Application Load Testing](#-application-load-testing)  

57. [DevOps Philosophy for Reliability](#-based-on-devops-philosophy-reliability-and-health-of-production-systems)  

58. [Meantime for Recovery](#-biggest-factor-to-consider-when-building-application-for-business-continuity-is-meantime-for-recovery-in-case-of-disaster-recovery)  

59. [Cloud Composer](#-cloud-composer)  

60. [Key Features of Google Cloud Confidential Computing](#-key-features-of-google-cloud-confidential-computing)  

61. [TO NOTE](#-to-note)  

---

## 🏢 Deployment Models

### **On-premises (Traditional Way)**

- Hosted on-site in an organization's data center with physical control and no need for third-party access.
- Requires procurement of hardware, setup of secure environments, and expert personnel to manage; hard to scale.

### **Private Cloud**

- Single-tenant environment dedicated to one organization, often hosted on-prem or in a dedicated facility.
- **Use Case:** Offers strong customization and control for strict compliance needs; but limited scalability and cost burden falls on organization.

### **Public Cloud**

- Multi-tenant model managed by third-party (e.g., Google Cloud), offering on-demand compute, storage, and network.
- **Use Case:** Best for scalability, cost savings, and flexibility; potential compliance/customization trade-offs.

### **Hybrid Cloud**

- Combines public and private environments, such as on-premises data centers with cloud services.
- **Use Case:** Ideal for balancing sensitive workloads with scalable public services.

### **Multicloud**

- Use of two or more public cloud providers in an architecture.
- **Use Case:** Avoid vendor lock-in, improve reliability, or access specific cloud services.

---

## 🔧 Cloud Service Models

Three types of cloud computing service models available in the public cloud:

### **1. Infrastructure as a Service (IaaS)**

- Offers compute and storage services. Offers on-demand availability of almost infinitely scalable infrastructure resources, such as compute, networking, storage, and databases as services over the internet. Provides the same technologies and capabilities as a traditional data center without having to physically maintain or manage all of it.
- eg; Compute Engine. Commonly used by IT engineers. For organizations requiring most control & customization. Requires the most management responsibilities and technical expertise. Commonly used by IT engineers. For organizations requiring most control & customization. Requires the most management responsibilities and technical expertise.

### **2. Platform as a Service (PaaS)**

- Offers a develop-and-deploy environment to build cloud apps. Provides platform for developers to develop, run, and manage their own apps without having to build and maintain the associated infrastructure.
- eg; App Engine. Commonly used by software developers. For organizations requiring platform to build software products. Requires some technical expertise and less management.Commonly used by software developers. For organizations requiring platform to build software products. Requires some technical expertise and less management.

### **3. Software as a Service (SaaS)**

- Delivers apps as services, where users get access to software on a subscription basis. Offers entire cloud-based application through a web browser, hosted by cloud provider. Abstracts technology completely from consumer. Can be accessed anywhere and anytime.
- eg; Google Workspace. Based on subscription model (yearly/monthly). Commonly used by end users. For customers requiring ready-to-use features and hassle-free installations. Least control and customizations.Based on subscription model (yearly/monthly). Commonly used by end users. For customers requiring ready-to-use features and hassle-free installations. Least control and customizations.

---

**Abstraction** – Hiding complex implementation details to expose only essential features for simplicity.

**Shared Responsibility Model** – Cloud provider secures infrastructure; customer secures configurations, access, and data.

---

## 🔄 Hybrid & Multicloud Drivers

1. Access to latest technologies  
2. Modernize at the right pace  
3. Improved ROI  
4. Flexibility through tool choices  
5. Reliability and resiliency  
6. Regulatory compliance  
7. Running apps on-premises  
8. Running apps at remote edge locations

---

## 📈 Benefits of Cloud Computing over Traditional

1. **Scalable:** Resources scale on-demand, accelerating deployment and reducing capital expense.  
2. **Flexible:** Access services from anywhere and adjust resources as needed.  
3. **Agile:** Rapidly develop and deploy new applications without infrastructure management.  
4. **Strategic Value:** Gain competitive advantages by using the latest innovations.  
5. **Secure:** Benefit from robust, expert-managed cloud security mechanisms.  
6. **Cost Effective:** Pay only for what is used—no upfront infrastructure investment.

---

## 🔄 Digital Transformation

### **Digital Transformation**

- Leveraging digital technologies to change or improve business processes, organizational culture, and customer experiences, enabling innovation and adaptability in a rapidly evolving digital economy.
- eg; Migrating legacy systems to the cloud to enable faster delivery cycles and better customer engagement.

**Transformation Cloud Basis**

1. **Data Cloud** – Unified solution to manage data lifecycle.  
2. **Open Infrastructure** – Run applications freely to avoid budget overrun.

**Transformation Advantages** – Break down silos and gain real-time insights.

**Open Infrastructure** – Based on open-source to avoid vendor lock-in.

**CapEx (Capital Expenditure)** – Upfront fixed asset investments.

**OpEx (Operating Expenditure)** – Pay-per-use; recurring costs with faster ROI.

### **Hybrid Cloud**

- Applications running in combination of different environments such as private and public cloud environments.
- eg; Combining on-premises infrastructure with Google Cloud to balance sensitive workloads and scalability.

### **Multicloud**

- Architectures that combine more than one public cloud provider.
- eg; Using Google Cloud, Amazon Web Services, and Microsoft Azure together to avoid vendor lock-in and access unique features.

### 🔄 Hybrid & Multicloud Drivers

1. Access to latest technologies  
2. Modernize at the right pace  
3. Improved ROI  
4. Flexibility through choices of tools  
5. Improve reliability and resiliency  
6. Maintain regulatory compliance  
7. Running apps on-premises  
8. Running apps at remote edge locations

---

## ⚙️ Key Concepts

### **Abstraction**

- Process of hiding complex implementation details while exposing only essential features.
- eg; Cloud users interact with services without managing underlying infrastructure.

### **Shared Responsibility Model**

- Customer secures anything created in the cloud such as configurations, access policies, and user data.
- eg; Google secures the physical infrastructure, customer secures access control and data.

---

## 🗃️ Data Services

**Database** – Captures data for storage, retrieval, and use.

### **1) Relational (SQL)**

- Stores structured data in tables with fixed schema; supports SQL for querying and enables table relationships via joins. Reliable and best for large structured datasets, often used for OLTP.
- eg; Cloud SQL, Spanner. Use for business operations requiring consistency.

### **2) Non-Relational (NoSQL)**

- Stores data in flexible formats like documents, key-value pairs, or graphs with schema-less designs. Supports unstructured/semi-structured data and real-time scalability.
- Bigtable (Large-scale and scalable). Firestore (Serverless document dabase for client-side apps).

### **Data Warehouse**

- Enterprise system to analyze and report on structured/semi-structured data from multiple sources. Cant handle large unstructured data.
- eg; BigQuery (serverless). Use for business intelligence.

### **Data Lake**

- Repository to ingest, store, explore, process and analyze any type or volume or raw data regardless of source. Can store different types of data in their original format w/o size limit. Suitable for unstructured data.
- eg; Cloud Storage. Use for unstructured data at scale.

### **Data Types by Source**

1. **First-party**: Directly collected from your users.  
2. **Second-party**: Trusted partner’s first-party data.  
3. **Third-party**: Collected by external providers.

### **Data Governance**

- Establishing internal policies and ensuring compliance with external standards.
- eg; Apply access control and audit policies to comply with data protection regulations.

### **Storage Class**

1. Standard: Frequently read data  
2. Nearline: 30 days  
3. Coldline: 90 days  
4. Archive: 1 year

### **Datastream**

- Serverless, real-time change data capture (CDC) and data replication service that can be used to synchronize data across databases, storage systems, and applications.

### **Structured/Semi-structured Workloads**

- Analytical workload → BigQuery (SQL) / NoSQL (Bigtable)  
- Transactional workload → Cloud SQL (SQL & Local) / Spanner (SQL & Global) / Firestore (NoSQL)

### **Streaming Analytics**

- Processing and analyzing of data records continuously instead of in batches. 2 Google Cloud products:-  
  1. Pub/Sub: Messaging service that can ingest hundreds of millions of events per second from any device/application.  
  2. Dataflow: Unifies streaming and batch data analysis and builds cohesive data pipelines. Handles infrastructure setup and maintenance for processing pipelines. Provides fully-managed, serverless execution and autoscales on data volume, ideal for scalable ETL pipelines in code.  

### **Data Pipeline**

- A series of actions or stages that ingest raw data from different sources and then move that data to a destination for storage and analysis.

### **Dataproc**

- Provides managed Hadoop/Spark clusters for batch ETL jobs using familiar open-source tools.

### **Looker**

- Google Cloud business intelligence platform designed to help individuals and teams analyze, visualize, and share data. Web-based, supports BigQuery and more than 60 SQL database.

### **Data Value Chain** (8 steps)
→ Data Generation, Data Collection, Data Storage, Data Processing, Data Analysis, Data Visualization, Decision & Action, Data Governance & Security.

---

## ✨ AI & ML

### **AI**

- The use of technologies to build machines and computers that can mimic cognitive functions associated with human intelligence.

### **ML**

- A subset of AI that lets a machine learn from data without being explicitly programmed.

**Problems ML can solve:**  
1. Replacing/simplifying rule-based systems (eg; Intuitive search query)  
2. Automate processes (eg; drone to replace human)  
3. Understanding unstructured data  
4. Personalization (Improved user experience)

### **High-quality data to feed into ML**

1. Completeness - All expected data fields are present  
2. Uniqueness - No duplicate records where uniqueness is required  
3. Timeliness - Data is updated and available in time for monitoring, detection, or analytics.  
4. Validity - Data adheres to required types, formats, and ranges  
5. Accuracy - Data correctly reflects real-world values  
6. Consistency - Data is uniform and doesn’t contain contradictory information.

### **Generative AI**

- AI that can produce new content, including text, images, audio, and synthetic data.

### **Google Cloud ML models**

1. BigQuery ML: Use SQL queries to create and execute machine learning models in BigQuery  
2. Pre-trained APIs; Leverage ML models already built and trained by Google. Ideal for organization with no specialized data scientists but has business analysts and developers. Fastest & lowest effort, least customizable eg; Vision API  
3. AutoML: A no-code solution to build models on Vertex AI. Use own data to train models.  
4. Custom training: Code your own ML environment to have control over ML pipeline.

### **Considerations when selecting Google Cloud AI/ML solution**

1. **Speed**, to get model to production  
2. **Differentiation** (Uniqueness of model),  
3. **Expertise** required embarking on AI/ML project,  
4. **Effort** required to build AI solution.

**Google AI Principles**: Google makes tools that empower others to harness AI for individual and collective benefit.

---

## 🔄 Cloud Migration Terms

### **Workload**

- An application, service, or group of resources that perform a business function. Example: email server, database system.

### **Retired**

- The workload is no longer needed and is shut down or decommissioned.

### **Retained**

- The workload stays on-premises or in its current environment, often for compliance, cost, or complexity reasons.

### **Rehosted (Lift and Shift)**

- Move the workload to the cloud **without changes**. Fast and simple migration strategy.

### **Replatform (Move and Improve)**

- Move to the cloud **with some changes** (e.g., updating OS or database). Less effort than refactoring but may involve complexity.

### **Refactored**

- Modify the **application code** to take advantage of cloud-native features (e.g., converting monolith to microservices).

### **Reimagined**

- Redesign or **completely rebuild** the workload using cloud-native tools and architecture (e.g., serverless, Kubernetes, AI/ML integration).

---

## 🏗️ Vertex AI

- Google’s Unified ML platform for building, training, and deploying machine learning models.  
→ **AutoML**: Toolset within Vertex AI that enables non-ML experts to train high-quality models without writing code (GUI).

### **Key Vertex AI Services**

1. **Vertex AI Data Labeling** – Create and manage labeled datasets for training ML models.  
2. **Vertex AI Pipelines** – Automate and orchestrate ML workflows from data preparation to deployment.  
3. **Vertex AI Feature Store** – Store, manage, and serve ML features consistently across training and prediction.  
4. **Vertex AI Experiments** – Track and compare training runs and tuning results for model reproducibility.  
5. **Vertex AI Workbench** – Jupyter-based environment for ML development integrated with GCP tools.  
6. **Vertex AI Model Registry** – Central hub to register, version, and manage trained models before deployment.  
7. **Vertex AI Prediction** – Deploy models to endpoints for real-time or batch prediction at scale.  
8. **Vertex AI Vizier** – Hyperparameter tuning service to optimize model performance automatically.

### **TensorFlow**

- Open-source platform for ML. Takes advantage of **TPU**, Google’s developed Application Specific Integrated Circuit (ASIC) used to accelerate machine learning workloads.

---

## 🌐 Google API

### **Vision API**

- Image analysis: labels, OCR, face, object, logo, and landmark detection. Extract text from documents.

### **Natural Language API**

- Can analyze and classify text for sentiment, toxicity, and inappropriate content, making it ideal for automating moderation of comments, posts, and other user‐generated text on websites and social platforms.

### **Translation API**

- Translate text between 100+ languages. Use for multilingual apps, email translation, or phishing analysis.

### **Speech-to-Text API**

- Converts audio to text. Use to transcribe voice notes, meetings, or customer service calls.

### **Text-to-Speech API**

- Converts text to natural-sounding speech. Use for voice assistants or accessibility tools.

### **Video Intelligence API**

- Detects objects, scenes, and activities in videos. Use for content tagging, moderation, or video search.

---

## 🤖 Google AI Solutions

### **Contact Center AI**

- Designed to help businesses improve customer service through AI-powered virtual agents, agent assist, and natural language understanding.

### **Document AI**

- Automates document processing using OCR. Great for extracting data from invoices, forms, and scanned files.

### **Discovery AI**

- Provides product recommendations and personalized search for e-commerce platforms.

### **Recommendations AI**

- Suggests products or content based on user behavior. Use for e-commerce personalization or media recommendations.

---

## ☁️ Compute Options

### VM-based Compute Options

1. **Compute Engine** – Google Cloud’s IaaS offering for creating and managing virtual machines on its global network, with customizable CPU, memory, storage, and networking, plus features like autoscaling and load balancing; ideal when you need complete OS-level control, want to lift-and-shift existing VM images, or must run software that can’t be easily containerized. Use case: Spotify  
2. **Google Cloud VMware Engine** – A fully managed VMware, infrastructure, networking and management services are run by Google. Use case: DBG  
3. **Bare Metal Solution** – Dedicated, single-tenant physical servers in Google’s data centers with low-latency links into your VPC; suited for workloads demanding physical isolation, strict compliance, or ultra-predictable performance (e.g., Oracle Database, SAP HANA).

### Container-based Compute Option

1. **Google Kubernetes Engine (GKE)** – Google Cloud manage service for container orchestration. Deploy, scale and manage containers on Compute Engine VM clusters, with built-in autoscaling, rolling updates, and integrated networking and security. Can be used for application development. Serverless

### Serverless Computing Options

1. **App Engine** – A fully managed PaaS for building and hosting web and mobile application in any language; auto-scales your app and lets you focus purely on code without managing servers.  
2. **Cloud Run** – Deploy container-based web applications in any language or framework; scales from zero to meet traffic instantly with no servers or infrastructure to provision.  
3. **Cloud Functions** – Event-driven FaaS designed to run single-purpose functions on triggers (HTTP requests, new orders being received).

---

## 🏗️ Patterns for Modernizing Applications

1. **Move to cloud, then change** – Shift workloads first, optimize later.  
2. **Change before move** – Re-architect apps for cloud readiness before migrating.  
3. **Greenfield** – Build entirely new infrastructure and applications in the cloud.  
4. **Brownfield** – Create a new app in the cloud to replace an existing legacy app. Used when legacy systems are outdated, can also be used concurrently (1 cloud and 1 legacy)  
5. **Move without change** – Simple lift-and-shift migration, no major alterations.

---

## 🧱 Developing Cloud-Native Applications

1. **Monolithic Architecture** – Single codebase, tightly coupled components. Updates are complex as the entire app must be redeployed.  
2. **Microservices** – Modular, independently deployable components—easier to scale and maintain.  
3. **CI/CD** – Automates testing, integration, and delivery; enables fast and safe deployments with minimal risk. CI/CD pipelines increases application release velocity and reliability.

---

## 🧓 Legacy System Challenges

1. Not developed to support of modern technologies or mobile applications eg; IoT, cloud.  
2. Operate on batch-based data flows and cannot support real-time processing needs.

---

## 🔗 API (Application Programming Interface)

- Enables integration between systems, supporting the development of connected digital ecosystems. Originally a tool for integration, APIs now drive innovation and create new business value.

---

## 🔐 API Management

- Centralized process of designing, securing, publishing, and monitoring APIs to ensure consistency, security, and performance. A key outcome is **measuring and tracking business performance** through usage analytics and operational insights.

---

## 🛠️ Apigee (Google Cloud API Platform)

- Google Cloud’s API management platform that helps organizations design, secure, publish, monitor, and analyze APIs.

---

## 🔒 Cloud Security Model

1. **Privileged Access Security Model**: Grants specific users access to broader set of resources than ordinary users  
2. **Least Privilege Security Principle**: Grants users only the access they need to perform their job responsibility - Minimum required access  
3. **Zero-Trust Architecture**: Assumes no user/device can be trusted by default, requires continuous authentication and authorization when accessing resources.

---

## 🔐 How Organizations Can Protect Itself from Cyber Threats

1. **Security be default**: Emphasizes integrating security measures into systems and applications from the initial stages of development  
2. **Security Posture**: Overall security status of a cloud environment - how well its prepared to defend against cyber attack  
3. **Cyber Resilience**: Organization’s ability to withstand/recover quickly from cyber attacks

---

## 🛡️ Security Measures to Protect Cloud Resources

1. **Firewall**  
2. **Encryption**  
3. **Decryption**

---

## 🛡️ CIA Triad

- Confidentiality, Integrity, Availability

---

## 🗄️ Artifact Registry

**Artifact Registry** is a **fully managed service** in Google Cloud for storing, managing, and securing **build artifacts** such as container images, Helm charts, and language packages (e.g., Java, Python). It supports **secure storage and sharing** of artifacts across environments and integrates with CI/CD pipelines.

It provides a **centralized, scalable repository** to manage deployment artifacts, enforce security policies, and streamline application delivery workflows.

---

## 🏠 Traditional On-Premises Security vs Cloud Security

1. **Location** – Cloud security hosts data and applications in off-site data centers managed by cloud providers, whereas on-premises security relies on the organization’s own local servers and infrastructure.  
2. **Responsibility** – In the cloud, the provider secures the infrastructure and physical environment, while the customer secures configurations, applications, and data; in on-premises setups, the organization is fully responsible for securing all aspects of the environment.  
3. **Scalability** – Cloud environments offer elastic scalability that allows resources to expand or shrink on demand, while on-premises environments require manual provisioning of hardware, which is costly and slow.  
4. **Maintenance & Updates** – Cloud providers manage infrastructure maintenance, patching, and updates, whereas on-premises environments require the organization to handle all system maintenance and software updates themselves.  
5. **Cost Model** – Cloud uses an OpEx model with pay-as-you-go flexibility and minimal upfront costs, while on-premises infrastructure follows a CapEx model with significant initial investment and ongoing operational expenses.

---

## ⚔️ Cybersecurity Threats

1. Deceptive Social Engineering: Phishing, BEC  
2. Physical Damage  
3. Malware, virus, ransomware  
4. Vulnerable third-party systems  
5. Configuration mishaps

---

## 🏢 Google Data Center

- Implementation of zero-trust architecture: Hardware and software are purpose-built with features like Tamper-evident hardware, secure boot, hardware-based encryption  
- Physical Security: Access control measure, biometric authentication, principle of least privilege  
- Embodies Concept of Security  
- Efficiency: Reduced energy consumption, lower operating costs, saves resources and environment. Measured through Power Usage Effectiveness (PUE)  
- Scalability: New hardware and servers can be quickly/seamlessly accommodated  
- Flexibility: Manage their own servers and network, unparalleled customization

---

## 🔒 Encryption

- All customer content are encrypted at rest (extra layer of protection)  
- Customer can manage encryption via Cloud Key Management Service (Cloud KMS)  
- Memory Encryption - data at use is locked inside computer memory  
- Encryption algo: AES

---

## 🆔 Identity

1. **Authentication**: Unique credentials. 2 step verification adds extra protective layer to cloud-based system.  
2. **Authorization**: Access control mechanism, determines what user/system is allowed to do within system  
3. **Auditing**: Monitors/tracks user activities

---

## 🗝️ Identity and Access Management (IAM)

- A framework of policies and technologies that ensures the right individuals and systems have the appropriate access to cloud resources at the right time.

---

## 🛡️ Network Security

- **Google Cloud Armor**: Google service designed to protect applications and services from Distributed Denial-of-Service (DDoS) attacks, malicious traffic, and unwanted requests at the edge of Google’s network.  
- **BeyondCorp Enterprise**: Enables zero trust security by continuously verifying user identity and context for every access request—ensuring secure access inside and outside your organization.  
- **Cloud VPN & Cloud Interconnect**: Provide secure private connectivity between on-premises or multi-cloud environments and Google Cloud, supporting hybrid and multi-cloud architectures.  
- **VPC Service Controls & Shared VPC**: Enhance perimeter security by isolating services across projects and enforcing strict access boundaries within Google Cloud environments.  
- **Web Application Firewall (WAF)**: Built into Google Cloud Armor, helps protect web applications from threats like DDoS, SQL injection, and cross-site scripting.  
- **Infrastructure Automation Tools (Terraform, Jenkins, Cloud Build)**: Automate cloud resource provisioning to create secure, immutable infrastructure—reducing configuration errors and enabling rapid recovery.

---

## 🛡️ Security Command Center (SCC)

- Google Cloud’s native security and risk-management platform that provides a centralized dashboard to **inventory assets, detect misconfigurations and vulnerabilities, surface real-time threats, and track compliance** across your GCP environment. It aggregates findings from Google and partner security services, enabling rapid investigation and unified policy enforcement at organization, folder, or project level.

---

## 🤝 Google Cloud Trust Principles

1. **You own your data, not Google**  
   – You can access, export, delete, and manage your data and its permissions at any time.  

2. **Google does not sell customer data to third parties**  
   – Your data is never sold or monetized for marketing or advertising purposes.  

3. **Google Cloud does not use customer data for advertising**  
   – Customer data is not used to build advertising profiles or serve targeted ads.  

4. **All customer data is encrypted by default**  
   – Data is automatically encrypted at rest and in transit to protect confidentiality and integrity.  

5. **We guard against insider access to your data**  
   – Strict access controls and monitoring are in place to prevent unauthorized employee access.  

6. **We never give any government entity "backdoor" access**  
   – Google only provides data when legally required and does not build hidden access paths.  

7. **Our privacy practices are audited against international standards**  
   – Google undergoes independent audits to validate compliance with global data protection regulations.

---

## 🌐 Data Sovereignty & Data Residency

- **Data sovereignty** means data is subject to the laws of the country where it resides, ensuring compliance with regulations like the EU’s GDPR.  
- **Data residency** refers to the physical location where data is stored or processed, often mandated to stay within a country’s borders. **Google Cloud supports data residency** by allowing you to choose specific regions (e.g., Germany, Finland) where your data will remain.

**Organization Policy and IAM settings** prevent accidental storage in unauthorized regions.

**VPC Service Controls** restrict access to data through defined network perimeters.

**Google Cloud Armor** adds protection by filtering traffic for external load balancer based on geographic origin.

These controls **work together** in layered defense:

- **Org Policy** (what’s allowed) → **IAM** (who can access) → **VPC SC & Cloud Armor** (network boundaries)

This layered approach is essential for **compliance, zero-trust security, and preventing data breaches**.

---

## 📜 Compliance Resource Center

- Details about certifications and compliance standards met by Google Cloud.

---

## 📰 Transparency Reports

- Provide a way for Google Cloud to share data about how the policies and actions of governments and corporations affect privacy, security, and access to information.

---

## 💰 Google Cloud Pricing Calculator

- A **proactive** tool to **simulate usage scenarios** and estimate future costs based on service configurations.

---

## 👥 Roles in Managing Cloud Costs

1. **People:** Involves finance, technology, and business teams working together to manage cloud costs effectively. Larger organizations may form a centralized group, such as a Cloud Center of Excellence, to ensure real-time visibility and cost control across departments.  
2. **Process:** Involves regular monitoring, cost analysis, and chargebacks to ensure optimized spending. A culture of accountability and collaboration across teams helps reduce waste and align cloud usage with business objectives.  
3. **Technology:** Refers to the use of cost management tools provided by platforms like Google Cloud. These tools improve visibility, prevent overspending, and deliver intelligent insights to optimize usage and promote responsible cloud consumption.

---

## 💼 Cloud Financial Best Practice

1. **Identify who manages cloud costs**  
   Assign ownership to a dedicated individual or a cross-functional team (IT + Finance) and promote cost accountability by sharing usage and spending visibility across departments.

2. **Understand invoices versus cost management tools**  
   Invoices show total spend, while cost tools provide insights into spending behavior. Use cost management tools to uncover trends, analyze usage, and inform optimization efforts.

3. **Use Google Cloud’s cost management tools**  
   - **Google Cloud Budgets** – Set custom spending thresholds and trigger email alerts to stakeholders as costs approach or exceed defined limits. Includes **Budget Threshold Rules** for setting alerts at defined percentage thresholds.  
   - **Billing Reports** – Analyze detailed historical cost and usage data to identify trends and track spending across projects and departments.  
   - **Google Cloud Pricing Calculator** – Estimate future costs by configuring potential service usage scenarios, helping with budget planning and decision-making.  
   - **Quota Policies** – Set usage limits on cloud resources (e.g., CPU, API calls) at the project or user level to prevent over-consumption and enforce resource control.

---

## 🏛️ Google Cloud Resource Hierarchy

- **Organization:** The top-level node represents the entire company or domain and encompasses all folders, projects, and resources. It provides centralized governance, policy enforcement, billing oversight, and visibility across the entire cloud environment.  
- **Folders:** Folders allow structured grouping of projects and even subfolders, making it easier to apply and manage IAM policies at scale. Permissions set here are inherited by all nested projects and resources, enabling consistent access control across teams or departments.  
- **Projects:** Projects serve as the primary unit for deploying and managing Google Cloud services. Each project has its own configurations, billing account, APIs, and policies, and acts as a logical boundary for organizing related resources.  
- **Resources:** The lowest level in the hierarchy includes specific services such as Compute Engine instances, Cloud Storage buckets, and BigQuery datasets. While they inherit policies from their parent project, some services allow direct policy assignment at the resource level.

---

## 📊 Four Golden Signals (SRE Monitoring)

1. **Latency** – Time it takes for a system to return a response.  
2. **Traffic** – Volume of requests sent to the system.  
3. **Errors** – Rate of failed or incorrect requests.  
4. **Saturation** – How full or close to capacity system resources are.

---

## 🔁 Replication

- Duplicates data or services across **multiple locations or systems**, ensuring availability even if one fails. This enhances **resilience** and **disaster recovery**.

---

## 👷‍♂️ Site Reliability Engineer

- Ensures the reliability, availability, and efficiency of software systems and services deployed in the cloud.

---

## 📞 Google Cloud Customer Care Support Levels

1. **Basic** – Free; includes documentation, community support, and billing help.  
2. **Standard** – Paid; 4-hour response for high-priority issues, suitable for small teams.  
3. **Enhanced** – Faster response (as low as 1 hour), 24/7 support, access to advisors.  
4. **Premium** – 15-min response for critical issues, includes TAM and proactive guidance.

---

## 🔎 Google Cloud Observability Tools

- **Cloud Trace** – Collects latency data to visualize request flow and identify slow operations.  
- **Cloud Logging** – Centralizes logs for analysis, monitoring, and troubleshooting.  
- **Cloud Monitoring** – Tracks system metrics, uptime, and performance with alerting capabilities.  
- **Cloud Profiler** – Identifies how much CPU power, memory, and other resources an application uses.  
- **Cloud Debugger** – Lets you inspect the state of applications in production without stopping or slowing them down.  
- **Error Reporting** – Automatically aggregates and reports errors from cloud applications for faster debugging.

---

## 🌍 Google's 2030 Goal

- Operate entirely on carbon-free energy (CFE), 24/7, across all its data centers and campuses worldwide.

---

## 🌱 ISO 14001

- Framework for an organization to enhance its environmental performance through improving resource efficiency and reducing waste.

---

## 📱 Google Cloud Console Mobile App

Allows users to:  
- View **alert notifications** (e.g., monitoring or budget alerts)  
- Access **billing information** (current spend, budgets)  
- Check **resource status** (health and availability of VMs, services, etc.)

It’s designed to help you **monitor and manage cloud resources on the go**.

---

## 🔄 Database Migration Service

- Migrates database with minimal disruptions and secures data in transit.

---

## 🌐 Google Cloud Anthos

- A hybrid and multi-cloud application management platform that lets you deploy, manage, and secure applications across GCP, on-premises data centers, and other cloud providers like AWS or Azure using a consistent Kubernetes-based environment.

---

## ⚙️ Google Cloud Operations

- A unified suite of observability and management tools (formerly Stackdriver) that provides **monitoring**, **logging**, **tracing**, **error reporting**, and **alerting** for applications and infrastructure on Google Cloud (and beyond). It enables teams to gain end-to-end visibility, troubleshoot issues faster, and ensure reliable service performance.

---

## 🖥️ AI Platform Notebooks

- Provides fully managed JupyterLab environments for data science and machine learning.

---

## 💻 Cloud Source Repositories

- Hosts and manage source code repositories in the cloud.

---

## 🖧 Managed Instance Group

- Refers to a set of computing engines that can be easily managed.

---

## 🌐 How Many Zones Are Present in a GCP?

**3**

---

## 🚀 Application Load Testing

- Should be done to sustain **5x** the expected traffic to the application.

---

## 🔧 Based on DevOps Philosophy, Reliability and Health of Production Systems

- Should be done first in modern cloud design.

---

## ⏱️ Biggest Factor to Consider When Building Application for Business Continuity

- **Meantime for recovery** in case of disaster recovery.

---

## 🌬️ Cloud Composer

- Google Cloud’s fully managed **Apache Airflow** service. It lets you author, schedule, and monitor data pipelines and workflows without the overhead of managing the Airflow infrastructure yourself.

---

## 🔐 Key Features of Google Cloud Confidential Computing

1. **Secure Enclave Technology**: Isolates workloads in hardware-based trusted execution environments (TEEs).  
2. **Hardware-based Encryption for Data in Use**: Encrypts data while it’s being processed, not just at rest or in transit.  
3. **Seamless Integration with Google Cloud Services**: Works with Compute Engine, GKE, and other GCP products for end-to-end confidentiality.

---

## 📝 TO NOTE

**Materials**: [Cloud Digital Leader Learning Path | Google Cloud Skills Boost](https://www.cloudskillsboost.google/paths/9)  
**Mock Exam**: [Cloud Digital Leader Sample Questions](https://docs.google.com/forms/d/e/1FAIpQLSedAmf77MGS7FGEaylFzY51KtBd7kkIZJIMDsV5zSRSmpKIOA/viewform)
