# MindFlow AI — State-Driven AI Well-Being Engine

A decoupled, multi-layered software architecture prototype designed to demonstrate how deterministic programmatic guardrails, Finite State Machines (FSM), and real-time Natural Language Processing (NLP) telemetry can be engineered to enclose and constrain generative Large Language Models (LLMs).

This project was built to address a critical challenge in modern AI safety: mitigating risks and enforcing structural boundaries when deploying open-ended generative models within sensitive domains like mental health and cognitive well-being.

---

## 🛠️ System Architecture & Data Pipeline

Rather than relying on a standard open-ended chatbot wrapper, **MindFlow AI** processes user inputs through three isolated algorithmic layers before generating a response:
[ User Input ]
│
▼
[ LAYER 1: Deterministic Safety Interceptor ] ──► (Short-circuits payload on crisis keywords)
│
▼
[ LAYER 2: Text Telemetry Extractor (NLP) ]   ──► (Computes mathematical sentiment & emotion)
│
▼
[ LAYER 3: Finite State Machine (FSM) ]       ──► (Progresses conversation stage variables)
│
▼
[ Context-Aware Dynamic Prompt Injection ]    ──► (Combines data stream into Gemini LLM Engine)

Here is a complete, polished, and professionally formatted `README.md` file for your GitHub repository or application portfolio. It is explicitly structured using the terminology that university admissions committees and computer science professors look for.

---

# `README.md`

```markdown
# MindFlow AI — State-Driven AI Well-Being Engine

A decoupled, multi-layered software architecture prototype designed to demonstrate how deterministic programmatic guardrails, Finite State Machines (FSM), and real-time Natural Language Processing (NLP) telemetry can be engineered to enclose and constrain generative Large Language Models (LLMs).

This project was built to address a critical challenge in modern AI safety: mitigating risks and enforcing structural boundaries when deploying open-ended generative models within sensitive domains like mental health and cognitive well-being.

---

## 🛠️ System Architecture & Data Pipeline

Rather than relying on a standard open-ended chatbot wrapper, **MindFlow AI** processes user inputs through three isolated algorithmic layers before generating a response:


```

[ User Input ]
│
▼
[ LAYER 1: Deterministic Safety Interceptor ] ──► (Short-circuits payload on crisis keywords)
│
▼
[ LAYER 2: Text Telemetry Extractor (NLP) ]   ──► (Computes mathematical sentiment & emotion)
│
▼
[ LAYER 3: Finite State Machine (FSM) ]       ──► (Progresses conversation stage variables)
│
▼
[ Context-Aware Dynamic Prompt Injection ]    ──► (Combines data stream into Gemini LLM Engine)


### 1. Deterministic Safety Interceptor (Hard Guardrail)
* **Mechanic:** The system scans strings locally for severe crisis keywords before any external API payload is compiled.
* **Engineering Purpose:** If triggered, the code completely short-circuits. It blocks network requests to the cloud LLM to minimize latency and instantly forces a hardcoded structural response containing verified emergency resources.

### 2. Telemetry Extractor (NLP Layer)
* **Mechanic:** Utilizes a local lexicon-based Natural Language Processing engine (`TextBlob`) to extract mathematical properties from subjective human text.
* **Engineering Purpose:** Calculates real-time sentiment polarity scores ranging precisely from `-1.0` (extreme negative distress) to `+1.0` (positive/relief) along with heuristic categorical emotion trees (Anxiety, Sadness, Anger, Joy).

### 3. Dialogue State Machine (Structural Controller)
* **Mechanic:** Manages a strict 3-stage linear progression sequence mapping standard clinical cognitive reframing protocols: `1. Assessment` ➔ `2. Cognitive Reframing` ➔ `3. Final Reflection`.
* **Engineering Purpose:** Prevents the AI model from wandering off-topic or hallucinating by forcing it to adapt its system instructions dynamically based on the active structural state of the conversation.

---

## 🚀 Technical Stack

* **Language:** Python 3.10+
* **LLM Engine Architecture:** Google GenAI Native SDK (`gemini-2.5-flash`)
* **Natural Language Processing:** TextBlob (Lexicon/Heuristic parsing)
* **User Interface:** Gradio (Responsive dual-panel telemetry dashboard hosted via Google Colab)

---

## 🔬 Current Engineering Scope & Evolving Roadmap

This repository represents an **active, evolving prototype**. While the local deterministic security boundaries and NLP telemetry calculations operate seamlessly, managing stateful asynchronous context synchronization within cloud-based LLM architectures presents highly complex edge cases. Leaving the project in this state highlights an active study of runtime pipeline optimization and data structure constraints.

### Planned System Enhancements:
1. **State Persistence and Storage:** Transition from in-memory dictionary-based session histories to an explicit local database architecture (e.g., SQLite) to securely handle long-term dialogue memory.
2. **Schema Enforcement:** Implement strict data contract typing via `Pydantic` to enforce rigorous structure over API request/response payloads and entirely eliminate data formatting errors.
3. **Advanced Telemetry:** Replace the lightweight rule-based lexicon engine with a fine-tuned, local transformer model (e.g., a micro-BERT pipeline) to achieve robust, contextual emotion classification.

```
