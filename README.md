# R. Hildermann

**Ex SAP and IT consultant, now building software.**
Kaiserslautern, Germany · available now · open to remote or hybrid

> Four years of SAP consulting taught me to find out why something doesn't behave the way the
> specification says. That's still the job — the tooling just changed.

| | |
|:--|:--|
| **Now** | Building and operating production software, AI-assisted |
| **Before** | SAP S/4HANA (SD/MM) · migration projects · test management |
| **Shipped** | A mental health app on iOS and Android · a self-hosted voice platform in daily use |
| **Looking for** | Junior software engineer · technical consultant · QA and test automation |

---

## Experience

### wefeel — cross-platform mental health app
*Two-month internship, mobile team*

Shipped into a production app that's live on iOS and Android: the events tab, a home screen
redesign, the training tab, a design token refactor, and the in-app subscription system on
both StoreKit and Google Play Billing.

**20+ pull requests, reviewed and merged.**

`React Native` `Expo Router` `TypeScript` `TanStack React Query`

<sub>Company code — not public. App already in production on both App Store and Google Play.</sub>

<br>

### WBS Coding School — software engineering programme
*One year full-time, completed August 2026*

Three twelve-week blocks — computer science in Python, frontend in JavaScript and
TypeScript, then backend with generative AI integration — followed by a four-week final
project and a two-month internship. The HiveMind Mobile MVP was that final project; the
wefeel internship closed the programme. Both ran on issues, feature branches and peer
review rather than exercises.

---

## Projects

### HiveMind Desktop
**Self-hosted voice and community platform.** A Discord replacement for a five-person crew,
built because three things broke down for us: screen-share quality at 1440p, German home
networks behind DS-Lite and CGNAT, and the fact that none of it was ours.

Built and operated solo. **In daily production use since August 2026** on a dedicated root server.

`Django REST Framework` `PostgreSQL` `Expo` `Tauri` `TypeScript` `Linux` `Docker`

→ Architecture, decisions and debugging write-ups: [https://github.com/R-u-d/hivemind-showcase](https://github.com/R-u-d/hivemind-showcase)

<br>

### HiveMind Mobile
**Four-week team MVP.** Where the project started — a community mobile app, built by a small
team through issues, feature branches and reviewed pull requests. My contribution is
documented in the repository.

`React Native` `Expo` `Django REST Framework` `PostgreSQL`

→ [github.com/R-u-d/hivemind-mobile](https://github.com/R-u-d/hivemind-mobile)

<br>

### Event-Intake
**Event ingestion API.** The ingest path, request correlation and the validation boundary —
persistence deliberately left out. Small enough to read in five minutes.

`Python` `FastAPI` `pytest`

→ [github.com/R-u-d/event-intake](https://github.com/R-u-d/event-intake)

<br>

### Geopatra
**Desktop chatbot that speaks its answers and animates an avatar in time with its own
voice.** Python and Tkinter — no game engine, no web stack. Started as a one-week group
project.

The avatar syncs to the *edge* of the speech engine's busy flag rather than to a timer,
because the length of an utterance isn't known in advance and anything clock-based drifts
within one sentence. The clips play forwards then backwards and are swapped only at a loop
boundary, so a change of mood never shows a cut. Works with the network unplugged —
the language model is an opt-in route behind a `?` prefix, and gets a reduced placeholder
set, so a model reply can change the avatar's mood but cannot reach `{quit}`.

Cleaned up afterwards: hardcoded token removed, response logic split from the GUI so that
**84 tests** run without opening a window.

`Python` `Tkinter` `pyttsx3` `pytest`

→ [github.com/R-u-d/geopatra](https://github.com/R-u-d/geopatra)

---

## How I work

**Requirement → architecture → AI-assisted implementation → validation against the domain.**

The last step decides whether the result is worth anything, and it's the one my consulting
years are good for. Four years of writing test cases and running acceptance means I know how
to break something on purpose before a user does it by accident.

---

## Working with others

| Where | What |
|:--|:--|
| **wefeel** | Mobile team, two months, 20+ reviewed PRs |
| **HiveMind Mobile** | Four-week team build — issues, feature branches, reviewed PRs |
| **[geopatra/Speak2Me](https://github.com/jobben-2025/Speak2Me/pulls?q=author%3AR-u-d)** | One-week group project — PRs into someone else's repository |

---

## Stack

| | |
|:--|:--|
| **Backend** | Python · Django REST Framework · FastAPI · PostgreSQL · REST API design |
| **Mobile** | React Native · Expo · Expo Router · TanStack React Query |
| **Frontend** | TypeScript · React · Tailwind |
| **Ops** | Linux root server · Docker · GitHub Actions · reverse proxy / TLS |
| **Domain** | SAP S/4HANA (SD/MM) · migration projects · test management (ISTQB) · project management (PRINCE2) |

---

## Contact

**r.hildermann@outlook.de** · Kaiserslautern, Germany
Open to permanent roles — remote or hybrid.
