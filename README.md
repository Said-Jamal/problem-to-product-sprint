# Problem-to-Product Sprint

This repository holds our final project from the **Problem-to-Product Sprint**, a 9-session program led by **Nijat Hajiyev** (Nexus Adv).

We worked on a real business problem for a real company, from start to finish - finding the problem, analysing the data, mapping the process, designing a solution, and building a working prototype.

---

## 👥 The Team - Ctrl+Solve

- **Said Jamalov**
- **Laman Aghayeva**

We came from different backgrounds, but we worked as one team. Every deliverable in this repo is the result of many hours of thinking, arguing, testing, and rewriting together.

---

## 🎯 The Problem

Our client was **a textile manufacturer in Azerbaijan**. Their production lines were stopping because raw materials (yarn, dye, chemicals) were running out - but nobody knew until the batch was about to start.

The numbers:

- **15-16 hours** of line stoppage, on average, every time a shortage happened
- **~2.22M AZN per year** in estimated total cost
- **0%** of shortages caught before the line stopped
- **Dyeing shop** carried around **60-63%** of the cost - the same finding held in two separate datasets

---

## 💡 Our Solution

A **Proactive Stock Threshold Alert system** - a simple idea that changes the timing of everything.

Instead of finding out about a shortage when the worker walks up to an empty rack, the system checks stock automatically and sends an alert to the warehouse and production manager **before** the batch is scheduled.

No AI in v1. Just a clear rule: *if stock is below the threshold, alert everyone at the same time.*

👉 **Live prototype:** [Open the working demo](https://claude.ai/public/artifacts/28004bb8-fa48-4568-9f9b-68037142128d)

---

## 📁 What's in this Repository

| Folder | What you'll find |
|--------|------------------|
| `/docs` | All session submissions (Session 2-5) and the full Product Brief |
| `/diagrams` | As-Is and To-Be process maps (PDF) |
| `/prototype` | The HTML prototype file - same as the live link above |

---

## 🛠️ Tools We Used

- **Claude** - for research, analysis, drafting, and building the prototype
- **Excel** - for the shortage dataset analysis
- **Graphviz & Mermaid** - for the process maps
- **Python (pandas)** - for the data reconciliation between two datasets

---

## 📝 What We Learned

- **Honesty beats polish.** Our acceptance tests came back **0 pass, 4 fail, 1 not verified** - and we reported it that way in every document. It felt uncomfortable at first, but it made the work stronger.
- **Two datasets can tell two different stories.** We had two files that did not agree with each other. Instead of picking one and moving on, we flagged the conflict everywhere it appeared.
- **Small scope is not weakness.** Our prototype only does one thing - the core alert loop. That was a deliberate choice, and we explained the gap between the prototype and the fuller Product Brief openly.
- **The riskiest assumption is usually about people, not tech.** The whole design depends on warehouse staff logging stock consistently. If that habit does not form, the tool is useless. We never hid this.

---

## 🙏 Thanks

To **Nijat Hajiyev** - for teaching this sprint, for the honest feedback, and for pushing us to think one level deeper. To **Nexus Adv** - for making this program possible.

And to each other, as a team. In a room full of working professionals (data analysts, product managers, business analysts), we finished this sprint side by side with them.

---

## 🔗 Related

- LinkedIn hashtag: **#ProblemToProduct**
- LinkedIn post series: 3 posts covering the sprint story, the problem + process maps, and the prototype

---

*This project was a training exercise. Numbers, names, and details are shared for learning purposes.*
