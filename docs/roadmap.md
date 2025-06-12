
---

## 🗂️ `docs/roadmap.md` (4-Week Agile Plan)

Save this as `docs/roadmap.md`.

```md
# 🗺️ LegalEase AI – Roadmap

### Sprint Duration: June 2025
### Dev Hours: 10 hours/week (Solo Developer)

---

## 🧾 Week 1: Project Setup + File Ingestion

**Goals**
- Initialize repo with proper .NET solution and projects
- Create file upload API (accept PDF/DOCX)
- Store uploaded docs with metadata (type, date, user)
- Add PDF text extraction (iText7) and OCR fallback (Tesseract)

**Deliverables**
- ✅ Project bootstrapped
- ✅ File upload and parse API
- ✅ Basic file listing UI
- ✅ Local PostgreSQL or SQL Server

---

## 🔍 Week 2: Search & Tagging Engine

**Goals**
- Tag documents automatically using AI keyword extraction
- Implement full-text search (Elastic or Azure Search)
- Frontend: search bar + document preview panel

**Deliverables**
- ✅ Tagger + searchable index
- ✅ Filterable document search
- ✅ Highlighted keyword display

---

## 🧠 Week 3: Summarization + Draft Generation

**Goals**
- AI-powered document summarization via Azure OpenAI
- Smart draft generation (NDA, motion, etc.)
- Frontend: summary and draft generation UI

**Deliverables**
- ✅ /summarize and /generateDraft endpoints
- ✅ Draft templates + JSON config
- ✅ Polished summary + editor panel

---

## 🔐 Week 4: Auth, Testing, Deployment

**Goals**
- Setup user roles (Admin / Paralegal)
- Write backend unit tests
- Add CI/CD via GitHub Actions
- Deploy API to Azure App Service

**Deliverables**
- ✅ Auth system working
- ✅ Tests running on push
- ✅ Azure app live

---

## Future (Post-MVP Ideas)
- Case bundling by ID (group docs by legal case)
- Relevance scoring for document search
- Redaction / entity anonymization
- Audit logs + user analytics
