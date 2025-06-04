# Marketing-GPT
Marketing Assistant

# 💡 Fintech Performance Marketing GPT

This is a Streamlit-based AI assistant designed to support performance marketing in the **B2C financial sector**. It uses OpenAI's GPT-4 and integrates with the Meta Ads API to generate ad copy, analyze campaigns, and suggest optimizations.

---

## 🚀 Features

- ✍️ Generate compliant and high-performing ad copy (Google, Meta, LinkedIn)
- 📊 Analyze Meta Ads campaign data in real-time
- 🧠 Get GPT-generated insights on performance, creatives, and budget reallocations
- 🔐 Designed with financial compliance and user intent in mind

---

## 📦 What's Inside

| File | Description |
|------|-------------|
| `streamlit_meta_gpt_app.py` | Main Streamlit app with Meta Ads + GPT integration |
| `app.py` | Ad copy generator via prompt input |
| `budget_function_calling.py` | Function-calling example with GPT-4 |
| `meta_ads_api_integration.py` | Script to fetch Meta Ads data via API |
| `.gitignore` | Excludes local secrets and cache |
| `requirements.txt` | Dependencies for deployment |
| `deployment_checklist.md` | Step-by-step setup guide for deployment |

---

## 🛠️ Setup

### 1. Install Dependencies
```bash
pip install -r requirements.txt
```

### 2. Add Secrets (Local)
Create a file at `.streamlit/secrets.toml`:
```toml
OPENAI_API_KEY = "your-openai-key"
META_ACCESS_TOKEN = "your-meta-token"
META_AD_ACCOUNT_ID = "act_your-account-id"
```

---

## ☁️ Deploy on Streamlit Cloud

1. Push this repo to GitHub
2. Go to [streamlit.io/cloud](https://streamlit.io/cloud) → New App
3. Select `streamlit_meta_gpt_app.py` as the main file
4. Paste your API keys into the **Secrets** section
5. Deploy and share the link!

---

## 📬 Questions?

Open an issue or email your marketing AI partner. Happy optimizing!
"""

# Write README.md
readme_path = output_dir / "README.md"
readme_path.write_text(readme_md.strip())

readme_path.name