# Object-Oriented-Analysis-Design-Review-M2

## Predictive Approaches to the SDLC

The traditional way with a similar core processes called phases:
- **Initiation**:
  - In predictive approaches, this combones identifies the problem and secures approval to develop
- **Planning**
- **Analysis**
- **Design**
- **Implementation**
- **Deployment** 
- **Support**
  - Upgrade and maintain the system after deployment

## Consolidated Sales and Marketing System (CSMS)
- **Sales Subsystem**
  - Integrates online, phone, retail stores
- **Order Fulfillment Subsystem**
  - Track shipments, rate products, services
- **Customer Account Subsystem**
  - Shopping history, linkups, rewards
- **Marketing Subsystem**
  - Promotions, partner relationships, reporting

## Systems Analysis Activities

To discover and understand the details:

**Gather details**
- Interviews
- questionnaires
- documents
- observing current processes
- researching vendors
- comments and suggestion
**Define requirements**
- Model functional requirements
- Model non-functional requirements
**Priortizze retuirements**
- Essentials
- Importants
- Nice to haves
**Develop UI dialogs**
**Evaluate requirements with users**

## Requirements

A physical, functional, condition or capability needed by a user to solve a problem

Business analysts, Systems Analysts, and subject experts are responsible for requirement gathering

**Business requirements**
- High-level objectives of the organization or customer
- Can be recorded in Business requirements Documents (BRD)
  - A company needs a new sales system
**Functional Requirements**
- Activities a system must be able perform, shown as use cases
  - A financial system must allow deposits
  - A financial system must allow withdraws
**Non-functional Requirements**
- Other system characteristics, constraints and performance goals
  - A financial system may be written in C# programming language
  - A financial system may provide meaningful error messages
  - Usability
  - Portability
  - Security
  - Efficiency
  - Scalability
**System Requirements**
- Functional requirements + Non-functional requirements
- Provides a clear understanding of the problem
- Can be recorded in system requirements specification (SRS)
**User requirement**
- A subset of functional requirements

### FURPS+

- **Functional requirements**: What a system must do
- **Usability requirements**: What makes a system easier to use
- **Reliability requirements**: What makes a system robust
- **Performance requirements**: What makes a system fast
- **Security requirements**: What makes a system secure
- **\+ Other categories**

## Models

- A representation of an aspect of real world

**Models of system components**
- Use case diagram
- Domain model class diagram
- Design class diagram
- Sequence diagram
- Package diagram
- Screen design template
- Dialog design storyboard
- Entity-relationship diagram (ERD)
- Database schema
**Models used to manage the development process**
- Gantt chart
- Organizational hierarchy chart
- Financial analysis models—NPV, payback period
- System development life-cycle model
- Stakeholders list
- Iteration plan
**Reasons for Modeling**
- Learning from the modeling process
- Reducing complexity by abstraction
- Remembering all the details

**Use case**
- Shows how a user uses a system to accomplish a goal
**Workflow Diagram**
- Sequence of processing steps that completes the system workflow
**Activity Diagram**
- Describes user (or system) activities, the person who does each activity, and the sequential flow of activities

### Activity diagram symbols

**Starting activity**: Black filled circle ●
**Transition**: Arrows with text annotations ↓
**Activity**: Boxes with rounded corner □
**Ending activity**: Circled black dot ⊙
**Decision/if activity**: Diamonds ◇
**Sync line**: The arrow split or merge with a thick line ——

## Tools

Software support that helps to create models or other components required in the project:
- Project management application
- Drawing/graphics application
- Word processor/text editor
- Visual modeling tool
- Integrated development environment (IDE)
- Database management application
- Reverse-engineering tool
- Code generator

## Techniques

A collection of guidelines that specify a method for how to carry out a development activity or task
- Strategic planning techniques
- Project management techniques
- User-interviewing techniques
- Data-modeling techniques
- Relational database design techniques
- Structured programming techniques
- Software-testing techniques
- Process modeling techniques
- Domain modeling techniques
- Use case modeling techniques
- Object-oriented programming techniques
- Architectural design techniques
- User-interface design techniques

### technology architecture

A set of computing hardware, network hardware and topology, and system software employed by an organization

### application architecture

The set of information systems (the software applications) the organization needs to support its strategic plan

### Incremental Development

Build one part or module of the system at a time, each part or module follows their own SDLC

## Stakeholder

An individual who is materially affected by the outcome of the system
**Internal Stakeholders**
- Stakeholders within the organization
**External Stakeholders**
- Stakeholders outside the organization
**Operational Stakeholders**
- Stakeholders who regularly interact with the system
**Executive Stakeholders**
- Stakeholders who don’t directly interact, but use the information or have financial interest
**Customers**
- Internal & external people that directly or indirectly do business with the project sponsors

### Determine who is a stakeholder

- The people who suffer from the problem
- Those investing in the business or system
- People determining the success of the solution
- Who are the people making decisions?
- Who will get something from the business or system?

## Quiz

### Models

Systems analysis involves the creation of logical models.​
- True

The reason an analyst uses many different models is that each relates to a different aspect of the system.​
- True

A key reason that modeling is important in system development is the complexity of describing information systems.​
- True

Diagrams and schematic representations of some aspect of a system are examples of a ______ model.​
graphical

A representation of some aspect of the system being built is a _______.​
- Model

A series of formulas that describe technical aspects of a system is a(n).:
- Mathematical model

_______ is an important part of the follow-up after an interview.​
- ​Building models

The term "I'll know it when I see it" applies to one valid way to get requirements definition.​
- True

Asking about error conditions usually is done in later interviews after the analyst understands and documents the basic processing requirements.​
- False

-----

### FURPS+ Requirements

_______ requirements are most often documented in graphical and textual models.
- Functional

Which of the following describes what the system is required to do?​
​- Functional requirements

_______ requirements are based on the procedures and rules that the organization uses to run its business.​
- Functional

_______ requirements are characteristics of the system other than the business procedures it must support.​
- Nonfunctional

The S in the FURPS acronym stands for _______.​
- Security requirements

The P in the FURPS acronym stands for _______.​
- Performance requirements

Every successful interview requires ____.​
- Preparation

The term "I'll know it when I see it" refers to what method of requirements definition.​
- Collecting active user comments

One important reason for prioritizing requirements is to _______.​
- Avoid scope creep

The "+" in FURPS+ includes which of the following types of requirements? (choose two)​
- Supportability requirements
- ​Design constraints

FURPS and FURPS+ are synonymous.​
- False, + represents other requirements such as supportability, design constraints

-----

### Stakeholder

"Identify the stakeholder" happens in which of the 6 core processes?
- 2, Planning

​The term stakeholders refers to all the people who:
- Have an interest in the successful implementation of the system

Before gathering detailed information, and analyst identifies every type of stakeholder.​
- True

In the RMO CSMS project, customers are not considered stakeholders because it is not feasible to interview them or use them in the project activities.​
- False, the customers are not directly impacted with project success / fail

Persons who regularly interact with the system as part of their jobs are called _______.​
- ​operational stakeholders

What type of stakeholders are those that do not use the system on day to day tasks, but use information, such as reports, from the system.​
- Executive stakeholders

The group that provides direction for the configuration of the new system in the existing computing environment are called _______.​
​- Technical stakeholders

Which of the following is normally the most time-consuming and resource-expensive operation?​
- Interview stakeholders

-----

### Analyze phase (core process 3)

Beginning analysts often underestimate how much there is to learn about the work the users perform.​
- True

If the analysts understand the major business processes, it is not usually necessary to create a comprehensive list of all business processes.​
- False, processes are crucial to analyze

Reviewing existing documentation is a good idea for analysts because it is a dependable source of accurate policies and procedures.​
- False

When observing business processes, it is not necessary to observe all the processes at the same level of detail.​
- True

It is a good idea to observe user processes so that the analyst will know exactly how to build the functions into the new system.​
- False

Sometimes a narrative description is the best form to use for recording information.​
- True

One of the dangers in researching vendor solutions is that users and analysts _______.​
- May want to buy one of these solutions prematurely

Which are the major business themes that guide analysts in fact finding activities? (chose 3)​
- ​What are the business processes?
- ​How are the business processes performed?
- What information is needed?

Two benefits of researching vendor solutions include _______ and ______. (Choose two)​
- Helping analysts discover state of the art solutions
- Helping users generate new ideas for business functions

-----

#### Analyze - Interview & Questionnaires

As part of the interview process, any unresolved issues should be _______.​
- Put on an open-items list

What are the two primary benefits of reviewing the documentation of existing inputs, outputs, and procedures.
- Obtain a preliminary understanding
- ​Serve as visual aids in interview discussions

Questions that have a simple, definitive answer are called _______ questions.​
- ​Close-ended

Questions that encourage discussion are called _______ questions.​
- Open-ended

Questionnaires can be useful in information gathering when users _____.​
- Are widely distributed geographically

Questionnaires can be used to ask questions that _______.​
- Ddetermine user opinions

The first and most important step in preparing for an interview is to determine who should be involved.​
- False

A fact finding user interview can usually be completed in one comprehensive session.​
- False

A good way to remember the details of an interview is to use a tape recorder.​
- False

During a fact-finding interview, an important guideline is ____.​
- Probe to get sufficient details

The strength of closed-ended questions is that they ____.​
- Limit answers to a set of choices

Which of the following statements is correct about questionnaires?​
- Questionnaires have a limited and specific use in information gathering.

The most important step in preparing for an interview is to _______.​
- Establish an objective

Asking many detailed, probing questions during an initial interview usually _______.​
- Is necessary to understand the business process

____ is an important part of each interview.​
- Follow-up

-----

### Activity Diagram

One way to show multiple, independent alternative paths within an activity diagram is with a _______.​
​- Decision diamond

Workflows can be documented using _______.​
- Activity diagrams

Looping in an activity diagram is best represented using what?​
synchronization bars

A decision point within an activity diagram may be shown with an activity symbol.​
- True

A synchronization bar in an activity diagram allows multiple agents or actors to participate in a workflow in separate rows.​
- False

-----

### Clients

Clients play what role in the development of the new system?​
- ​Fund the project

What do we call the person or group who provides funding for the development of the new system?​
- Client

-----

### Technology & Application architecture

The term technology architecture refers to:
- hardware, network, and system software Application architecture

Which of the following items is NOT a part of the application architecture?​
- Virtual private networks
