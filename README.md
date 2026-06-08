# Cliengo

Cliengo is an AI-powered customer communication platform for sales, support, and customer service teams. It centralizes WhatsApp, website chat, Instagram, and Facebook Messenger conversations into one omnichannel inbox, automates responses with business-trained AI assistants, qualifies leads, routes conversations to the right team, and gives teams actionable reporting on every interaction.

The platform is designed for companies that need to respond instantly, capture more qualified leads, reduce manual support work, and convert conversations into revenue.

## Core capabilities

- **AI chatbot for WhatsApp and web chat**: automated 24/7 responses trained on company knowledge, FAQs, products, services, and operating rules.
- **Omnichannel inbox**: one workspace for WhatsApp, website chat, Instagram, Facebook Messenger, and handoff to human agents.
- **Dynamic conversation flows**: no-code workflows for lead qualification, appointment scheduling, routing, escalation, and follow-up.
- **WhatsApp campaigns**: bulk and segmented outbound messaging with automated bot follow-up.
- **Lead qualification**: capture contact details, intent, budget, urgency, and business-specific qualification fields.
- **CRM sync**: push contacts, leads, conversation history, tags, and lifecycle status into external CRM systems.
- **Conversation analytics**: track volume, conversion rate, campaign performance, response time, handoff rate, and bot effectiveness.
- **AI copilot insights**: analyze conversations to identify objections, missed opportunities, common questions, and optimization opportunities.

## Repository structure

```text
.
├── analytics-service/      # Metrics, dashboards, funnel reporting, and conversation insights
├── chatbot-engine/         # AI assistant runtime, flows, lead qualification, and escalation logic
├── conversation-hub/       # Omnichannel inbox, message state, routing, and agent handoff
├── crm-sync-api/           # CRM integrations, lead/contact sync, and lifecycle updates
└── whatsapp-connector/     # WhatsApp Business API webhooks, outbound messages, and delivery events
