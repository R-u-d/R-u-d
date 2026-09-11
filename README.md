# <R. Hildermann>

Ex SAP and IT consultant, now building software. Kaiserslautern, Germany — available now.

**Where I come from:** four years of SAP consulting. S/4HANA (SD/MM), migration and
transformation projects, test management (ISTQB), project management (PRINCE2). The work was
requirements, interfaces, acceptance criteria and finding out why something didn't behave the
way the specification said it would.

**What I do now:** I design systems, decide the trade-offs, and orchestrate AI tooling to
implement them — then check the result against what the people using it actually need.
The judgement is the part I bring; the throughput comes from the tooling.

---

## What I build

### HiveMind — self-hosted voice and community platform
A replacement for Discord for a five-person crew, because three things broke down for us:
screen-share quality at 1440p, German home networks behind DS-Lite and CGNAT, and the fact
that none of it was ours.

Built and operated solo. **In daily production use since <08/2026>** on a dedicated root server.

`Django REST Framework` · `PostgreSQL` · `Expo` · `Tauri` · `TypeScript` · `Linux / Docker`

Architecture, engineering decisions and debugging write-ups: [LINK:SHOWCASE]

### HiveMind Mobile — four-week team MVP
Where the project started: a community mobile app, built by a small team through issues,
feature branches and reviewed pull requests. My contribution is documented in the repository.

`React Native` · `Expo` · `Django REST Framework` · `PostgreSQL`

[LINK:MOBILE]

### [event-intake](https://github.com/R-u-d/event-intake) — event ingestion API
A small FastAPI service: the ingest path, request correlation and the validation boundary,
with persistence deliberately left out. Small enough to read in five minutes.

`Python` · `FastAPI` · `pytest`

---

## How I work

Requirement → architecture → AI-assisted implementation → validation against the domain.

The last step is the one that decides whether the result is worth anything, and it is the one
my consulting years are good for. Four years of writing test cases and running acceptance
means I know how to break something on purpose before a user does it by accident.

The setup I use for this — agent instructions, workflows, review gates — is here: [LINK:STANDARDS]

---

## Working with others

- **HiveMind Mobile** — four-week team build: issues, feature branches, reviewed PRs
- **[PokedexDiary](https://github.com/jobben-2025/PokedexDiary/pulls?q=author%3AR-u-d)** —
  duo project during the programme; 3 pull requests, reviewed and merged

---

## Stack

| | |
|---|---|
| **Backend** | Python · Django REST Framework · FastAPI · PostgreSQL · REST API design |
| **Frontend** | TypeScript · React · React Native · Expo · Tailwind |
| **Ops** | Linux root server · Docker · GitHub Actions · reverse proxy / TLS |
| **Domain** | SAP S/4HANA (SD/MM) · migration projects · test management (ISTQB) · project management (PRINCE2) |

Everything listed here is something I can walk you through in one of the repositories above.

---

## Contact

<r.hildermann@outlook.de> · [LinkedIn](<http://bit.ly/48eWrjj>) · Kaiserslautern, Germany
Open to permanent roles — remote or hybrid.
