# NIST

## 1. Cybersecurity Framework

### 1.1. NIST CSF 2.0

#### 1.1.1. Overview

The NIST Cybersecurity Framework (CSF) 2.0, released in February 2024, is a flexible and non-prescriptive framework designed to help organizations manage cybersecurity risks effectively. It applies to entities of all sizes and across sectors, various missions, technologies (including AI), and regulatory environments, integrating cybersecurity with enterprise risk management.

##### 1.1.1.1. Scoping of AI system and/or cybersecurity purview

The NIST CSF 2.0 provides a flexible structure for scoping cybersecurity efforts, including AI systems, by integrating governance, risk management, and technical safeguards into a unified framework.

*By using the NIST CSF 2.0, organizations can effectively:*

1. *Define and document the scope of AI systems, aligning with organizational risk management practices.*
2. *Ensure that cybersecurity safeguards and monitoring mechanisms address the unique challenges of AI technologies.*
3. *Establish clear roles and responsibilities for managing risks associated with AI and other scoped systems.*
4. *Continuously improve scoping practices to adapt to emerging threats, technologies, and regulatory changes.*

##### 1.1.1.2. Persona addressed

| **CSF Function / Activity**                | **AI System Owner** | **Cybersecurity Team** | **Data Scientist / AI Engineer** | **Software Development Team** | **SRE Team** | **Software Architecture Team** | **Legal / Compliance Team** | **Executive Leadership** | **External Vendors** |
| ------------------------------------------ | ------------------- | ---------------------- | -------------------------------- | ----------------------------- | ------------ | ------------------------------ | --------------------------- | ------------------------ | -------------------- |
| **Govern (GV)**                            |                     |                        |                                  |                               |              |                                |                             |                          |                      |
| Define AI cybersecurity governance scope   | R                   | A                      | C                                | C                             | I            | C                              | C                           | I                        | I                    |
| Establish AI risk management strategy      | A                   | R                      | C                                | C                             | C            | C                              | C                           | I                        | I                    |
| Develop supply chain risk policies for AI  | R                   | C                      | I                                | I                             | I            | C                              | A                           | I                        | R                    |
| Define ethical AI usage guidelines         | A                   | C                      | R                                | C                             | I            | C                              | R                           | I                        | I                    |
| **Identify (ID)**                          |                     |                        |                                  |                               |              |                                |                             |                          |                      |
| Inventory AI systems and dependencies      | R                   | C                      | R                                | C                             | C            | C                              | I                           | I                        | C                    |
| Conduct AI-specific risk assessments       | C                   | R                      | A                                | C                             | I            | C                              | C                           | I                        | C                    |
| Map AI data flow and privacy risks         | R                   | C                      | R                                | C                             | I            | C                              | A                           | I                        | I                    |
| Evaluate third-party AI components         | R                   | R                      | C                                | C                             | I            | C                              | I                           | I                        | A                    |
| **Protect (PR)**                           |                     |                        |                                  |                               |              |                                |                             |                          |                      |
| Implement access controls for AI systems   | C                   | R                      | C                                | C                             | R            | C                              | I                           | I                        | I                    |
| Secure training data and models            | R                   | R                      | A                                | C                             | C            | C                              | I                           | I                        | I                    |
| Encrypt data in AI pipelines               | I                   | R                      | A                                | C                             | R            | C                              | I                           | I                        | C                    |
| Enforce secure software development        | C                   | R                      | A                                | R                             | C            | A                              | I                           | I                        | R                    |
| **Detect (DE)**                            |                     |                        |                                  |                               |              |                                |                             |                          |                      |
| Monitor AI models for adversarial inputs   | C                   | R                      | R                                | I                             | R            | C                              | I                           | I                        | C                    |
| Detect anomalies in AI behavior            | C                   | R                      | A                                | C                             | R            | C                              | I                           | I                        | I                    |
| Monitor AI supply chain for threats        | C                   | R                      | I                                | I                             | C            | C                              | I                           | I                        | R                    |
| Analyze cybersecurity incidents in AI      | R                   | A                      | C                                | I                             | R            | C                              | I                           | I                        | I                    |
| **Respond (RS)**                           |                     |                        |                                  |                               |              |                                |                             |                          |                      |
| Activate incident response for AI attacks  | R                   | A                      | C                                | I                             | R            | C                              | C                           | I                        | C                    |
| Mitigate data poisoning or model tampering | C                   | R                      | A                                | C                             | R            | C                              | I                           | I                        | I                    |
| Report AI-related incidents to regulators  | I                   | R                      | C                                | I                             | I            | C                              | A                           | C                        | I                    |
| Share threat intelligence with partners    | C                   | R                      | I                                | I                             | I            | C                              | C                           | I                        | A                    |
| **Recover (RC)**                           |                     |                        |                                  |                               |              |                                |                             |                          |                      |
| Rebuild or retrain compromised models      | R                   | C                      | A                                | C                             | C            | C                              | I                           | I                        | I                    |
| Validate integrity of restored AI systems  | R                   | R                      | C                                | C                             | C            | A                              | I                           | I                        | C                    |
| Communicate recovery progress              | I                   | R                      | C                                | I                             | C            | C                              | C                           | A                        | I                    |



##### 1.1.1.3. Guidance provided

The NIST Cybersecurity Framework (CSF) 2.0 provides guidance for organizations to manage cybersecurity risks effectively and integrate cybersecurity practices with broader enterprise risk management strategies. 

The NIST CSF 2.0 serves as a foundational tool to:

1. Standardize cybersecurity practices across organizations, sectors, and regions.
2. Integrate cybersecurity into business strategies and risk management frameworks.
3. Adapt to emerging challenges in technology, supply chains, and global threats.
4. Foster a culture of proactive risk management and continuous improvement.

#### 1.1.2. Detail on current framework

CSF consists of three core sections:

1. ***CSF Core:*** A hierarchy of cybersecurity outcomes categorized into six Functions: Govern, Identify, Protect, Detect, Respond, and Recover.
2. ***Profiles:*** Mechanisms to describe an organization's current and target cybersecurity postures.
3. ***Tiers:*** Four levels (Partial, Risk Informed, Repeatable, Adaptive) for evaluating the rigor of cybersecurity governance and risk management.
   


##### 1.1.2.1. CSF functions and key concepts applicable to scoping AI systems #####


***1. Govern (GV): Defining Scope and Strategy***

| Function | Details |
| --- | --- |
| **GV.OC (Organizational Context)** | 1. Understand the mission and objectives of the AI system. |
| | 2. Assess internal and external stakeholders expectations, such as customers or regulatory bodies. |
| | 3. Document legal, regulatory, and contractual requirements related to AI systems, such as GDPR or AI-specific laws. |
| **GV.RM (Risk Management Strategy)** | 1. Define the organization's risk appetite and tolerance specific to AI and cybersecurity risks. |
| | 2. Develop a strategy to address risks from AI systems, such as adversarial attacks, model drift, and data poisoning. |
| | 3. Align AI system goals with broader enterprise risk management (ERM) strategies. |
| **GV.SC (Supply Chain Risk Management)** | 1. Integrate supply chain considerations for AI, such as third-party datasets, pre-trained models, and cloud services. |
| | 2. Establish roles, responsibilities, and contractual requirements with suppliers managing AI components. |


***2. Identify (ID): Mapping Scope and Risks***

| Function | Details |
| --- | --- |
| **ID.AM (Asset Management)*** | 1. Create an inventory of AI system components, including data sources, algorithms, hardware, and cloud services. |
|  | 2. Maintain a list of critical assets across the cybersecurity domain, ensuring dependencies are mapped. |
| **ID.RA (Risk Assessment)** | 1. Assess potential threats to the AI system, such as adversarial manipulation or data breaches. |
| | 2. Evaluate vulnerabilities in AI lifecycle stages (e.g., training, deployment) and external dependencies. |
| | 3. Quantify the likelihood and impact of risks, such as model exploitation or ethical violations. |
| **ID.IM (Improvement)** | 1. Use lessons learned from AI system incidents or evaluations to refine scoping. |
| | 2. Identify gaps in cybersecurity coverage or governance that impact AI-specific risks. |



***3. Protect (PR): Defining Safeguards Within Scope***

| Function | Details |
| --- | --- |
| **PR.AA (Identity Management and Access Control)** | 1. Enforce access controls to safeguard AI models, training data, and outputs. |
| | 2. Ensure identity management practices for users accessing AI systems are robust. |
| **PR.DS (Data Security)** | 1. Protect AI data at rest, in transit, and in use from unauthorized access and tampering. |
| | 2. Secure sensitive datasets used for training and inference processes. |
| **PR.PS (Platform Security)** | 1. Implement secure configurations for AI infrastructure, including cloud environments and hardware accelerators. |
| | 2. Prevent unauthorized software installation or execution within AI pipelines. |


***4. Detect (DE): Monitoring for Threats***


| Function | Details |
| --- | --- |
| **DE.CM (Continuous Monitoring)** | 1. Monitor AI system performance for anomalies, such as adversarial inputs or unexpected outputs. |
| | 2. Track network activity and system logs for indicators of compromise in AI components. |
| **DE.AE (Adverse Event Analysis)** | 1. Analyze anomalies in AI behavior to determine root causes, such as training data corruption or adversarial manipulation. |
| | 2. Correlate information from multiple sources, including threat intelligence, to understand incidents affecting AI systems. |


***5. Respond (RS): Taking Action Within Scope***


| Function | Details |
| --- | --- |
| **RS.MA (Incident Management)** | 1. Execute incident response plans for AI-related events, such as data breaches or system exploitation. |
| | 2. Coordinate responses with external stakeholders, including cloud providers and AI model vendors. |
| **RS.CO (Incident Communication)** | 1. Communicate incident details to internal teams, partners, and customers to mitigate downstream impacts. |
| | 2. Share lessons learned with stakeholders to improve future scoping efforts. |


***6. Recover (RC): Post-Incident Adjustments***


| Function | Details |
| --- | --- |
| **RC.RP (Incident Recovery Plan Execution)** | 1. Restore AI systems to operational status while ensuring the integrity of restored components, such as data and models. |
| | 2. Validate backups before using them for recovery to avoid reintroducing vulnerabilities. |
| **RC.CO (Incident Recovery Communication)** | 1. Inform stakeholders about recovery progress and measures taken to prevent recurrence. |
| | 2. Update scoping documents and risk assessments based on lessons learned. |



#### 1.1.3. What is missing for defenders of AI systems

The NIST CSF 2.0 provides a strong general framework but could be enhanced for AI system defenders by:

1. Incorporating AI-specific risks, such as adversarial attacks, model drift, and poisoning.
2. Addressing supply chain vulnerabilities unique to AI.
3. Providing detailed guidance for AI-focused incident response, recovery, and monitoring.
4. Integrating AI ethics, explainability, and transparency into governance practices.
5. Explicitly aligning with NIST AI RMF for a holistic approach to AI risk management.



### 1.2. NIST RMF

#### 1.2.1. Overview
 
The NIST Risk Management Framework (RMF) is a structured framework, that integrates security and privacy into the lifecycle of information systems (including AI systems). It is widely used in federal agencies and private organizations to ensure a consistent, scalable, and effective method for protecting sensitive information.

The RMF is mandatory for federal agencies under laws like FISMA (Federal Information Security Modernization Act) and is recommended for private organizations seeking robust risk management practices. It aligns closely with the NIST Cybersecurity Framework (CSF) for broader risk management.

##### 1.2.1.1. Scoping of AI system and/or cybersecurity purview

In the NIST RMF, scoping is critical to the Prepare, Categorize, and Select steps. It ensures that the boundaries of the system, its operational context, and applicable controls are well-defined to align with organizational objectives, compliance requirements, and risk management strategies.

| **RMF Step**       | **Scoping Objective**                                                                                           |
|---------------------|----------------------------------------------------------------------------------------------------------------|
| **Prepare**         | Define the scope of the system, including boundaries, stakeholders, critical assets, and risk management strategies. |
| **Categorize**      | Identify the scope of information and systems to be categorized based on their confidentiality, integrity, and availability impact. |
| **Select**          | Determine the scope of security and privacy controls required to address identified risks and tailor them to system needs. |
| **Implement**       | Apply controls to all scoped system components and document how they address the defined security and privacy boundaries. |
| **Assess**          | Validate that scoped controls operate effectively within the defined boundaries and meet security/privacy objectives. |
| **Authorize**       | Ensure the scoped system and its components are evaluated for residual risks within the defined authorization boundary. |
| **Monitor**         | Continuously monitor scoped assets and controls to detect changes, emerging threats, and ensure compliance with security objectives. |


##### 1.2.1.2. Persona addressed

| **RMF Activity**                     | **Senior Accountable Official for Risk Management** | **Chief Information Officer (CIO)** | **Authorizing Official (AO)** | **Senior Agency Official for Privacy (SAOP)** | **Senior Agency Information Security Officer (SAISO)** | **System Owner** | **Control Assessor** | **System Security Officer (SSO)** | **System Privacy Officer** | **Data Scientist/AI Engineer** | **Software Development Team** | **SRE** | **Software Architecture Team** | **Common Control Provider** | **Mission/Business Owner** |  
|--------------------------------------|----------------------------------------------------|-------------------------------------|-------------------------------|-----------------------------------------------|--------------------------------------------------------|------------------|-----------------------|-----------------------------------|---------------------------|----------------------------------|----------------------------------|-------|------------------------------|-----------------------------|-----------------------------|  
| **Prepare**                          | A                                                | R                                   | C                             | C                                             | C                                                      | I                | I                     | I                                 | I                         | C                                | I                                | I     | C                            | C                           | A                           |  
| Identify Risk Management Roles       | A                                                | R                                   | C                             | C                                             | R                                                      | I                | I                     | I                                 | I                         | I                                | I                                | I     | I                            | I                           | A                           |  
| Define Risk Management Strategy      | A                                                | C                                   | R                             | C                                             | C                                                      | I                | I                     | I                                 | I                         | I                                | C                                | I     | R                            | I                           | A                           |  
| Perform Risk Assessment              | R                                                | C                                   | A                             | C                                             | R                                                      | C                | R                     | I                                 | I                         | C                                | R                                | C     | C                            | I                           | C                           |  
| **Categorize AI Systems**            | R                                                | C                                   | A                             | C                                             | R                                                      | R                | I                     | C                                 | C                         | R                                | R                                | C     | R                            | I                           | A                           |  
| Identify Privacy/Security Impacts    | C                                                | C                                   | A                             | R                                             | C                                                      | R                | I                     | R                                 | C                         | R                                | R                                | I     | C                            | C                           | A                           |  
| **Select Controls**                  | A                                                | C                                   | R                             | C                                             | R                                                      | R                | C                     | C                                 | C                         | C                                | C                                | I     | R                            | I                           | A                           |  
| Tailor Controls to AI Systems        | A                                                | C                                   | R                             | C                                             | R                                                      | R                | C                     | R                                 | R                         | C                                | R                                | I     | R                            | I                           | A                           |  
| **Implement Controls**               | C                                                | C                                   | A                             | C                                             | C                                                      | R                | I                     | R                                 | R                         | R                                | R                                | R     | R                            | C                           | I                           |  
| Deploy Privacy & Security Features   | C                                                | C                                   | A                             | R                                             | R                                                      | R                | I                     | R                                 | R                         | R                                | R                                | R     | R                            | I                           | I                           |  
| **Assess Controls**                  | C                                                | C                                   | A                             | C                                             | C                                                      | I                | R                     | R                                 | R                         | C                                | I                                | I     | C                            | C                           | I                           |  
| Validate AI Security and Privacy     | C                                                | C                                   | A                             | C                                             | C                                                      | I                | R                     | R                                 | R                         | R                                | I                                | I     | C                            | I                           | I                           |  
| **Authorize AI System**              | C                                                | C                                   | A                             | C                                             | C                                                      | C                | C                     | C                                 | C                         | C                                | C                                | C     | C                            | I                           | A                           |  
| Risk Decision and Authorization      | C                                                | C                                   | A                             | C                                             | C                                                      | C                | C                     | C                                 | C                         | C                                | I                                | C     | C                            | I                           | A                           |  
| **Monitor AI Systems**               | C                                                | C                                   | A                             | C                                             | R                                                      | R                | I                     | R                                 | R                         | C                                | R                                | R     | R                            | I                           | A                           |  
| Continuous Monitoring Strategy       | A                                                | C                                   | R                             | C                                             | R                                                      | C                | C                     | R                                 | R                         | C                                | C                                | R     | R                            | C                           | C                           |  


##### 1.2.1.3. Guidance provided

The NIST RMF provides general risk management principles that can be tailored to address the unique risks associated with AI systems. 

#### 1.2.2. Detail on current framework

Applying the NIST Risk Management Framework (RMF) to AI systems involves tailoring the framework's steps to address the unique challenges and risks associated with AI technologies. AI systems introduce complexities such as data bias, model integrity, adversarial vulnerabilities, and explainability requirements, which must be integrated into the RMF process.

| **RMF Step**       | **Objective**                                                                                   | **AI-Specific Tasks**                                                                                                  | **Output**                                                                                 |
|---------------------|-----------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------|
| **Prepare**         | Establish readiness to manage AI-specific risks.                                              | Define AI system boundaries, identify stakeholders, develop AI-specific risk management strategy.                      | AI-specific risk strategy and system inventory.                                           |
| **Categorize**      | Determine the AI system’s security impact level.                                              | Evaluate sensitivity of data, assess impact of model failures, identify AI-specific vulnerabilities (e.g., adversarial). | Categorization documentation that includes AI-specific risks.                            |
| **Select**          | Choose controls to mitigate AI risks.                                                         | Tailor controls for privacy, bias, adversarial robustness, and explainability. Integrate supply chain risk management.  | Control baselines tailored for the AI system.                                             |
| **Implement**       | Deploy controls within the AI system’s lifecycle.                                             | Apply data governance policies, implement runtime protections, document model and data lineage.                        | Evidence of implemented controls (e.g., secure pipelines, data protection measures).      |
| **Assess**          | Validate that controls mitigate AI-specific risks effectively.                                | Test for model robustness, bias detection, performance validation, and incident response readiness.                    | Security Assessment Report (SAR) with AI-specific findings.                              |
| **Authorize**       | Approve the AI system for operation after evaluating residual risks.                          | Review ethical and regulatory compliance, evaluate residual risks with input from data scientists and legal advisors.   | Authorization decision (ATO or denial).                                                  |
| **Monitor**         | Continuously track AI system risks and update controls as needed.                             | Monitor for model drift, detect adversarial attacks, maintain data usage logs, automate monitoring processes.           | Updated risk assessments and monitoring reports.                                          |


#### 1.2.3. What is missing for defenders of AI systems

While the RMF is adaptable, it lacks AI-specific extensions that address unique risks, such as adversarial threats, explainability, bias, and dynamic system behaviors. 

Defenders need:
1. Tailored threat models for AI.
2. Explicit controls for adversarial robustness, fairness, and privacy.
3. Enhanced guidance for real-time monitoring, secure AI development, and incident response.
4. Focus on training and interdisciplinary collaboration for AI and cybersecurity teams.

## 2. AI Risk Management Framework

### 2.1. NIST AI RMF 1.0

#### 2.1.1. Overview

##### 2.1.1.1. Scoping of AI system and/or cybersecurity purview

##### 2.1.1.2. Persona addressed

##### 2.1.1.2. Guidance provided

#### 2.1.2. Detail on current framework

#### 2.1.3. What is missing for defenders of AI systems

### 2.2. NIST AI RMF 1.0 for Generative AI (GAI)

#### 2.2.1. Overview

##### 2.2.1.1. Scoping of AI system and/or cybersecurity purview

##### 2.2.1.2. Persona addressed

##### 2.2.1.3. Guidance provided

#### 2.2.2. Detail on current framework

#### 2.2.3. What is missing for defenders of AI systems

### 2.3. NIST AI Adversarial Machine Learning (AML)

#### 2.3.1. Overview

##### 2.3.1.1. Scoping of AI system and/or cybersecurity purview

##### 2.3.1.2. Persona addressed

##### 2.3.1.3. Guidance provided

#### 2.3.2. Detail on current framework

#### 2.3.3. What is missing for defenders of AI systems

## 3. References

| Framework | Referenced Material |
| --- | --- |
| NIST CSF 2.0 | [NIST CSF 2.0](https://nvlpubs.nist.gov/nistpubs/CSWP/NIST.CSWP.29.pdf) |
| NIST RMF | [NIST RMF](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-37r2.pdf) |
| NIST AI RMF 1.0 | [NIST AI RMF 1.0](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.100-1.pdf) |
| NIST AI RMF 1.0 for Generative AI (GAI) | [NIST AI RMF 1.0 for Generative AI (GAI)](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.600-1.pdf) |
| NIST AI Adversarial Machine Learning (AML) | [NIST AI Adversarial Machine Learning (AML)](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.100-2e2023.pdf) |