# LegalEase AI

**LegalEase AI** is an AI-powered legal assistant designed to help law firms and public defenders automate time-consuming legal document tasks. It summarizes case files, flags important insights, and makes legal data searchable — freeing up time for more critical legal thinking.

## ✨ Features
- 📄 Upload and parse legal documents (PDFs, DOCX, scanned files)
- 🧠 Summarize contracts and court records with Azure OpenAI
- 🔍 Full-text search and intelligent auto-tagging
- ✍️ Generate draft NDAs and motion templates
- 👤 Role-based login (Admin / Paralegal)
- ☁️ CI/CD-ready and deployable to Azure

## 🧱 Tech Stack

| Layer      | Technology              |
|------------|--------------------------|
| Frontend   | Blazor                   |
| Backend    | ASP.NET Core Web API     |
| Database   | SQL Server / PostgreSQL  |
| AI/NLP     | Azure OpenAI / HuggingFace |
| OCR        | Tesseract OCR + iText7   |
| Search     | ElasticSearch or Azure Cognitive Search |
| DevOps     | GitHub Actions + Azure App Services |

## 📁 Project Structure

```bash
legalease-ai/
│
├── src/                 # All source code
│   ├── Api/             # .NET Web API project
│   ├── Frontend/        # Blazor or React frontend
│   └── Shared/          # Shared DTOs, models
│
├── data/                # Sample legal docs for development
├── docs/                # Docs, roadmap, architecture notes
├── README.md
└── .gitignore
