# Requirement Analysis

## What is Requirement Analysis?
Requirement analysis is a critical phase in the software development life cycle where a team gathers, analyzes, and defines the software requirements of the product to be developed. This ensures clarity among all stakeholders on what the product does and how it should perform.

---

## Why is Requirement Analysis Important?
- Reduces ambiguity on the expectations of what the final product should do.  
- Clearly defines the scope of the project, helping avoid scope creep.  
- Serves as the foundation for design and development.  
- Makes cost and duration estimation easier.  
- Ensures the final product meets customer expectations.  

---

## Key Activities in Requirement Analysis

### 1. Requirement Gathering
- Collect requirements via interviews, surveys, observations.  
- Hold workshops with stakeholders.  
- Review existing documentation.  

### 2. Requirement Elicitation
- Brainstorming and focus group sessions.  
- Create simple prototypes for visualization.  

### 3. Requirement Documentation
- Develop a **Requirements Specification Document**.  
- Include: functional & non-functional requirements, user stories, use case diagrams.  

### 4. Requirement Analysis and Modeling
- Assess feasibility of requirements.  
- Prioritize based on project importance.  
- Create models (e.g., data flow diagrams) to visualize requirements.  

### 5. Requirement Validation
- Review requirements with stakeholders.  
- Define clear acceptance criteria.  
- Ensure traceability.  

---

## Types of Requirements

### Functional Requirements
Describe **what** the system should do. Example (Booking System):  
- Hotel Management  
- Search and Booking  
- View Bookings  
- Notifications  
- Payment Integration  

### Non-Functional Requirements
Describe **how** the system should perform. Example (Booking System):  
- Scalability (handle high traffic)  
- Speed/Performance  
- Availability/Uptime  
- Fault Tolerance (via microservices)  
- Data Archiving  
- Consistency  

---

## Use Case Diagram

Visual representation of how users interact with the system:  

![Use Case Diagram](https://drive.google.com/uc?export=view&id=1p7Hldj2EdNH4N6MIpKlj9GGh5xnqZQmg)

---

## Acceptance Criteria

Acceptance criteria define when a feature is considered **done**, ensuring quality and clarity.  

**Example: Checkout Feature (Booking System)**  

- **Start Checkout**:  
  User selects property and dates → clicks checkout → sees booking summary.  

- **Payment Options**:  
  User can pay via PayPal, Card, or MPesa.  

- **Validation**:  
  Invalid payments trigger an error message. No booking created.  

- **Successful Booking**:  
  Valid payment → booking saved → email sent → user redirected to success screen.  

- **Failed Booking**:  
  Declined payment → user shown failure message with retry option.  

- **Security**:  
  All payment data handled securely.  
