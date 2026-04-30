# JLHC AI Portfolio

Public reference workflows showing how I approach data automation, document extraction, scraping, reporting, validation, and AI-assisted review.

These repositories use synthetic, low-stakes examples, but the workflow patterns are real: messy inputs, structured outputs, validation checks, human-review cues, and maintainable handoff.

## Portfolio map

| Area | What it demonstrates | Typical client need |
|---|---|---|
| PDF/OCR and document extraction | Convert messy PDFs or scanned-like documents into structured, reviewable outputs | Extract tables, catalogues, forms, packets, or operational documents |
| Web scraping and data extraction | Collect heterogeneous website data, normalize records, and export structured datasets | Build repeatable data collection workflows from public or semi-structured sources |
| Spreadsheet and workbook automation | Sync, validate, and audit Excel/CSV workflows | Reduce manual spreadsheet work and create controlled reporting processes |
| AI-assisted workflows | Use LLMs for bounded extraction or classification with validation and human review | Add AI support without treating model output as automatically correct |
| Reporting automation | Convert structured data into repeatable PDF, HTML, Excel, or review-ready deliverables | Replace manual reporting with reproducible outputs |
| Research and geospatial pipelines | Process, document, and publish analytical or scientific datasets | Build reproducible research-grade data workflows |
| DOCX standardization | Standardize inconsistent Word documents into validated, editable drafts with review packets and QA logs | Normalize SOPs, playbooks, internal guides, training material, or operational documentation |

## Selected examples

- **PDF/OCR Catalog Review Workflow**  
  Converts varied catalog-style PDFs into structured draft records, CSV/JSON/SQLite outputs, validation warnings, source evidence, and human-review packets.

- **Supplier PDF to Excel/CSV Review Packet**  
  Recovers structured rows from messy supplier-style PDFs, applies confidence scoring and validation flags, and produces an Excel/CSV handoff for review.

- **Web Listings Extraction & Normalization Pipeline**  
  Collects static, paginated, JavaScript-rendered, and cookie-gated listings into one normalized CSV/JSON catalog with an inspectable HTML QA report.

- **PDF/DOCX Packet Structuring Workflow**  
  Turns mixed document packets into source-cited run sheets with validation warnings, unresolved questions, and reviewer-facing outputs.

- **AI-Assisted DOCX Playbook Standardization Workflow**  
Standardizes inconsistent Word playbooks into validated JSON, editable DOCX drafts, review packets, logs, replay evals, and human-review cues.

- **AI-Assisted Email Intake Review Workflow**  
  Extracts fields from informal emails with LangGraph/OpenAI, matches them against workbook rules, and writes review packets without auto-sending.

- **Excel Formula Sync & Audit Workflow**  
  Syncs reviewed formulas into an Excel-compatible workbook while rejecting unsafe or invalid rows and preserving an audit trail.

- **AI-Assisted Publishing Review Workflow**  
  Turns incomplete event/workshop requests into draft public copy, organizer digests, explicit review flags, and hold/publish decisions.

- **CSV-to-PDF Automated Reporting Pipeline**  
  Rebuilds a repeatable PDF packet from structured CSV data with validation, deterministic ordering, and stable layout.

## How to read these repositories

The goal is not to showcase large production systems with private client data. The goal is to make my delivery style visible:

- clear problem framing;
- documented inputs and outputs;
- structured exports;
- validation and QA checks;
- reviewable intermediate files;
- reproducible workflows;
- maintainable handoff.

## Core skills represented

Python, R, ETL, data extraction, PDF/OCR workflows, DOCX automation, web scraping, Excel/CSV automation, JSON Schema validation, automated reporting, AI-assisted workflows, LangChain/LangGraph-style orchestration, validation, QA, reproducibility, and maintainable data pipelines.

## Professional positioning

I help clients turn messy data, documents, websites, spreadsheets, and research workflows into reliable analyses, automated pipelines, and decision-ready outputs.

My work combines practical implementation with statistical rigor, reproducible delivery, documentation, validation, and maintainable handover.
