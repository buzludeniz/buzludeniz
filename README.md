## Hi, I'm Deniz 👋

I'm a developer in Victoria, BC, Canada. By day I do paid development work at
**Ruboss**. The rest of the time I build my own tools and small products,
mostly in TypeScript and Python.

### About me

- **I like problems where getting the numbers right matters.** That's what
  pulled me into quantitative finance: I've written an options-pricing library
  and a local-first desktop app for market research.
- **I care about software being honest with its users.** My weather app shows a
  dash instead of a made-up value when the data isn't there, and that rule shaped
  the whole design.
- **I build things for people, not just for practice.** A short exercise that
  helps students get some distance from a setback. A training prototype built at
  a hackathon. A tax-risk checker for Albanian businesses.
- **I like automating my own workflow.** One of my repositories maintains itself:
  every night an agent picks an item from its backlog, writes the test first,
  implements it and opens a pull request for me to review.
- **I ship with tests and CI.** Five of the six projects below run
  their test suites in GitHub Actions on every push to `main`.

### Selected projects

| Project | What it is | Stack |
| --- | --- | --- |
| [devkit](https://github.com/buzludeniz/devkit) | Developer productivity CLI in a repo that maintains itself: a nightly agent implements backlog items test-first and opens a PR for review | TypeScript, pnpm workspaces, Vitest, GitHub Actions |
| [weather_app](https://github.com/buzludeniz/weather_app) | Nimbus Weather: a forecast web page and phone app built around one rule, "never show a number the provider did not send" | TypeScript, Express, PostgreSQL, Redis, React Native (Expo) |
| [black_scholes_model](https://github.com/buzludeniz/black_scholes_model) | European option pricing with Greeks, implied volatility and a Monte Carlo cross-check, behind a Python API, CLI and GUI | Python, NumPy, pytest |
| [quantview](https://github.com/buzludeniz/quantview) | Local-first quant research desktop app for equities, rates and options, with data stored in DuckDB | Python, DuckDB, PyQt6 |
| [dear-alex](https://github.com/buzludeniz/dear-alex) | A short self-distancing experience for university students after a setback | React, TypeScript, FastAPI |
| [pocket-trainer](https://github.com/buzludeniz/pocket-trainer) | Role-based corporate training prototype built for a hackathon | React, Vite, Recharts, Three.js |

### Tech I use

**Languages:** TypeScript, JavaScript, Python, SQL, Java

**Front end:** React, React Native (Expo), Vite, Tailwind CSS, Material UI

**Back end and data:** Node.js / Express, FastAPI, SQLAlchemy, PostgreSQL, Redis, DuckDB

**Testing and delivery:** Vitest, pytest, Jest, GitHub Actions, Docker

### Get in touch

I'm open to collaborating on interesting projects. The easiest way to reach me
is to open an issue on any of my repositories.
