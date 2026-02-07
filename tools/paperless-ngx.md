# Paperless-ngx

## What It Is

Paperless-ngx is a community-supported, open-source document management system that transforms physical documents into a searchable, archivable digital collection. It performs OCR on scanned documents and uses machine learning to automatically tag and classify them.

## What It's Used For

- Creating a searchable digital archive of physical documents
- Organizing receipts, bills, invoices, and correspondence
- Automating document classification and tagging with AI
- Building a paperless office environment
- Full-text search across all your documents

## Key Features

- **OCR Processing** — Tesseract-based OCR with 100+ language support
- **Full-Text Search** — Search across document text, metadata, and tags
- **Auto-Classification** — Machine learning assigns tags, correspondents, and document types
- **Nested Tags** — Hierarchical tag structures for organized categorization
- **PDF/A Archival** — Long-term storage format alongside original files
- **Multi-Format Support** — PDFs, images, plain text, Word, Excel, PowerPoint, and LibreOffice files
- **Web UI** — Responsive interface for managing, filtering, and editing documents
- **Self-Hosted** — Runs on your own infrastructure; data never leaves your server
- **Docker Ready** — Pre-built images for easy deployment
- **Workflows** — Hook into the document pipeline for custom automation

## How to Get Started

**Quick install (Docker Compose):**

```bash
bash -c "$(curl -L https://raw.githubusercontent.com/paperless-ngx/paperless-ngx/main/install-paperless-ngx.sh)"
```

This interactive script pulls the Docker image, configures the environment, and creates your superuser account.

**Manual setup:** Follow the guide at [docs.paperless-ngx.com/setup](https://docs.paperless-ngx.com/setup/)

## Pricing

Completely free and open source. The only costs are your server hardware and electricity.

## Official Links

- **Docs:** [docs.paperless-ngx.com](https://docs.paperless-ngx.com/)
- **GitHub:** [github.com/paperless-ngx/paperless-ngx](https://github.com/paperless-ngx/paperless-ngx)
- **Docker Hub:** [hub.docker.com/r/paperlessngx/paperless-ngx](https://hub.docker.com/r/paperlessngx/paperless-ngx)
- **Usage Guide:** [docs.paperless-ngx.com/usage](https://docs.paperless-ngx.com/usage/)
