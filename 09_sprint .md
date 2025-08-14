

## 🚀 What is a Sprint?

A **Sprint** is a **time-boxed development cycle**, typically lasting 1–4 weeks, where a specific set of tasks (features, bugs, spikes, etc.) are completed and delivered.

> In Agile, especially Scrum, sprints are the heartbeat of product and project delivery.

---

## 🧱 Sprint Basics

| Term                     | Meaning                                                             |
| ------------------------ | ------------------------------------------------------------------- |
| **Sprint Goal**          | High-level objective for the sprint (e.g., "Deploy MVP of Chatbot") |
| **Sprint Backlog**       | List of stories and tasks planned for this sprint                   |
| **Sprint Duration**      | Fixed time period (commonly 2 weeks)                                |
| **Sprint Planning**      | Team decides what to deliver                                        |
| **Daily Stand-up**       | Short daily sync on progress and blockers                           |
| **Sprint Review**        | Demo of what was built                                              |
| **Sprint Retrospective** | Lessons learned and improvements for next sprint                    |

---

## 🧭 Sprint Lifecycle (End-to-End)

```
1. Sprint Planning 🔧
   ↓
2. Sprint Execution 🏗
   ↓
3. Daily Stand-ups 🧍‍♂️
   ↓
4. Sprint Review ✅
   ↓
5. Sprint Retrospective 🔁
```

---

## 🏗 Sprint Planning (How to Run It)

### Inputs:

* Product backlog (all available stories)
* Sprint goal (e.g., “Enable RAG-based QA pipeline”)
* Team capacity (availability, bandwidth)
* Velocity (story points completed per sprint)

### Activities:

* Select stories from backlog
* Break into sub-tasks
* Estimate story points (using Planning Poker, T-shirt sizing, Fibonacci scale)
* Assign owners
* Define **Definition of Done (DoD)**

> 🔧 Example Sprint Goal: "Implement document ingestion and retriever setup for RAG pipeline."

---

## 📋 Sprint Example for AI/ML/GenAI Project

| Issue Type | Description                                      | Est. Points |
| ---------- | ------------------------------------------------ | ----------- |
| Epic       | RAG Pipeline Setup                               | —           |
| Story      | Create document ingestion script using LangChain | 5           |
| Story      | Configure FAISS vector store                     | 3           |
| Task       | Load data to S3                                  | 2           |
| Bug        | Prompt returns empty response on large docs      | 1           |
| Spike      | Evaluate embedding models (OpenAI vs Cohere)     | 3           |

---

## 🧠 Sprint Execution

During the sprint:

* Team **works only on committed items**
* Use **Jira board** to track:
  `To Do → In Progress → Code Review → Done`
* **Daily stand-up (15 mins)**:

  * What did I do yesterday?
  * What will I do today?
  * Any blockers?

> 🧠 Tip: Blockers like "awaiting AWS credentials" should be resolved ASAP to avoid sprint failure.

---

## ✅ Sprint Review

At the end of the sprint:

* **Demo** completed work to Product Owner/client
* **Accept** stories that meet DoD
* Collect **feedback**

Example: Show GenAI chatbot responding to PDF queries via UI.

---

## 🔁 Sprint Retrospective

Team reflects on:

* ✅ What went well
* ❌ What didn’t
* 🚀 What can improve

**Retrospective tools**:

* Start / Stop / Continue
* Mad / Sad / Glad
* 4Ls (Liked, Learned, Lacked, Longed for)

---

## 📈 Sprint Metrics to Track (Consultant View)

| Metric                     | Meaning                                |
| -------------------------- | -------------------------------------- |
| **Velocity**               | Avg. story points completed per sprint |
| **Burndown Chart**         | Tracks remaining work in sprint        |
| **Cycle Time**             | Time from task start to finish         |
| **Commitment Reliability** | % of planned work actually completed   |

---

## 🧰 Sprint in Jira

In Jira:

* Create a **Sprint** in the board
* Add issues from backlog
* Start the sprint (set duration)
* Use the **Active Sprint Board** to track movement
* View reports: Burndown, Sprint Report, Velocity

---

## 🎓 Sprint Tips for AI/ML Consultants

* **Split big stories**: ML training → Preprocessing, Training, Evaluation
* Include **Spikes**: For research-heavy GenAI components (e.g., prompt tuning)
* Keep stories **independent and testable**
* Track dependencies in Jira with `is blocked by`
* Involve **Product Owner** to refine goals before sprint

---

## 🔄 Sprint Cycle Timeline (2-week sample)

| Day     | Activity                           |
| ------- | ---------------------------------- |
| Day 1   | Sprint planning                    |
| Day 2–9 | Daily stand-ups + execution        |
| Day 10  | Sprint review + demo               |
| Day 11  | Retrospective                      |
| Day 12  | Backlog refinement for next sprint |


