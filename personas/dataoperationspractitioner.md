# Data Operations Personas

## Name: Daniel the Data Scientist

### Role:
- Applied ML Researcher in a healthcare startup

### Background:
- Daniel develops machine learning models using clinical data. She frequently experiments with new datasets, pretrained models, and open-source ML libraries. While experienced in model evaluation and performance metrics, she is less familiar with security threats in ML workflows and often unaware of potential risks in data or pretrained components.

### Goals:
- Deliver accurate and explainable ML models
- Maintain compliance with health data privacy regulations
- Reproduce experiments for audit and debugging

#### Personal
- Become a leader in applying ML to health outcomes
- Ensure her work aligns with responsible and ethical AI practices

#### Project
- Produce high-performing models without introducing bias or security risks
- Ensure models can be maintained and evaluated over time

#### Organization
- Align with security, regulatory, and reproducibility standards
- Avoid data leakage and model misuse

### Challenges:
- Lacks tooling to detect poisoned or anomalous training data
- Security validation steps are not integrated into notebooks or pipelines
- Difficult to track lineage and integrity of datasets and models
- No standard process for documenting model security posture

### How the OpenSSF can help:
- Create developer-friendly tools to flag insecure datasets and dependencies within ML environments
- Offer templates and standards for model cards with reproducibility and security metadata
- Promote open-source privacy-preserving defaults and example pipelines for common ML tasks
- Advocate for adversarial robustness and input validation best practices in ML tooling

---

## Name: Susan the Data Engineer

### Role:
- Senior Data Platform Engineer at a financial institution

### Background:
- Susan manages data ingestion and transformation pipelines using distributed frameworks like Spark and Airflow. He ensures that data systems are scalable and reliable, but security has traditionally been handled by IT or infosec teams. With growing ML use, he is now more involved in securing the data lifecycle.

### Goals:
- Maintain secure and reliable pipelines for ML and analytics
- Avoid propagation of corrupted or unvalidated data
- Track provenance and enforce pipeline integrity

#### Personal
- Improve automation and reliability of data operations
- Upskill in ML-specific risk areas

#### Project
- Build secure data pipelines with well-governed datasets
- Reduce time spent debugging data quality or security incidents

#### Organization
- Ensure data compliance and traceability for audit and regulation
- Align with enterprise data governance frameworks

### Challenges:
- No easy way to sign or verify dataset integrity across pipeline stages
- Lacks integrated controls for verifying external data sources or APIs
- Hard to enforce versioning or rollback for changing data
- ML engineers often treat the data as “just there” without understanding its risks

### How the OpenSSF can help:
- Provide secure-by-default modules or plugins for Airflow/Spark
- Promote signing and hashing practices for datasets and intermediate artifacts
- Offer examples of secure ingestion patterns and lineage tracking tools
- Align with data governance efforts to bridge ML and platform teams

---

## Name: Noura the Data Governance Analyst

### Role:
- Data Privacy and Compliance Lead in a government agency

### Background:
- Noura ensures that data used in analytics and ML respects privacy regulations and internal policies. She’s responsible for approvals, classification, and tracking lineage. Her technical knowledge is moderate, but her role is critical in assessing risk and enabling compliance.

### Goals:
- Prevent use of unapproved or sensitive data in ML systems
- Maintain traceability of data usage and transformations
- Support safe data sharing across teams and partners

#### Personal
- Reduce manual review cycles through clear controls and metadata
- Empower teams to follow data policies without creating bottlenecks

#### Project
- Flag and audit sensitive data use across ML systems
- Ensure ML outputs do not leak private or restricted information

#### Organization
- Meet privacy regulations such as GDPR or HIPAA
- Build public trust through responsible data stewardship

### Challenges:
- Difficult to enforce policies when ML pipelines are opaque
- No visibility into how data flows through models once deployed
- Limited tooling for assessing third-party ML component risk
- Compliance processes are reactive and documentation-heavy

### How the OpenSSF can help:
- Provide schemas and tooling for data classification and policy tagging in ML workflows
- Promote integrations between metadata tracking and ML toolchains
- Offer standards for auditability and explainability in AI governance
- Create pathways for compliance automation using policy-as-code templates
