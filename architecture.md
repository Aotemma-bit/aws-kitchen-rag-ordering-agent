# System Architecture


WhatsApp
      │
      ▼
WhatsApp Trigger
      │
      ▼
AI Agent
      │
      ├───────────────┐
      │               │
      ▼               ▼
Customer Memory   RAG Search
                      │
                      ▼
             Vector Knowledge Base
                      │
                      ▼
               Menu Information
                      │
                      ▼
              Google Sheets Orders
                      │
                      ▼
            WhatsApp Confirmation


## Core Components

- WhatsApp Trigger
- AI Agent
- Retrieval-Augmented Generation (RAG)
- Vector Knowledge Base
- Customer Memory
- Google Drive
- Google Sheets
- Error Handling
