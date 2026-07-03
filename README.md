# Chatbot & AI Agents — Learning with the Anthropic API (using Gemini)

Notes and code from Anthropic's official Skilljar course on building with Claude. The course itself is taught using the Anthropic (Claude) API, but I'm working through the exercises using a **Google Gemini API key** instead — same concepts, different model backend.

## What's inside

**`ChatBot/`**
- A basic conversational chatbot, covering system prompts, multi-turn message handling, and response basics — built following the course structure but wired up to the Gemini API.
- Prompt evaluation workflows — testing and scoring prompt outputs against expected results.
- Prompting techniques — few-shot examples, role prompting, chain-of-thought, output formatting, and other patterns for getting more reliable completions.

## Tech stack

- Python
- Jupyter Notebook
- [Google Gemini API](https://ai.google.dev/) (`google-generativeai` Python SDK)

## Setup

```bash
git clone https://github.com/Yaqoob-hassan/Chatbot----AI-Agents.git
cd Chatbot----AI-Agents
pip install google-generativeai jupyter
```

Set your API key as an environment variable:

```bash
export GEMINI_API_KEY="your-key-here"
```

Then launch the notebooks:

```bash
jupyter notebook
```

## Status

🚧 Actively being updated as I work through the course. More notebooks (tool use, agents) will be added as I progress.

## Reference

Course: [Anthropic Skilljar](https://anthropic.skilljar.com/) — Claude API fundamentals (concepts followed here, implemented with Gemini).

---

**Author:** [Muhammad Yaqoob Hassan](https://github.com/Yaqoob-hassan) · [LinkedIn](https://www.linkedin.com/in/muhammad-yaqoob-hassan)
