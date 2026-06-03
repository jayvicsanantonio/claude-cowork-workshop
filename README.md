# Claude Co-Work Workshop

Welcome to the **Claude Co-Work Workshop**! This repository features an interactive, comprehensive course that combines the strategic **AI Operator Method** with a detailed diagnostics guide to **AI Limitations**.

---

## Unified Workshop (`index.html`)

Instead of viewing the files in isolation, open [index.html](file:///Users/jayvicsanantonio/Developer/claude-cowork-workshop/index.html) in your web browser. It hosts a cohesive learning curriculum, structured as follows:

### 1. **Master Tactics**
- **Meta-Move 1: Use AI to use AI**: Learn how to collaborate with a model to design your prompts before execution.
- **Meta-Move 2: Break it down**: Understand thread segregation and handoff patterns across isolated sessions.

### 2. **Course Modules**
We map the **8 Failure Modes** from the AI Field Guide directly to the **4 Phases of the AI Operator Loop** to secure your pipeline logic:
* **Gather Phase (Module 1)**: Curate shapes, voice, substance, and constraints.
  * *Threat Model*: Cold Start & Context Tax (№ 01), Finite Context Windows (№ 06), and Knowledge Cutoff (№ 07).
* **Brainstorm Phase (Module 2)**: Collaborate with the model as a strategy partner.
  * *Threat Model*: Sycophancy & Flattery (№ 03) and the Overeager Intern guessing requirements (№ 04).
* **Draft Phase (Module 3)**: Lock structural markdown narratives.
  * *Threat Model*: Tyranny of the Average (№ 08).
* **Build Phase (Module 4)**: Compile into target formats and fact-check.
  * *Threat Model*: Hallucinations and Confident Fabrications (№ 02).
* **Hygiene Layer (Module 5)**: Preservation guidelines for long sessions.
  * *Threat Model*: Context Rot & attention decay (№ 05).

### 3. **Interactive Utilities**
- **Kickoff Prompt Customizer**: Input your target deliverable parameters (outputs, inputs, constraints, and audience) to dynamically compile a robust "First Message Intake Prompt" that forces the model to halt and interview you before writing.
- **The AI Operator Challenge**: A 5-question scenario quiz testing your ability to deploy prompt workarounds. Scoring unlocks a completion certificate badge.

---

## Getting Started

Simply open `index.html` directly in your browser:
* Double-click [index.html](file:///Users/jayvicsanantonio/Developer/claude-cowork-workshop/index.html) from your file explorer.
* Or, if running locally, use a local server like VS Code's Live Server or run `npx serve .` to preview the page.

---

## Design & Tech Stack

* Dark-mode aesthetics with glassmorphic cards (`backdrop-filter`).
* Font pairing: *Fraunces* (editorial headers), *Outfit/DM Sans* (UI and body), and *JetBrains Mono* (prompts and code).
* SVG interactive diagram models.
* Standard HSL responsive layouts.
* Zero-dependency vanilla JavaScript logic.

