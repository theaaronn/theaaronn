# I'm Aaron

3 years of building backend systems.  
Probably hanging out in a CLI app

---

### Tech Stack

| Category | Tools |
| :--- | :--- |
| **Languages** | <a href="https://go.dev"><img src="./assets/go.svg" height="25"></a> <a href="https://www.gnu.org/software/bash/"><img src="./assets/bash.svg" height="25"></a> |
| **Data** | <a href="https://www.postgresql.org"><img src="./assets/postgresql.svg" height="25"></a> <a href="https://www.mysql.com"><img src="./assets/mysql.svg" height="25"></a> <a href="https://redis.io"><img src="./assets/redis.svg" height="25"></a> |
| **SSR** | <a href="https://htmx.org"><img src="./assets/htmx.svg" height="25"></a> <a href="https://templ.guide"><img src="./assets/templ.svg" height="25"></a> |
| **Platform & Ops** | <a href="https://www.kernel.org"><img src="./assets/linux.svg" height="25"></a> <a href="https://learn.microsoft.com/en-us/windows/wsl/"><img src="./assets/wsl.svg" height="25"></a> <a href="https://git-scm.com"><img src="./assets/git.svg" height="25"></a> <a href="https://www.hetzner.com"><img src="./assets/hetzner.svg" height="25"></a> <a href="https://www.digitalocean.com"><img src="./assets/digitalocean.svg" height="25"></a> |
---

### Architecture & Projects

**[Engineering Portfolio](https://github.com/theaaronn/portfolio)**  
Technical breakdowns and public tools.

*   **[Essential Oil Knowledge Engine](https://github.com/theaaronn/portfolio/blob/main/projects/essential-oil-engine.md)**: B2B RAG platform (Go/pgvector/Redis) focused on context-bounded generation.

---

### Why This Stack?

**Go + HTMX**  
I'm a fan of hypermedia-driven architectures. [HATEOAS](https://htmx.org/essays/hateoas/)
(from Roy Fielding's REST dissertation) describes how the server should drive
application state through hypermedia—not through JSON endpoints with rigid client
logic. HTMX lets me build this way: the server sends HTML with the available actions,
and the browser does what it was designed to do. (Also not a huge fan of JS)

**Server as Source of Truth**  
I prefer keeping logic and state on the server. When the server owns the truth
and the frontend just renders it, complexity stays in one place and bugs have
fewer places to exist. [JSON APIs aren't RESTful](https://roy.gbiv.com/untangled/2008/rest-apis-must-be-hypertext-driven)—they're
RPC with extra steps.

**VPS Over Cloud Abstractions**  
I lean toward Hetzner and self-hosted tools like Dokploy. I like understanding
my infrastructure stack and having direct control over where things run. Cloud
platforms are powerful, but I prefer the transparency and cost model of a VPS.

**CLI-First**  
Most of my workflow happens in the terminal. I prefer keeping my hands on the keyboard than reaching for my mouse.

---

### Connect with me

[Email](mailto:caper2711@hotmail.com)

<div align="right">
  <img src="./assets/gopherpet.gif" alt="Gopher Pet" width="20"/>
</div>
