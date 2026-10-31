<div align="center">

# Sahir Ul Hassan

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/sahirulhassan)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sahirulhasan2002@gmail.com)
[![X](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/sahirulhasan)

**Backend Systems Engineer | Full-Stack Developer | Automation Specialist**  
*System Architect & Project Lead at [Ukaaz](https://github.com/ukaaz) | Creator of [Teach-Meter](https://github.com/Teach-Meter)*

<p align="center">
  Software engineer specializing in high-throughput modular monoliths, relational database design, and automated data synchronization pipelines.
</p>

---

</div>

### Engineering Profile

I am a software engineer focused on architecting resilient backend systems, database schemas, and developer tooling. My work spans high-concurrency auction engines and escrow platforms, distributed web ecosystems, administrative API reverse-engineering, system resource monitors, and algorithmic state machines.

- **System Architecture & Modular Monoliths**: Leading system design and relational data modeling for **[Ukaaz](https://github.com/ukaaz)** (AI-powered auction and escrow marketplace) and **[Teach-Meter](https://github.com/Teach-Meter)**. Adhering to strict Dependency Inversion (DIP) and database-level constraint-driven atomicity.
- **High-Performance Backends**: Building type-safe, schema-driven REST and WebSocket backends using Fastify v5, TypeScript, Drizzle ORM, Prisma, PostgreSQL, Redis, and Better Auth.
- **Reverse Engineering & Automation**: Developing multi-tier catalog migration engines, session/CSRF state handlers, and event-driven automation bots with concurrency control.
- **Systems & Desktop Applications**: Building native desktop utilities with Python and PyQt6 (process monitors, signal handling, psutil) and JavaFX (transactional desktop suites).
- **Cross-Platform & Reactive UI**: Engineering mobile clients in Flutter (Riverpod, GoRouter) and web frontends with React 19, TanStack Router and Query, and Chakra UI.

---

### Featured Projects

<table>
  <thead>
    <tr>
      <th width="32%">Project</th>
      <th width="28%">Primary Stack</th>
      <th width="40%">Architecture & Engineering Highlights</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <a href="https://github.com/ukaaz"><b>Ukaaz Ecosystem</b></a><br>
        <sub>AI-powered auction, storefront & escrow marketplace</sub>
      </td>
      <td>
        <code>Fastify 5</code> <code>Drizzle ORM</code><br>
        <code>PostgreSQL 16</code> <code>Redis</code><br>
        <code>Better Auth</code> <code>Cloudflare R2</code><br>
        <code>Flutter</code> <code>Riverpod</code>
      </td>
      <td>
        - <b>Role: Project Lead & System Architect</b>.<br>
        - Modular monolith adhering to DIP; domain services decoupled from SQL via repository interfaces.<br>
        - Real-time auction engine with anti-sniping dynamic time extensions and escrow settlement.<br>
        - PostgreSQL <code>ltree</code> category trees with GiST indexing and transaction retry wrappers (<code>withTransactionRetry</code>).<br>
        - Cross-platform Flutter client with typed routing and Riverpod state management.
      </td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/Teach-Meter"><b>TeachMeter Ecosystem</b></a><br>
        <sub>Educational faculty & institution evaluation platform</sub>
      </td>
      <td>
        <code>Fastify 5</code> <code>Prisma 7</code><br>
        <code>PostgreSQL</code> <code>Redis</code><br>
        <code>React 19</code> <code>Chakra UI 3</code><br>
        <code>Flutter</code> <code>Vitest</code>
      </td>
      <td>
        - <b>Role: Creator & Lead Architect</b>.<br>
        - Domain-driven modular API with cursor-based pagination and TypeBox schemas.<br>
        - Redis caching layer, Sentry telemetry, and Vitest test coverage.<br>
        - Automated OpenAPI client generation (Orval) synchronizing React and mobile clients.
      </td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/sahirulhassan/wabot"><b>WABot Engine</b></a><br>
        <sub>Automated WhatsApp messaging & media dispatcher</sub>
      </td>
      <td>
        <code>Node.js</code> <code>Express</code><br>
        <code>whatsapp-web.js</code> <code>SSE</code>
      </td>
      <td>
        - Real-time Server-Sent Events (SSE) status stream and QR auth lifecycle.<br>
        - Concurrency gating via <code>p-limit</code> (5 concurrent tasks).<br>
        - Anti-detection randomized human jitter delays (6–10s) and session persistence.
      </td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/sahirulhassan/ProcWatch"><b>ProcWatch</b></a><br>
        <sub>Task Manager-grade system & process resource monitor</sub>
      </td>
      <td>
        <code>Python 3</code> <code>PyQt6</code><br>
        <code>psutil</code> <code>Qt Designer</code>
      </td>
      <td>
        - Real-time multi-threaded metrics for CPU cores, RAM, disk I/O, and socket connections.<br>
        - Custom <code>QStandardItemModel</code> with sub-second table refreshes.<br>
        - Safe process signal management and termination workflows.
      </td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/sahirulhassan/KMP-Mealy-Automata"><b>KMP & Mealy Automata</b></a><br>
        <sub>Algorithmic substring search & finite state machine generator</sub>
      </td>
      <td>
        <code>Python</code> <code>Flask</code><br>
        <code>Graphviz</code> <code>Algorithms</code>
      </td>
      <td>
        - Exact Longest Proper Prefix-Suffix (LPS) array computation.<br>
        - Dynamic compilation of pattern transitions into Mealy Machine finite automata.<br>
        - Interactive visualizer rendering vector graph diagrams.
      </td>
    </tr>
  </tbody>
</table>

---

### Technical Capabilities

| Domain | Technologies & Frameworks |
|---|---|
| **Languages** | TypeScript, Python, Java, JavaScript, Dart, SQL, Bash, PowerShell |
| **Backend & Services** | Fastify, Express.js, Node.js, Spring Boot, RESTful APIs, WebSockets / SSE |
| **Databases & Cache** | PostgreSQL, MySQL, Redis, SQLite, MongoDB, Drizzle ORM, Prisma ORM, Hibernate |
| **Frontend & UI** | React 19, TanStack Router & Query, Chakra UI, Vite, Flutter, PyQt6, JavaFX |
| **DevOps & Infrastructure** | Docker, Google Cloud Platform (Cloud Run, Functions, Pub/Sub), Cloudflare R2, ImageKit, Git, CI/CD |
| **Testing & Quality** | Node.js Test Runner (<code>node:test</code>), Vitest, PyTest, Biome, ESLint, Prettier, Husky, Sentry |

---

### GitHub Activity & Analytics

<div align="center">

<img src="https://github-readme-stats-eight-theta.vercel.app/api?username=sahirulhassan&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&show_icons=true" alt="Sahir's GitHub Stats" />
<br/><br/>
<img src="https://streak-stats.demolab.com/?user=sahirulhassan&theme=tokyonight&hide_border=true" alt="Sahir's GitHub Streak" />
<br/><br/>
<img src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=sahirulhassan&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&layout=compact" alt="Top Languages" />

</div>

---

<div align="center">
  <sub>Engineered with precision • Driven by clean architecture</sub>
</div>
