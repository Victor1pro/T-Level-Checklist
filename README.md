# T-Level-Checklist
# T-Level-Digital Production Design And Development - Task1 A & B

## Activity A Checklist

### Preparation and Research
**Part I**
Cover:
- Hardware and software applications
- Emerging Tech
- Meeting diverse user needs
- Industry specific guidelines and regulations

Tips:
Research supports rationale for proposal
All notes must be factual

Cover:
- Use credible sources (industry reports, standards, tech blogs)
- Organise notes under headings
- keep notes facts - no analysis
- Include security considerations - encryption, secure data storage etc.
- Note relevant lawaws


### **Business Context**
- - [ ] Overview of the organisation - What they do and offer
  - [ ] Overview of the scenario problem - What are the problem of their current system
- - [ ] Intended users -  Who are the user that interact with the system
  - [ ] Current challenges


### **Busines Requirements Plan & Documentation**
- - [ ] https://assets.asana.biz/m/2dcf4dfc471895ad/original/Business-Requirements-Document-Template-PDF.pdf
- - [ ] Constraints
  - [ ] time, budget, deadlines, resources, security and compliance

### **Empathy Mapping**
- - [ ] Create empathy maps for the main user groups (e.g., customers, support agents, managers). Each map should include:
    - [ ] Says (What the user verbally expresses)
    - [ ] Thinks (What concerns or motivations they have internally)
    - [ ] Does (Their actions and behaviours)
    - [ ] Feels (Emotions related to the support experience)


### **User Needs analysis & Requirements**
- - [ ] From the empathy mapping analyses the different types of user needs in relation to the type of user e.g. (consider accessibiliy and security compliance)
    - [ ] Customer Needs: 
    - [ ] Suppport Agent Needs: 
    - [ ] Manager Needs: 
    - [ ] Business Needs & Objectives: 


### **User Stories & Acceptance**
- - [ ] Create a table with 4 Columns: Use this format (“As a [Type of user], I want [goal], so that [Benefit], Acceptance Criteria)


### **SWOT Analysis with how it will affcet business, customer**
- - [ ] Strengths: What are the strength of the Business (Current system & Future development)
- - [ ] Weakness: What are the weakness of the Business (Current system & Future development)
- - [ ] Opportunities: What are the opportunities of the Business (Current system & Future development) e.g Automated flows, Customer experince, Business goals
- - [ ] Threats: What are the threats to the Business (Current system & Future development) e.g internal and exteranl threats.


### **Stakeholders & Stakeholders Map** 
- - [ ] Discover the types of stakeholders in the proposal sector
- - [ ] Discuss why this stakeholder is important and how will they influence and affect the decision or motive you make.
- - [ ] Create a stakeholder map (Use canva or Word)


### **Functional Requirements**
- - [ ] What the system must do for user e.g
    - [ ] User Management
    - [ ] Content management
    - [ ] Serach & Filter Functionality
    - [ ] Notifications
    - [ ] Security & compliances


### **Non-Functional Requirements**
- - [ ] What the system must do normally to functions e.g
    - [ ] Performance
    - [ ] Reliablity
    - [ ] Usablity
    - [ ] Accessibility
    - [ ] Scalibility


### **Decomposition of Problems**
- - [ ] Break the solution into smaller logical components e.g:
    - [ ] Subsystems
    - [ ] Features
    - [ ] Data Processes
    - [ ] Interfaces
    - [ ] Intercations


### **KPI's & User Acceptance**
- - [ ] include security needs, and compliance with GDPR, what would happen if not etc
    - [ ] Load Times
    - [ ] Error Rates
    - [ ] User Satisfaction
    - [ ] Accuracy
    - [ ] Systsm uptimes
- - [ ] Clear statements of what must be true for users to accept the system. e.g
    - [ ] 


### **Proposed Solution**
- - [ ] **Description of Proposed Solution shoudd be in paragraphs** 
    - [ ] Architecture (The layout & design of old and future system)
    - [ ] Technologies used (What type of API framework, Frontend, Backend Technologies and give what they do and why you have chosen them)
    - [ ] Data Flows (The way data will be transimitted between clintn & server)
    - [ ] Interfaces, Dashboards, Analytics (The user device)
    - [ ] Hardware & Software used e.g API Framework, cloud hosting, Databases, Authentication Tools.
    - [ ] How it fist ther Scenario


### **Justification**
- - [ ] **Meet the Client and User needs**
    - [ ] Provide Evidence based arguments
    - [ ] Links to Research (but not copied analysis from notes)

- - [ ] **Risks, Mitigation & Wider Issues**
    - [ ] Risks
        - [ ] Cybersecuirty risks
        - [ ] Data loss
        - [ ] Lack or user adoption
        - [ ] Technical Failures
    - [ ] Mitigation
        - [ ] Provide Backups & Backup Plans
        - [ ] Authnetication
        - [ ] Authorisation
        - [ ] Training
        - [ ] Testing
    - [ ] Wider Issues
        - [ ] 
        
- - [ ] **Regulatory Guidelines and Legal Requirements**
    - [ ] GDPR Compliances
    - [ ] CIA Triad & Data Security 
    - [ ] Accessibility Concerns
    - [ ] Sector legal requirements


### **Appendix**
    - [ ] (Site link) - Topic Description



# 📘 Activity B Checklist — Design & Development

## General Design Guidance
- [ ] Use Activity A research to guide all design decisions
- [ ] Show multiple design approaches (not just one)
- [ ] Clearly label all diagrams
- [ ] Keep diagrams simple and readable
- [ ] Include accessibility considerations throughout
- [ ] Address security, compliance, and data protection in the design
- [ ] Maintain consistency with user needs and acceptance criteria

---

# 🏗️ System Architecture
- [ ] Architecture Diagram
- [ ] Client / Server Components ()
    - [ ] Diagrams use: Server(Package Diagram, ERD) & Client(Class Diagram, Object Diagram, ERD )
- [ ] Data Storage & Access 
    - [ ] Digrams use: Flowcharts, PseudoCode
- [ ] APIs / Integrations
    - [ ] Frontend file structure (Tree File structure)
    - [ ] API Backend file structure (Tree File structure)
    - [ ] API Backend Diagram (UML: Sequence Diagram)
- [ ] Data Flow Between Components
    - [ ] Data transmission: Data flow Diagram level 0, 1 & Sequence Diagram: Shows how data moves between Components
    - [ ] Data Models: Class Diagram: Ideal for represneting Entities, attributes & Relationship
    - [ ] Data Processing: Activity Diagram: Shows transformations, branching, validation steps
    - [ ] Communication Diagram: Data Dictionary, Use Case Diagram
- [ ] Deployment Environment (cloud / local / hybrid): Deployment Diagram
- [ ] Developement Plan (Gantt Chart: MS project)


## Security Controls
- [ ] Authentication: Utils Folder in backend (JSON webtokens, oauth2)
- [ ] Encryption (Hashing)
- [ ] Secure Data Transmission (Protected Routes & Controller Logic, Cookies)
- [ ] Validation Techniques (Javascript, )

---

# 🎨 Visual Interface Design
- [ ] Wireframes Created
  - [ ] Effective Whitespace
  - [ ] Clear Hierarchy
  - [ ] Visually Appealing Layout
- [ ] Accessibility Features Included such as use "aria-labels"
- [ ] Annotations Explaining Design Decisions
- [ ] User Journey / User Flow
- [ ] Navigation Flow / Sitemap
- [ ] Front-End Requirementsn & File structure
- [ ] Back-End Requirements & File structure

---

# 🔐 Data Protection
- [ ] Data Retention Policy
- [ ] Storage Location (e.g., cloud region) In development sqlite3 & Production - Postgres 
- [ ] Access Control Levels - admin or User or Visitor
- [ ] Encryption Approach (at rest and in transit and in Motion)

---

# 🗄️ Data Design
- [ ] Entity Relationship Diagram (ERD)
- [ ] Use Case Diagram & UMLs
- [ ] Data Dictionary
- [ ] Data Flow Diagram (DFD)
- [ ] Data Validation Rules
- [ ] Data Protection Considerations

---

# ⚙️ System Processes & Algorithms
- [ ] Flowcharts
- [ ] Pseudocode
- [ ] Input–Process–Output Tables
- [ ] Error Handling
- [ ] Try & Exception Handling
- [ ] Process Logic Descriptions (Async, Await, Fetch)

---

# 🧪 Testing Strategy
- [ ] Functionality Testing
- [ ] Usability Testing
- [ ] Interface Testing
- [ ] Database Testing
- [ ] Compatibility Testing
- [ ] Performance Testing
- [ ] Security Testing
- [ ] Crowd Testing
- [ ] Unit Testing
- [ ] Accessibility Testing
- [ ] Acceptance Testing
- [ ] Alpha Testing
- [ ] Beta Testing
- [ ] Black Box Testing
- [ ] White Box / Structural Testing

---

# ⚖️ Security, Legal & Compliance
- [ ] GDPR Compliance
- [ ] Data Minimisation
- [ ] User Consent Management
- [ ] Access Control & Authentication
- [ ] Cyber Threat Mitigation
- [ ] Sector-Specific Regulations (if applicable)
- [ ] Privacy by Design Principles

---

# 🖥️ Technical Specifications
- [ ] Technology Stack
- [ ] Software Requirements
- [ ] Hardware Requirements
- [ ] APIs / Endpoints
- [ ] Integration Requirements
- [ ] Performance Requirements
- [ ] Scalability Considerations
- [ ] Reliability / Availability Targets

---

# 📊 Non-Functional Requirements Mapping
- [ ] Performance Targets
- [ ] Security Requirements
- [ ] Accessibility Requirements
- [ ] Reliability Targets
- [ ] Usability Requirements
- [ ] Maintainability Considerations

---

# 💡 Design Justification
- [ ] Link to Client Requirements
- [ ] Link to User Needs
- [ ] Link to Constraints (time, budget, resources)
- [ ] Accessibility Justification
- [ ] Security Justification
- [ ] Technical Justification
- [ ] Alternatives Considered and Rejected
- [ ] Risk Reduction Explanation

---

# 📎 Appendices
- [ ] Early Design Ideas
- [ ] Rough Sketches
- [ ] Research References
- [ ] Standards References (e.g., WCAG, GDPR)
- [ ] Extended Diagrams
- [ ] Supporting Documentation

---

# 🗣️ Communication
- [ ] Stakeholder Meetings
- [ ] Progress Reports
- [ ] Documentation Strategy
- [ ] Version Control (e.g., Git)
- [ ] Feedback Methods
- [ ] Change Management Process



## Activity Task2 Checklist
