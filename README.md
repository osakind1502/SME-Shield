
# 🛡️ SME-Shield

SME-Shield is a full-stack cybersecurity assistant platform designed to help small and medium enterprises (SMEs) monitor, assess, and improve their security posture. It combines a FastAPI backend, a modern frontend (React or Next.js), and an AI-powered assistant to deliver actionable insights and compliance support.

---

## 📦 Project Structure

SME-Shield/
├── backend/         # FastAPI backend for APIs and business logic
├── frontend/        # React or Next.js  frontend dashboard
├── ai-agent/        # AI assistant logic and prompt orchestration
├── infrastructure/  # Cloud provisioning (Azure Bicep, Terraform)
├── docs/            # Architecture diagrams and API specs
├── .env.example     # Environment variable template
├── .gitignore
├── requirements.txt
└── README.md


---

## 🚀 Features

- 🔐 **Tenant Management**: Manage SME profiles, devices, and policies
- 📊 **Risk Analysis**: Analyze telemetry and generate risk reports
- 🤖 **AI Assistant**: Natural language interface for security insights and recommendations
- ☁️ **Cloud-Ready**: Infrastructure-as-Code for Azure deployment
- 🧪 **Test Coverage**: Backend and frontend unit tests included

---

## 🧰 Tech Stack

| Layer         | Tech Stack                     |
|---------------|--------------------------------|
| Backend       | Python, FastAPI, Pydantic      |
| Frontend      | React or Next.js, TypeScript   |
| AI Assistant  | LLM Orchestration, Prompt APIs |
| Infrastructure| Azure Bicep, Terraform, Bash   |

---

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/SME-Shield.git
cd SME-Shield

# backend setup,
cd backend
python -m venv venv
.\venv\Scripts\Activate
pip install -r requirements.txt
uvicorn app.main:app --reload

# frontend setup
cd frontend
npm install
npm run dev

# Environment variables
Copy .env.example to .env and fill in your secrets.

# Deployment
Infrastructure as Code is located in the infrastructure/ folder. Use the provided scripts to deploy to Azure using Bicep or Terraform.

# Contributing
We welcome contributions! Please open issues or submit pull requests.
