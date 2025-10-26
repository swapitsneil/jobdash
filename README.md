# jobdash - AI Job Market Dashboard  
*10 Real-World Business Problems Solved with Python*  

---

## Project Overview  
**Analyze 15,000+ AI job postings** to uncover **salary trends, top skills, remote work**, and more!  
Built for **beginners** using **pandas + matplotlib** — **clean, simple, job-ready code**  

---

## Dataset (`ai_job_dataset.csv`)  
| Column | Meaning |
|--------|--------|
| `job_id` | Unique ID |
| `job_title` | Role name |
| `salary_usd` | Salary in USD |
| `experience_level` | EN, MI, SE, EX |
| `company_size` | S, M, L |
| `remote_ratio` | 0%, 50%, 100% |
| `required_skills` | Comma-separated list |
| `posting_date` | When job was posted |

---

## 10 Business Problems Solved  

| # | Problem | Key Insight |
|---|--------|-----------|
| 1 | **Average Salary by Experience** | EX: **$180K** |
| 2 | **Top 5 Highest-Paying Roles** | ML Engineer: **$160K** |
| 3 | **Salary by Company Size** | Large (L): **$110K** |
| 4 | **Which Company Size Pays Most?** | **L > M > S** |
| 5 | **Experience vs Salary Correlation** | **r = 0.69** (Strong) |
| 6 | **Remote Work Distribution** | **37% on-site, 34% full remote** |
| 7 | **Top 5 Industries by Benefits** | Consulting: **8.1/10** |
| 8 | **Top 10 Industries by Jobs** | Finance: **10 jobs** |
| 9 | **Salary by Education** | Associate: **$115K** |
| 10| **Job Postings by Month** | **June & August** peak |

---

## Tools Used  
- `pandas` – Data cleaning & analysis  
- `matplotlib` – Simple charts  
- `numpy` – Math & stats  

---

## How to Run  
```bash
# 1. Install
pip install pandas matplotlib

# 2. Run in Jupyter or .py file
python ai_jobs_analysis.py
