# System Architecture

The proposed solution is a contractor-focused AI receptionist designed for small home service businesses such as plumbers, electricians, HVAC technicians, landscapers, and general contractors.

The system is intended to act as the first point of contact for customers calling a business. Rather than reaching voicemail or waiting for a human receptionist, customers interact directly with an AI assistant capable of understanding natural language and responding appropriately.

## High-Level Workflow

1. Customer places a phone call.
2. AI receptionist answers the call.
3. AI collects customer information.
4. AI identifies the requested service.
5. AI answers common business questions using a business knowledge base.
6. AI schedules an appointment when required.
7. Appointment information is stored in the business calendar.
8. Confirmation information is provided to the customer.

## Main Components

### Customer Interface

The customer interface consists of the phone call interaction between the customer and the AI receptionist.

### AI Receptionist

The AI receptionist is responsible for:

* Answering incoming calls
* Understanding customer requests
* Asking follow-up questions
* Collecting customer information
* Providing responses

### Knowledge Base

The knowledge base contains business-specific information such as:

* Operating hours
* Services offered
* Service areas
* Pricing information
* Frequently asked questions

### Appointment Scheduling System

The scheduling system manages appointment creation and stores bookings in a calendar.

### Business Dashboard

The dashboard allows business owners to:

* Review call summaries
* Update business information
* Manage appointments
* Review customer inquiries

## Architecture Diagram

The architecture diagram included in the repository visually represents the flow of information between customers, the AI receptionist, the knowledge base, and the scheduling system.
