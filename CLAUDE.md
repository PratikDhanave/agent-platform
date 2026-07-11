# Agent Platform

Curated samples and tutorials for building agents on **Gemini Enterprise Agent Platform** (previously Vertex AI). Maintained by Google Cloud.

## Project Structure

This is primarily a documentation and reference repository. The README serves as the main index linking to external resources across the platform ecosystem:

- **Foundation Models** — Gemini API, Veo, Lyria, Nano Banana, Model Garden
- **Build** — ADK, Agents CLI, Agent Studio, Agent Garden, Grounding, RAG Engine
- **Protocols** — A2A, MCP, A2UI, AP2, UCP
- **Scale** — Agent Runtime, Sessions, Memory Bank, Sandbox
- **Govern** — Gateway, Identity, Policies, Registry, Model Armor
- **Optimize** — Evaluation, Simulation, Observability, Optimizer

## Conventions

- Follow Google's Open Source Community Guidelines
- All contributions require a Google CLA (Contributor License Agreement)
- All changes go through GitHub pull requests with code review
- README links use shortened Google URLs (`goo.gle/...`) where available

## Languages & Tooling

The `.gitignore` supports Python, Node.js, and Terraform. When adding code:

- **Python**: Use virtual environments, follow PEP 8
- **Node.js**: Use `node_modules/` (gitignored)
- **Terraform**: State files are gitignored
- **Jupyter Notebooks**: `.ipynb_checkpoints` are gitignored

## What NOT to Do

- Do not commit secrets, credentials, or `.env` files
- Do not commit IDE-specific files (`.idea/`, `.vscode/settings.json`)
- Do not add large binary files to the repo
- Do not modify links without verifying they resolve correctly
