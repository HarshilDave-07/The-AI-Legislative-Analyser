🏛️ AI Legislative Intelligence Platform

Last Updated: March 20, 2026

Doge is an advanced AI-driven legislative intelligence platform built to simplify how people understand complex laws and policy documents. It enables users to upload and compare different versions of legal documents and instantly receive structured insights, impact analysis, and stakeholder breakdowns.

Designed for policymakers, journalists, researchers, and informed citizens, Doge eliminates the need to manually decode dense legal text—turning hours of analysis into seconds.

✨ Overview

Modern legislation is often difficult to interpret due to its length, technical language, and constant revisions. Doge addresses this by combining artificial intelligence with intuitive design to deliver:

Clear summaries of legal changes

Side-by-side comparisons of documents

Insights into affected stakeholders

Future impact predictions based on data

⚡ Core Capabilities
📄 Smart Document Comparison

Upload two PDF versions of a bill or policy and instantly detect meaningful differences.

🧾 AI-Generated Summaries

Get concise, structured overviews of major updates with supporting references.

👥 Stakeholder Insights

Identify which groups are impacted and how, using categorized analysis.

📊 Impact Projection

Visualize short-term and long-term consequences (1-year, 3-year, 5-year outlook).

🎯 Evidence-Based Output

All insights include extracted quotes and references from the original documents.

🎨 Clean Interface

A minimal, professional UI inspired by government platforms for clarity and usability.

🧠 System Architecture

The platform is powered by a modern AI pipeline combining backend processing with intelligent analysis.

🔧 Workflow

File Upload
Users upload two PDF documents via the frontend interface.

Text Extraction
The backend processes files using PDF parsing tools to extract raw content.

AI Processing
Extracted text is analyzed using OpenAI models with structured prompts.

Structured Output
The AI returns organized JSON containing:

Key changes

Summary insights

Stakeholder effects

Policy implications

Frontend Visualization
Data is displayed through charts, timelines, and comparison views.

🛠️ Technology Stack
Backend

FastAPI (API framework)

PyPDF2 (document parsing)

OpenAI API (AI analysis)

Uvicorn (server)

Pydantic (data validation)

Frontend

Next.js + React

TypeScript

Tailwind CSS

Recharts (data visualization)

Framer Motion (animations)

React PDF (document rendering)

Axios (API communication)

Dev Tools

pnpm (package manager)

ESLint (linting)

Vercel (deployment)

🚀 Getting Started
Requirements

Node.js (v18+)

Python (3.8+)

OpenAI API key

Setup
git clone https://github.com/your-username/contest-doge.git
cd contest-doge
Install Frontend
pnpm install
Install Backend
cd backend
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
pip install -r ../requirements.txt
cd ..
Environment Variables

Create .env.local:

OPENAI_API_KEY=your_api_key_here
Run Application

Backend:

cd backend
python main.py

Frontend:

pnpm dev

Access the app at:
👉 http://localhost:3000

📁 Project Layout
contest-doge/
├── app/                # Frontend (Next.js)
├── backend/            # FastAPI server
├── components/         # UI components
├── lib/                # Utility functions
├── public/             # Static assets
└── requirements.txt    # Backend dependencies
🔌 API Routes
Backend

GET / → Basic health check

GET /health → System + AI status

POST /api/compare → Document comparison

POST /api/test-pdf → PDF extraction test

Frontend

/api/compare → Proxy endpoint

/api/healthz → Frontend status

/api/test-pdf → Testing endpoint

🎨 Interface Modules

File Upload & Processing

AI Summary Dashboard

Stakeholder Visualization Charts

Timeline Impact Forecast

Side-by-Side Document Viewer

Interactive Data Cards

🔐 Security & Privacy

No file storage (processed in-memory)

HTTPS-secured communication

No user tracking or analytics

Server-side API handling for security

🤝 Contributing
 
Contributions are welcome:

git checkout -b feature/your-feature
git commit -m "Add feature"
git push origin feature/your-feature

Then open a Pull Request.

📜 License

This project is licensed under the MIT License.


Doge aims to democratize access to legislative understanding by making complex policies transparent, interactive, and accessible to everyone—from experts to everyday citizens.
