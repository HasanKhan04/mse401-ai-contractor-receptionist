# Generative AI Usage Documentation

## Reflection

Generative AI was used throughout the project as a supporting tool for research, analysis and brainstorming. Specifically, AI was used to assist with understanding the problem domain, researching existing AI receptionist solutions, identifying relevant references, generating and evaluating alternative design concepts, brainstorming requirements and the system architecture, generating an architecture diagram, and improving documentation quality. All AI-generated outputs were reviewed, modified, validated, and refined by team members before inclusion in project deliverables. Generative AI was used to accelerate research and design activities; however, all final decisions, evaluations, and project deliverables remained the responsibility of the project team.

---

## Prompt 1 – Problem Understanding and Research

### Prompt

Analyze the challenges faced by small service businesses such as plumbers, contractors etc when managing customer calls and appointments. What are the stakeholders, impacts of missed calls, and common approaches to handle these challenges

### Response Excerpt

> Home service businesses often experience highly variable call volumes depending on seasonality, weather conditions, and emergency service demand. During peak periods, business owners may be unable to answer calls while working in the field. Studies on customer service behaviour suggest that many customers expect a response within minutes and may contact another provider if they are unable to reach someone immediately. This challenge is particularly significant for small businesses that lack dedicated administrative staff and cannot justify the cost of a full-time receptionist.

### Use in Project

Used as a starting point for the Problem Analysis section and stakeholder identification.

---

## Prompt 2 – Competitor Analysis and Industry Research

### Prompt

Compare existing AI receptionist solutions and solutions for contractors including Vapi, Retell AI, Smith.ai, RingCentral AI Receptionist, Jobber, Housecall Pro. Whats their strengths weaknesses target, and gaps could be addressed by a new solution?

### Response Excerpt

> Many existing AI voice solutions position themselves as infrastructure providers rather than complete business solutions. Platforms such as Vapi and Retell AI focus on enabling developers to build custom voice agents, while companies such as Smith.ai emphasize managed receptionist services. Contractor software platforms focus primarily on scheduling, dispatching, and operational workflows. This distinction suggests that there may be opportunities for industry-specific products that combine conversational AI capabilities with workflows tailored to a particular business sector.

### Use in Project

Used to support the Existing Solutions and Competitor Analysis section and competitive gap assessment.

---

## Prompt 3 – Concept Generation and Evaluation

### Prompt

What are some idead ans designs for an AI receptionist specializd for small contractor businesses. Include advantages disadvantages, and why its valsaube for each.

### Response Excerpt

> An alternative concept would be a lead-capture assistant that focuses exclusively on gathering customer information and forwarding requests to business owners. While simpler to implement than a full receptionist system, this concept provides less value because it still requires manual follow-up and does not address appointment scheduling or customer self-service needs. Another concept could integrate SMS follow-up functionality and automated reminders, although this would increase project complexity and expand the project scope beyond the core problem being addressed.

### Use in Project

Used during concept generation and concept evaluation activities.

---

## Prompt 4 – Requirements Development

### Prompt

Generate functional and non-functional requirements for a contractor specialized AI receptionist capable of answering calls, collecting customer information, answering questions, and scheduling appointments.

### Response Excerpt

> Requirements should be prioritized according to the primary goals of the system. Features directly related to customer accessibility, lead capture, and appointment management should receive the highest priority because they are most closely connected to the problem being solved. Additional capabilities such as analytics dashboards, customer history tracking, automated follow-up messaging, multilingual support, and advanced reporting may provide value but could be considered lower-priority requirements during the initial stages of development.

### Use in Project

Used as a starting point for requirements development and acceptance criteria definition.

---

## Prompt 5 – System Architecture and Diagram Development

### Prompt

Design a high-level architecture for a contractor-focused AI receptionist system capable of answering calls, collecting customer information, answering FAQs, and scheduling appointments.

### Response Excerpt

> The architecture should separate business knowledge from conversational logic so that information such as operating hours, service areas, pricing details, and frequently asked questions can be updated without modifying the core AI system. This separation improves maintainability, allows businesses to customize information more easily, and reduces the effort required to support different businesses using the same overall system architecture.

### Follow-Up Prompt

Create a conceptual architecture diagram for the interactions between the customer, AI receptionist, knowledge base, appointment scheduling system, and business dashboard. Show the information data flow in it.

### Response Excerpt

> A conceptual architecture diagram should emphasize relationships between major system components rather than implementation technologies. The diagram should remain technology-agnostic and focus on how information flows between customers, business information sources, scheduling functions, and business users. This approach keeps the diagram aligned with conceptual design objectives while avoiding unnecessary implementation details that may change during later stages of development.

### Use in Project

Used to support architecture development and creation of the architecture diagram included in the repository.
