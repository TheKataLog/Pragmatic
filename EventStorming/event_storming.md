# Event Storming Workshop

## Introduction

In our recent workshop, we used Event Storming to explore and map out various domains within our business processes. The session focused on capturing and documenting the flow of events, actors, and interactions between systems. This document summarizes our outcomes and serves as a guide to understanding our approach.

## Workshop Goals

- **Discover key domains**: Identify and understand the core business domains and their boundaries.
- **Document workflows**: Capture the flow of domain events, commands, actors, and external systems.
- **Clarify ambiguities**: Document open questions, decisions, problems, and solutions as they arose during the session.

## Workshop Outcomes

### 1. **Actors**:

- We identified the main actors involved in each process. Actors are the individuals or systems that initiate commands and trigger domain events.
- Examples include customers, internal users, external services, and job candidates.

### 2. **Commands**:

- Commands represent actions initiated by actors. We captured the key commands that drive the business process, such as placing an order, submitting a payment, or updating job application status.
- A specific point discussed was allowing job candidates to declare that they do not wish to be hired, even if they have been marked as "hired" within the system.

### 3. **Domain Events**:

- Domain events describe significant occurrences in the business process, such as "Order Placed", "Payment Processed", or "Candidate Hired".
- We also anonymized resumes in our system by referring to them as "Stories" for privacy and compliance reasons.
- The events were organized in chronological order to display the flow of the business process.

### 4. **External Systems**:

- We noted the external systems that interact with our business processes, such as payment gateways, third-party services, or databases.
- These systems were documented to show how and where they interface with the internal process.

### 5. **Uncertainties and Decisions**:

- As we mapped the workflow, we documented any open questions, problems, or decision points in a structured manner:
  - **Questions**: Areas requiring further clarification.
  - **Problems**: Issues or roadblocks encountered.
  - **Decisions**: Consensus reached during the session.

One key decision was to make the payment process synchronous, ensuring that payments are processed in real-time to improve user experience and system accuracy.

## Workshop Process

1. **Domain Event Mapping**:
   We started by mapping the domain events, capturing them on orange sticky notes and placing them in chronological order.

2. **Commands and Actors**:
   We then identified the commands that trigger each event and linked them to the relevant actor responsible for that action.

3. **External Systems**:
   We noted external systems interacting with the process, marking these points in the timeline.

4. **Uncertainties**:
   Throughout the session, we raised and captured open questions or ambiguities, noting their status for further follow-up.

## Key Decisions

- **Anonymized resumes**: Resumes are anonymized and referred to as "Stories" to ensure privacy.
- **Synchronous Payment Process**: The payment process will be synchronous, allowing for real-time transaction processing.
- **Candidate Status Flexibility**: Job candidates can decide not to be hired, even if the system marks them as hired, providing greater flexibility in the hiring process.

## 1. Iteration

We conducted the initial Event Storming session by placing sticky notes on a table to map out the workflow in a physical format.
![Event strorming sticky note](/EventStorming/assets/eventstorming_stickynotes.jpeg)

## 2. Iteration

In the second iteration, we digitized the workflow, transitioning from the physical sticky notes to a digital format for easier collaboration and refinement.
![Event Storming 2. iteration digital](/EventStorming/assets/Eventstorming.png)

## Iteration 2

## Conclusion

The Event Storming workshop helped us gain a clear understanding of our business processes and uncover important insights. We documented actors, commands, domain events, external systems, and clarified open issues.
