<img align='center' src='https://user-images.githubusercontent.com/74038190/226127923-0e8b7792-7b3c-462b-951b-63c96ba1a5af.gif' width='310' height='310'>


# 🤍 Hi, I'm Negin Parseh |

### 🚀 AI/ML & Full-Stack Developer

A passionate Software Engineering graduate (Associate & Bachelor's) with a strong foundation in computer science, architecture, and system design. I love bridging the gap between data-driven systems and interactive user experiences. Currently focusing on Deep Tech, AI/ML Engineering, and Full-Stack development using JavaScript and Python ecosystems.

### 🎈 Checkout My **Portfolio** [Follow The Link](https://imgigin2003.github.io/My-Portfolio/)

---

### 🧠 About Me

- 🎓 **Education:** B.Sc. & Associate Degree in Computer Software Engineering.
- 💡 **Interests:** Artificial Intelligence, Machine Learning, Microservices, and Pixel Art-Style Apps.
- ⚡ **Tech Philosophy:** Writing clean, scalable, and modular code to solve complex algorithmic problems.
- 🎯 **Current Goals:** Building production-ready AI pipelines and mastering full-stack architectures.

---

### 🛠️ Tech Stack & Tools

<table>
  <tr>
    <td align="center" width="96">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python" height="40"/>
      <br />Python
    </td>
    <td align="center" width="96">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="JavaScript" height="40"/>
      <br />JavaScript
    </td>
    <td align="center" width="96">
      <img src="https://github.com/devicons/devicon/blob/v2.17.0/icons/typescript/typescript-original.svg" alt="Typescript" height="40"/>
      <br />TypeScript
    </td>
    <td align="center" width="96">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" alt="React" height="40"/>
      <br />React
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
      <img src="https://github.com/devicons/devicon/blob/v2.17.0/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="AWS" height="40"/>
      <br />AWS
    </td>
    <td align="center" width="96">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/rust/rust-original.svg" alt="Rust" height="40"/>
      <br />Rust
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

#### 🌱 [StudySprout](https://studysprout.pages.dev/) · [source](https://github.com/imgigin2003/StudySprout)
A cute and cozy web-app for planting flowers and starting pomo sessions.
* **Flexible Focus:** — Study blocks from 5 to 60 minutes
* **Task-Linked Growth:** — Attach your timer to a specific plant in your garden
* **Partial XP:** — Stop early and still earn XP for every full minute you focused
* **Session Tracking:** — Automatic break reminders after every 4 Pomodoros
* **Secure Auth:** — JWT-based authentication with bcrypt password hashing
* **Streak Unlocks:** — New plant varieties unlock every 7 days of consistent study

#### 🏔️ [Lumen Retreat](https://lumen-retreat.vercel.app/login) · [source](https://github.com/imgigin2003/LumenRetreat)
A midnight-luxury dashboard for managing a boutique cabin resort, built in 3D.
* **Procedural 3D:** — Low-poly cabins built from pure code, zero model files
* **Orbit & Inspect:** — Spin any cabin in real time, materials shift by tier
* **Living Dashboard:** — Animated KPIs, revenue charts and today's arrivals
* **One-Tap Check-In:** — Move guests through their stay from a single click
* **Midnight Glass:** — Deep ink, warm amber accents and a light-mode toggle
* **Zero Backend:** — Runs fully in the browser on a seeded in-memory store

#### 💳 [FraudFlux](https://github.com/imgigin2003/FraudFlux)
A fraud detection pipeline built on 284,807 real credit card transactions, comparing Logistic Regression, Decision Trees, and Random Forest under a severe 0.172% class imbalance.
* **Model Comparison Pipeline:** Trains and evaluates three classifiers with class_weight="balanced", then tunes decision thresholds per-model to navigate the precision-recall tradeoff rather than trusting default cutoffs.
* **Data Leakage Discipline:** Deduplicates before splitting, stratifies the train/test split to preserve class ratio, and fits scalers on training data only — avoiding the leakage traps this kind of imbalanced dataset invites.
* **A Documented Change of Mind:** Started with a strict "recall over precision" stance, then abandoned it after seeing the real false-alarm cost (629 alerts to catch 5 extra frauds) — and shipped the model that balances both instead of the one with the flashiest single metric.

#### 🕸️ [InsightGraph](https://insight-graph-alpha.vercel.app/) · [source](https://github.com/imgigin2003/InsightGraph)
A full-stack algorithm and graph visualization platform for learning and research.
* **Step-Trace Animation:** Watch 16 algorithms (BFS, Dijkstra, A*, Quick Sort, and more) execute step by step, with play/pause/scrub controls and live pseudocode highlighting.
* **Interactive Graph Building:** Draw directed/weighted graphs on a React Flow canvas, import real datasets from CSV/JSON, and explore hypergraphs rendered as convex hulls.
* **Research Analytics:** NetworkX-powered dashboard with density, centrality, and clustering metrics, graph similarity comparison, and one-click PDF report export.

#### 📝 [KnowledgeBase](https://github.com/imgigin2003/KnowledgeBase)
A powerful, Notion-inspired productivity and knowledge management system.
* **Rich Text Rendering:** Add articles using raw HTML tags or Markdown, with immediate inline real-time output visualization.
* **Smart Categorization:** Advanced custom filtering and strict category management for documentation.
* **Workflow Management:** Built-in task and intern manager structured around color-coded priorities and custom kanban-style logic.

#### 🌐 [HG-db](https://github.com/imgigin2003/HG-db)
A microservices-based web application designed for complex hypergraph data visualization and management.
* **Microservices Architecture:** Built with a highly modular and distributed mindset.
* **Streamlit & D3.js:** Features a robust [Streamlit](https://streamlit.io) interface seamlessly integrated with a powerful [D3.js](https://d3js.org) service for interactive graphics.
* **Rust Bridge:** Utilizes Rust as an ultra-fast performance bridge between backend data and front-end visualization engines.
* **Capabilities:** Full rendering capabilities for Hypergraphs, Dual Hypergraphs, and Layer Hypergraphs.


---

### 🤝 Connect with Me

* 📧 **Email:** [negin2003parseh@gmail.com](mailto:negin2003parseh@gmail.com)
* 💼 **LinkedIn:** [Negin Parseh](https://www.linkedin.com/in/negin-parseh)

Looking forward to collaborating on innovative Open Source AI/ML projects and Full-Stack web apps!
