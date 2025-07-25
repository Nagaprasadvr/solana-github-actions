# ⚙️ Solana GitHub Actions CI Template

This repository includes a **GitHub Actions CI workflow** to:

- 🔧 Build your Rust project
- 🧱 Compile Solana SBF programs
- ✅ Run Rust tests (unit + integration)
- 🧹 Run Clippy and Format checks
- ⚡ Cache dependencies for faster CI runs

---

## 📁 Setup Instructions

### 1. Create GitHub Actions Workflow File

Inside your Rust or Solana project, create the following folder and file:

```bash
mkdir -p .github/workflows
touch .github/workflows/ci.yml
```
