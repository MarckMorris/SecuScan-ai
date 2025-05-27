# 🛡️ SecuScan AI

**SecuScan AI** is an AI-powered SaaS platform for automated security scanning of web and mobile applications.  
It integrates industry-standard tools like OWASP ZAP and AI/LLM models to detect vulnerabilities before attackers do.

---

## 📦 Monorepo Structure

secuscan-ai/
│
├── backend/ → FastAPI application (API & logic)
├── frontend/ → Web dashboard built with Next.js
├── engine/ → Security scanning scripts (ZAP CLI, LLM models)
├── infrastructure/ → Terraform scripts for GCP deployment
├── .github/workflows/ → CI/CD pipelines (GitHub Actions)
└── README.md


---

## 🚀 Roadmap (Beta Release)

- [x] Setup monorepo structure
- [ ] Build FastAPI backend
- [ ] Connect to PostgreSQL
- [ ] Integrate ZAP + AI engine
- [ ] Build frontend dashboard (Next.js)
- [ ] Deploy to GCP (Cloud Run + Terraform)
