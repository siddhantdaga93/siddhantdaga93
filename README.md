# MobileForge

**Every AI app builder generates web apps. MobileForge generates native iOS and Android apps that ship to the App Store.**

---

## Apps Built with MobileForge

Four prompts. Four apps. Four completely different design languages. All running on real iPhones.

<br>

**Tideline** &nbsp;·&nbsp; *"Build a surf session tracker with wave quality ratings"*

| &nbsp; | &nbsp; | &nbsp; |
|---|---|---|
| ![](https://github.com/user-attachments/assets/fe0feb0b-fb8f-4dfc-82a0-878a69614abc) | ![](https://github.com/user-attachments/assets/0d8c3474-379f-4728-a5fc-0e47ebe4ecb0) | ![](https://github.com/user-attachments/assets/818dfa6c-c34e-47f8-bd69-c410ae7addce) |

<br>

**Workout Tracker** &nbsp;·&nbsp; *"Build a fitness logger with calorie tracking and a journey dashboard"*

| &nbsp; | &nbsp; | &nbsp; |
|---|---|---|
| ![](https://github.com/user-attachments/assets/53caa812-c570-471f-a973-7d4823ab5fa7) | ![](https://github.com/user-attachments/assets/d9d583a5-750c-49d4-a128-2ecc659046de) | ![](https://github.com/user-attachments/assets/388ea721-1792-48d2-9cd5-d1453a6cb755) |

<br>

**Mireille** &nbsp;·&nbsp; *"Build a recipe manager with categories and chef preferences"*

| &nbsp; | &nbsp; | &nbsp; |
|---|---|---|
| ![](https://github.com/user-attachments/assets/5ff27fae-0a51-448e-887f-14632f123666) | ![](https://github.com/user-attachments/assets/91e7ffb6-f266-46c4-91cd-79696a144f05) | ![](https://github.com/user-attachments/assets/d67a928d-c7a2-4b3b-bfcf-538f00d3e9d2) |

<br>

**Pawfound** &nbsp;·&nbsp; *"Build a pet adoption app with animal profiles and shelter info"*

| &nbsp; | &nbsp; | &nbsp; |
|---|---|---|
| ![](https://github.com/user-attachments/assets/680206e7-fe46-434c-9444-a53f7b6704eb) | ![](https://github.com/user-attachments/assets/bdc9c2e3-cc10-4ad0-8c47-1693dc3e773a) | ![](https://github.com/user-attachments/assets/88636bcb-f2f0-49b8-89e8-3a22d78ded1c) |

---

## What It Is

MobileForge is a platform that turns a text prompt into a complete, deployable React Native app in under 60 seconds. The output is real native code — not a web wrapper, not a prototype — that compiles and ships to the App Store via Expo's build infrastructure.

Users describe what they want. The platform handles architecture, design, data layer, and navigation. Each app gets a unique visual identity — color palette, typography, component layout — derived from the prompt context. No two apps look the same.

Post-generation, users iterate through natural language edits. Each edit resolves to the exact file that needs changing, rewrites it completely with full context, and refreshes the preview. The platform handles the rest.

---

## Product Decisions Worth Noting

**Local-first by default.** Apps work immediately with on-device storage. No backend setup, no auth friction, no configuration. Backend connectivity is an upgrade path, not a prerequisite — which means the first experience is always fast and complete.

**Design ownership stays with the AI.** The platform enforces structural contracts (file boundaries, data hooks, navigation patterns) and gives the AI complete creative freedom over everything visual. This produces genuinely different apps rather than variations of the same template.

**Edit pipeline designed for reliability over features.** One model call per edit, full file in context, complete file returned. No retry loops, no validation chains. Fewer moving parts means fewer failure modes.

**Generation and editing are separate concerns.** Generation optimizes for visual quality and completeness. Editing optimizes for precision and speed. Different prompting strategies, different models, different constraints.

---

## Stack

React Native · Expo · TypeScript · Next.js · Anthropic Claude · Supabase · Prisma · EAS Build

---

*In active development. Private repository.*  
siddhantdaga93@gmail.com &nbsp;·&nbsp; [linkedin.com/in/siddhantdaga](https://linkedin.com/in/siddhantdaga)
