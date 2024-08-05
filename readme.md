## Experience in EY, August 2020 to present day

**Position**: Senior Manager, AI & Data

### Enterprise Architect for AI Strategy Development for Large Automotive and Manufacturing Equipment Company

We were tasked with developing the AI strategy for this Large Automotive and Manufacturing Equipment Company, which involved three main streams:
1. Value Stream

This stream focused on determining how AI could enhance this company's products and services and improve their business processes.

2. Governance and People and Skills Stream

This stream concentrated on the necessary governance changes to effectively integrate AI. It also examined the impact on current jobs at this company, anticipated future job roles, and identified areas where employees might need re-skilling.

3. Architecture Stream

My area of involvement. This stream was about defining the technical capabilities required across this company’s entire enterprise architecture to support AI-driven solutions. Initially, this company had a somewhat simplistic view, seeing AI as merely another box within their architecture diagram.  However, AI needs to integrate more comprehensively into products, function as standalone services or applications, and either be developed in-house or integrated as plug-ins into existing business processes. My role was to build a cohesive and enterprise-wide set of technical capabilities to enable this company to develop and deploy AI-driven solutions effectively. The vision I created, which was agreed upon with the steering group and senior management, translated into four key principles for the architecture design:

- Adaptability with Current and Future AI Developments

We aimed to define the technical capabilities based on current understanding and devlopments in AI, incorporating advancements from academia and industry. These capabilities needed to be flexible enough to adapt to future AI developments.

- Federated Deployment

The system’s capabilities would be defined, configured, and initialised centrally, with deployment and usage by individual teams, departments, or business units. Control and management would remain centralised, following a hub-and-spoke model rather than a fully decentralised federated approach.

- Robust Foundation

Adherence to the principles of the existing enterprise architecture, was crucial. The architecture needed to be comprehensive and cover all stages of development and deployment without assumptions, ensuring the capabilities were integral, sustainable parts of the enterprise architecture.

- Responsible Design

Transparency and explainability were emphasied to ensure AI products are understandable to their operators. Principles such as sustainability, fairness, and robustness, which were already part of the enterprise architecture design principles, were maintained, with transparency and explainability highlighted as essential elements for responsible AI design.

Over the next four months, I focused on assembling the necessary technical capabilities for AI integration into the company’s systems and solutions. To simplify understanding and tracking developments, we categorised our approach into two streams: Generative AI and Analytical AI (this company’s term for Predictive AI).

- Generative AI

We considered capabilities like document parsing and analysis, synthetic data generation, embeddings management, vector database indexing, prompt engineering, fine-tuning, hosting and cataloguing LLMs, enhancing transparency and explainability, human feedback loop capability, and more. These capabilities were envisioned as enterprise-wide resources, buildable and usable across the entire organization.

- Analytical AI

We outlined essential enterprise-wide capabilities in traditional AI domains, including machine learning. This involved building new models, creating and storing features in a feature store, dataset creation from mixed data sources, feature preparation, supporting exploratory data analysis, cataloguing algorithms, and tracking previous experiments. Some capabilities, such as synthetic data generation and feature stores, overlapped between Generative and Analytical AI. Transparency and explainability were emphasised for Analytical AI solutions as well.

In summary, I compiled a comprehensive list of AI capabilities, providing detailed explanations of their purpose and implementation as enterprise-wide resources. This would enable different solutions to leverage these capabilities effectively. We also accounted for other non-AI-specific services and capabilities already defined within the enterprise architecture, such as application integration, API management, data classification, data management, and DevSecOps. These components were crucial for successfully implementing AI solutions, and I outlined these foundation services within the architecture diagram developed for this company.

The next phase involved creating an investment plan and an implementation roadmap. Initially, we estimated the costs for implementing the AI-specific capabilities using a T-shirt sizing approach. We also estimated the effort needed to adapt the foundational services to support the AI-specific capabilities, engaging with various teams whithin the company responsible for these foundation services. 

For instance, we consulted with the API management team to ensure they were prepared to support AI applications. Some services were fully capable (marked as green), while others required minor adjustments. After these consultations, we developed an investment plan detailing the costs associated with deploying these AI capabilities. We then created an implementation roadmap and presented it to senior executive leadership. 

Due to our compelling and comprehensive AI strategy case, along with a detailed investment plan, the Senior Executive Leadership team agreed to invest in the implementation. Consequently, I was re-engaged by this company to help define parameters, including the necessary guardrails and guidelines, for implementing and using these technical capabilities. Additionally, I have been asked to elaborate further on the capabilities and develop a more detailed investment plan and roadmap for fully implementing the enterprise architecture aspects of the AI strategy over the next two and a half to three years.

### Generative AI RAG internal solution

I worked on a PoC designed to improve the process of crafting responses to RFPs by leveraging insights and knowledge gained from previous submissions. This project specifically aimed to support the government tenders and engagements group within EY's technology consultancy.

A Retrival Augmented Generation solution utilising semantic searching of previously created RFP answers. This AI-powered system enabled team members to input their questions and receive customised responses based on historical data, significantly accelerating the bid creation process.

Initially, I collaborated with a developer to design and implement the solution. However, I eventually assumed full responsibility for the project when the developer had to transition to a different task. At this point, the project's potential was recognised by our leadership, and the government tenders team expressed considerable interest in the results, eager to adopt the solution. We are set to initiate its internal implementation and launch soon.

In addition to my role as a software architect, I led a small development team and worked closely with the Government engagements team to identify areas for enhancement in the solution. I also managed expectations from the managing partners, crafting tailored communications to gain their support. This was critical in ensuring the ongoing development and acceptance of the solution as an internal accelerator. Moreover, we positioned it as a sales process accelerator to highlight our expertise in generative AI technology.

### Generative and Predictive AI PoC
In response to an RFP from the Revenue Office in Ireland, I developed a proof of concept (PoC) aimed at migrating their existing document management system from an on-premises solution to SharePoint in the cloud. The project presented a significant challenge due to the large volume of documents with unclear contents and ambiguous relevance, which necessitated a manual review to determine their future.

To tackle this issue, I designed a sophisticated solution that employed Generative AI to summarise and understand the contents of the documents, assessing their relevance for migration or archiving. Furthermore, I implemented a Machine Learning solution that utilised the Generative AI insights and learned from past human decisions to automatically migrate or archive documents.

The PoC I created effectively demonstrated this innovative approach to the Revenue Office and was well received, showcasing how advanced technology can streamline document management processes.

### AIB RPA

In my role as Software Development Manager, I led a small, globally distributed team of 5 people to deliver a Robotic Process Automation solution for AIB Bank, with a primary focus on customer applications for new banking products and overall customer relationship management. My responsibilities encompassed team management, coordination with the bank to ensure our solution aligned with their needs, and overseeing the implementation process.

Our team operated from various global locations, including India, Belfast, and Limerick. Through our RPA developments, we successfully streamlined AIB’s business processes. One of the most significant challenges I've encountered was navigating the complexities of the bank's operations, particularly when it came to integrating our solution with the existing IT infrastructure and the customer experience team.

Although AIB already had an RPA framework in place, it was limited to their IT department and had not been extended to include the customer experience team. We worked closely with the IT department to deploy the necessary technology, thereby enhancing the capabilities of the customer experience team and the IT RPA CoE. A major hurdle in this process was deploying the RPA solutions to production, which required addressing various external concerns and ensuring alignment with our business process requirements. A significant portion of my efforts was dedicated to managing diverse stakeholders within the bank and understanding how their requirements impacted our deliverables. One notable issue was obtaining test data for our RPA implementation. We needed access to real or pre-existing customer applications and forms to ensure our robots produced accurate outputs. However, this data was not readily available in a format conducive to thorough testing. For example, testing new card applications posed a challenge since once an application was processed, it could not be reused for further testing. Additionally, creating a comprehensive testing environment that included all necessary business systems was a complex undertaking. Despite these challenges, I collaborated closely with other departments to implement the required systems and establish a proper testing environment.

Ultimately, this project provided me with deep insights into the intricacies of the bank’s internal operations and equipped me with the skills to effectively deliver a robust RPA solution.

### HSE

I briefly collaborated with HSE to explore the automation of their report generation process for submission to external regulatory bodies, such as the Ministry of Health. The focus was on reports related to expenditure and fund allocation across different projects. My primary goal was to understand their existing processes and then streamline them to enable automatic report generation. To achieve this, I devised a solution and developed a PoC that incorporated their existing applications, particularly leveraging SharePoint and other Microsoft tools.


### RFP Responses
I have played a pivotal role in developing responses to requests for tender and proposals. One of the most notable ones was a groundbreaking project to establish a new navigational port for the Saudi Arabian government. The goal was to create a fully digital and future-ready facility as part of a larger initiative to build the city of the future.

In response to the request for proposal (RFP), I designed an event-driven architecture that effectively integrated IoT devices from boats, cranes, and various port equipment with critical operational systems, including CRM, finance, invoicing, and HR. To facilitate efficient data processing and real-time communication, I utilised advanced technologies such as Kafka, Kafka Connect, and an IoT gateway.

In addition to the architectural design, I developed a comprehensive investment plan and an implementation roadmap to guide the successful execution of the proposed solution. This included addressing budgetary considerations and mitigating uncertainties associated with the integration of new systems, as well as navigating the complexities of interfacing with various legacy systems.

Through this project, I've built on my expertise in software architecture, emphasising strategic integration of cutting-edge technologies to drive digital transformation in large-scale infrastructure initiatives.

## Experience in Truata, June 2020 to August 2022

**Position**: Engineering Manager, Web & Integration Team

At Truata, I served as the Engineering Manager for the newly established **Web & Integration team**. My key responsibilities included:

1. **Establishing a Robust Engineering Framework**:  
   I developed and implemented a comprehensive **Software Development Life Cycle (SDLC)** to ensure the delivery of high-quality, innovative software solutions. This involved:
   - Selecting the right tools to support the SDLC.
   - Creating a culture of high performance within the team.
   - Leading the hiring process to build a skilled workforce focused on software development excellence.

2. **Providing Software Architecture Expertise**:  
   I applied my architectural knowledge to select appropriate **design patterns** and components necessary for **integrating data engineering solutions**. These solutions utilized **privacy-enhancing algorithms** to process large datasets and required a strong emphasis on developing an innovative, responsive front-end, which the team also created. When I joined, the team comprised of 2 permanent employees and 2 external contractors from one of our partners.

### Key Products Developed

Truata focused on developing and offering two primary products:

- **Privacy-Enhanced Analytics Platform**:  
   Originally built for MasterCard, this adaptable platform catered to various clients, providing vital analytics and Machine Learning (ML) models while ensuring data privacy.

- **Calibrate**:  
   Our flagship product, Calibrate, consisted of a suite of tools, algorithms, and facilities designed to:
   - Process big data while identifying potential privacy risks.
   - Recommend transformation functions to mitigate these risks.
   - Apply these transformations to datasets to create **privacy-enhanced datasets**, preserving as much of the original data's value as possible.

   Notably, Calibrate included functionalities beyond identifying **Personally Identifiable Information (PII)**; it also aimed to detect whether a person's **digital fingerprint** could be inferred from various data columns across multiple datasets owned by an organisation. This capability empowered companies to assess their data for privacy concerns before utilising it for **Machine Learning models** or **Business Intelligence **systems**.

## Engineering Management Approach

I will outline my engineering management approach focused on building a productive culture, fostering an effective work environment, and implementing a robust Software Development Life Cycle (SDLC) to develop a high-performing team, all with the added challange of COVID lockdowns.

### Initial SDLC and Team Dynamics

The incumbent SDLC was centered around Scrum, with a Scrum Master responsible for ensuring the team understood and effectively applied Scrum principles. My primary role was to identify the best ways to support the team in developing the approved software product designs while ensuring their adaptability to frequently changing product requirements, which is typical for a start-up environment. I collaborated closely with the Scrum Master to secure appropriate access that would enable me to mentor the engineers on my team while granting them the autonomy to produce high-quality code and embrace the challenges inherent in their work.

### Continuous Delivery Pipeline

I also partnered with the DevOps team to implement the necessary components for a continuous delivery pipeline for our products. This included establishing a branching strategy in Git, implementing code quality assurance tools and configurations, and defining the appropriate testing strategies for unit testing, integration testing, and user acceptance testing (UAT).

### Security Practices

Collaboration with the Security team was essential to ensure that our development process adhered to secure coding practices. We engaged in appropriate security testing, including penetration testing, at critical points to address necessary security risks as outlined by the OWASP Top 10.

### Alignment and Collaboration

An integral aspect of establishing a successful SDLC and coherent culture at Truata was aligning with the Engineering Manager of the Data Engineering team and the Chief Data Scientist overseeing the Data Science team. We maintained effective communication channels and adopted similar management approaches. When the Data Engineering Manager departed, I took over managerial responsibilities for that team as well.

### Behavior-Driven Development (BDD)

The resulting SDLC was based on **Behavior-Driven Development (BDD)**, which facilitated effective collaboration with the Product Manager, as he could describe functionalities using the Given-When-Then framework. This approach allowed our engineers to comprehend the necessary functionality as well as the associated tests. I fostered a culture of quality software development by promoting comprehensive integration and user acceptance testing. Rather than having a separate testing team, engineers were responsible for either developing functional code or writing test code during sprints, ensuring they did not work on the same product feature simultaneously. This approach achieved two significant goals for high-quality software development: 
1. Most tests were automated, with manual testing being minimal and reserved for emergencies.
2. Engineers gained a deeper understanding of various application features from a user’s perspective through their engagement in testing.

### Culture of Openness and Collaboration

I encouraged a culture of open knowledge sharing, constructive criticism, and a shared understanding of architectural decisions (ADR). Given that we were navigating the height of the COVID-19 pandemic, my team held as many non-work-related gatherings as possible to foster a team spirit. I maintained an "open-door" culture, virtually, by inviting colleagues to reach out to me using Microsoft Teams whenever they needed assistance, without requiring permission or blocking my calendar, essentially simulating the experience of walking to someone’s desk.

I also empowered engineers to explore solutions independently and consider changing architectural decisions to enhance product quality. As long as they supported their proposals with sound technical reasoning, I welcomed discussions and debates, provided we remained focused on delivering the best possible product within the agreed timelines. If their suggested changes demonstrated clear benefits, I supported them in discussions with the Product Manager to revise the delivery roadmap.

### Team Development and Achievements

From June 2020 to August 2022, I have built and developed a high-performing **Web & Integrations team** capable of delivering the two primary products mentioned earlier. The team successfully added new features and collaborated with product managers and clients to meet high standards of performance, user experience, and cost efficiency. I onboarded three experienced engineers, each of whom took over leadership of their respective group of engineers focused on their areas of expertise: UI, Integrations, and runtime environments. By supporting the promotion of two of these experienced engineers to **Principal Engineer** level, I effectively established two well-connected teams: one dedicated to UI and the other to backend integration. Ultimately, I grew the Web & Integrations team to 12 engineers, successfully maintaining a team of 10 engineers even when the sales process for the two products did not meet expected levels.

### Software Architecture experience in Truata

#### Architectural Approach for Privacy-Enhanced Analytics Platform (PEAP) and Calibrate

I will outline the approach I used for designing the architecture of the two products mentioned above.

My guiding principles, patterns, and practices were derived from **Domain Driven Design** and the [Reactive Manifesto](https://www.reactivemanifesto.org) for implementing reactive systems. I focused on identifying Bounding Contexts, creating Context Maps, developing a shared Ubiquitous Language, and defining the appropriate domain Events and Entities. I then applied the principles of the Reactive Manifesto—**Responsive**, **Elastic**, **Message Driven**, and **Resilient**—to select the right patterns, modules, and components for the implementation.

- Privacy-Enhanced Analytics Platform (PEAP)

For the **Privacy-Enhanced Analytics Platform (PEAP)**, I developed an **event-driven architecture** utilising Angular for the front end. The senior engineer I hired to lead the UI team was an expert in Angular. The backend was built using microservices in Java, deployed with containers, and incorporated **RabbitMQ** as the message broker. The data engineering aspect utilised **KNIME**, a data science platform that facilitated the execution and management of Spark jobs. Although the data engineering solution was more complex than necessary at the time, it represented the "legacy" method for running Jupyter notebooks within a Spark cluster environment. 

The primary reason for proposing an event-driven integration was to abstract the data engineering platform through events, enabling future replacement with a simpler solution.

- Calibrate Product

For the **Calibrate product**, I designed a similar architecture, accommodating the long-running data processing elements essential to the solution. This design also aimed to support potential data processing clusters that clients might already have in place, including Databricks subscriptions, personal Spark Cluster environments, or other technologies like Apache Beam or Apache Flink.

"Calibrate" provides tools for identifying privacy risks within any dataset, including digital fingerprinting and transformation solutions for mitigating these risks. I crafted the architecture to integrate existing data processing algorithms for application to large datasets by multiple users, ensuring an optimal user experience for long-running jobs. This included features for job monitoring, immediate issue alerts related to the dataset, and the capability for users to cancel long-running jobs without losing important findings.

The application architecture adopted the **micro-kernel pattern**, featuring a central functionality component (kernel) that enabled the integration of diverse plugins for various algorithms, data processing solutions, and client-specific identity management components, including **Security Key Vaults**, Data Warehouses, Data Lakes, or any other storage facilities. This structure provided a flexible licensing model and allowed for easy upgrades.

I also collaborated with the DevOps engineers to deploy the application as a **SaaS product** within the **Azure Marketplace** and **IBM’s Cloud Pak for Data**.

### Security Measures and Data Access

For both applications, I implemented an internal **Certification Authority** to facilitate mutual TLS identification using digital certificates for secure communication between the majority of components, particularly when connecting to RabbitMQ.

I proposed and designed abstraction layers for the data access facility in Calibrate, allowing for seamless integration of any data source for both ingestion and output, with capabilities for data streaming input and output. The authorisation mechanism relied on signed **JWTs** and authorisation claims to facilitate integration with any client-specific Identity Management solutions, as well as to support the development of a standalone product utilising an internal **Keycloak** IdM.

## Jaguar LandRover (JLR) Jan 2019 to June 2020

**Position**: Software Development Manager

### Software Development Management experience at Jaguar Land Rover (JLR)

I joined Jaguar Land Rover as a **Software Development Manager** with the goal of growing and developing a team of 6 engineers working on multiple projects, one of which was the **Digital Payments Gateway** product known as **Digital Wallet**. In my role as a people manager, I worked closely with the engineers to align their career aspirations with the company's development plans. Through regular 1-1 meetings and ad-hoc discussions, I helped them connect their individual goals with the broader business objectives of the organisation.

I also assisted the team in finding the right balance between contributing to the newly established development center in Shannon and building strong relationships with their colleagues, fostering new friendships along the way. For some engineers looking to pivot from embedded application development to web application development, I facilitated this transition. Additionally, I guided recent graduates with limited experience in exploring various career paths to identify the best fit for them.

I collaborated with the more experienced engineers in my team to ensure that their expertise was effectively utilised within our projects and development processes. Furthermore, I promoted greater visibility for our team within the larger software engineering group by connecting them with colleagues at other development centers in the UK and the US.
#### Platform Reliability Engineering
After the Digital Wallet entered "business as usual" mode, I pivoted my focus towards establishing the **Platform Reliability Engineering (PRE)** team. In this role, I took the lead in ensuring that all development teams using the digital platform had reliable access to its services. The PRE team was dedicated to enhancing aspects such as scalability, observability, secure communication channels, consistent runtime environments, and predictable performance.

I collaborated closely with diverse stakeholders—including product managers, development teams, and business teams—to develop a comprehensive roadmap for the PRE team. This initiative not only ensured the stability and reliability of the digital platform but also equipped product development teams with the necessary support and expertise in software architecture patterns, enabling their applications to operate reliably in production.

### Software Architecture experience at Jaguar Land Rover (JLR)

My initial project at JLR involved establishing the internal digital payments gateway, known as **Digital Wallet**. This concept originated in the development center in Shannon and was initially envisioned as part of a suite of features for the entertainment unit in JLR vehicles, allowing for digital payments on the road, such as tolls, fuel, and fines. However, during development, we identified a more pressing need for a solution that would support both internal and customer-facing applications for digital payments. Consequently, we evolved the design from a Digital Wallet to a **Digital Payments Gateway**.

Recognising the potential issues with Internet connectivity in JLR vehicles, I opted for a design aligned with **Reactive Systems** principles and patterns. This architecture relied on integration components that facilitated payment submission and completion from any application, whether deployed within the JLR enterprise or directly in JLR cars. We implemented an abstraction layer to integrate with various digital payment providers, starting with **Stripe**. Importantly, we designed the system to avoid storing any credit card details within JLR's infrastructure, leveraging the payment providers' facilities and minimizing PCI DSS compliance burden.

The architecture utilised **RabbitMQ** as the message broker, incorporating the **Pub/Sub** pattern and allowing for a flexible events-based integration through the AMQP specific Binding and Routing keys. Events generated by the components were stored in JSON format, with sensitive elements encrypted as necessary. All components connected to RabbitMQ via **TLS**, and we established an internal **Certification Authority** to authorise topic subscriptions using Mutual TLS.

Each application component was packaged as a **Docker** container, with some deployed within a **Kubernetes** cluster to enable elastic scalability. I collaborated with the team to establish a Continuous Integration pipeline using **GitLab hooks**, which later evolved into a Continuous Deployment pipeline utilising containers and **Google Kubernetes Engine (GKE)**.

The Digital Wallet was ultimately deployed on the **JLR GCP private cloud**, and several proof-of-concepts began utilising the system. It became an integral part of the emerging **Digital Platform for Connected Car**.

After the Digital Wallet transitioned to "business as usual" mode, I shifted my focus to support the **Enterprise Architecture team**. Together, we designed the data and integration architecture for the newly launched Digital Platform for Connected Car. Drawing from my expertise in integration platforms, I created an architecture that supported data streaming from cars to the platform, integrating with other enterprise applications such as the Digital Wallet, CRM, and financial applications. This integration encompassed both synchronous and asynchronous paradigms.

I designed the necessary components for **REST-based API integration**, including an API gateway, management, integration with **SSO**, and the internal identity management system. Additionally, I developed a message broker integration for both Pub/Sub and command/response messaging.

I also worked on designing a **Digital Twin** approach to create and maintain a real-time view of every JLR car produced, capturing relevant information such as status, mileage, and sensor data.

Once the design was finalised, I proposed and established the **[Platform Reliability Engineering (PRE)][1]** team described above.

## University of Limerick, Sept 2018 to Dec 2018
**Position** : Enterprise Data Architect and Governance Manager

A short but very fruitful stint with University of Limerick where I was responsible for designing a data architecture aimed at ensuring the reliability of data across various University departments. I identified all data sources within the departments, including those residing in data repositories and alternative facilities. Additionally, I gathered data requirements and assessed data confidence levels within each department. This comprehensive analysis informed the creation of an enterprise data architecture architecture, along with a detailed implementation roadmap to guide the execution of the proposed design.

## Allied Irish Banks, Jan 2017 to Sept 2018
**Position** : Solution Architect followed by Software Development Manager

### Solutions Architect Experience at AIB

As a member of the architecture team for the new **Digital Business Banking** application, I designed the platform architecture to integrate the front-end application, built with **Backbase**, with core banking systems, including accounts, payments, and fraud detection. I created templates for integration services that addressed critical quality concerns, such as observability, security, reliability, and scalability. The architecture included the implementation of REST interfaces for front-end integration, connecting internal banking systems via REST, asynchronous messaging, and SDK-based calls.

In my role, I introduced **Continuous Integration** principles to enhance the release process. I collaborated closely with Scrum Masters, the Quality Assurance team, and the infrastructure teams to set up necessary artifacts and development processes. Our software development lifecycle was based on **Behavior Driven Development (BDD)**, and we utilised the **SAFe** framework to manage Agile implementation and ensure alignment with the development team for the legacy application.

Additionally, I collaborated with the Bank’s **Microservices Working Group** to define and implement the target architecture for the new Bank-wide microservices framework. This experience allowed me to contribute to a robust and scalable digital banking solution while fostering effective collaboration across teams to drive successful outcomes.

### Software Development Management Experience at Allied Irish Banks

In this role, I transitioned into my first position as a **People Manager** while also serving as the technical lead, taking on the responsibilities of **Software Development Manager** for 3 teams: the Development team, the Release team, and the Migration team, collectively comprising between 15 to 18 engineers.

As the Software Development Manager, my primary goal was to align these three teams to facilitate smoother operations for releasing new features and gradually migrating functionalities that clients used from the old application to the new one. This challenge encompassed not only technical complexities but also significant people-related challenges, requiring me to ensure that all three teams operated cohesively as a unified group.

To enhance team performance and collaboration, I conducted regular 1-1 meetings with team members, despite the fact that all but one engineer were contractors. These meetings were vital for maintaining and boosting team morale, fostering collaboration, and addressing any concerns or challenges the engineers faced throughout the development process.

## AXA Experience Sept 2014 to Jan 2017
**Position** : Technical Architect Lead

I joined Genworth as an Architect within the **Enterprise Architecture team**, with the goal of improving integration among applications in the ecosystem and enhancing data usage and understanding. Shortly after my arrival, the CIO launched the “**5-Day App**” challenge, which aimed to streamline processes and enhance the applications underlying the Policies and Claims Management systems, enabling new features or products to be delivered to customers in very short time, significantly shorter than 6 months, which what was the norm at the time.

The existing Policies and Claims platform consisted of a suite of Oracle Forms applications and PL/SQL code, with configurations managed in a complex array of Excel spreadsheets. This architecture was not conducive to rapid changes. In response to this challenge, I designed a modular solution that addressed various aspects of the business process, allowing asynchronous communication between components to facilitate variable processing speeds.

During this time, concepts such as **microservices** and **Domain Driven Design** were gaining traction, which I encountered through my subscription to the O’Reilly Learning Platform. Utilising these emerging ideas, I crafted an architecture that implemented the **“Strangler” pattern** (though I was unaware it had a name at the time). We leveraged existing functionality from the old system for policy management while developing a new set of services to provide the necessary capabilities for launching new customer products. We also implemented wrappers around the existing data structures in the legacy policy management application to process events produced by the new application and to generate events whenever new policies were added or errors occurred.

This new architecture supported the implementation of a **CI/CD pipeline**, which we managed to establish in a relatively short timeframe. After approximately four months of work with a team of three, including myself, we successfully delivered the new architecture, complete with the CI/CD pipeline, in the development environment. As evidence of our architecture’s effectiveness, we were able to integrate a new payment method based on **Stripe** into the application in under five days, achieving the goals of the 5-Day App initiative.

As a result of this achievement, I was tasked with designing a new architecture for a **Digital Platform**, which encompassed new Policies and Claims systems, incorporating lessons learned from the 5-Day App challenge. This new architecture featured an event-driven design, enabling microservices to produce and consume events related to CRUD operations on policies and claims. Our approach allowed for better integration with clients and other financial institutions that resell our insurance products, accommodating multiple consumers for the same event and supporting specific integration requirements for individual clients when necessary.

Following AXA's acquisition of Genworth, I was responsible for providing architectural design for a solution to facilitate the convergence of the two companies on the existing platform within Genworth. While I endeavored to develop the new Digital Platform and integrate the two companies using it, business pressures ultimately necessitated convergence using the legacy Policies and Claims platform, which proved to be a frustrating experience.

Throughout my role as an architect, I worked closely with the development team, not only on the 5-Day App project but also in maintaining the existing Policies and Claims applications. I provided technical mentorship to developers as they navigated the challenges associated with transitioning from a monolithic application to an events-driven, distributed, and modular architecture.

## Oracle, June 2007 to Sept 2014

Here’s the revised version of your experience at Oracle, incorporating your individual contributions and the recognition of your ability to lead the Machine Translation solution from concept to production:

---

### Experience at Oracle

I began my journey at Oracle as a **Senior Software Engineer** responsible for maintaining and improving an existing application used by translators worldwide to obtain work packages from Oracle. Translators translated English content into their respective languages and returned the texts to be loaded into the **Translation Factory**, the primary product for streamlining the translation process. This role required significant C++ development, utilising an older version of Microsoft Visual Studio 6, MFC libraries, and an internal Oracle database.

During my time on the translation tool, I implemented two major improvements to the product. The first was migrating the internal character set from a Windows-specific encoding to **UTF-8**. This migration necessitated extensive changes in memory allocation strategies, text manipulation classes, and updates to the MFC libraries. This milestone was crucial as it enabled support for new languages that were previously not accommodated by the default Windows character set.

The second significant enhancement involved upgrading the internal Oracle database, including the **OCI** driver, from version 7 to version 8. Although this change appeared minor at first glance, the OCI 8 driver introduced substantial changes, including shifts in data types—from `int16` to `int32` and from `char8` to `char32`—resulting in fundamental impacts on our application.

Parallel to my work on the translators' tool, I continued my interest in **Artificial Intelligence for Translation** and explored various options, including an internal project that utilised a rules-based machine learning solution, which ultimately failed to deliver significant improvements. My research led me to an open-source Statistical Machine Learning product called **Moses**. After evaluating its potential, I formulated a plan and received management approval to assemble a small team dedicated to leveraging our internal translation database from the Translation Factory. Our goal was to train an Oracle-specific machine translation solution using Moses.

We initiated a proof of concept (PoC) focusing on a few “easier” languages, like Italian and French, producing translation suggestions from English texts. These suggestions were assessed by internal Oracle language specialists and demonstrated a high level of accuracy, making a strong case for deploying this solution across five languages, including English to Japanese translations.

Over the course of four years, my team expanded to include more language specialists and developers, achieving productivity improvements of 10-20% for the 5 languages involved. My role was critical in taking the initial idea of using machine translation and moving it through to production, influencing business processes, managing a variety of stakeholders, from language specialists to individual translators, and finding the best technical solutions throughout the process. 

As a result of my team’s successes in improving translation productivity and reducing costs through machine learning enhancements, I was promoted to **Principal Software Engineer** after three years of working on the Machine Translation solution.

When Oracle management in the US decided to establish an internal **NLP** group, we began sharing our work with them, allowing them to utilise some of our libraries and data preparation tools. Subsequently, the management of the Worldwide Product Translation Group, to which I belonged, decided to transition the Machine Translation solution to "Business as Usual" mode, awaiting the NLP group’s development of a new solution. At that point, I pivoted to integrating the Machine Translation system with the Translation Factory via REST-based APIs, focusing on designing and implementing services to automate the translation process.

## Work Experience Original Solutions, Feb 2004 to June 2007

In Original Solution my role was as Senior Applications Consultant.
My most important engagement was to define the architecture and lead the software development efforts for the Web Application front-end to the internally-built, Oracle Forms and PL/SQL based solution called Unified Gateway, which empowered other telecom operators in the country to benefit from selling telecommunication services  as a result of the opening up of the telecommunication network, decentralisation of these services, managed by the previously state-owned Eir(Eircom at the time). Part of the process I had also defined processes, methodologies and tools for the design, development and deployment phases of the project.
Another project that I’ve worked on while in Original Solutions was as J2EE technical consultant for Mainframe Integration. I had designed an enterprise service using EJBs to provide access to a legacy system built on an IBM mainframe using NEON Systems Shadow technology.
Apart from these projects I had also been involved in supporting as software architect various other consultancy engagements with other customers.

## Work experience in Orygen, April 2001 to May 2003

Orygen was the Irish subsidiary of a large telecommunications US company called Level 3. When the Dot Com boom finished the US company decided to withdraw from Ireland, and some of the people in Orygen formed Original Solutions.
My role in Orygen was as Senior Software Architect.
The last engagement I have worked on in Orygen, before it closed down, was a Customer Relationship Management Portal application for an important Health Insurance British company operating in Ireland (Bupa). I was the main software architected and I had lead the implementation team for  improvements to an existing, in-house built, CRM system.
Before that project I had been the Software Architect and Lead Developer for Corporate Banking Online application for Bank of Ireland. I was responsible with designing and implementing new functionality or improvements for existing Java application and the middleware integration layer and mentoring a small team of Java developers, ex mainframe developers, who wanted to continue their careers in Internet technologies.

## Work experience between May 2003 until Feb 2004.

Once Orygen closed down I have managed to work on a short, 3 months contract with Lionbridge and then joined Clare County Council as Analyst programmer. Here I had designed and developed an Extranet to Sharepoint integration tool using C# and ASP.NET. This application was used for automatic files publishing from specified locations on the Intranet, based on Sharepoint, to a protected location on the Extranet Web server. 

Another solution I have built in Clare County Council was a Resource Booking application using C#, ASP.NET and MS SQL server used for managing the allocation of the large county council meeting room for improved occupancy and usage.

## Before 2001

For the period of 1996 until 2001 I had worked in a few software development and Internet service providers in Romania. In the later part of this period, between 1998 and 2001 I had been working in 3 companies at the same time.

My main position was that of Senior Software Engineer in Multinet where I had architected and implemented web and desktop applications for a multitude of domains (tourism, communications, banking) using OOP, XP, Java, J2EE, Pascal, C++

I had also been Technical Director in a new start-up that I had been a founder of, along-side other people, which provided Internet services in the local town. I had put together the technical infrastructure to resale the Internet service to businesses and individuals in our town.

I had also set up a company with my wife to build web applications, called Lynet, which operated between May 2000 until April 2001. In this company I had been the Java and J2EE Software architect and development team Lead for a multitude of web applications using J2EE 1.2, MySQL server, JavaScript, Apache Struts. I had also mentored a small team of developers in emerging technologies like Java and J2EE.

## Spare time projects

In my spare time, I am continuing to enhance my knowledge in software engineering both the architecting side as well as team management.

In the software architecture I have always been interested in modular and distributed systems and best way to implement them to address the challenges of performance, data consistency, scalability and user experience. I have been a long time subscriber of the O’Reilly learning platform, and in Autumn 2023 I had decided to join a few other developers and set up a team to compete in the **Architecture Katas** challange. We had managed to bring our solution to the semi-final, which was quite a success given that the team members haven’t know each other before this and had quite different expertise and levels of experience. The solution we’ve proposed can be viewed at https://github.com/WildSight-Wizards/wildlifewatcher . My contribution there was to build the software architecture of integrating the cameras distributed across the globe in a seamless way, I had borrowed from my experience in Jaguar LandRover where I’ve designed the Digital Twin solution.

I also like exploring the challenges posed by explaining how AI systems operate and how can they be safely integrated with humans, via innovative software architectures, to enhance the software solutions I develop. I have recently graduated a Masters in Artificial Intelligence, which gave me the necessary theoretical foundation to better understand how AI can be built, how ML works and how the inferences can be integrated. Continuing from there I want to understand how we can integrate feedback loops that allow application users to get answers to questions about how the application that employs an AI component has come up to the specific decisions it made. It is a complex field of study involving Explainable AI as well as understanding how deep learning algorithms model the patterns that form the foundation of the generated predictions.


[1]: #platform-reliability-engineering
