# 🚀 Project Remote 50 LPA+ — Career Growth Plan

A structured **8-week roadmap** to achieve a **Remote Senior Data Engineer** offer worth **₹50–60 LPA**.  
This repository helps me plan, act, and reflect systematically using Markdown-based tracking.

---

## 🎯 Objective

| Item | Detail |
|------|---------|
| 🧭 Goal | Land a Remote Senior Data Engineer role |
| 💰 Target CTC | ₹50–60 LPA (Current: ₹37 LPA) |
| ⏱ Duration | 2 months |
| 🎓 Focus | Consistent daily output, strong portfolio, confident interviews |

---

## 🗓️ Detailed 8-Week Action Plan

### **Month 1 — Preparation and Positioning**
| Week | Theme | Deliverables | Metrics of Success |
|------|--------|--------------|--------------------|
| **Week 1:** Resume + LinkedIn Revamp | - ATS-ready resume<br>- New LinkedIn headline, summary, and featured projects | Recruiter response rate > 20% |
| **Week 2:** Airflow + BigQuery Deep Dive | - Create end-to-end ETL DAG<br>- Document GCP project in GitHub | Portfolio project live |
| **Week 3:** Dataflow / Beam & GCS Integration | - Build streaming job (Pub/Sub + Beam)<br>- Explore watermarking | Working streaming pipeline |
| **Week 4:** Outreach & Branding | - Send 20 applications<br>- Message 10 recruiters | 3–5 recruiter responses |

### **Month 2 — Execution and Negotiation**
| Week | Theme | Deliverables | Metrics of Success |
|------|--------|--------------|--------------------|
| **Week 5:** Mock Interviews & Real Screens | - SQL, Airflow, GCP mock tests<br>- Record 2 mocks | At least 1 live interview |
| **Week 6:** System Design + Behavioral Mastery | - STAR story refinement<br>- System design whiteboard practice | 2 advanced interviews |
| **Week 7:** Offer Negotiation Prep | - Salary benchmark sheet<br>- Counteroffer scripts | Compensation discussions started |
| **Week 8:** Offer Closure & Transition Plan | - Offer evaluation sheet<br>- Resignation plan | Offer accepted |

---

## 🔧 Core Skill Focus

| Area | Topics |
|------|---------|
| **SQL** | Window functions, query tuning, CTEs, partition pruning |
| **Airflow** | Idempotency, retries, sensors, datasets, testing |
| **BigQuery** | Clustering, MVs, cost optimization |
| **Beam / Dataflow** | Streaming, late data, watermark handling |
| **Cloud Infra** | IAM, Terraform, CMEK, VPC-SC |
| **Communication** | STAR storytelling, docs, stakeholder clarity |

---

## 🧠 Folder Overview

| Folder | Purpose |
|---------|----------|
| `/tracker/` | Log all applications or link a Google Sheet |
| `/interview_experiences/` | Add one file per interview experience |
| `/learnings/daily_learnings/` | Add daily notes (e.g. `2025-11-03.md`) |
| `/learnings/common_learnings/` | Add reusable concepts (e.g. `airflow_tips.md`) |

---

## 🕘 Daily Workflow

**Morning (9 AM)**  
- Review yesterday’s learnings  
- Write 2–3 focus tasks in today’s file under `/learnings/daily_learnings/`  

**Evening (9:30 PM)**  
- Check ✅ completed tasks  
- Summarize learnings and blockers  
- Update `/tracker/applications_template.md`  
- If interviewed → log in `/interview_experiences/`  

---

## 📈 Weekly Review (Sunday 7 PM IST)

**Review:**  
- Number of applications and replies  
- Interview rounds cleared  
- Top 3 learnings / blockers  
- Adjust focus for next week  

**Template:**
```
### Week X Summary
✅ Highlights:
- ...
📊 Metrics:
- Applications: ...
- Responses: ...
- Interviews: ...
💡 Learnings:
- ...
🎯 Focus Next Week:
- ...
```

---

## 🧩 Templates

### 🧠 Daily Learning Template
```
# YYYY-MM-DD — Daily Learnings
**Focus:** [SQL / Airflow / Interview / Outreach]

### ✅ What I Worked On
- …

### 💡 Learnings
- …

### ⚙️ Blockers
- …

### 🎯 Next Focus
- …
```

### 💬 Interview Experience Template
```
# Company — Role — Date
**Round Type:** [Technical / Managerial / HR]  
**Duration:** 45 min  
**Panel:** [Name / Role]  

## 🔍 Questions Asked
- …

## ✅ What Went Well
- …

## ⚠️ What Could Improve
- …

## 💡 Key Takeaways
- …
```

### 🗂️ Common Learning Template
```
# Topic — e.g. Airflow Reliability

### 🧩 Key Concepts
- Idempotent DAGs
- Retries & Backfill strategy
- Deferrable operators

### 💡 Code Snippet
```python
@task(retries=3, retry_delay=timedelta(minutes=5))
def load_data():
    ...
```

### 📘 Notes
- Use catchup=False unless backfill required.
- Prefer deferrable sensors for long waits.
```

---

## 📊 Tracker (inside `/tracker/`)

Keep this Markdown table updated or link your Google Sheet:

```markdown
# Applications Tracker
👉 [Google Sheet Tracker](https://docs.google.com/spreadsheets/d/your_google_sheet_id_here/edit?usp=sharing)

| Date | Company | Role | Source | Type | Status | Next Step | Notes |
|------|----------|------|--------|------|--------|-----------|-------|
| 2025-10-31 | Fintorch | Sr Data Engineer | LinkedIn | Remote | Applied | Await recruiter screen | Shared Beam repo |
| 2025-11-02 | Acme GCC | Sr DE | Referral | Remote | Tech 1 Passed | Prepare System Design | Follow-up mail sent |
```

---

## 🧭 How to Use

1️⃣ Clone / download repo  
2️⃣ Edit `README.md` for your personal start date and goals  
3️⃣ Add one daily file to `/learnings/daily_learnings/` each day  
4️⃣ Add one interview file to `/interview_experiences/` after every round  
5️⃣ Update `/tracker/` as progress evolves  

**Commit daily:**
```bash
git add .
git commit -m "Daily update — YYYY-MM-DD"
git push
```

---

## 🧾 Notes

- Consistency beats perfection — update something daily.  
- Archive older content monthly into `/archive/` if needed.  
- Keep Google Sheet + repo in sync weekly.  

---

**Author:** Harshavardhan Raja  
Cloud & Data Engineer · IIT Guwahati  
[LinkedIn](https://www.linkedin.com/in/harshavardhan-raja) · [GitHub](https://github.com/HarshavardhanRaja)
