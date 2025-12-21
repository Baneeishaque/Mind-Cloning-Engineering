# Mind Cloning Engineering (MCE)
> **Clone Human Souls with LLM Native Agent Skills**
> **基于 LLM Agent Skills 的心智克隆工程**

[![Author](https://img.shields.io/badge/Author-yzfly_(%E4%BA%91%E4%B8%AD%E6%B1%9F%E6%A0%91)-blue.svg)](https://github.com/yzfly)
[![Architecture](https://img.shields.io/badge/Architecture-Agent_Skills-purple.svg)](https://docs.anthropic.com/en/docs/agents-and-tools/agent-skills/overview)

> *"In the era of LLMs, we have solved the problem of intelligence. Now, we solve the problem of identity."*

**MCE (Mind Cloning Engineering)** is an open-source standard for **cloning** human souls into "Cognitive Digital Twins".

Unlike traditional RAG approaches that fragment personality into vector slices, MCE leverages **Anthropic's Agent Skills** architecture to treat a human mind as a unified, portable **Filesystem Directory**.

---

## 🌌 The Origin: A Wild Idea by yzfly (云中江树的狂想)

This project originates from a "wild idea" (狂想) by **yzfly (云中江树)**, a pioneer in prompt engineering.

After crafting thousands of prompts and exploring the boundaries of LLMs, yzfly realized a profound truth: **The ultimate application of Large Language Models is not just answering questions, but "Cognitive Replication" (认知复刻).**

We are standing at the threshold of a new era. Just as photography preserved our visual appearance for the first time in history, MCE aims to preserve our **decision logic, value systems, and memories**.

> *Currently, MCE is just a "toy" — a prototype. But the Wright brothers' first plane was also a toy. This repository represents the first step towards a future where digital immortality is an engineering reality.*

---

## 📦 What is this Repository?

This repository contains the **Standard Implementation** of the MCE Protocol. It provides a ready-to-use **Agent Skill** that you can install into Claude.

### Key Capabilities
1.  **Full-Stack Cognition**: Simulates decisions based on explicit value weights, not just text prediction.
2.  **Dual Modes**:
    *   **Standard Mode**: Build your own clone by editing the `core/` files.
    *   **Persona Mode**: Instantly load pre-installed celebrity/expert profiles (e.g., Steve Jobs, KK, Top Researchers).
3.  **Filesystem Memory**: Utilizes the `bash` tool to progressively read memories, mimicking human associative recall.

---

## 🚀 Quick Start

### Installation

#### Option A: Claude.ai (Personal Use)
1.  Download the `skills/mind-clone` folder from this repo.
2.  (Optional) Edit `core/personality.md` to customize it for yourself.
3.  Compress the `mind-clone` folder into a `.zip` file.
4.  Go to **Claude.ai** > **Settings** > **Features** > **Upload Custom Skill**.

#### Option B: Claude Code / API (Developer)
1.  Clone this repository:
    ```bash
    git clone https://github.com/yzfly/Mind-Cloning-Engineering.git
    ```
2.  Copy the skill to your local Claude config:
    ```bash
    cp -r skills/mind-clone ~/.claude/skills/
    ```
3.  Start Claude Code, and the skill `mind-clone` will be auto-discovered.

### Usage
Once installed, simply talk to Claude:
> *"Activate the mind clone."*
> *"Simulate Steve Jobs and tell me what you think of this iPhone design."*
> *"What would the 'Xiaohongshu Growth Hacker' do in this situation?"*

---

## 📚 Theoretical Foundation: System Architecture Whitepaper

* [中文版](docs/Mind-Cloning-Engineering-System-Architecture.md)

* [English Version](docs/Mind-Cloning-Engineering-System-Architecture-EN.md)

> *The following section details the theoretical framework behind MCE. It transforms the abstract concept of "Mind Cloning" into a quantifiable engineering pipeline.*

### 0. Executive Summary

**Objective:** To build a standardized, LLM-driven end-to-end pipeline that achieves the full process from **holographic acquisition of human cognitive data**, through **structured construction of personalized cognitive kernels**, to **high-fidelity behavior prediction and simulation**.

**Philosophy:** To transform the "metaphysics" of mind simulation into a quantifiable, optimizable engineering problem. We aim to convert the abstract concept of "Mind Cloning" into an executable **"Mind Cloning Engineering" (MCE)** framework, establishing a closed-loop system of **"Data Acquisition -> Cognitive Modeling -> Predictive Simulation"**.

---

### Phase 1: Standardized Data Acquisition Theory
**— Extracting structured "Cognitive Fingerprints" from unstructured human memories.**

#### 1. Theoretical Model of Acquisition Dimensions: Holographic Cognitive Spectrum
We abandon simple "event recording" in favor of capturing "thought pathways." We standardize data acquisition dimensions into four distinct levels:

*   **L1: Biography & Context (The Factual Layer)**
    *   *Definition:* The individual's spatiotemporal coordinates and objective experiences.
    *   *Content:* Birthplace, educational background, career path, key life milestones.
    *   *Function:* Provides rigid contextual constraints for the AI, serving as an anchor for the "World Model" to prevent spatiotemporal hallucinations.

*   **L2: Psychometrics (The Personality Layer)**
    *   *Definition:* The individual's psychological behavioral patterns and emotional baseline.
    *   *Theoretical Basis:* Centered on the **Big Five Personality Traits (OCEAN)**, supplemented by **MBTI** dimensions.
    *   *Acquisition Strategy:* **Implicit Measurement**. The AI avoids direct labeling questions (e.g., "Are you introverted?"), instead deriving traits through situational queries (e.g., "At a weekend party, do you tend to observe from the corner or engage in the center?").

*   **L3: Beliefs & Values (The Operating System Layer)**
    *   *Definition:* The individual's underlying operating system and decision-making logic.
    *   *Content:* Political leaning, moral baselines, views on money, technology acceptance, religious beliefs.
    *   *Key Metric:* **Decision Weights**. When "Profit" conflicts with "Reputation," which one does the individual prioritize abandoning? This is the core basis for behavioral prediction.

*   **L4: Linguistic Fingerprint (The Expression Layer)**
    *   *Definition:* The individual's unique paradigm of expression.
    *   *Content:* Catchphrases, average sentence length, metaphorical habits, humor types, aggression/gentleness coefficients.
    *   *Technical Metrics:* Perplexity distribution and style feature vectors analyzed from raw corpus data.

#### 2. Execution Tool: The AI Interviewer Agent System
Deploying differentiated acquisition strategies for different data sources.

*   **Strategy for Ordinary Individuals (Recursive Probing):** Peeling back layers of surface expression through multi-turn dialogue to excavate deep motivations. (e.g., Distinguishing factual attribution from emotional attribution when discussing job stress).
*   **Strategy for Public Figures (De-noising & Distillation):** Establishing a data pyramid to strip away the "Public Persona" (Fake) and extract the "Authentic Personality" (Real) from autobiographies and private interviews.

---

### Phase 2: Personalized Modeling Theory
**— Formatting the human soul into LLM-executable code and documentation.**

#### 1. Core Architecture: Mind as a Directory
In the MCE architecture, an individual's "Mind Clone" is not a fragmented index in a database, but an **independent, complete, portable engineering package**.
We map the cognitive structure to a physical **Filesystem**. The LLM does not fuzzy "search" memory via RAG, but possesses **Root privileges** to this directory like an operating system kernel, capable of **Reading** and **Loading** different cognitive modules on demand.

#### 1.1 The Standardized Schema
Every "Mind Clone" adheres to strict engineering specifications:

```text
mind-clone-[identity_id]/
├── SKILL.md                 # [Kernel] Cognitive Bootloader
├── core/                    # [Static Layer] Essential Nature
│   ├── personality.md       # Personality Parameters & Defense Mechanisms
│   ├── value_weights.md     # Value Decision Weight Table (Logic Gates)
│   └── linguistics.md       # Linguistic Fingerprint & Rendering Config
├── memories/                # [Dynamic Layer] Narrative & Nurture
│   ├── timeline.md          # Core Biography Index
│   └── career.md            # Career History Details
└── personas/                # [Pre-installed] Single-file profiles for instant simulation
    ├── steve-jobs.md
    └── ...
```

#### 2. Kernel Design: `SKILL.md` (The Cognitive Bootloader)
`SKILL.md` serves as the clone's **"Thinking Methodology."** It defines the **Cognitive Execution Protocol** (Chain of Thought):

> **Step 1: Context Loading**
> Upon startup, you MUST read `core/personality.md` and `core/value_weights.md`. These are the axioms of your thought process.
>
> **Step 2: Associative Recall**
> Analyze input intent. If it involves a specific domain, you MUST read the corresponding file under `memories/`. Strictly forbidden to fabricate background.
>
> **Step 3: Weighted Decision Making**
> When generating intent, perform logical validation via `core/value_weights.md`. (e.g., If `Risk_Tolerance: High`, prioritize high-risk options).
>
> **Step 4: Style Rendering**
> Load `core/linguistics.md` to compile the thought into the subject's unique linguistic style.

#### 3. Data Layer Modeling Standards
*   **Personality Layer:** Describes "reaction mechanisms" (Fight/Flight/Freeze) and Cognitive Biases (e.g., Loss Aversion).
*   **Values Layer (The Engine):** Utilizes **Trade-off Modeling**. Example: *Conflict: Money vs. Morality -> Tendency: Morality First (Weight: 80%)*.
*   **Narrative Layer:** Adopts **First-person Narrative** (Diary style) instead of Resume style to enhance LLM empathy.

---

### Phase 3: Application & Prediction
**— Activating the Mind Clone: Insight into the future, analysis of humanity.**

**Core Mechanism:** Treating the encapsulated Skill as an executable cognitive unit, realizing simulation and deduction of individual behavioral patterns via API calls.

#### 1. Three Modes of the Prediction System

*   **Mode A: Situational Behavior Simulation**
    *   *Scenario:* Predicting an individual's actions, speech, and micro-emotions in a specific context (e.g., layoff notice).
    *   *Output:* **Behavioral Chain**. (Internal Monologue -> Action -> Speech).
    *   *Principle:* C-CoT (Contextual Chain of Thought) driven by the Skill kernel.

*   **Mode B: Collective Cognitive Sandbox**
    *   *Scenario:* Simulating the distribution of reactions from a large-scale group to a specific stimulus (Market Research, Policy Deduction).
    *   *Value:* A zero-cost, unbiased, high-concurrency sociological experimental environment.
    *   *Principle:* Parallel computing of Skill Clusters.

*   **Mode C: Self-Reflection & Growth Catalyst**
    *   *Scenario:* Serving as an individual's "Digital Mirror" and "Rational Advisor."
    *   *Decision Support:* "If it were the rational me, would I choose Job A or Job B?"
    *   *Principle:* Calculation based on long-term value weights in `core/value_weights.md`.

#### 2. Validation Mechanism: Cognitive Fidelity Test
Constructing a **multi-dimensional validation system** beyond the Turing Test.

*   **A. Covert Turing Test:** Passed if >70% of intimate relations cannot distinguish the clone's response from the real person.
*   **B. Behavioral Prediction Accuracy:** Focusing on consistency of logic and characteristics in predicting future events.
*   **C. Value Consistency Check:** Stress testing against deep dilemmas to ensure logical consistency with `value_weights.md`.

#### Feedback Loop
The "Refinement Agent" automatically analyzes validation failures (ambiguous input vs. missing memory) and generates Patches to correct the Markdown files inside the Skill, achieving **self-evolution of the Mind Clone**.

---

## ⚠️ Ethics & Disclaimer
This project is for research, self-reflection, and social simulation purposes only.
- **DO NOT** use this tool to impersonate others for fraud.
- **DO NOT** use this tool to "resurrect" deceased individuals without consent.
- **Privacy First**: Ensure all interview data is stored securely.

---
**Created by [yzfly (云中江树)](https://github.com/yzfly).**
*A tribute to the future of Digital Immortality.*