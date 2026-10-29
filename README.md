# NM1130 – AI & Digital Skills | Learning Portfolio

**University College of Engineering (BIT Campus), Anna University, Tiruchirappalli**
Department of CSE (AI & ML) | Academic Year 2026-2027 | Semester III

This repository is a learning portfolio for the NM1130 AI and Digital Skills experiments. It brings together eight Python programs, supporting datasets, and generated visual outputs.
Each program demonstrates a practical concept and prints a clear result when run.

## Experiments

| Ex.No | Experiment | Program | What it demonstrates |
|------:|------------|---------|----------------------|
| 1 | AI Fluency | [`01.ai_fluency.py`](01.ai_fluency.py) | AI timeline, classification, regression, clustering, optimization, neural network, NLP sentiment analysis |
| 2 | AI Productivity | [`02.ai_productivity.py`](02.ai_productivity.py) | Copilot-style assistant: email drafting, summaries, action items, proposals, sales insights (optional real LLM call) |
| 3 | AI Applications | [`03.ai_applications.py`](03.ai_applications.py) | Healthcare, banking fraud detection, recommendation engine, agriculture yield prediction |
| 4 | LinkedIn: Building Your Professional Brand | [`04.linkedin_profile_analyzer.py`](04.linkedin_profile_analyzer.py) | Profile scoring, common-mistake detection, headline generator, before/after chart |
| 5 | Cybersecurity | [`05.cybersecurity_toolkit.py`](05.cybersecurity_toolkit.py) | Password strength, secure generator, salted hashing, phishing URL detector, 2FA (TOTP), data integrity |
| 6 | GitHub Foundations | [`06.mini_git.py`](06.mini_git.py) | Mini Git: commit, branch, merge, conflict, clone, push, pull request, review |
| 7 | Power BI | [`07.power_bi_dashboard.py`](07.power_bi_dashboard.py) | Get data, clean (Power Query), KPIs (DAX), dashboard image, CSV export for Power BI Desktop |
| 8 | Career Essentials | [`08.career_essentials.py`](08.career_essentials.py) | Skill self-assessment, gap analysis, radar chart, SMART goals, Eisenhower matrix |

## How to run

```bash
# 1. (optional) create a virtual environment
python -m venv .venv
.venv\Scripts\activate        # Windows
source .venv/bin/activate     # macOS / Linux

# 2. install the libraries
pip install -r requirements.txt

# 3. run any experiment
python 01.ai_fluency.py
python 08.career_essentials.py --interactive
```

Requires Python 3.10 or newer. Experiments 2, 5 and 6 need no extra libraries.
Supporting images and CSV files are included in the repository root. When you run the dashboard or visualization programs, check the program output for the location where generated files are saved.

## Output files

- `04.profile_improvement.png`
- `07.sales_dashboard.png`, `07.sales_clean.csv` (import the cleaned CSV into Power BI Desktop)
- `08.career_skills_radar.png`
