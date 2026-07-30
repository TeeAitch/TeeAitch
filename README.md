# Hi, I'm Tolga 👋

Software engineer with an architect's mindset. I like systems that are **boring in production** — clear structure, honest tests, and a straight path from commit to server.

Right now: **Java** for the fun parts, **Go** for the lean ones, a lot of **AI-assisted development**, **GitHub Actions** everywhere, and **Kubernetes** next on the list.

What I care about:

- **Robust over clever** — best practices first, surprises last
- **Readable** — if the next person needs a call to understand it, it isn't done
- **Documented** — code, decisions and runbooks, not just code
- **Automated end to end** — no manual step between merge and deploy

---

### Stack

![Java](https://img.shields.io/badge/Java-1a1a1a?style=flat-square&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-1a1a1a?style=flat-square&logo=spring&logoColor=white)
![Go](https://img.shields.io/badge/Go-1a1a1a?style=flat-square&logo=go&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-1a1a1a?style=flat-square&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-1a1a1a?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-1a1a1a?style=flat-square&logo=kubernetes&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-1a1a1a?style=flat-square&logo=postgresql&logoColor=white)

---

### How my code gets to production

```mermaid
flowchart LR
    A[Commit] --> B[Build]
    B --> C[Unit & Integration Tests]
    C --> D[Quality Gates<br/>lint · coverage · scan]
    D --> E[Container Image]
    E --> F[Staging]
    F --> G[Prod]

    style A fill:#0d1117,stroke:#30363d,color:#e6edf3
    style B fill:#0d1117,stroke:#30363d,color:#e6edf3
    style C fill:#0d1117,stroke:#30363d,color:#e6edf3
    style D fill:#161b22,stroke:#3fb950,color:#e6edf3
    style E fill:#0d1117,stroke:#30363d,color:#e6edf3
    style F fill:#0d1117,stroke:#30363d,color:#e6edf3
    style G fill:#161b22,stroke:#58a6ff,color:#e6edf3
```

Every stage is a gate. If it's red, it doesn't move.

---

### Stats

<p>
  <img height="165" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=TeeAitch&theme=github_dark" alt="Profile details" />
</p>
<p>
  <img height="165" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=TeeAitch&theme=github_dark" alt="Repos per language" />
  <img height="165" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=TeeAitch&theme=github_dark" alt="Most used languages" />
</p>

Most of my work lives in private company repos — so the graph is quieter than the calendar.

---

<sub>Want to talk architecture, pipelines or clean handovers? Open an issue anywhere or reach out.</sub>
