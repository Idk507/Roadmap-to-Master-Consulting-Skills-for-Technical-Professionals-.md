
---

## 📘 What is Cost-Benefit Analysis (CBA)?

**Cost-Benefit Analysis** is a **quantitative technique** used to compare the total expected **costs** vs. total expected **benefits** of one or more actions in order to choose the most economically viable option.

> 🔎 **Goal:** Determine if **Benefits > Costs** → Proceed
> If **Costs > Benefits** → Rethink, delay, or cancel

---

## 🧮 CBA Formula

At its core:

### ➕ **Net Benefit (or Net Present Value)**:

$$
\text{Net Benefit} = \sum \text{Benefits} - \sum \text{Costs}
$$

Or more accurately (with time value of money):

### ⏳ **NPV-based CBA**:

$$
\text{NPV} = \sum_{t=0}^{n} \frac{\text{Benefits}_t - \text{Costs}_t}{(1 + r)^t}
$$

Where:

* `t` = time period (year/month)
* `r` = discount rate
* `n` = time horizon

---

## 🧩 Components of a Cost-Benefit Analysis

| **Costs**                              | **Benefits**                     |
| -------------------------------------- | -------------------------------- |
| Direct costs (CAPEX, OPEX)             | Revenue gains                    |
| Indirect costs (training, change mgmt) | Time savings, process efficiency |
| Opportunity costs                      | Increased customer satisfaction  |
| Risk/uncertainty costs                 | Compliance or security benefits  |
| Maintenance or support                 | Competitive advantage            |

---

## 🧭 Steps to Perform a Cost-Benefit Analysis

### ✅ Step 1: Define the Scope

* What is the project/investment?
* What are the goals?
* Who are the stakeholders?

### ✅ Step 2: Identify and List All Costs

* One-time (e.g., AI infra setup)
* Recurring (e.g., API usage, DevOps)
* Intangible (e.g., brand risk, legal)

### ✅ Step 3: Identify and Quantify All Benefits

* Revenue generation
* Cost reduction
* Time efficiency
* User experience improvements

### ✅ Step 4: Assign Monetary Values

* Convert **qualitative benefits** into **quantified estimates**
* Use benchmarking or market proxies if needed

### ✅ Step 5: Calculate Net Benefit or ROI

* Compute:

  * **Net Benefit**
  * **Benefit-Cost Ratio (BCR)** = Total Benefits / Total Costs
  * **Return on Investment (ROI)** = (Net Benefit / Total Cost) × 100

### ✅ Step 6: Perform Sensitivity Analysis

* Change assumptions to test robustness
* Test against best/worst/most likely scenarios

### ✅ Step 7: Make Recommendation

* Based on Net Benefit, BCR, risk profile

---

## 📊 Example: Cost-Benefit Analysis of Implementing a GenAI Chatbot

| Category        | Details                      | Value (₹)  |
| --------------- | ---------------------------- | ---------- |
| **Costs**       | Initial Dev + Infra          | ₹10,00,000 |
|                 | LLM API usage (annual)       | ₹3,00,000  |
|                 | Change management & training | ₹2,00,000  |
|                 | Maintenance                  | ₹1,00,000  |
| **Total Costs** |                              | ₹16,00,000 |

\| **Benefits** | Reduced support tickets (₹2L/month) | ₹24,00,000/year |
\| | 10% reduction in employee effort | ₹5,00,000/year |
\| | Better customer satisfaction (NPS↑) | Qualitative |
\| **Total Benefits** |  | ₹29,00,000

### ➕ Net Benefit = ₹29L – ₹16L = ₹13L

### 📈 ROI = (₹13L / ₹16L) × 100 ≈ **81.25%**

👉 **Decision**: Implement GenAI chatbot ✅

---

## ⚠️ Limitations of CBA

* Difficult to **assign value to intangibles** (e.g., brand equity, user happiness)
* May **ignore strategic or long-term goals**
* Sensitive to assumptions (discount rate, estimates)
* Doesn't directly account for risk (use Monte Carlo / Scenario Planning alongside)

---

## ✅ Use Cases in Consulting & Data Projects

| Domain         | CBA Application                                             |
| -------------- | ----------------------------------------------------------- |
| **AI/ML**      | Evaluate ROI of model deployment (vs manual)                |
| **Healthcare** | Cost of AI diagnosis tool vs improved outcomes              |
| **Finance**    | New risk engine vs cost of legacy system                    |
| **Retail**     | Personalized recommender system vs development + infra cost |
| **IT**         | Cloud migration vs maintenance + agility gains              |
| **HR**         | Employee GenAI assistant vs L\&D investment                 |

---

## 📁 Deliverables to Create in a CBA Project

| Deliverable               | Purpose                                    |
| ------------------------- | ------------------------------------------ |
| 📄 Business Case Document | Describes rationale for investment         |
| 📊 Excel Model            | Dynamic cost-benefit + ROI calculator      |
| 📈 Sensitivity Analysis   | Visualize impact of variables              |
| 🖼️ Dashboard             | Live tracking of realized vs projected ROI |
| 🎯 Executive Summary      | For leadership approval                    |

---


