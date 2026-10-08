# Viktor Stoianov

**Full-stack developer · Python & TypeScript · AI applications · IoT**

I build web applications and experimental systems that connect user interfaces, APIs, databases, AI models and physical devices. My projects range from an encrypted personal journal to an ESP32 greenhouse controller. I've been studying and building software since 2021.

## Selected projects

### [LifeLog — encrypted personal journal and AI-assisted logging](https://github.com/ViktorVitsk/LifeLog)
**React · TypeScript · Dexie/IndexedDB · FastAPI · PostgreSQL**

An experimental full-stack MVP with browser-side encryption of sensitive text, offline change queues, versioned synchronisation and conflict handling. AI integrations can propose structured actions, which require user confirmation before saving. Includes a local fictional-data demo, database/browser regression tests and [GitHub Actions CI](https://github.com/ViktorVitsk/LifeLog/actions). Built for personal experimentation, not public hosting with sensitive data.

### [Grow System — ESP32 greenhouse automation](https://github.com/ViktorVitsk/Grow-System)
**ESP32 · MicroPython · MQTT · FastAPI · PostgreSQL · React**

A physical prototype combining soil, climate and water sensors with pump/relay control, Telegram commands and a web dashboard. The firmware separates automation decisions from hardware access and enforces bounded output durations and sensor interlocks. I selected, wired, soldered, flashed and tested the equipment. A [synthetic dashboard preview](https://github.com/ViktorVitsk/Grow-System/blob/main/docs/assets/demo-dashboard.png) is available; the revised firmware still needs a new hardware test and long-term growing trials.

### [Ogorod Market — family-farm storefront prototype](https://github.com/ViktorVitsk/ogorod-market)
**Next.js · React · TypeScript · FastAPI · SQLAlchemy · PostgreSQL**

A full-stack shop prototype developed in 2025, with authentication, product catalogue management and a cart API. It is not a completed e-commerce service: checkout, orders and payments are not implemented.

## Technical background

- **Backend and data:** Python, FastAPI, SQLAlchemy, PostgreSQL, REST APIs, authentication, migrations; Django experience from independent study.
- **Frontend:** JavaScript, TypeScript, React, Next.js, HTML/CSS; Angular and Vue through coursework and experiments.
- **Devices and integrations:** ESP32, MicroPython, sensors, GPIO, MQTT, Telegram bots, LLM APIs and user-confirmed tool actions.
- **Development and verification:** Git, Linux, Docker Compose, pytest, browser testing and GitHub Actions CI.

## Learning and earlier work

- **2021 — computer science and Java:** intensive coursework in programming fundamentals, algorithms, data structures and practical Java assignments.
- **2022 — [RS School, JavaScript / Front-end](https://github.com/ViktorVitsk/RSSchool-tasks):** frontend projects with preserved development history, including responsive layouts, TypeScript and asynchronous applications. [Certificate](https://app.rs.school/certificate/pupy1aod).
- **2023 — [Telegram GPT voice bot](https://github.com/ViktorVitsk/tg-bot-with-gpt):** an early TypeScript experiment with Telegram, Whisper transcription and GPT integration.

## Current exploration

I'm exploring multi-model coding-agent workflows with [DeepSeek Harness](https://github.com/deepseek-ai/deepseek-harness), sandboxed execution and permission boundaries. Earlier experiments include [ASCP](https://github.com/ViktorVitsk/ASCP) and [linSec](https://github.com/ViktorVitsk/linSec), research prototypes rather than deployed security products.

## How I work

I use AI assistants for architecture discussions, implementation and code review. My role includes defining requirements, comparing technical approaches, integrating components and checking results. The projects are openly described as AI-assisted, and their repositories distinguish tested functionality from planned work and known limitations.
