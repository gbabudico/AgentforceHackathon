# AI-Powered Virtual Service Advisor 🚗🤖

This project was developed as part of the **Salesforce Agentforce Hackathon** to demonstrate how AI can enhance customer experience in the **automobile service industry**. The solution leverages Salesforce Service Cloud, Embedded Service, Prompt Builder, and AI capabilities to deliver intelligent, real-time support to vehicle owners.

## 🔧 Core Use Cases

### 1. Roadside Assistance Handling
- Customers interact via a portal or chatbot.
- The AI service agent collects incident details.
- Real-time assistance is triggered (towing/technician dispatch).

### 2. Driving Behavior Coaching
- Vehicle AI analyzes data to detect unsafe driving behavior.
- Sends automated email to customer with coaching tips.
- Optionally schedules a free check-up with a technician.

### 3. IoT & Predictive Maintenance Alerts
- Vehicle sensor data is monitored (brakes, coolant, oil, etc.).
- When issues are detected, personalized emails are sent.
- Schedules a service appointment based on severity.

## 🧠 Key Features
- Built with Salesforce Service Cloud + Prompt Builder
- AI-generated content based on record-level field inputs
- Email and appointment logic driven entirely by system data
- Aligned with real-world automotive service processes

## 📁 Repository Structure

```
force-app/main/default/       # Salesforce metadata (objects, flows, templates)
prompts/                      # Prompt templates for email generation
docs/                         # Diagrams and supporting documents
examples/                     # Test records, email output examples
```

## 📌 Future Enhancements
- Data Cloud integration for 360° customer personalization
- Use case expansion into insurance claims and warranty support
- EV-specific service logic (battery, charging insights, etc.)

## 🏷️ Technologies Used
- Salesforce Service Cloud
- Prompt Builder (Einstein 1 Studio)
- Apex (for automation where needed)
- GitHub for version control and collaboration

## 📸 Diagrams
👉 Please refer to the `/docs` folder for:
- High-level architecture
- Use case interaction flows
- Data model diagram

## 🙌 Acknowledgement
Created for the Salesforce Agentforce Hackathon to empower the automotive service ecosystem using AI, data, and automation.

---

