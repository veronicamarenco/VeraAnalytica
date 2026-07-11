# Supply Chain Data Science Portfolio
## Honest Insights for Supply Chain Leaders

Welcome(:

I build tools that solve supply chain problems. The kind that keep planners up at night, make analysts spend weekends explaining variances, and leave CFOs skeptical of ROI claims.

This portfolio includes four tools that transform those headaches into clarity.

## The Four Projects (in progress)

### 1. [From Gut Feel to Forecast Confidence](https://github.com/[yourname]/forecast-confidence)
**The demand planner's credibility problem**

Forecast misses happen. The spreadsheet has numbers, but it doesn't have answers. Was it seasonality? A promotion that didn't land? Market volatility? External shock?

This tool identifies which signals actually drive your forecast errors—and quantifies them. Turns "I don't know why we missed" into "here's exactly what happened, and here's what to tune next time."

**Impact:** If your forecast accuracy improves from 85% to 92%, that's fewer expedites, lower safety stock, and a supply chain that actually trusts the plan.

- **Built with:** Python (Prophet/ARIMA), Pandas, Plotly, Streamlit
- **Dataset:** 3 years of demand data with known seasonality, promotions, and external shocks
- **Core insight:** Signals (trend, seasonality, promo, external) aren't equal. This tool tells you which ones matter.

[→ Explore the full project](https://github.com/[yourname]/forecast-confidence)

---

### 2. [Variance Decoded: The Story Behind Your Numbers](https://github.com/[yourname]/variance-decoded)
**The analyst's explanation nightmare**

Every month: cost variance shows up. Finance asks why. You have 47 slides showing that it's complicated. They ask again. You're back to square one.

Supply chain variances are like an iceberg. Finance sees $2M. You live the complexity: Was it price? Volume? Mix shift? Supplier quality? Or a combination?

This tool segments variance automatically, flags what matters (the 20% that drives 80%), and generates the one-page story so you don't have to.

**Impact:** If your variance explanation drops from 10 hours to 1 hour, that's 36 hours/year you get back. If you prove that 60% of your variance is *mix* (actually good news) vs. 40% *price* (concerning), the conversation shifts.

- **Built with:** SQL (cost data), Python (NumPy), Plotly (waterfall charts), Jinja2 (reporting)
- **Dataset:** 12 months of GL + purchasing data across 5 product lines and 20 suppliers
- **Core insight:** Variance isn't one number. It's price × volume × mix × efficiency × quality. This tool breaks it down automatically.

[→ Explore the full project](https://github.com/[yourname]/variance-decoded)

---

### 3. [Savings Attribution Engine: Prove Your Supply Chain ROI](https://github.com/[yourname]/savings-attribution)
**The finance visibility gap**

You negotiated a better supplier contract. Your team optimized the network. Procurement got more aggressive on pricing. Finance asks: "How much of our margin improvement came from supply chain?"

You guess. They guess. $500K savings might be real or might be fiction.

This tool attributes cost reductions to their actual source: negotiation, process improvement, network optimization, quality improvement, or volume consolidation. It builds the financial case so CFOs actually believe you.

**Impact:** Supply chain improvements are invisible to finance. This tool makes them visible. $5M in provable savings beats $15M in claimed savings. Credibility = future investment.

- **Built with:** SQL (purchasing history), Python (Pandas, NumPy), Plotly (waterfall), Python-pptx (reporting)
- **Dataset:** 3-year purchasing history with known initiatives (negotiations, network changes, process improvements)
- **Core insight:** Savings don't appear magically. They come from specific levers. This tool quantifies which lever drove which savings.

[→ Explore the full project](https://github.com/[yourname]/savings-attribution)

---

### 4. [Cloud Migration Reality Check: ERP On-Prem vs. Cloud TCO](https://github.com/[yourname]/cloud-migration-tco)
**The strategic decision-maker's risk**

Your CTO says cloud saves money. Every vendor claims 30% savings. Your CFO is skeptical. Your supply chain team worries about downtime.

Nobody has a model that accounts for *your* company's specific situation. So you guess.

This tool builds a 5-year financial model: on-premise vs. cloud, for your supply chain ERP. Shows capex, opex, migration costs, downtime risk, and breaks even when. Not the vendor's model. *Your* model.

**Impact:** If your analysis shows cloud breaks even in Year 4 (not Year 2 like the vendor claimed), you have realistic expectations. If it quantifies that 3 months of migration risk costs $X, you can budget for contingency.

- **Built with:** Python (Pandas, NumPy, Scipy), Streamlit, Plotly
- **Dataset:** Hardware, software, licensing, staffing costs (5-year projection with sensitivity analysis)
- **Core insight:** Cloud isn't always cheaper. It depends on your baseline, growth rate, and risk tolerance. This tool shows your specific math.

[→ Explore the full project](https://github.com/[yourname]/cloud-migration-tco)

---

## Why These Four?

They answer the questions that actually matter:

| Question | Project | Audience |
|----------|---------|----------|
| "Why did our forecast miss?" | Forecast Confidence | Demand Planners |
| "How do we explain our cost variance?" | Variance Decoded | Supply Chain Analysts |
| "Where's the ROI from our supply chain improvements?" | Savings Attribution | CFOs |
| "Should we migrate to cloud?" | Cloud Migration TCO | CIOs / Strategic Leaders |

Together, they tell a story: **From tactical clarity → to analytical rigor → to financial visibility → to strategic confidence.**

---

## My Background

I've worked in **aerospace and semiconductors**—industries where precision matters and mistakes cost millions.

I've sent emails to 50 suppliers. I've built forecast models in Excel that took 4 hours to update manually. I've explained variances to CFOs who didn't trust the numbers. I've watched companies make infrastructure decisions on vendor claims instead of data.

**That's why I build these tools.**

I speak the language of engineers (they run on numbers), business leaders (they run on dollars), and the C-Suite (they run on credibility). I understand that supply chain is complex, messy, and *human*—but that doesn't mean insights have to be.

I'm also passionate about **data that's honest**. Not the data that tells the story you want to hear. The data that tells the story that's true. Because that's the only data worth acting on.

---

## For Luxury/Beauty, Aerospace, and Tech

**If you're in Luxury/Beauty:**
- Seasonal demand volatility kills forecasts. Project 1 helps you understand your signals.
- Supplier margins are tight. Project 3 proves where you're actually saving money.
- Sustainability is non-negotiable. Project 4 models the cost of upgrading your systems for compliance.

**If you're in Aerospace:**
- Supplier capacity planning is mission-critical. Project 1's forecast accuracy directly impacts production.
- Compliance + cost control go hand-in-hand. Project 2's variance analysis ensures you're explaining every dollar.
- Long-term contracts are complex. Project 3 proves negotiation ROI over 5+ years.

**If you're in Tech:**
- Product forecasts drive supply. Project 1 identifies the signals hidden in volatility.
- Fast-moving supply chains need real-time variance analysis. Project 2 automates the explanation.
- Unit economics matter. Project 3 quantifies supply chain ROI clearly.
- Cloud-first thinking is natural. Project 4 shows the actual financial case.

---

## Tech Stack

All four projects use a consistent, modern stack:

- **Python** (Pandas, NumPy, Scikit-learn) — data manipulation and analysis
- **SQL** (Postgres or SQLite) — querying and aggregating large datasets
- **Plotly** — interactive visualizations (better than static dashboards for insights)
- **Streamlit** — turning analyses into interactive web apps (deployed free to Streamlit Cloud)
- **Jinja2** — auto-generating reports and business cases
- **Git + GitHub** — version control and collaboration

No dependencies on expensive tools. No black boxes. Just Python, SQL, and clear thinking.

---

## How to Explore

Each project has its own GitHub repository with:

- **README** — the problem, solution, and impact
- **Notebooks** — step-by-step analysis (starting with exploration → ending with insights)
- **Source code** — production-ready Python modules
- **Streamlit app** — interactive dashboard (live demo)
- **Data** — sample datasets (synthetic but realistic)
- **Docs** — methodology and assumptions

Start with the one that resonates most. Or read them all—they build on each other.

---

## Let's Connect

I'm looking for supply chain roles in **Paris** where I can bring this combination of skills:

- Deep supply chain experience (aerospace, semiconductors, ERP systems)
- Data science fundamentals (Python, SQL, statistics, visualization)
- Business acumen (speaking to engineers, analysts, CFOs)
- Honest storytelling (data that's true, insights that matter)

**[LinkedIn]((https://www.linkedin.com/in/vmarenco1/))**]

---

## One More Thing

I feel satisfied, when a variance waterfall chart suddenly makes sense, or when a forecast accuracy model starts catching patterns a human hasn't.

Supply chain is complex. But complexity doesn't mean it has to be opaque.

These four projects are my attempt to bring clarity to the messiness.

---

*Last updated: July 2026 | Built in Paris | For supply chain leaders everywhere*
