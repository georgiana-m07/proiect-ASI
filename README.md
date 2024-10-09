# Dental Clinic Information System - ASI Project

This project was developed for the "Informational SYstem Analysis / Analiza sistemelor informaționale" (ASI) course. It focuses on analyzing and designing an information system for tracking dental procedures and managing clinic operations. The project simulates a real-world system to manage patient appointments, dental treatments, materials procurement, and external collaborations with specialists.

## Project Overview

The system was designed for **Cabinet Medical de Medicină Dentară Dr. Izvernari Cosmina**, a dental clinic. It covers both internal operations (scheduling, procedures) and external collaborations (specialists, suppliers). The project employs multiple methodologies such as BPMN for business process modeling and UML for system structure.

### Key Features of the System:
- **Patient Management**: Tracking patient appointments and medical records.
- **Material Procurement**: Ordering and receiving medical supplies needed for treatments.
- **Collaboration with Specialists**: Referring patients to external specialists and receiving feedback from them.
- **Tracking Dental Work**: Documenting all procedures performed on patients and maintaining a history of dental treatments.

## Project Structure and Components:

### 1. Organization Overview
The system is built for a real-world dental clinic, and the project includes a thorough analysis of the clinic’s operations:
- **Clinic Name**: Cabinet Medical de Medicină Dentară Dr. Izvernari Cosmina
- **Established**: March 13, 2017
- **Services**: General and specialized dental consultations, invasive dental treatments, hygiene, teeth whitening, and prevention procedures.
- **Legal Form**: Authorized Physical Person (PFA)
- **External Collaborations**: 
- **Suppliers**: Polident, DentStore, Dentotal
- **Specialists**: Radiologists, dental surgeons, orthodontists, and endodontists

### 2. Organizational Structure and Flowchart

The dental clinic operates with a minimalist structure:
- **Stomatologist**: The primary practitioner who manages all patient appointments and treatments.
- **External Collaborations**: Most specialized services (e.g., dental surgeries, radiographies) are outsourced. The clinic collaborates with external specialists and suppliers.
- **Challenges**: Lack of administrative staff, leading to inefficiencies in managing external collaborations and appointments.

### 3. Business Process Modeling (BPMN)

A **BPMN Diagram** was created to represent the business processes within the clinic, from patient registration to treatment execution. The diagram includes key processes such as:
- **Patient Scheduling**: The system manages scheduling based on patient needs and availability.
- **Materials Procurement**: The clinic places orders for medical supplies and tracks their delivery.
- **Specialist Referrals**: The system handles patient referrals to external specialists, such as orthodontists and radiologists, and logs the feedback and results received from these collaborators.
  
*The BPMN diagram clearly illustrates how these processes interact and flow through the clinic's system.*

### 4. Existing Information System Analysis

The analysis phase focused on understanding the existing processes within the clinic:
- **Document Inventory**: This lists all documents used in the clinic, such as appointment registers, dental procedure forms, invoices, and medical records.
- **System Flowchart**: A flowchart was developed to map out how documents and data move through the clinic’s system, including information coming from external collaborators (e.g., dental technicians, radiologists).

### 5. UML Modeling

The system’s structure is modeled using UML diagrams to provide a detailed overview of how users interact with the system and how data flows between components:
- **Use Case Diagram**: Represents different interactions between users (patients, dentist, suppliers, specialists). It details actions like scheduling appointments, requesting materials, and referring patients to specialists.
- **Activity Diagram**: Describes the flow of activities, such as the process of treating a patient or handling external referrals.
- **Class Diagram**: Defines the relationships between different entities within the system, including `Patient`, `Appointment`, `DentalProcedure`, `MaterialOrder`, and `SpecialistReferral`.

### 6. System Implementation

The information system focuses on automating the following processes:
- **Appointment Scheduling**: Automates the process of registering and tracking patient appointments.
- **Material Orders**: Keeps track of medical supplies ordered and received, ensuring the clinic has the necessary tools for procedures.
- **Specialist Collaboration**: Facilitates communication and information exchange between the clinic and external specialists, logging all referrals and received feedback.

## Technologies and Tools Used

This project uses a variety of techniques and tools to analyze and design the system:
- **BPMN Diagrams** for business process modeling.
- **UML Diagrams** for detailed system structure modeling, including use case, class, and activity diagrams.
- **Flowcharts** for visualizing the existing information system and identifying areas for improvement.
- **Microsoft Visio** for creating BPMN diagrams, UML diagrams, and flowcharts.


## Screenshots

### Organizational Structure
![image](https://github.com/user-attachments/assets/5845ca0e-9f1a-498b-a2d3-fa9bde42b0cf)
*Figure: Organizational chart illustrating the structure of the dental clinic.*

### Flowchart
![image](https://github.com/user-attachments/assets/579c4768-3017-4984-8740-03d62910a3ac)
*Figure: Flowchart illustrating the flow of information and document management in the clinic.*

### BPMN Diagram
![image](https://github.com/user-attachments/assets/c5ae5da5-660f-41e5-97d4-305c52b0337e)
*Figure: BPMN diagram illustrating the workflow of processes within the dental clinic.*

### Use Case Diagram
![image](https://github.com/user-attachments/assets/44199776-0448-47a7-a8f6-e9eb351898c1)
*Figure: Use Case Diagram showing interactions between patients, dentists, and external specialists.*

### Class Diagram
![image](https://github.com/user-attachments/assets/41080a70-a7a4-4be2-92f2-c35589d5caed)
*Figure: Class Diagram illustrating the relationships between entities such as patients, procedures, and materials.*

### Activity Diagram
![image](https://github.com/user-attachments/assets/4660391b-a2a7-45de-8d51-810c5ce46a22)
*Figure: Activity Diagram showing the flow of activities involved in managing a dental procedure.*


## Future Enhancements
1. **Online Appointment System**: Automating the patient scheduling process by integrating an online booking platform.
2. **Personnel Expansion**: Hiring administrative staff to improve workflow efficiency and manage external collaborations.
3. **Service Expansion**: Adding new services to the clinic’s offering, including more advanced dental treatments and consultations.

---
