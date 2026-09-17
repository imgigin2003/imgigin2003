<img align='center' src='https://user-images.githubusercontent.com/74038190/212747903-e9bdf048-2dc8-41f9-b973-0e72ff07bfba.gif'>


# 🤍 Hi, I'm Negin

### 🚀 AI Engineer & Backend Developer

A passionate Software Engineer with a strong foundation in computer science, architecture, and system design. While I started out in full-stack development, I've naturally gravitated toward AI engineering and backend systems. I love working on the infrastructure that makes smart models actually usable. Currently focusing on Machine Learning, LLMs, and building reliable backend architecture to run AI in production.

### 💜 Checkout My **[Portfolio]**(https://portfolio-imgigin2003s-projects.vercel.app/)

---

### 🧠 About Me

- 🎓 **Education:** B.Sc. & Associate Degree in Computer Software Engineering.
- 💡 **Interests:** Machine Learning, Deep Learning, LLM Engineering, Backend Architecture, and API Design.
- ⚡ **Tech Philosophy:** A good system isn't just about high accuracy on a test set—it's about being robust under real conditions and honest about its own limits.
- 🎯 **Current Goals:** Building production-ready AI pipelines and owning backend infrastructure from requirements through deployment.

---

### 🛠️ Tech Stack & Tools

<table>
  <tr>
    <td align="center" width="96">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python" height="40"/>
      <br />Python
    </td>
    <td align="center" width="96">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" alt="Node.js" height="40"/>
      <br />Node.js
    </td>
    <td align="center" width="96">
      <img src="https://github.com/devicons/devicon/blob/v2.17.0/icons/express/express-original.svg" alt="Express.js" height="40"/>
      <br />Express
    </td>
    <td align="center" width="96">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/rust/rust-original.svg" alt="Rust" height="40"/>
      <br />Rust
    </td>
    <td align="center" width="96">
      <img src="https://github.com/devicons/devicon/blob/v2.17.0/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="AWS" height="40"/>
      <br />AWS
    </td>
    <td align="center" width="96">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" alt="Typescript" height="40"/>
      <br />TypeScript
    </td>
    <td align="center" width="96">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="JavaScript" height="40"/>
      <br />JavaScript
    </td>
    <td align="center" width="96">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" alt="React" height="40"/>
      <br />React
    </td>
  </tr>
</table>


---

### 📂 Featured Projects

#### 🎙️ [AffectCare](https://affectcare-extended.pages.dev/) · [source](https://github.com/imgigin2003/AffectCare-Extended)
A CNN+LSTM audio classifier that detects vocal distress signals for elderly care safety monitoring, built around a recall-first design philosophy.
* **Distress Detection Pipeline:** Converts raw audio into MFCC spectrograms and classifies them through a hybrid CNN (spatial patterns) + LSTM (temporal patterns) architecture.
* **Recall-First Engineering:** F1-based early stopping, weighted loss, and a deliberately low decision threshold — because a missed emergency costs more than a false alarm.
* **Real Dataset Debugging:** Includes an audit script that surfaced genuine spurious correlations (siren vs. scream confusion) in the training data, not just theoretical edge cases.

#### 💳 [FraudFlux](https://github.com/imgigin2003/FraudFlux)
A fraud detection pipeline built on 284,807 real credit card transactions, comparing Logistic Regression, Decision Trees, and Random Forest under a severe 0.172% class imbalance.
* **Model Comparison Pipeline:** Trains and evaluates three classifiers with class_weight="balanced", then tunes decision thresholds per-model to navigate the precision-recall tradeoff rather than trusting default cutoffs.
* **Data Leakage Discipline:** Deduplicates before splitting, stratifies the train/test split to preserve class ratio, and fits scalers on training data only — avoiding the leakage traps this kind of imbalanced dataset invites.
* **A Documented Change of Mind:** Started with a strict "recall over precision" stance, then abandoned it after seeing the real false-alarm cost (629 alerts to catch 5 extra frauds) — and shipped the model that balances both instead of the one with the flashiest single metric.

#### 🕸️ [InsightGraph](https://insight-graph-alpha.vercel.app/) · [source](https://github.com/imgigin2003/InsightGraph)
A full-stack algorithm and graph visualization platform for learning and research.
* **Backend Integration:** Powered by a FastAPI backend to handle complex algorithmic steps securely and efficiently.
* **Step-Trace Animation:** Watch 16 algorithms (BFS, Dijkstra, A*, Quick Sort, and more) execute step by step, with play/pause/scrub controls and live pseudocode highlighting.
* **Interactive Graph Building:** Draw directed/weighted graphs on a React Flow canvas, import real datasets from CSV/JSON, and explore hypergraphs rendered as convex hulls.
* **Research Analytics:** NetworkX-powered dashboard with density, centrality, and clustering metrics, graph similarity comparison, and one-click PDF report export.

#### 🌱 [StudySprout](https://studysprout.pages.dev/) · [source](https://github.com/imgigin2003/StudySprout)
A cute and cozy web-app for planting flowers and starting pomo sessions.
* **Secure Auth & Backend:** JWT-based authentication with bcrypt password hashing running on an Express backend.
* **Flexible Focus:** Study blocks from 5 to 60 minutes.
* **Task-Linked Growth:** Attach your timer to a specific plant in your garden.
* **Partial XP & Streaks:** Stop early and still earn XP; new plant varieties unlock every 7 days of consistent study.

#### 🏔️ [Lumen Retreat](https://lumen-retreat.vercel.app/login) · [source](https://github.com/imgigin2003/LumenRetreat)
A midnight-luxury dashboard for managing a boutique cabin resort, built in 3D.
* **Procedural 3D:** Low-poly cabins built from pure code, zero model files.
* **Living Dashboard:** Animated KPIs, revenue charts and today's arrivals.
* **Zero Backend Mode:** Runs fully in the browser on a seeded in-memory store for instant demonstration capabilities.

#### 🌐 [HG-db](https://github.com/imgigin2003/HG-db)
A microservices-based web application designed for complex hypergraph data visualization and management.
* **Microservices Architecture:** Built with a highly modular and distributed mindset.
* **Streamlit & D3.js:** Features a robust [Streamlit](https://streamlit.io) interface seamlessly integrated with a powerful [D3.js](https://d3js.org) service for interactive graphics.
* **Rust Bridge:** Utilizes Rust as an ultra-fast performance bridge between backend data and front-end visualization engines.

#### 📝 [KnowledgeBase](https://github.com/imgigin2003/KnowledgeBase)
A powerful, Notion-inspired productivity and knowledge management system.
* **Rich Text Rendering:** Add articles using raw HTML tags or Markdown, with immediate inline real-time output visualization.
* **Workflow Management:** Built-in task and intern manager structured around color-coded priorities and custom kanban-style logic.


---

### 🤝 Connect with Me

* 📧 **Email:** [negin2003parseh@gmail.com](mailto:negin2003parseh@gmail.com)
* 💼 **LinkedIn:** [Negin Parseh](https://www.linkedin.com/in/negin-parseh)

Looking forward to collaborating on innovative Open Source AI/ML projects and Backend systems!
