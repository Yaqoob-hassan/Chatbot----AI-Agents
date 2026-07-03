# Chatbot & AI Agents — Learning with the Anthropic API

Notes and code from Anthropic's official Skilljar course on building with Claude. This repo tracks my hands-on progress through the fundamentals of the Anthropic API — from a basic chatbot to prompt evaluation and prompting techniques.

## What's inside

**`ChatBot/`**
- A basic conversational chatbot built directly on the Anthropic API (`messages` endpoint), covering system prompts, multi-turn message handling, and response streaming basics.
- Prompt evaluation workflows — testing and scoring prompt outputs against expected results.
- Prompting techniques — few-shot examples, role prompting, chain-of-thought, output formatting, and other patterns for getting more reliable completions.

## Tech stack

- Python
- Jupyter Notebook
- [Anthropic API](https://docs.claude.com) (`anthropic` Python SDK)

## Setup

```bash
git clone https://github.com/Yaqoob-hassan/Chatbot----AI-Agents.git
cd Chatbot----AI-Agents
pip install anthropic jupyter
```

Set your API key as an environment variable:

```bash
export ANTHROPIC_API_KEY="your-key-here"
```

Then launch the notebooks:

```bash
jupyter notebook
```

## Status

🚧 Actively being updated as I work through the course. More notebooks (tool use, agents) will be added as I progress.

## Reference

Course: [Anthropic Skilljar](https://anthropic.skilljar.com/) — Claude API fundamentals.

---

**Author:** [Muhammad Yaqoob Hassan](https://github.com/Yaqoob-hassan) · [LinkedIn](https://www.linkedin.com/in/muhammad-yaqoob-hassan)
