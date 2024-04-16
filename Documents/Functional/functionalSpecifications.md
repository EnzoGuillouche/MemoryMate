# MemoryMate
<img src="./Img/MemoryMate.png" width="100">

# Functional specifications

This project has been started as my moonshot project for ALGOSUP.

The goal of the project is to create an Artificial Intelligence linked with a database that supports individuals with Alzheimer's in their daily lives. The AI could understand voice orders.

<details>
<summary>Table of Contents</summary>

- [MemoryMate](#memorymate)
- [Functional specifications](#functional-specifications)
  - [Stakeholders](#stakeholders)
    - [Project member](#project-member)
    - [Other stakeholders](#other-stakeholders)
  - [Project scope](#project-scope)
  - [Deliverables and milestones](#deliverables-and-milestones)
  - [Functional requirements](#functional-requirements)
    - [Product](#product)
    - [Voice Recognition](#voice-recognition)
    - [Personal Information Database](#personal-information-database)
    - [Memory Aid Functionality](#memory-aid-functionality)
    - [Voice Response](#voice-response)
    - [Learning and Adaptation](#learning-and-adaptation)
    - [Emergency Assistance](#emergency-assistance)
    - [Accessibility Features](#accessibility-features)
    - [Multi-language Support](#multi-language-support)
    - [Security and Authentication](#security-and-authentication)
    - [Scalability and Performance](#scalability-and-performance)
    - [User Feedback and Reporting](#user-feedback-and-reporting)
  - [Personas and Use cases](#personas-and-use-cases)
    - [Persona 1 - Daniella Brabushka](#persona-1---daniella-brabushka)
      - [Goals](#goals)
      - [Challenges](#challenges)
    - [Persona 2 - Josh Kepper](#persona-2---josh-kepper)
        - [Goals](#goals-1)
        - [Challenges](#challenges-1)
    - [Persona 3 - Jessica Yota](#persona-3---jessica-yota)
      - [Goals](#goals-2)
      - [Challenges](#challenges-2)
    - [Use cases](#use-cases)
  - [Acceptance criteria](#acceptance-criteria)
  - [Non-functional requirements](#non-functional-requirements)
    - [Product](#product-1)
    - [Voice Recognition](#voice-recognition-1)
    - [Personal Information Database](#personal-information-database-1)
    - [Memory Aid Functionality](#memory-aid-functionality-1)
    - [Voice Response](#voice-response-1)
    - [Learning and Adaptation](#learning-and-adaptation-1)
    - [Emergency Assistance](#emergency-assistance-1)
    - [Accessibility Features](#accessibility-features-1)
    - [Multi-language Support](#multi-language-support-1)
    - [Security and Authentication](#security-and-authentication-1)
    - [Scalability and Performance](#scalability-and-performance-1)
    - [User Feedback and Reporting](#user-feedback-and-reporting-1)
  - [Risks and assumptions](#risks-and-assumptions)
  - [Future improvements](#future-improvements)
  - [Glossary](#glossary)
</summary></details>

## Stakeholders

### Project member

| Full name       | Occupation               | Links                                                             |
| --------------- | ------------------------ | ----------------------------------------------------------------- |
| Enzo Guillouche | Project Multitasker     | [LinkedIn](https://www.linkedin.com/in/enzoguillouche/) |

### Other stakeholders

| Name           | Occupation                  | Links                          |
| -------------- | --------------------------- | ------------------------------ |
| Franck JEANNIN | ALGOSUP's director | [Website](https://algosup.com) |

## Project scope

We have multiple objectives for this project:

- Creation of an AI system and a [database](#glossary).
- Link between both the AI and the database.
- Implementation of a [NLP](#glossary) to process voices.
- Security of the database and personal information.

## Deliverables and milestones

- [Functional Specifications](../Functional/functionalSpecifications.md)
- [Technical Specifications](../Technical/technicalSpecifications.md)
- [The Architecture Diagram](../Technical/Img/architectureDiagram.png)
- [The Test Plan](../Test/testPlan.md)
- The Product
- Unit Tests
- [All the Monthly Reports](../Management/MonthlyReports/monthlyReportCumulative.md)

## Functional requirements

### Product

The Product deals with:

- An personal AI that processes voice orders and answers them as voice.
- A database linked with the AI, containing and supplying personal information.

It has to contain all the requirements below:

### Voice Recognition

- The system should accurately recognize the voices of registered users.
- It should be able to distinguish between different users' voices.
- The recognition should work even in noisy environments.

### Personal Information Database

- The system should have a secure database to store personal information of users.
- It should allow authorized personnel to update and manage the database.
- Compliance with data privacy regulations such as [GDPR or HIPAA](#glossary) should be ensured.

### Memory Aid Functionality

- Memory prompts should be tailored to individual users based on their personal information.
- The system should remind users of important events, appointments, and tasks.
- It should assist users in recalling names, faces, and other relevant information.

### Voice Response

- The system should respond to user queries and prompts using natural language processing.
- Responses should be clear, concise, and personalized based on the user's profile.

### Learning and Adaptation

- MemoryMate should continuously learn from user interactions and adapt its responses accordingly.
- It should improve its accuracy in voice recognition and personalization over time.

### Emergency Assistance

- The system should have a feature to alert caregivers or emergency contacts in case of emergencies or when the user requires immediate assistance.

### Accessibility Features

- MemoryMate should have accessibility features such as adjustable font sizes, voice commands, and compatibility with screen readers for visually impaired users.

### Multi-language Support

- The system should support multiple languages to cater to users from diverse linguistic backgrounds.

### Security and Authentication

- Robust authentication mechanisms should be in place to ensure that only authorized users can access personal information stored in the database.
- Measures like encryption should be implemented to protect sensitive data.

### Scalability and Performance

- Response times for voice recognition and query processing should be kept within acceptable limits.

### User Feedback and Reporting

- MemoryMate should allow users to provide feedback on the system's performance and suggest improvements.
- It should generate reports for caregivers or healthcare professionals to track the user's interactions and usage patterns.

## Personas and Use cases

### Persona 1 - Daniella Brabushka

| Daniella Brabushka                                                                      | 69 years old                                                                                                                                                                                                                                                                                     |
| --------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| <img alt="Daniella Picture" src="./Img/daniellaBrabushka.png" style="max-width: 200px;"> | **Description:**<br>Daniella is a woman suffering from Alzheimer's and diabetes. She's quite autonomous though she's having a hard time remembering important things such as appointments and insuline injections.<br><br>**Frequence of use:** <br>- Often |

#### Goals

- Daniella wants an AI that can remind her of important appointments, tasks, and events throughout the day.
- She wants to remember to take her medication on time and in the correct doses.
- She wants something offering companionship and reassurance during moments of confusion or distress.
- She wants a tool being able to call for help in case of emergencies, such as falls or medical issues.

#### Challenges

- Daniella could have a hard time dealing with the fact that she may forget how to interact with the AI or forget the purpose of certain features over time.
- The AI needs to adapt to Daniella's changing needs and abilities as her condition progresses.
- Communication and coordination between the AI and Daniella's caregivers should be regulated and calibrated, to ensure consistent support.
- She will have to create a sense of trust and familiarity between her and the AI to encourage her to rely on it for assistance.

### Persona 2 - Josh Kepper

| Josh Kepper                                                                      | 32 years old                                                                                                                                                                                                                                                                                     |
| --------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| <img alt="Josh Picture" src="./Img/joshKepper.png" style="max-width: 200px;"> | **Description:**<br>Josh is a caring son facing the challenges of caring for his father, who is suffering from Alzheimer's disease. Despite his demanding job, Josh prioritizes his family above all else.<br><br>**Frequence of use:** <br>- Often |

##### Goals

- Josh aims to provide the best possible care for his father while allowing him to maintain a sense of independence and dignity at home.
- He wants a tool that can assist in monitoring his father's well-being and ensuring his safety, even if he's not physically present.
- He desires a solution that can adapt to his father's preferences, habits, and changing needs over time.

##### Challenges

- Josh may face a learning curve in setting up and utilizing the AI system, especially if it involves complex configurations or interfaces.
- He will need to trust that the AI can provide the right support at the right time.
- He will need a solution that seamlessly fits into his father's daily life without causing disruption.

<hr>

### Persona 3 - Jessica Yota

| Jessica Yota                                                                      | 27 years old                                                                                                                                                                                                                                                                                     |
| --------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| <img alt="Josh Picture" src="./Img/jessicaYota.png" style="max-width: 200px;"> | **Description:**<br>Jessica is a care assistant helping her patients at home, who is suffering from Alzheimer's disease. She's dedicated to her job, regardless how many patients she has.<br><br>**Frequence of use:** <br>- Sometimes |

#### Goals

- Jessica wants the best for her patients. She will need a tool that would help her look after many patients.
- She would want to monitor and help specific patients 24/7, due to their specificities.

#### Challenges

- Jessica wonders if she needs to be available at any time if something goes wrong.
- She's nervous not knowing whether the AI will be the same for her and her patients or not, in terms of functionalities and accessibility.

### Use cases

<!-- TO-DO -->

## Acceptance criteria

<!-- TO-DO -->

## Non-functional requirements

### Product



### Voice Recognition



### Personal Information Database



### Memory Aid Functionality



### Voice Response



### Learning and Adaptation



### Emergency Assistance



### Accessibility Features



### Multi-language Support



### Security and Authentication



### Scalability and Performance

### User Feedback and Reporting

## Risks and assumptions

<!-- TO-DO -->

## Future improvements

<!-- TO-DO -->

## Glossary

**Database** \
A database is an organized collection of data or a type of data store based on the use of a DataBase Management System (DBMS). Small databases can be stored on a file system, while large databases are hosted on computer clusters or cloud storage.
[Wikipedia](https://en.wikipedia.org/wiki/Database)

**Natural Language Processing (NLP)** \
NLP is primarily concerned with giving computers the ability to support and manipulate human language. It involves processing natural language datasets, such as text corpora or speech corpora, using either rule-based or probabilistic machine learning approaches.
[Wikipedia](https://en.wikipedia.org/wiki/Natural_language_processing)

**GDPR (General Data Protection Regulation)** \
GDPR is a regulation in EU law on data protection and privacy concerning all individuals within the European Union (EU) and the European Economic Area (EEA). It also addresses the export of personal data outside these areas. It aims to give control to individuals over their personal data and to simplify the regulatory environment for international business by unifying the regulation within the EU.
[Wikipedia](https://en.wikipedia.org/wiki/General_Data_Protection_Regulation)

**HIPAA (Health Insurance Portability and Accountability Act)** \
HIPAA is a United States legislation that provides data privacy and security provisions for safeguarding medical information. It was enacted to protect patient confidentiality and secure health information. HIPAA applies to healthcare providers, health plans, and healthcare clearinghouses, as well as their business associates who handle Protected Health Information (PHI).
[Wikipedia](https://en.wikipedia.org/wiki/Health_Insurance_Portability_and_Accountability_Act)
