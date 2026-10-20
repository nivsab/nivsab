# Hi, I'm Niv Saban

I'm seeking **software development roles in embedded systems, AI development, and machine learning**. My projects span low-level C/C++, applied NLP, and AI-powered business workflows.

[LinkedIn](https://www.linkedin.com/in/niv-saban-software-development) | [GitHub](https://github.com/nivsab)

## Embedded Systems & C++

Low-level software, concurrent applications, and firmware verification.

- **[STM32 Bare-Metal GPIO Driver](https://github.com/nivsab/STM32-Bare-Metal-GPIO-Driver)** — A C++ GPIO driver using direct register manipulation, object-oriented design, and non-blocking state machines.
- **[Multithreaded Sensor Simulation](https://github.com/nivsab/Multithreaded-Sensor-Simulation)** — A C++17 producer-consumer simulation with a thread-safe bounded queue, sensor interfaces, and a consumer thread pool.
- **[VirtuFirm-CI](https://github.com/nivsab/VirtuFirm-CI)** — A virtual firmware environment for simulating LED/button interactions and checking finite-state-machine behavior with Python automation.

**Technologies:** C, C++, STM32, multithreading, Python.

## Applied AI & Machine Learning

Document understanding, domain-specific evaluation, and retrieval-based assistants.

- **[Automated Datasheet Extraction](https://github.com/nivsab/datasheet-extraction)** — PDF-to-JSON extraction using synthetic training data and fine-tuned DeBERTa. The [published benchmark](https://github.com/nivsab/datasheet-extraction#benchmark-results) reports **T2-F1 of 0.587 on seven real-world datasheets**, versus 0.579 for preprocessing alone; T2 requires a parameter-name match and a numeric value within ±10% of the reference.
- **[CoEval: Hebrew Special Education Case Study](https://github.com/nivsab/CoEval-special_ed)** — Evaluated **five models across 40 Hebrew scenarios**, producing 200 responses and 1,050 valid judge evaluations. The [documented results](https://github.com/nivsab/CoEval-special_ed#results) show different leaders for stage assessment and intervention planning under the study's judge and rubrics.
- **[JACK: Vehicle Assistant & Manual Retrieval](https://github.com/nivsab/Jack_Skill)** — A Claude Code skill with structured PDF extraction, manual retrieval, cached vehicle specifications, and parts-search tools. **Code-level example:** `brake pad replacement` maps to `brake_caliper_torque` and `brake_fluid_type`, selecting relevant specification fields before retrieval.

**Technologies:** Python, PyTorch, DeBERTa, LLM evaluation, RAG, Supabase/pgvector, Ollama.

## Business Automation | 8200 for Businesses

### Client Project — Completed and in Client Use

Completed a project through **8200 for Businesses**, now in use by the client.

The available technical materials cover an **Operations Resolver** workflow for e-commerce support: retrieving order and customer information, checking return policies, and handling refund decisions or escalation to a human.

- **Business rules:** Explicit eligibility checks, refund limits, and escalation conditions.
- **Structured output:** A decision, supporting evidence, and a customer-facing reply in Hebrew.
- **Technical foundation:** Tool wrappers, typed agent state, and Pydantic output schemas, with LangGraph and Groq integration components.

**Technologies:** Python, LangGraph, LangChain, Groq, Pydantic.

## More Projects

- **[Taki Card Game](https://github.com/nivsab/taki-game)** — A multiplayer console game in C featuring special cards, dynamic memory management, and modular code.
- **[CoEval Framework Fork](https://github.com/nivsab/CoEval)** — My fork of the evaluation framework used for the special education case study.

---

Interested in embedded software, AI development, or ML opportunities? [Connect with me on LinkedIn](https://www.linkedin.com/in/niv-saban-software-development).
