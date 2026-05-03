You are a senior backend batch-processing engineer, distributed workflow architect, and enterprise Golang systems maintainer.

Bootstrap a professional Golang monorepo portfolio repository named:

GO DISTRIBUTED FILE PROCESSOR

This project must simulate a real distributed asynchronous backend platform responsible for receiving large file uploads, persisting them to object storage, validating records, processing batch jobs, generating reports, and notifying users when execution is complete.

====================================================
MAIN OBJECTIVE
====================================================

Generate the complete professional initial repository foundation including:

1. Full enterprise-grade README.md
2. Realistic monorepo architecture skeleton
3. Initial Golang bootstrap starter files
4. Docker Compose infrastructure
5. Processing domain contracts/interfaces
6. Architecture documentation
7. Makefile
8. .env.example
9. GitHub-worthy engineering project presentation

This repository must look like a serious distributed file processing backend, not a toy upload app.

====================================================
TECH STACK
====================================================

Use:

- Golang 1.24+
- PostgreSQL
- Redis
- MongoDB
- RabbitMQ
- MinIO (object storage)
- Prometheus
- Grafana
- Jaeger/OpenTelemetry
- Docker Compose
- Clean Architecture
- Domain Driven Design
- SOLID
- TDD mindset

====================================================
BUSINESS CONTEXT
====================================================

The platform should support a realistic enterprise batch-processing lifecycle:

- file upload intake
- object storage persistence
- validation queue
- batch record processing
- report generation
- processing status polling
- user notification dispatch
- audit event persistence

Possible services:

- upload-api
- validation-worker
- processing-worker
- report-worker
- notification-worker
- audit-service

====================================================
README.MD MUST INCLUDE
====================================================

Generate a polished professional README.md containing:

- title and subtitle
- project overview
- business problem statement
- distributed processing goals
- architecture principles
- service overview
- file processing lifecycle
- stack details
- observability strategy
- testing strategy
- monorepo structure
- docker startup instructions
- roadmap milestones
- future enhancements
- engineering value for backend portfolio presentation

README must be written in polished professional GitHub English.

====================================================
REPOSITORY STRUCTURE
====================================================

Generate a FULL realistic monorepo tree including:

cmd/
internal/
services/
deployments/
docs/
tests/
scripts/

and detailed service subfolders using:

domain/
application/
infrastructure/
interfaces/

====================================================
MANDATORY STARTER FILES
====================================================

Generate realistic starter content for:

- docker-compose.yml
- Makefile
- .env.example
- docs/architecture.md
- docs/file-processing-lifecycle.md
- docs/testing-strategy.md
- docs/adr/0001-file-platform-architecture.md

Starter files must contain realistic content, not TODO placeholders.

====================================================
IMPORTANT OUTPUT FORMAT
====================================================

Output in this exact order:

1. COMPLETE README.md
2. COMPLETE repository tree
3. COMPLETE content of every starter file

Do not summarize.
Do not explain decisions.
Directly generate the repository bootstrap.
