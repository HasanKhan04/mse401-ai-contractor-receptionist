# System Architecture

The proposed solution is a contractor-focused AI receptionist designed for small home service businesses such as plumbers, electricians, HVAC technicians, landscapers, and general contractors.

The goal of the system is to automate routine customer interactions while ensuring customers can easily obtain information and schedule services. The architecture is designed to reduce missed calls, improve customer accessibility, and decrease the administrative workload placed on business owners and staff.

## High-Level Workflow

1. Customer places a phone call.
2. AI receptionist answers the call.
3. AI collects relevant customer information.
4. AI identifies the customer's service request.
5. AI provides information using business-specific knowledge.
6. AI schedules appointments when required.
7. Confirmation information is provided to the customer.

## Main Components

### Customer Interface

The customer interface consists of the phone call interaction between the customer and the AI receptionist.

### AI Receptionist

The AI receptionist serves as the central component of the system and is responsible for:

* Answering incoming calls
* Understanding customer requests
* Asking follow-up questions
* Collecting customer information
* Providing responses
* Guiding appointment scheduling

### Knowledge Base

The knowledge base contains business-specific information used to answer customer questions, including:

* Operating hours
* Services offered
* Service areas
* Frequently asked questions
* General business information

### Appointment Scheduling System

The appointment scheduling system manages service bookings and appointment availability.

### Business Dashboard

The business dashboard allows business owners to manage business information, review customer interactions, and monitor appointments.

## Architecture Diagram

The architecture diagram included in the repository visually represents the flow of information between customers, the AI receptionist, the knowledge base, and the scheduling system.
