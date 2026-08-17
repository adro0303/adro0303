<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=2800&pause=1200&color=58A6FF&center=true&vCenter=true&width=650&lines=Software+%26+AI+Developer;Backend+systems+%E2%80%A2+ML+pipelines+%E2%80%A2+automation;Learning+by+shipping%2C+not+just+studying" alt="Typing SVG" />

# Hi, I'm Adrian 👋

**Junior Software / AI Developer who'd rather ship a rough prototype than read one more tutorial.**

I build backend systems, ML pipelines, and small tools that solve one problem well —
then push them until they actually work, not just until the demo does.

### 🌐 [Visit my portfolio / landing page →](https://landing-page-phi-one-98.vercel.app/)

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=vercel&logoColor=white)](https://landing-page-phi-one-98.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/adrianpliegoperez/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:adroplpe@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/adro0303)

</div>

<br>

<div align="center">
  <img src="assets/terminal.svg" alt="Terminal: whoami -> junior software / ai developer, ls ./projects -> ipa-builder auto_applyer quant-research, cat motto.txt -> ship it, see what breaks, fix it for real" width="100%" />
</div>

<br>

## What I build

<table>
<tr><td>🧠&nbsp;<strong>AI / ML pipelines</strong></td><td>Forecasting, anomaly detection, and applied research — built with PyTorch and scikit-learn, evaluated honestly</td></tr>
<tr><td>🔁&nbsp;<strong>Automation & tooling</strong></td><td>Python tools that replace repetitive manual work, with real safety rails instead of blind auto-pilot</td></tr>
<tr><td>⚙️&nbsp;<strong>Developer infrastructure</strong></td><td>CI/CD pipelines and small open-source tools that solve exactly one annoying problem</td></tr>
<tr><td>🧪&nbsp;<strong>Applied experiments</strong></td><td>Projects built to answer a specific question — including the ones where the answer wasn't flattering</td></tr>
</table>

<br>

## Featured projects

<table>
<tr>
<td width="50%" valign="top">

### 🚀 [ipa-builder](https://github.com/adro0303/ipa-builder)

Open-source pipeline that builds unsigned iOS `.ipa` files in the cloud — no Mac, no $99/year Apple Developer account.

**Problem:** testing your own iOS app normally means owning a Mac or paying Apple.
**Built:** a GitHub Actions workflow that spins up a macOS runner to compile any Expo/React Native project, using scoped fine-grained tokens to securely check out a *different* target repo.

`GitHub Actions` `macOS runners` `Bash / YAML` `gh CLI`

**Why it's interesting:** it's pure CI/infrastructure engineering — no app code, just a secure, reusable build pipeline solving a real cost problem.

→ [View project](https://github.com/adro0303/ipa-builder)

</td>
<td width="50%" valign="top">

### 🤖 [auto_applyer](https://github.com/adro0303/auto_applyer)

Local-first Python tool that automates job-outreach *without* turning into a spam bot.

**Problem:** manual outreach doesn't scale, but full automation is how you burn your reputation.
**Built:** a CLI + Streamlit dashboard covering lead import, draft generation, manual approval, dry-run checks, rate-limited SMTP sending, and delivery reports.

`Python` `Streamlit` `SMTP` `CLI design`

**Why it's interesting:** live sending requires `AUTO_SEND_ENABLED=true` *and* typing `SEND LIVE` — product thinking applied to a personal scripting problem.

→ [View project](https://github.com/adro0303/auto_applyer)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📈 Quant research — [macro news forecasting](https://github.com/adro0303/macro-news-market-forecasting) · [mandate investor profiling](https://github.com/adro0303/mandate-investor-profiling-fyp)

Two-part BSc final year project: can daily macro news predict next-day ETF returns, and can investor "mandates" (not just a risk score) drive better portfolio allocation?

**Built:** a PyTorch MLP vs. 5 classical baselines under strict walk-forward validation for the forecasting side; a Random Forest mandate predictor feeding a regime-aware, backtested ETF allocator on the portfolio side.

`Python` `PyTorch` `scikit-learn` `pandas`

**Why it's interesting:** both repos report the results that *didn't* work too — e.g. the Markowitz baseline beating the mandate strategy on Sharpe — instead of only showing wins.

→ [Forecasting](https://github.com/adro0303/macro-news-market-forecasting) · [Portfolio allocation](https://github.com/adro0303/mandate-investor-profiling-fyp)

</td>
<td width="50%" valign="top">

### 🔐 [AI-LogAnomalyDetectionSystem](https://github.com/adro0303/AI-LogAnomalyDetectionSystem)

Unsupervised anomaly detection over OpenSSH logs — flagging suspicious activity without labeled attack data.

**Problem:** in security logs, "normal" vastly outweighs "attack," and clean labels rarely exist.
**Built:** a config-driven pipeline (Isolation Forest, LOF, One-Class SVM) with temporal feature engineering, weak-label heuristics for evaluation, and PR-AUC/Recall@K as proxy metrics.

`Python` `scikit-learn` `Docker` `pytest` `GitHub Actions`

**Why it's interesting:** forces careful evaluation design when ground truth barely exists — accuracy alone would be meaningless here.

→ [View project](https://github.com/adro0303/AI-LogAnomalyDetectionSystem)

</td>
</tr>
</table>

<br>

## Currently building

- 🔧 Actively iterating on **[ipa-builder](https://github.com/adro0303/ipa-builder)** — my most recently pushed project, open source and open to issues/PRs
- 📊 Working through the next steps I flagged myself in the FYP repos — time-series cross-validation and better regime coverage for the portfolio backtests
- 🧰 Looking for the next small, annoying manual task worth turning into a tool — that's how `auto_applyer` started

<br>

## Tech stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**AI / Machine Learning**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

**Backend, automation & tooling**

![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![CLI](https://img.shields.io/badge/CLI%20tools-4D4D4D?style=flat-square&logo=gnubash&logoColor=white)
![YAML](https://img.shields.io/badge/YAML%20configs-CB171E?style=flat-square&logo=yaml&logoColor=white)

**CI/CD & DevOps**

![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

<sub>**Primary focus:** Python, PyTorch/scikit-learn, GitHub Actions · **Also used, smaller/earlier projects:** JavaScript, Java, C++, HTML/CSS</sub>

<br>

## Engineering mindset

- Prototype first, read the docs when it breaks — not before
- One command that runs the whole pipeline beats ten manual steps in a README
- Walk-forward validation isn't optional when the whole point is "did this actually generalize"
- If a project of mine has a `Limitations` section, I probably wrote it myself before anyone had to ask

<br>

## GitHub activity

<div align="center">
  <img src="assets/stats.svg" alt="GitHub snapshot: language breakdown and repo count" width="100%" />
</div>

<br>

## Let's connect

Open to junior backend, AI/ML, and Python engineering roles — and always up for talking about a weird technical idea.

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=vercel&logoColor=white)](https://landing-page-phi-one-98.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/adrianpliegoperez/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:adroplpe@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/adro0303)

</div>

<br>

<div align="center">
<img src="assets/plasma.svg" alt="ascii plasma easter egg" width="100%" /><br>
<sub><i>you scrolled this far — here's some ascii plasma 🌀</i></sub>
</div>
