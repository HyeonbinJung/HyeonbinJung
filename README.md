<h1 align="center">Hyeonbin Jung</h1>

<p align="center">
  <b>Computer Science & Mathematics @ Columbia University</b><br>
  Machine learning for finance · Quantitative research · Software engineering<br>
  Founder, <a href="https://extriver.com">Extriver Partners</a>
</p>

<p align="center">
  <a href="mailto:hj2784@columbia.edu"><img src="https://img.shields.io/badge/Email-hj2784%40columbia.edu-B31B1B?style=flat-square&logo=gmail&logoColor=white"></a>
  <a href="https://hyeonbin.dev"><img src="https://img.shields.io/badge/Website-hyeonbin.dev-000000?style=flat-square&logo=googlechrome&logoColor=white"></a>
  <a href="https://extriver.com"><img src="https://img.shields.io/badge/Extriver-extriver.com-1F2937?style=flat-square"></a>
</p>

---

## 💻 Languages

What I write most, measured across all of my public repositories (bytes of code):

| Language | Share | |
|---|---:|---|
| ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white) | **53.6%** | `██████████▋` |
| ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) | 13.5% | `██▋` |
| ![Racket](https://img.shields.io/badge/Racket-9F1D20?style=flat-square&logo=racket&logoColor=white) | 10.8% | `██▏` |
| ![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=css3&logoColor=white) ![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white) | 10.0% | `██` |
| ![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white) | 6.2% | `█▏` |
| ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) | 3.2% | `▋` |
| ![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black) | 2.4% | `▍` |

Also: ![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white) ![Shell](https://img.shields.io/badge/Shell-121011?style=flat-square&logo=gnubash&logoColor=white)

---

## 🧠 Machine Learning & Data

**Modeling**
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![statsmodels](https://img.shields.io/badge/statsmodels-4051B5?style=flat-square)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square)

- Regularized regression (Ridge / Elastic Net with CV), linear & polynomial regression, `Pipeline` + `StandardScaler` workflows
- Time-aware train/test splits (chronological training, out-of-period testing) to avoid look-ahead bias
- Statistical testing & curve fitting — OLS (`statsmodels`), Spearman / Pearson correlation, `scipy.optimize`
- Factor models & alternative data — K-Food consumption signals as an equity factor, multi-factor strategy fitting and backtesting

**LLMs & AI systems**
![Llama 3](https://img.shields.io/badge/Llama%203-0467DF?style=flat-square&logo=meta&logoColor=white)
![DigitalOcean Gradient AI](https://img.shields.io/badge/DigitalOcean%20Gradient%20AI-0080FF?style=flat-square&logo=digitalocean&logoColor=white)
— real-time anomaly detection and incident summaries over streaming logs (InsightStream)

**Financial data**
SEC Company Facts / XBRL · Capital IQ · yfinance · Excel modeling automated with `xlwings` / `openpyxl`

**MLOps, data & infrastructure**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare%20R2-F38020?style=flat-square&logo=cloudflare&logoColor=white)

**Application stack**
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=flat-square&logo=socketdotio&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)

**Finance**
DCF / FCFF · public comps · 3-statement & LBO modeling · M&A diligence · EV-to-equity bridges

---

## 🚀 Selected Projects

| Project | What it does | Stack |
|---|---|---|
| [**Automated-DCF-ML**](https://github.com/HyeonbinJung/Automated-DCF-ML) | Engineers SEC Company Facts / XBRL data and fits **Ridge & Elastic Net** forecasts for six value drivers (revenue growth, EBIT margin, tax, D&A, CapEx, NWC intensity); converts them to NOPAT and FCFF, then a DCF to enterprise / equity value and fair value per share. Chronological training (through 2018) and testing (2022+). | Python · scikit-learn · SciPy |
| [**Consumption-to-Alpha**](https://github.com/HyeonbinJung/Consumption-to-Alpha-A-U.S.-K-Food-Alternative-Data-Factor-Model) | U.S. K-Food alternative-data factor model — tests consumption signals as an equity return factor. | Python · statsmodels · SciPy |
| [**InsightStream**](https://github.com/HyeonbinJung/InsightStream) ⭐ | DigitalOcean Gradient™ AI Hackathon — AI observability platform that streams logs through Kafka and uses Llama 3 to detect anomalies and summarize incidents in real time. | Kotlin · Spring Boot · Kafka · Next.js |
| [**Quant-Research-Backtesting-Platform**](https://github.com/HyeonbinJung/Quant-Research-Backtesting-Platform) | MLOps-style research platform on Kubernetes: data collectors, a factor engine on PostgreSQL, strategy fitting / backtesting and a model-serving API. | Kubernetes · PostgreSQL · Python |
| [**Quant-Strategy**](https://github.com/HyeonbinJung/Quant-Strategy) · [**Investment-helper**](https://github.com/HyeonbinJung/Investment-helper) | Basic systematic trading strategies; short-term price prediction and buy / sell timing. | Python · pandas · yfinance |
| [**Extriver Partners**](https://extriver.com) | Product & business modeling — creator audience geography, engagement and sector demand to evaluate vertical-software concepts; subscription, conversion and revenue-share scenarios; internal partner pipeline and research-to-execution workspace. Distribution tested through an owned short-form account (**70K followers, 20M peak views, ~1M average views / video**). | Node.js · Socket.io · Cloudflare R2 |

---

## 💼 Experience

**Data Science Intern** — [Paratus Investment](https://www.paratusinvestment.com/) · Seoul · *Feb 2025 – Aug 2025*
- Screened 24 private-company targets using Capital IQ and 160+ listed peers; built LTM / NTM EV/Revenue, EV/EBITDA and P/E comp sets with growth, margin and size adjustments
- Automated peer selection, multiple refreshes and EV-to-equity bridges in Excel / xlwings / Python — **~40% fewer manual model updates**
- Built five-year FCFF / DCF cases with WACC, terminal-growth and exit-multiple methods; analyzed revenue, EBIT margin, CapEx and NWC sensitivities for transaction pricing

**Growth Capital Intern** — [Yuanta Investment](http://yuantainvest.com/) · Seoul · *Oct 2024 – Feb 2025*
- Valued private companies using 10–15 relevant public peers, normalized EBITDA and trading multiples; supported valuation exhibits and investment committee (IC) reports
- Built operating and LBO models for prospective investments, stress-testing entry / exit EV/EBITDA, debt paydown, leverage and sponsor IRR / MOIC under base and downside cases
- Assessed Sunbo Industrial bolt-on targets, pro forma EBITDA and synergies; automated daily deal / industry news clipping and EML-based macro signals for portfolio review

**FA Deal Advisory Intern** — [Deloitte Korea](https://www.deloitte.com/kr/ko.html) · Seoul · *Jan 2023 – Feb 2023*
- Supported buy-side medical-device M&A diligence, analyzing revenue concentration, normalized EBITDA, working-capital movement and cash-flow conversion
- Prepared peer screening and target comparisons; identified acquisition candidates with potential commercial synergies, financial risks and integration considerations

**Research Assistant** — [Paratus Investment](https://www.paratusinvestment.com/) · Seoul · *Jun 2022 – Sep 2022*
- Built manufacturing-sector DCF models linking volume, pricing, margins, CapEx and NWC to FCFF, discounted terminal value and implied equity value
- Standardized Excel valuation templates and automated research / market-news collection to update peer multiples, assumptions and deal-monitoring inputs

---

## 🎓 Education

**[Columbia University](https://www.columbia.edu/)** — New York, NY · *2026 – Present*
Bachelor of Computer Science – Mathematics
Relevant coursework: Calculus 3, Applied Statistical Computing

**[University of Waterloo](https://cs.uwaterloo.ca)** — *Cheriton School of Computer Science* · Ontario, Canada · *Sep 2024 – Sep 2026*
Bachelor of Computer Science
Relevant coursework: Honors Calculus, Algebra, Algorithms, Data Abstraction
Combined GPA 3.53 / 4.00 (self-calculated) · External coursework: 19 credits (UMass Global 13, BYU 6)
