
# Supply Chain Data Science Portfolio
## Honest Insights for Supply Chain Leaders

Welcome(:

I build tools that solve supply chain problems. The kind that keep planners up at night, make analysts spend weekends explaining variances, and leave CFOs skeptical of ROI claims.

This portfolio includes three tools that removes headaches to reveal clarity.

---

## The Three Projects

### 1. [From Gut Feel to Forecast Confidence](https://github.com/[yourname]/forecast-confidence-luxury)
**Luxury & Beauty: Demand Planning for Hermès, Dior, LVMH**

Luxury demand isn't rational. It's driven by psychology: scarcity, celebrity endorsement, trend velocity, and the seasonal emotional spending patterns of wealth.

Q4 spikes 300% (holiday gifting). A new celebrity posts a Hermès Birkin on Instagram and demand jumps 40%. Fashion weeks shift collections. Summer vacations drop demand 60%. Your spreadsheet-based forecast can't capture any of this.

This tool identifies which signals actually drive luxury demand—trend shifts from fashion events, scarcity effects from waitlists, external signals from influencers and luxury indices—and quantifies them. Turns guessing into signal detection.

**Impact:** If you can predict a fashion trend 4 weeks early instead of 4 weeks late, you stock the right items before competitors do. That's margin protection.

- **Built with:** Python (Prophet for seasonality), Pandas, Plotly (interactive confidence bands), Streamlit
- **Dataset:** 4 years of Hermès Birkin/Kelly sales across leather types, colors, regions, with known trend shifts (celebrity moments, fashion weeks, virality)
- **Insight:** Luxury demand is driven by psychology and scarcity, not logic. This tool identifies trend breaks (structural shifts vs. seasonal noise) so you can react fast.

[→ Explore the full project](https://github.com/[yourname]/forecast-confidence-luxury)

---

### 2. [Variance Decoded: The Story Behind Your Numbers](https://github.com/[yourname]/variance-decoded-aerospace)
**Aerospace & Defense: Cost Variance Analysis for Boeing, Airbus, Raytheon**

Your company ordered $500M of materials. Actual cost: $525M. Variance: $25M unfavorable.

Finance presents to the board: "We overspent by 5%."

But supply chain knows the real story: Titanium prices surged 30% (market, not your fault). A critical supplier quality failure required rework and alternate sourcing—$5M that prevented aircraft delivery delays worth $50M+. You expedited 200 shipments to manage supply delays—$8M that prevented production stoppage. You negotiated new contracts and saved $12M.

Finance sees overspend. Supply chain managed a crisis. Nobody knows how to tell that story.

This tool segments aerospace cost variance automatically into price, volume, mix, quality, expedite, and efficiency components—then tells the real story. "Here's what was bad. Here's what was good risk management. Here's what was unavoidable market conditions. Here's what was smart spending."

**Impact:** Your CFO stops looking incompetent to the board. Supply chain gets credit for risk management, not blame for overspending. Credibility for future supply chain investments increases.

- **Built with:** SQL (purchase orders, quality records, expedite logs), Python (Pandas, NumPy), Plotly (waterfall charts), Jinja2 + Python-pptx (auto-generate board decks)
- **Dataset:** $500M annual procurement across 50 suppliers, 10,000+ line items, with known cost drivers (commodity surges, quality escapes, expedites, negotiations)
- **Core insight:** In aerospace, cost variance isn't a problem—it's a safety/schedule/quality story. This tool proves that "overspending" actually prevented $50M+ in delays.

[→ Explore the full project](https://github.com/[yourname]/variance-decoded-aerospace)

---

### 3. [Supply Chain ROI Reality](https://github.com/[yourname]/supply-chain-roi-reality-tech)
**Tech (Google, Apple, Microsoft): Cloud Modernization ROI for Scale**

Your legacy ERP is 12 years old. Demand planning is Excel + Python scripts. Variance analysis is quarterly PDF reports. Your supplier portal is 1990s web interface.

Your CIO says: "We need to modernize. Cloud, AI/ML, real-time visibility."

Your CFO says: "Show me the ROI. This costs $50M. What do we get?"

Your supply chain director says: "If we're investing, let's make sure we actually unlock the $130M/year in improvements we claim."

Nobody has a model that connects all three perspectives. So the CIO and CFO are misaligned. The board is skeptical. The decision gets postponed.

This tool builds a unified financial model that answers: **"Should we modernize? When do we break even? What are the real risks?"**

It shows CFOs the ROI (payback in 3 months, NPV $485M over 5 years). It shows CIOs the execution risks (30% chance of 3-month delay, 20% chance of adoption resistance). It shows supply chain directors which improvements matter most (forecast accuracy, supplier performance, network optimization).

**Impact:** CFO and CIO align on numbers. Board approves $50M investment. Supply chain modernizes with confidence, not debate.

- **Built with:** Python (NumPy for financial modeling, Monte Carlo for risk simulation), Pandas (scenario building), Plotly (waterfall for costs, timeline for payback), Streamlit (CFO view + CIO view + Board view)
- **Dataset:** Realistic Google/Apple/Microsoft scenario—$50B procurement budget, 5,000+ suppliers, 50+ data centers, with conservative/base/aggressive benefit scenarios
- **Core insight:** Cloud supply chain modernization ROI is guaranteed (even pessimistic scenario breaks even in Year 2). The real risk is execution, not financial risk.

[→ Explore the full project](https://github.com/[yourname]/supply-chain-roi-reality-tech)

---

## Why These Three?

Each addresses a different industry and audience:

| Project | Industry | Problem | Audience | Core Insight |
|---------|----------|---------|----------|--------------|
| **Forecast Confidence** | Luxury & Beauty | Demand driven by psychology, not seasonality | Demand Planners | Scarcity and trend velocity drive luxury demand—not rational forecasting |
| **Variance Decoded** | Aerospace & Defense | Cost variance hides risk management and good decisions | Supply Chain Leaders + CFO | Variance tells a safety/quality/schedule story, not just budget story |
| **Supply Chain ROI Reality** | Tech | Modernization debate stalls without unified financial model | CFO + CIO + Supply Chain | Investment ROI is guaranteed. The question is execution risk. |

Together, they show progression: **From understanding your customer's psychology → to explaining supply chain complexity → to enabling strategic modernization.**

---

## My Background

I've worked across **aerospace, sustainability and semiconductor**—industries where supply chain decisions directly impact margin, safety, and competitive advantage.

I've watched planners miss builds because their models treated weren't rigourous enough to factor in more than 1 or 2 variables at a time. I've seen aerospace supply chain leaders struggle to explain $25M cost variances to skeptical CFOs. I've watched tech companies debate whether $50M supply chain modernization is worth the investment—without a unified financial model.

**That's why I build these tools.**

I speak the language of engineers (they run on numbers), business leaders (they run on dollars), and the C-Suite (they run on credibility). I understand that supply chain is complex, messy, and *human*—but that doesn't mean insights have to be.

I'm passionate about **data that's honest**. Not the data that tells the story you want to hear. The data that tells the story that's actually true. Because that's the only data worth acting on.

---

## Three Industries. Three Problems. Three Solutions.

**If you're in Luxury/Beauty:**
- Demand is driven by psychology (scarcity, celebrity, trend velocity), not seasonality
- Project 1 (Forecast Confidence) identifies trend breaks 4 weeks early so you stock before competitors
- **Value**: Margin protection through fast fashion forecasting

**If you're in Aerospace & Defense:**
- Cost variance is a safety/quality/schedule story, not a budget story
- Project 2 (Variance Decoded) proves that "overspending" actually prevented $50M+ in delays
- **Value**: Supply chain gets credit for risk management; CFO looks competent to the board

**If you're in Tech:**
- Supply chain modernization payback is fast, but execution risk is real
- Project 3 (Supply Chain ROI Reality) proves ROI is guaranteed; the question is execution
- **Value**: CFO + CIO alignment on $50M+ modernization investments

---

## Tech Stack

All three projects use a consistent, modern stack:

- **Python** (Pandas, NumPy, Scikit-learn, Prophet) — data manipulation, time series forecasting, analysis
- **SQL** (Postgres or SQLite) — querying and aggregating large datasets
- **Plotly** — interactive visualizations (waterfall charts, confidence intervals, sensitivity analysis)
- **Streamlit** — turning analyses into interactive dashboards (deployed free to Streamlit Cloud)
- **Jinja2** — auto-generating reports and executive summaries
- **Git + GitHub** — version control and collaboration
- **Monte Carlo simulation** (for tech project risk modeling)

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

## How to Explore These Projects

Each project has its own GitHub repository with:

- **README** — the problem, solution, and impact (tailored to the industry)
- **Notebooks** — step-by-step analysis (exploration → insights → conclusions)
- **Source code** — production-ready Python modules
- **Streamlit app** — interactive dashboard with live demo
- **Data** — sample datasets (synthetic but realistic)
- **Docs** — methodology and assumptions

Start with the project that resonates most with your industry. Or read all three—they build on each other conceptually.

---

## Let's Connect

I'm building supply chain data science projects in **Paris**, focused on luxury, aerospace, and tech industries.
Skills:
- Deep supply chain experience (aerospace, semiconductors, ERP systems)
- Data science fundamentals (Python, SQL, statistics, visualization)
- Business acumen (speaking to demand planners, analysts, CFOs, CIOs)
- Honest storytelling (data that's true, insights that matter)

**[LinkedIn](https://linkedin.com/in/vmarenco1) | [Email](veronica.marenco26@gmail.com)**

---

## One More Thing

Supply chain is complex. But complexity doesn't mean it has to be opaque.

These Three projects are my attempt to bring clarity to the messiness.

---

*Last updated: July 2026 | Built in Paris | For supply chain leaders everywhere*
