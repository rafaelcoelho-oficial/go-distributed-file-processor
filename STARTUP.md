You are a senior backend batch-processing engineer and distributed file workflow architect.

Bootstrap a professional Golang monorepo repository called:

GO DISTRIBUTED FILE PROCESSOR

This project must simulate a real asynchronous distributed backend platform that receives files, validates content, processes large batches, generates reports and notifies users when processing is complete.

====================================================
MAIN DELIVERABLE
====================================================

Generate:

1. Full enterprise-grade README.md
2. Realistic monorepo skeleton
3. Initial Golang starter files
4. Docker Compose infrastructure
5. Processing domain contracts/interfaces
6. Architecture documentation
7. Makefile
8. .env.example
9. GitHub-quality engineering presentation

This repository must look like a serious distributed file processing backend.

====================================================
TECH STACK
====================================================

Use:

- Golang 1.24+
- PostgreSQL
- Redis
- MongoDB
- RabbitMQ
- MinIO or local object storage
- Prometheus
- Grafana
- Jaeger/OpenTelemetry
- Docker Compose
- Clean Architecture
- DDD
- SOLID
- TDD

====================================================
BUSINESS FLOW
====================================================

The platform should support:

- file upload intake
- object storage persistence
- validation pipeline
- row batch processing
- report generation
- status polling
- user notification
- processing audit logs

Possible services:

- upload-api
- validation-worker
- processing-worker
- report-worker
- notification-worker

====================================================
README MUST INCLUDE
====================================================

Generate a professional README.md containing:

- title/subtitle
- project overview
- distributed file processing problem statement
- architecture goals
- service overview
- processing lifecycle
- stack details
- observability
- testing strategy
- monorepo structure
- docker startup instructions
- roadmap
- engineering portfolio relevance

====================================================
REPOSITORY TREE
====================================================

Generate:

cmd/
internal/
services/
deployments/
docs/
tests/
scripts/

with:

domain/
application/
infrastructure/
interfaces/

====================================================
MANDATORY FILES
====================================================

Generate starter content for:

- docker-compose.yml
- Makefile
- .env.example
- docs/architecture.md
- docs/file-processing-lifecycle.md
- docs/testing-strategy.md
- docs/adr/0001-file-platform-architecture.md

====================================================
OUTPUT FORMAT
====================================================

Output:

1. COMPLETE README.md
2. COMPLETE repository tree
3. COMPLETE starter files content

Do not explain.
Generate directly.
