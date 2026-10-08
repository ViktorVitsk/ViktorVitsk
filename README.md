# Viktor Stoianov

**Python & TypeScript · Full-stack applications · Automation, IoT & AI-agent systems**

I build full-stack applications and automation systems with Python and TypeScript, connecting web interfaces, APIs, databases, AI models and physical devices.

I develop these projects with AI agents for architecture, implementation and review. I define requirements, compare technical approaches, integrate components and verify results. The repositories connect engineering decisions to code, tests and CI.

## Selected projects

### [LifeLog — personal journal with encrypted text and offline synchronisation](https://github.com/ViktorVitsk/LifeLog)

**Python · FastAPI · PostgreSQL · React · TypeScript · Dexie/IndexedDB**

A personal-use MVP with browser-side encryption, an offline change queue, versioned synchronisation and conflict handling. Optional AI integrations propose structured records that require user confirmation before saving.

- **Engineering focus:** account-scoped state and per-item sync outcomes preserve concurrent writes while isolating a failed item in a batch.
- **Evidence:** [PostgreSQL concurrency and rollback tests](https://github.com/ViktorVitsk/LifeLog/blob/main/backend/tests/test_sync_database_atomicity.py), [two-browser-context deletion regression](https://github.com/ViktorVitsk/LifeLog/blob/main/frontend/e2e/two-contexts-delete.spec.ts), and a [successful CI run](https://github.com/ViktorVitsk/LifeLog/actions/runs/37853709810) covering backend, frontend and live API/browser checks.
- **Explore:** [architecture](https://github.com/ViktorVitsk/LifeLog/blob/main/ARCHITECTURE.md), [local fictional-data demo](https://github.com/ViktorVitsk/LifeLog#fictional-demo-no-api-key), [privacy and recovery boundaries](https://github.com/ViktorVitsk/LifeLog#privacy-and-recovery-boundaries).

### [Grow System — ESP32 greenhouse automation](https://github.com/ViktorVitsk/Grow-System)

**ESP32 · MicroPython · MQTT · FastAPI · PostgreSQL · React**

A home-greenhouse prototype connecting soil, climate and water sensors to pump/relay control, Telegram commands and a web dashboard. I selected, wired and soldered components, flashed and configured the ESP32, and tested the assembled equipment. Architecture and software development were AI-assisted.

- **Engineering focus:** a [shared output controller](https://github.com/ViktorVitsk/Grow-System/blob/main/controllers/bounded_output.py) gives manual and automatic control the same deadline, cooldown and sensor interlocks.
- **Evidence:** [failure-scenario tests](https://github.com/ViktorVitsk/Grow-System/blob/main/tests/test_runtime_safety.py) cover repeated ON commands, stale sensors, mode changes and shutdown before notifications; [CI](https://github.com/ViktorVitsk/Grow-System/actions/runs/37845720496) passes host firmware/backend tests, frontend checks, mobile typechecking and documentation build.
- **Explore:** [synthetic dashboard preview](https://github.com/ViktorVitsk/Grow-System/blob/main/docs/assets/demo-dashboard.png), [hardware guide](https://github.com/ViktorVitsk/Grow-System/blob/main/HARDWARE_BUILD_GUIDE.md). See [verification scope](https://github.com/ViktorVitsk/Grow-System/blob/main/docs/verification.md) for hardware checks and safety boundaries.

### [linSec — Linux change monitoring and bounded AI investigation](https://github.com/ViktorVitsk/linSec)

**Python · SQLite · Linux/systemd · JavaScript · unittest · Ruff**

An archived engineering prototype that compares workstation observations with a reviewed baseline, retains alert history and exposes CLI/Web views. Optional AI explanations use bounded evidence lookups without host-remediation authority.

- **Engineering focus:** incomplete observations retain uncertainty instead of turning missing evidence into a deletion or a clean-host claim.
- **Evidence:** [partial-scan and baseline regressions](https://github.com/ViktorVitsk/linSec/blob/main/tests/test_watchdog.py), [AI authority boundary](https://github.com/ViktorVitsk/linSec/blob/main/docs/decisions/ADR-003-m2b-investigation-boundary.md), and [successful repository checks](https://github.com/ViktorVitsk/linSec/actions/runs/37826250675).
- **Decision record:** [ADR-007](https://github.com/ViktorVitsk/linSec/blob/main/docs/decisions/ADR-007-reuse-first-orchestrator.md) records reassessing scope and removing a synthetic-only subsystem. Explore the [synthetic demo and verification notes](https://github.com/ViktorVitsk/linSec#safe-demonstration).

CI evidence links to successful runs verified on 9 October 2026.

## Other projects

- **[Ogorod Market](https://github.com/ViktorVitsk/ogorod-market)** — independent 2025 storefront prototype using Next.js, FastAPI and PostgreSQL, with authentication, a catalogue and a cart API.
- **[ASCP](https://github.com/ViktorVitsk/ASCP)** — archived research prototype for read-only linSec status reporting and optional model explanations. Its [report contract](https://github.com/ViktorVitsk/ASCP/blob/master/docs/core-report-contract.md) separates deterministic evidence from model output; the [test-quality audit](https://github.com/ViktorVitsk/ASCP/blob/master/docs/test-quality-audit-2026-10-05.md) traces process and report failures to regressions. 

## Learning and collaboration

- **2021 — programming foundations:** computer science, algorithms, data structures and Java coursework.
- **2022 — [RS School JavaScript / Front-end](https://github.com/ViktorVitsk/RSSchool-tasks):** responsive layouts, TypeScript and asynchronous applications, with preserved development history. [Certificate](https://app.rs.school/certificate/pupy1aod).
- **2022 — [RS Lang team coursework](https://github.com/Lebedev-023046/rslang):** my merged pull requests include [API implementation #21](https://github.com/Lebedev-023046/rslang/pull/21), [user-word game work #38](https://github.com/Lebedev-023046/rslang/pull/38), and [Sprint game page #40](https://github.com/Lebedev-023046/rslang/pull/40).
- **2023 — [Telegram GPT voice bot](https://github.com/ViktorVitsk/tg-bot-with-gpt):** an early TypeScript experiment with Telegram, Whisper transcription and GPT integration, preserved as historical work.

## Technical background

- **Backend and data:** Python, FastAPI, SQLAlchemy, PostgreSQL, SQLite, REST APIs, authentication and migrations.
- **Frontend:** JavaScript, TypeScript, React, Next.js, HTML/CSS and browser persistence.
- **Devices and integrations:** ESP32, MicroPython, GPIO, MQTT, Telegram bots, LLM APIs and user-confirmed tool actions.
- **Development and verification:** Git, Linux, Docker Compose, pytest/unittest, browser testing and GitHub Actions.

Earlier study and experiments also include Django, Angular and Vue. My current exploration focuses on coding-agent workflows, sandboxed execution and permission boundaries.
