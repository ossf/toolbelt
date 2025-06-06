# Data Operations Personas

## Name: Daniel the Data Scientist

### Role:
- Senior Data Scientist at a digital health startup

### Background:
- Daniel builds predictive models using healthcare and sensor data to improve patient outcomes. He's responsible for experimentation, model performance, and reproducibility. Outside of his work, he’s passionate about secure and ethical AI. He recently began contributing to an OpenSSF project on secure model provenance. Balancing his full-time job with open source contributions has been challenging, but he sees it as essential to pushing ML security forward.

### Goals:
- Develop ML models that are both high-performing and safe for clinical use
- Bring practical security practices into the ML workflows he uses daily
- Help improve open-source tooling for reproducible and secure AI pipelines

#### Personal
- Become recognized as a leader in trustworthy AI
- Maintain a sustainable balance between work, open source, and family life

#### Project
- Ensure reproducibility and data traceability for every model released
- Contribute to OpenSSF to advance practical tools for ML security

#### Company
- Align with data protection regulations and ensure safe model deployment
- Use insights from open source to improve internal ML security practices

### Challenges:
- Managing contributions to OpenSSF while keeping up with sprint deadlines
- ML notebooks and experiments are hard to integrate into security pipelines
- There is no established process at work for evaluating external model dependencies
- His team lacks dedicated support for integrating open-source security tools into research workflows

### How the OpenSSF can help:
- Provide reproducibility templates and secure model card standards that Daniel can use and share internally
- Offer tools like Scorecard adapted to ML projects, enabling better visibility into risks for shared models and datasets
- Host mentoring sessions and asynchronous contributor onboarding for working professionals like Daniel
- Promote examples of how companies have successfully integrated MLSecOps practices

#### If contributing to OpenSSF project
- Easy-to-follow contribution workflows that fit around work hours
- Documented reproducibility and integrity standards that he can adapt internally

#### If using OpenSSF tools in enterprise
- Secure model artifact verification via SLSA extensions
- Reproducible training environment setups aligned with best practices
 
---

## Name: Susan the Data Engineer

### Role:
- Senior Data Platform Engineer at a financial institution

### Background:
- Susan manages large-scale data pipelines using Spark, Airflow, and custom ingestion services. She works closely with data scientists and analysts to ensure reliable delivery of datasets for ML and BI. Recently, she began contributing to an OpenSSF working group focused on securing data pipelines. Juggling this with internal compliance obligations and technical debt has been challenging, but she’s driven by the desire to help modernize how data infrastructure supports secure ML.

### Goals:
- Improve pipeline observability and introduce security checks at ingestion points
- Enable her organization to adopt secure data provenance and validation practices
- Contribute to and benefit from open-source solutions for ML data security

#### Personal
- Develop leadership in secure data engineering practices
- Balance community contributions with high-pressure enterprise responsibilities

#### Project
- Embed security scanning into existing ETL workflows without major refactors
- Use lessons from OpenSSF to develop reusable internal patterns for data integrity

#### Organization
- Demonstrate compliance through end-to-end data traceability
- Support ML teams with trustworthy, auditable datasets

### Challenges:
- Hard to justify time spent on upstream contributions in a fast-paced compliance-driven org
- Many OSS data pipeline tools lack security or signing support by default
- No standardized way to prove pipeline-level integrity or control input quality
- Security controls often live outside data pipelines and are hard to align with platform architecture

### How the OpenSSF can help:
- Publish hardened examples of secure ML data pipelines with reproducible, signed inputs
- Develop integrations with pipeline orchestrators like Airflow and dbt for metadata and signature enforcement
- Make the Scorecard and SLSA framework applicable to data pipelines and ingestion systems
- Provide contributor templates, Slack access, and async-friendly contribution guides to lower the barrier for part-time contributors

#### If contributing to OpenSSF project
- Susan benefits from collaboration with peers facing similar issues across industries
- Access to code examples, contributor templates, and async support for patching pipeline tools

#### If using OpenSSF tools in enterprise
- Tools for signing and verifying datasets used in retraining loops
- Reference architectures and policies for aligning ML data pipelines with secure software supply chain practices

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
