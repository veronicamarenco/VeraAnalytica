
# Supply Chain Data Science Portfolio
## Honest Insights for Supply Chain Leaders

Welcome. I build tools that solve real supply chain problems—the ones that keep planners up at night, make analysts struggle to explain costs, and leave CFOs skeptical of modern supply chain ROI claims.

I've lived these problems. I've watched demand planners miss seasonal luxury trends. I've seen aerospace supply chain leaders struggle to explain cost variance to finance. I've watched tech companies debate whether supply chain modernization is worth the investment.

This portfolio is three tools that transform those headaches into clarity—each built for a different industry and audience.

---

## The Three Projects

### 1. [From Gut Feel to Forecast Confidence](https://github.com/[yourname]/forecast-confidence-luxury)
**Luxury & Beauty: Demand Planning for Hermès, Dior, LVMH**

Luxury demand isn't rational. It's driven by psychology: scarcity, celebrity endorsement, trend velocity, and the seasonal emotional spending patterns of wealth.

Q4 spikes 300% (holiday gifting). A new celebrity posts a Hermès Birkin on Instagram and demand jumps 40%. Fashion weeks shift collections. Summer vacations drop demand 60%. Your spreadsheet-based forecast can't capture any of this.

This tool identifies which signals actually drive luxury demand—trend shifts from fashion events, scarcity effects from waitlists, external signals from influencers and luxury indices—and quantifies them. Turns guessing into signal detection.

**Impact:** If you can predict a fashion trend 4 weeks early instead of 4 weeks late, you stock the right items before competitors do. That's margin protection.

- **Built with:** Python (Prophet for seasonality), Pandas, Plotly (interactive confidence bands), Streamlit
- **Dataset:** 4 years of Hermès Birkin/Kelly sales across leather types, colors, regions, with known trend shifts (celebrity moments, fashion weeks, TikTok virality)
- **Core insight:** Luxury demand is driven by psychology and scarcity, not logic. This tool identifies trend breaks (structural shifts vs. seasonal noise) so you can react fast.

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

I've worked across **luxury goods, aerospace, and semiconductors**—industries where supply chain decisions directly impact margin, safety, and competitive advantage.

I've watched Hermès planners miss seasonal luxury trends because their models treated demand like Walmart. I've seen aerospace supply chain leaders struggle to explain $25M cost variances to skeptical CFOs. I've watched tech companies debate whether $50M supply chain modernization is worth the investment—without a unified financial model.

**That's why I build these tools.**

I speak the language of demand planners (they live with forecast errors), supply chain analysts (they drown in complexity), and CFOs/CIOs (they demand clarity). I understand that supply chain is complex, messy, and *human*—but that doesn't mean insights have to be opaque.

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

I'm building a supply chain data science practice in **Paris**, focused on luxury, aerospace, and tech industries.

I bring:
- Deep supply chain experience (aerospace, semiconductors, ERP systems)
- Data science fundamentals (Python, SQL, statistics, visualization)
- Business acumen (speaking to demand planners, analysts, CFOs, CIOs)
- Honest storytelling (data that's true, insights that matter)

**[LinkedIn](https://linkedin.com/in/[yourname]) | [Email](mailto:your.email@domain.com)**

---

## One More Thing

I grew up with Excel. My first bar chart (5th grade, milk preferences) got printed alongside 30 others. I felt a wave of satisfaction.

That's still how I feel when a variance waterfall chart suddenly makes sense to a CFO, or when a demand forecast model catches a trend shift before it happens.

Supply chain is complex. But complexity doesn't mean insights have to be opaque.

These three projects are my attempt to bring clarity to real supply chain problems.

I hope they're useful.

---

*Last updated: July 2026 | Built in Paris | For supply chain leaders in luxury, aerospace, and tech*

Welcome(:

I build tools that solve supply chain problems. The kind that keep planners up at night, make analysts spend weekends explaining variances, and leave CFOs skeptical of ROI claims.

This portfolio includes three tools that transform those headaches into clarity.

## The Three Projects (in progress)

### 1. [Variance Decoded: The Story Behind Your Numbers](https://github.com/[yourname]/variance-decoded)
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

### 2. [Savings to Strategic Investment: The Complete Financial Story](https://github.com/[yourname]/ROI)
### Savings to Strategic Investment: The Complete Financial Story

**What it does:**
Links supply chain savings directly to infrastructure investment decisions. Shows: "Here's what we're saving. Here's what modernization costs. Here's when we break even. Here's the risk."

**For CFOs:**
- Quantify supply chain improvements by lever (negotiation, process, network, quality)
- Model the ROI of cloud infrastructure investment
- Sensitivity analysis: "What if savings grow 30% faster with better systems?"

**For CIOs:**
- Build total cost of ownership for cloud vs. on-prem
- Quantify migration risk (downtime, delays, budget overruns)
- Scenario modeling: "What if we migrate in phases instead of big bang?"

**For Supply Chain Leaders:**
- Make the case that investments in better systems unlock more savings
- Show which improvements matter most to finance
- Align operations with technology strategy

**Key features:**
1. **Savings Attribution Dashboard** — Where does our $5M come from?
2. **Infrastructure Cost Model** — Cloud vs. on-prem TCO
3. **ROI Calculator** — When does cloud investment pay for itself?
4. **Risk Quantification** — What's the cost of downtime? Budget overrun?
5. **Scenario Comparison** — Conservative vs. optimistic vs. pessimistic cases
6. **Executive Summary** — One page showing: Savings → Investment → Payback

[→ Explore the full project](https://github.com/[yourname]/forecast-confidence)

---
### 3. [From Gut Feel to Forecast Confidence](https://github.com/[yourname]/forecast-confidence)
**The demand planner's credibility problem**

Forecast misses happen. The spreadsheet has numbers, but it doesn't have answers. Was it seasonality? A promotion that didn't land? Market volatility? External shock?

This tool identifies which signals actually drive your forecast errors—and quantifies them. Turns "I don't know why we missed" into "here's exactly what happened, and here's what to tune next time."

**Impact:** If your forecast accuracy improves from 85% to 92%, that's fewer expedites, lower safety stock, and a supply chain that actually trusts the plan.

- **Built with:** Python (Prophet/ARIMA), Pandas, Plotly, Streamlit
- **Dataset:** 3 years of demand data with known seasonality, promotions, and external shocks
- **Core insight:** Signals (trend, seasonality, promo, external) aren't equal. This tool tells you which ones matter.

[→ Explore the full project](https://github.com/[yourname]/forecast-confidence)

---


## Why These Three?

They answer the questions that actually matter:

| Question | Project | Audience |
|----------|---------|----------|
| "Why did our forecast miss?" | Forecast Confidence | Demand Planners |
| "How do we explain our cost variance?" | Variance Decoded | Supply Chain Analysts |
| "If we invest in cloud and unlock better forecasting, how much more can we save?" | Cloud Migration | CFOs CIOs|

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

**[LinkedIn](https://linkedin.com/in/vmarenco1) | [Email](veronica.marenco26@gmail.com)**

---

## One More Thing

I feel satisfied, when a variance waterfall chart suddenly makes sense, or when a forecast accuracy model starts catching patterns a human hasn't.

Supply chain is complex. But complexity doesn't mean it has to be opaque.

These four projects are my attempt to bring clarity to the messiness.

---

*Last updated: July 2026 | Built in Paris | For supply chain leaders everywhere*
