# ai-skill-adapters (scaffold)

This repository defines a small universal skill manifest and adapters to invoke skills across platforms.

Quickstart
1. python -m venv .venv && source .venv/bin/activate
2. pip install -r requirements.txt
3. pytest
4. python -m examples.skills.summarize.implementation --text "Your text here"

Notes
- The OpenAI adapter will run only if OPENAI_API_KEY is set in the environment.
- Expand by adding more skills in examples/skills and adapters under adapters/.
