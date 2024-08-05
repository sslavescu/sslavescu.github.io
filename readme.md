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

University of Limerick, Sept 2018 to Dec 2018
A short but very fruitful stint with University of Limerick where I was charged with designing a data architecture and the implementation roadmap to ensure the reliability of data across the University departments. Part of this process I have identified all the sources of data within the departments in the University residing in data repositories or other alternative facilities. After that collated the data requirements and data confidence levels in all the departments in the University. All this information was then used to create an enterprise data architecture design and implementation roadmap.
Allied Irish Banks, Jan 2017 to Sept 2018
Software Architecture experience
I have been part of the architecture team for the new Digital Business Banking application, which was a new implementation of an existing application for corporate banking. My role was to design the architecture of the platform to integrate the front-end application built using Backbase, with the core banking systems (accounts, payments, fraud detection, etc.) This platform included a template for all integration services, which had taken care of cross-cutting, quality concerns, such as observability, security, reliability, scalability. The services offered a ReST interface for the front-end and connected with the internal banking systems in multiple ways, via ReST, asynchronous messaging and direct SDK-based calls. I had also worked very closely with the software engineers to translate the architecture into quality code.
An important aspect of my role there was to introduce the principles of Continuous Integration with the goal of improving the release process and to achieve Continuous Delivery. Part of this challenge I had worked with the Scrum masters, the internal Quality Assurance team and the infrastructure team to set up the necessary artefacts, development process and architectural designs. The result was that we had managed to achieve Continuous Integration, including integration and user acceptance tests, but we failed to overcome the issues posed by the shared database and the internal infrastructure provisioning processes, to achieve the Continuous Delivery goal.
Software Development Management experience
This was the first time when I ventured into the role of People Manager along-side the technical lead role by taking on the position of Software Development Manager for the development team, release team and the migration team, 15-18 engineers.
My role as development manager was to align these 3 teams for a smoother operation of releasing new features and partially transferring features that clients used from the old application to the new one. Apart from the technical challenges that this problem posed I had to deal with the people challenges and to make sure the 3 teams operated as one.
I had regular 1-1s even though all but 1 engineers in the team were contractors with the purpose of maintaining and increasing the teams’ performance and collaboration
AXA Experience Sept 2014 to Jan 2017
I was brought in as Architect part of the Enterprise Architecture team with the scope of improving the integration between the applications in the ecosystem and for a better understand and use of data. Shortly after I have started the CIO lunched this challenge “The 5-day App” with the scope of improving the processes and the applications underlying the policy and claims management systems so that a new feature or product will be available to customers in 5 days, or less. The existing policies and claims platform was a suite of Oracle Forms applications and PL/SQL code, for which the configuration was maintained in a very complicated suite of Excel spreadsheets. Obviously, such an architecture wouldn’t be conducive to quick changes. My answer to the challenge was to design a modular solution which will address different part of the business process and which will communicate with each other asynchronously to allow for variable processing speed. At the time the ideas of microservices and Domain Driven Design were emerging, and I had come across them through the O’Reilly Learning Platform (at the time operating as Safari Books Online), for which I’m a subscriber from its inception. Utilising these new ideas of decomposing business process and implementing modular and distributed applications I had designed an architecture that implemented the “Strangler” pattern (I didn’t know it had a name at the time). We were utilising functionality already implemented in the old system, for policy management, but we have created a new set of services that were providing the necessary functionality to offer a new service to customers. We were collecting the data associated with this new product through the new application and we have implemented a few wrappers around the existing data structures within the existing policy management application, that were able to process events produced by the new application and to produce events when the new policies were added to the existing system or whenever any errors occurred.
The new architecture lent itself to implementing a CI/CD pipeline, which we have managed to put in place in quite a short time. In the end, after about 4 months of work, with a team of 3 people, including me, we have managed to deliver this new architecture, with the appropriate CI/CD pipeline, working in the Dev environment and, as proof of our architecture completing the 5-day app, we were able to add a new payment method based on Stripe, to the application in less than 5 days.
As a result of this achievement I was tasked with designing a new architecture for a new Digital Platform which included new Policies and Claims systems using the lessons learnt during the implementation of the 5-day App challenge. This architecture was an event-driven design, relying on microservices to produce and consume events to do with CRUD operations on policies or claims. We were also able to use the new Digital Platform design to better integrate our business with our clients, other financial institutions resellers of our insurance products, as we could accommodate multiple consumers to same event, for product updates or other such changes, and we could also accommodate specific integration requirement for each client, if necessary.
When the acquisition by AXA occurred, I was tasked with providing architectural design to the solution that will ensure the convergence of the 2 companies on the existing platform within Genworth. I was trying at the same time to develop the new Digital Platform and integrate the 2 companies via this new solution but the business pressures were too strong to allow for this, hence we had to converge using the old Policies and Claims platform, which was a very frustrating process.
As part of my role as an architect I was working very closely with the development team, not only in the 5-day App but to maintain the existing Policies and Claims applications. I had provided technical mentorship to developers in that team as they were navigating the challenges posed by the paradigm shift from working on a monolithic application to an events-based distributed and modular architecture.
Work experience in Oracle, June 2007 to Sept 2014
I had started as Senior Engineer maintaining and improving an existing application that translators around the world were using to get packages of work from Oracle, to add translations of English content into their language of expertise and then return the texts so that they can be loaded into the internal Translation Factory which was the main product to streamline the product translation process. This effort required a lot of C++ development, using an old version of Microsoft Visual Studio 6, MFC libraries and other such tools especially an internal Oracle database. There were two major improvements that I’ve added to the product. One was to migrate the internal character set from Windows specific one to UTF8, which involved a lot of changes in memory allocation approaches, classes for manipulating text, MFC libraries version, etc. This was recognised a very important milestone in the life of the product as it was the main enabler to accommodate new languages which were not covered by the default Windows character set.
The second major improvement was migrating the internal Oracle database, including the OCI driver used, from version 7 to version 8. On the face of it the change was quite small but the OCI 8 driver had a significant amount of changes versus the OCI 7 driver including the type of variables used from int 16 rather than int 8 to char 32 rather than char 8 and other such changes of fundamental impact.
At the same time with working on the Translators tool I had an interest in Artificial Intelligence for Translation and looked at a few options out there including an internal project that used a Rules Based Machine Learning solution, which didn’t produce important improvements. In my research I came across this Statistical Machine Learning open-source product called Moses. After evaluating its potential I had put together a plan and got management approval to start a small team to look into using the internal database of translations from Translation Factory to train an Oracle specific machine translation solution using this product. We had initially started with a small PoC that used a few “easy” languages like Italian and French. We took English texts and produced suggestions, which were assessed by the internal Oracle language specialists for those languages. These translations had a high level of accuracy that helped us make a case for building this solution in production for 5 languages, amongst which we’ve tackled the English to Japanese language translations too. Over the next 4 years the team that I formed got expanded with more language specialists and developers and we achieved productivity improvements between 10-20% for the 5 languages. My work was to understand the technical challenges that the open source solution was struggling with in translating for the 5 languages chosen, and design solutions to make the translations’ quality better. These solutions involved data preparation tools to operate on what was quite large text corpus, some changes to the statistical algorithms used for mapping n-grams between different languages, and solutions in productionising the Machine Translation within the existing process, especially for adding machine generated suggestions to the work packages for translators as well as monitoring the quality of our suggestions over time, comparing them with the result produced by humans and improving our confidence level into the quality of our suggestions.
When Oracle management in US decided to build an internal NLP group we started sharing the work we’ve done with them and they had used some of our libraires and data preparation products. Not long after, the decision by the management of the Worldwide Product Translation Group, which I was part of, was to put the Machine Translation solution in Business as Usual mode and wait for the NLP group in US to produce a new solution. At that point I have pivoted to working on integrating the Machine Translation system with the Translation Factory via ReST based APIs, so I got involved in designing and implementing these services to automate the Translation Process.
Work Experience Original Solutions, Feb 2004 to June 2007
In Original Solution my role was as Senior Applications Consultant.
My most important engagement was to define the architecture and lead the software development efforts for the Web Application front-end to the internally-built, Oracle Forms and PL/SQL based solution called Unified Gateway, which empowered other telecom operators in the country to benefit from selling telecommunication services  as a result of the opening up of the telecommunication network, decentralisation of these services, managed by the previously state-owned Eir(Eircom at the time). Part of the process I had also defined processes, methodologies and tools for the design, development and deployment phases of the project.
Another project that I’ve worked on while in Original Solutions was as J2EE technical consultant for Mainframe Integration. I had designed an enterprise service using EJBs to provide access to a legacy system built on an IBM mainframe using NEON Systems Shadow technology.
Apart from these projects I had also been involved in supporting as software architect various other consultancy engagements with other customers.
Work experience in Orygen, April 2001 to May 2003
Orygen was the Irish subsidiary of a large telecommunications US company called Level 3. When the Dot Com boom finished the US company decided to withdraw from Ireland, and some of the people in Orygen formed Original Solutions.
My role in Orygen was as Senior Software Architect.
The last engagement I have worked on in Orygen, before it closed down, was a Customer Relationship Management Portal application for an important Health Insurance British company operating in Ireland (Bupa). I was the main software architected and I had lead the implementation team for  improvements to an existing, in-house built, CRM system.
Before that project I had been the Software Architect and Lead Developer for Corporate Banking Online application for Bank of Ireland. I was responsible with designing and implementing new functionality or improvements for existing Java application and the middleware integration layer and mentoring a small team of Java developers, ex mainframe developers, who wanted to continue their careers in Internet technologies.
Work experience between May 2003 until Feb 2004.
Once Orygen closed down I have managed to work on a short, 3 months contract with Lionbridge and then joined Clare County Council as Analyst programmer. Here I had designed and developed an Extranet to Sharepoint integration tool using C# and ASP.NET. This application was used for automatic files publishing from specified locations on the Intranet, based on Sharepoint, to a protected location on the Extranet Web server. 
Another solution I have built in Clare County Council was a Resource Booking application using C#, ASP.NET and MS SQL server used for managing the allocation of the large county council meeting room for improved occupancy and usage.
For the period of 1996 until 2001 I had worked in a few software development and Internet service providers in Romania. In the later part of this period, between 1998 and 2001 I had been working in 3 companies at the same time.
My main position was that of Senior Software Engineer in Multinet where I had architected and implemented web and desktop applications for a multitude of domains (tourism, communications, banking) using OOP, XP, Java, J2EE, Pascal, C++
I had also been Technical Director in a new start-up that I had been a founder of, along-side other people, which provided Internet services in the local town. I had put together the technical infrastructure to resale the Internet service to businesses and individuals in our town.
I had also set up a company with my wife to build web applications, called Lynet, which operated between May 2000 until April 2001. In this company I had been the Java and J2EE Software architect and development team Lead for a multitude of web applications using J2EE 1.2, MySQL server, JavaScript, Apache Struts. I had also mentored a small team of developers in emerging technologies like Java and J2EE.
Spare time projects
In my spare time, I am continuing to enhance my knowledge in software engineering both the architecting side as well as team management.
In the software architecture I have always been interested in modular and distributed systems and best way to implement them to address the challenges of performance, data consistency, scalability and user experience. I have been a long time subscriber of the O’Reilly learning platform and in Autumn 2023 I had decided to join a few other developers and set up a team to compete. We had managed to bring our solution to the semi-final, which was quite a success given that the team members haven’t know each other before this and had quite different expertise and levels of experience. The solution we’ve proposed can be viewed at https://github.com/WildSight-Wizards/wildlifewatcher . My contribution there was to build the software architecture of integrating the cameras distributed across the globe in a seamless way, I had borrowed from my experience in Jaguar LandRover where I’ve designed the Digital Twin solution.
I also like exploring the challenges posed by explaining how AI systems operate and how can they be safely integrated with humans, via innovative software architectures, to enhance the software solutions I develop. I have recently graduated a Masters in Artificial Intelligence, which gave me the necessary theoretical foundation to better understand how AI can be built, how ML works and how the inferences can be integrated. Continuing from there I want to understand how we can integrate feedback loops that allow application users to get answers to questions about how the application that employs an AI component has come up to the specific decisions it made. It is a complex field of study involving Explainable AI as well as understanding how deep learning algorithms model the patterns that form the foundation of the generated predictions.


[1]: #platform-reliability-Engineering
