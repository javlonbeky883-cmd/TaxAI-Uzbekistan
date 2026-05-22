# TaxAI Uzbekistan

TaxAI Uzbekistan is an AI-powered tax optimization platform built for Uzbekistan businesses, freelancers, and IT exporters.

## Overview

TaxAI Uzbekistan is positioned as an AI-based Tax Strategy Platform that helps companies:

- Legally minimize tax obligations
- Verify IT Park compliance
- Automatically detect tax risks
- Optimize tax strategy for export services and freelancers

The Uzbekistan market is in a strong growth phase due to:

- Rapid expansion of IT Park
- Growth of service exports
- Increasing foreign currency revenue
- A growing freelancer economy

## Architecture

```
taxai-uzbekistan/
│
├── frontend/
│   ├── flutter_app/
│   └── admin_dashboard/
│
├── backend/
│   ├── app/
│   ├── ai/
│   ├── services/
│   ├── routes/
│   └── database/
│
├── vector_db/
│
├── tax_laws/
│   ├── raw_pdf/
│   ├── parsed/
│   └── embeddings/
│
├── docs/
│   ├── architecture/
│   ├── investor_pitch/
│   └── api_docs/
│
├── scripts/
├── docker/
├── .github/
│   └── workflows/
│
├── README.md
├── docker-compose.yml
└── requirements.txt
```

## Tech Stack

### Frontend
- Flutter
- Riverpod
- GoRouter

### Backend
- FastAPI
- PostgreSQL
- SQLAlchemy

### AI
- OpenAI API
- LangChain
- Qdrant (Vector DB)

### Infrastructure
- Docker
- AWS
- Nginx

## Development Phases

### Phase 1 — Foundation
- Project initial structure
- FastAPI base server
- Flutter base UI
- PostgreSQL connection

### Phase 2 — Tax Law RAG Pipeline
- Tax Law PDF Parser
- Embedding Generator
- Vector Search

### Phase 3 — AI Tax Intelligence
- AI Tax Chat
- Risk Score Engine
- IT Park Analyzer

### Phase 4 — Productization
- PDF Report Generation
- Invoice Analyzer
- Admin Dashboard

## CI/CD

- Backend Test
- Flutter Build
- Docker Build
- Auto Deploy

## License

Proprietary — All rights reserved.
