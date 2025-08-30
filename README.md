# Requirement Analysis in Software Development

This repository is dedicated to exploring and documenting the process of requirement analysis in software development. It highlights the importance of gathering, analyzing, and managing requirements to ensure that software projects align with user needs and business goals.

## What is Requirement Analysis?

Requirement Analysis is the process of identifying, gathering, and defining the functional and non-functional requirements of a software system. It serves as the foundation of the Software Development Lifecycle (SDLC), ensuring that the final product meets the needs of users and aligns with business objectives.

During this phase, stakeholders—including clients, end-users, and developers—collaborate to clarify expectations and document requirements in a precise and structured way. This reduces ambiguity, prevents scope creep, and minimizes costly rework later in the project.

### Importance in SDLC:

- **Clarity of Objectives:** Ensures all stakeholders share a common understanding of what the software must achieve.
- **Better Planning:** Provides a clear roadmap for design, development, and testing.
- **Cost and Time Efficiency:** Detects potential issues early, reducing expensive changes during later stages.
- **Quality Assurance:** Sets measurable criteria to validate whether the final product meets user expectations.
- **Risk Reduction:** Identifies challenges and constraints upfront, helping in risk management.

#### Why is Requirement Analysis Important?

Requirement Analysis plays a crucial role in the Software Development Lifecycle (SDLC) as it lays the groundwork for successful project execution. Here are three key reasons why it is important:

1. **Prevents Miscommunication:**  
   By clearly documenting user needs and expectations, requirement analysis ensures that stakeholders, developers, and testers are aligned, reducing the risk of misunderstandings.

2. **Saves Time and Costs:**  
   Identifying requirements early helps detect potential issues before development begins, avoiding costly changes and rework during later stages of the project.

3. **Improves Software Quality:**  
   Well-defined requirements set measurable standards for testing and validation, ensuring the final product meets both functional and non-functional expectations.

#### Key Activities in Requirement Analysis

The Requirement Analysis process involves several key activities that ensure software requirements are well-understood and properly managed:

- **Requirement Gathering:** Collecting information from stakeholders, users, and other sources to identify what the system should achieve.
- **Requirement Elicitation:** Engaging stakeholders through interviews, surveys, workshops, and observation to uncover explicit and implicit needs.
- **Requirement Documentation:** Recording requirements in a structured format (e.g., Software Requirement Specification - SRS) for clear communication.
- **Requirement Analysis and Modeling:** Analyzing requirements for feasibility, consistency, and completeness, and representing them through models or diagrams.
- **Requirement Validation:** Reviewing and confirming requirements with stakeholders to ensure accuracy, relevance, and alignment with project goals.

#### Types of Requirements

### Functional Requirements

Functional requirements describe what the system should do — the specific behaviors, tasks, or functions it must perform.

**Examples (Hotel Booking Management Project):**

- **Hotel Management Service:** Add, update, and remove hotel details.
- **Customer Service (Search + Booking):** Allow customers to search hotels by location, price, and availability, then book rooms online.
- **View Booking Service:** Display booking details, status, and history for a customer.

### Non-functional Requirements

Non-functional requirements define how the system performs, focusing on quality attributes such as performance, usability, reliability, and security.

**Examples (Hotel Booking Management Project):**

- **Hotel Management Service:** Must support concurrent updates by multiple admins without data conflicts.
- **Customer Service (Search + Booking):** Search results should be returned within 2 seconds for up to 10,000 hotel entries.
- **View Booking Service:** Booking history should be accessible 24/7 with 99.9% system uptime.

#### Use Case Diagrams

Use Case Diagrams are a visual tool in Requirement Analysis used to represent the interactions between users (actors) and the system. They help stakeholders quickly understand system functionality, user roles, and how different services are expected to work together.

### Benefits of Use Case Diagrams:

- **Clarity:** Provides a simple and clear visualization of system behavior.
- **Communication:** Bridges the gap between technical teams and non-technical stakeholders.
- **Requirement Validation:** Ensures that all user interactions and system functions are captured.

### Booking System Use Case Diagram

The following diagram illustrates the interactions in the Hotel Booking Management System:

- **Actors:**

  - Customer
  - Hotel Admin
  - System

- **Use Cases:**
  - Search Hotels
  - Book Hotel
  - View Booking
  - Manage Hotels (add/update/remove details)
  - Cancel Booking

![Booking System Use Case Diagram](/home/marto/Downloads/_alx-booking-uc.png)
