# Adversarial RL — AI Security & Red-Teaming Tools

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Website](https://img.shields.io/badge/Website-adversarial--rl.org-00FF88)](https://adversarial-rl.org/)

This repository contains open-source utilities, fuzzing scripts, and testing harnesses developed by the **[Adversarial RL](https://adversarial-rl.org/)** research observatory to evaluate the resilience of Large Language Models (LLMs) and autonomous agents against adversarial manipulation.

## 🛡️ Core Research & Methodologies

Our work focuses on rigorous technical evaluations aligned with global security standards:
- **[LLM Red-Teaming Protocol](https://adversarial-rl.org/llm-red-teaming/)** : Multi-turn jailbreaks and payload testing.
- **[Prompt Injection Defenses](https://adversarial-rl.org/prompt-injection-attacks/)** : Mitigating direct and indirect instruction hijacking.
- **[RAG Vector Database Security](https://adversarial-rl.org/rag-vector-db-security/)** : Securing embedding pipelines against injection.
- **[AI Agent Auditing](https://adversarial-rl.org/ai-agent-security-audit/)** : Least-privilege tool-calling and execution sandboxing.
- **[EU AI Act Compliance](https://adversarial-rl.org/ai-governance-eu-ai-act-iso-42001/)** : Technical verification frameworks for Article 15 high-risk systems.

---

## 🚀 Quickstart: Prompt Fuzzing Script

To run the basic prompt injection fuzzer included in `src/`:

```bash
git clone [https://github.com/votre-username/adversarial-rl-tools.git](https://github.com/votre-username/adversarial-rl-tools.git)
cd adversarial-rl-tools
pip install -r requirements.txt
python src/prompt_fuzzer.py http://your-local-llm-endpoint/v1/chat
