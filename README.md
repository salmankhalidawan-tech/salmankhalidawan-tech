<div align="center">

```
┌──────────────────────────┐
│   ⚡ WEBHOOK TRIGGER       │
│   event: "new_visitor"    │
└─────────────┬────────────┘
              │
              ▼
┌──────────────────────────┐
│   🔍 IF: curious_about    │
│   ("agentic systems")     │
└──────────┬───────────────┘
      true │
              ▼
┌──────────────────────────┐
│   📄 Set: load_profile    │
│   node_id: salman-002     │
└──────────┬───────────────┘
              │
              ▼
       keep scrolling ↓
```

# workflow: salman_khalid_awan.json
### `status: active` · `last_execution: success` · `retries: 0`

</div>

<br>

## 🧾 Execution Log

```log
[08:41:02] TRIGGER   → visitor arrived at profile
[08:41:02] NODE      → resolve(identity)
[08:41:02] RETURN    → { role: "AI Automation Intern @ Tech Buzz",
                          degree: "BSCS, Lahore Garrison University",
                          gpa: 3.75, note: "High Achievers List" }
[08:41:03] NODE      → resolve(current_obsession)
[08:41:03] RETURN    → "the unglamorous plumbing that makes automation
                          trustworthy — retries, conditional routing,
                          human-in-the-loop approval"
```

I don't just call APIs — I wire them into pipelines that keep running after I close the laptop. Most of my "work" is invisible: a webhook fires, an agent classifies something, a doc gets written, a Slack message lands, and nobody had to click a button.

<br>

## 🗂️ Node Inspector

*(click a node to expand its config — this is how I actually think about my own history)*

<details>
<summary><b>🎓 Node: Education</b> <code>type: trigger</code></summary>
<br>

```json
{
  "institution": "Lahore Garrison University",
  "program": "BSCS — 3rd Year",
  "gpa": "3.75 / 4.0",
  "recognition": "High Achievers List",
  "teaching_experience": [
    "Senior CS Lecturer",
    "CS Teacher"
  ]
}
```
</details>

<details>
<summary><b>🧬 Node: Research — GenEdge</b> <code>type: multi-agent pipeline</code></summary>
<br>

```json
{
  "framework": "CrewAI",
  "problem": "bias detection & debiasing across ML fairness datasets",
  "agents": 6,
  "datasets_tested": 4,
  "result": "full Disparate Impact parity on 3/4 datasets",
  "recognition": "selected from 305+ submissions — IEEE IES GenAI Challenge 2026",
  "publication": "accepted @ IRAI 2026, Melbourne"
}
```
</details>

<details>
<summary><b>⚙️ Node: Tech Buzz — AI Automation Intern</b> <code>type: production workflow</code></summary>
<br>

```json
{
  "stack": ["n8n", "Groq", "Google Drive", "Google Docs", "Slack", "Gmail"],
  "shipped": [
    "Gmail organiser — nested label routing + AI classification",
    "Slack task tracker — multi-assignee enforcement, daily report",
    "AI Data Analyst — Stats/Trend/RootCause/Forecast agents → PDF via QuickChart",
    "Website scraper → structured Google Docs output",
    "SEO keyword engine — auto-drafts articles to Docs",
    "YouTube Shorts agent — Groq + Pollinations + ElevenLabs + FFmpeg",
    "WhatsApp FAQ bot — Twilio + Supabase + Groq, RAG-backed"
  ],
  "in_progress": "client onboarding automation — Groq → Trello → Drive → Docs → Slack → Gmail",
  "documentation": "one build logged per session — 'Day X of my AI Automation Internship'"
}
```
</details>

<details>
<summary><b>🧩 Node: Independent Builds</b> <code>type: parallel branch</code></summary>
<br>

```json
[
  {
    "name": "NLP Resume Screener",
    "stack": ["FastAPI", "PostgreSQL", "Scikit-learn", "Docker"],
    "method": "TF-IDF + Cosine Similarity ranking"
  },
  {
    "name": "Heart Disease Prediction Dashboard",
    "stack": ["Python", "Scikit-learn"]
  },
  {
    "name": "MindTrace",
    "type": "AI journaling app",
    "output": "ML-based recommendations from user activity patterns"
  }
]
```
</details>

<br>

## 🔐 .env

```bash
LANGUAGES=Python,JavaScript,SQL,C++
AGENTIC=CrewAI,LangChain
AUTOMATION=n8n,Zapier,GoHighLevel
BACKEND=FastAPI,PostgreSQL,MySQL
ML=Scikit-learn,Pandas,NumPy
DEVOPS=Docker,Git,AWS
CURRENT_FOCUS="agentic workflows that replace manual, repetitive work"
```

<br>

## ♻️ Error Handling & Retry Policy

> This is genuinely how I approach both automations *and* my own career.

```yaml
on_error: retry
max_retries: 3
backoff: exponential
fallback: human_in_the_loop
philosophy: >
  A workflow that only works on the happy path isn't a workflow —
  it's a demo. I build for the retry, the timeout, the malformed
  webhook payload. Same applies to internships, interviews,
  and research submissions: I don't archive the failed run,
  I reroute it.
```

<sub>case in point: an assessment platform failed mid-attempt during a remote internship process — I documented it, escalated it, and moved on to the next node instead of stalling the pipeline.</sub>

<br>

## 📊 Response Body — GitHub Stats API

<div align="center">
<img src="https://github-readme-stats-iota-murex-54.vercel.app/api?username=salmankhalidawan-tech&show_icons=true&hide_border=true&theme=default" height="160"/>
<img src="https://github-readme-stats-iota-murex-54.vercel.app/api/top-langs/?username=salmankhalidawan-tech&layout=compact&hide_border=true&theme=default" height="160"/>
</div>

<div align="center">
<img src="https://github-readme-streak-stats.herokuapp.com/?user=salmankhalidawan-tech&hide_border=true&theme=default" height="160"/>
</div>

<br>

## 📦 Installed Packages (Certifications)

| package | source |
|---|---|
| `agent-skills-with-anthropic` | DeepLearning.AI |
| `chatgpt-prompt-engineering` | DeepLearning.AI |
| `programming-in-python` | Meta / Coursera |
| `data-quality-governance` | Udemy — MFT Institute |

<br>

## 📡 Webhook Response — Let's Connect

```json
{
  "status": 200,
  "open_to": ["AI Automation", "Agentic AI", "Applied ML"],
  "contact": {
    "email": "salmanawanlgu@gmail.com",
    "linkedin": "linkedin.com/in/salmankhalidd",
    "github": "github.com/salmankhalidawan-tech",
    "portfolio": "salmankhalidawan-tech.github.io"
  },
  "note": "if it involves wiring LLMs into something that actually runs unattended, send the payload."
}
```

<div align="center">
<sub>workflow executed successfully · 0 errors · 1 new connection pending</sub>
</div>
