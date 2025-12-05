# Simple Multi-Agent

A simple multi-agent system with Supervisor, Researcher, and Writer nodes.
Demonstrates basic AI agent teamwork and workflow logic.

## Architecture

![Architecture Diagram](architecture_diagram.png)

**Nodes:**

- Supervisor: Routes workflow between agents
- Researcher: Gathers facts
- Writer: Writes a structured post

**Workflow:** Supervisor -> Researcher -> Supervisor -> Writer -> Supervisor -> FINISH

## Run

```bash
pip install -r requirements.txt
python multi_agent_flow.py
```
