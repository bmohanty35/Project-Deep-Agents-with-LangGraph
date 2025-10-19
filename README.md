# 🧱 Deep Agents from Scratch

<img width="720" height="289" alt="Screenshot 2025-08-12 at 2 13 54 PM" src="https://github.com/user-attachments/assets/90e5a7a3-7e88-4cbe-98f6-5b2581c94036" />

* **Task planning (e.g., TODO), often with recitation**
* **Context offloading to file systems**
* **Context isolation through sub-agent delegation**

This course will show how to implement these patterns from scratch using LangGraph! 

### Project Overview

This repository contains five progressive notebooks to build advanced AI agents:

### `0_create_agent.ipynb` -
This component,
- implements a ReAct (Reason - Act) loop that forms the foundation for many agents.
- is easy to use and quick to set up.
- serves as the

### `1_todo.ipynb` - Task Planning Foundations
This notebook introduces:
- Task tracking with status management (pending/in_progress/completed)  
- Progress monitoring and context management
- The `write_todos()` tool for organizing complex multi-step workflows
- Best practices for maintaining focus and preventing task drift

### `2_files.ipynb` - Virtual File Systems
Implement a virtual file system stored in agent state for context offloading:
- File operations: `ls()`, `read_file()`, `write_file()`, `edit_file()`
- Context management through information persistence
- Enabling agent "memory" across conversation turns
- Reducing token usage by storing detailed information in files

### `3_subagents.ipynb` - Context Isolation
Master sub-agent delegation for handling complex workflows:
- Creating specialized sub-agents with focused tool sets
- Context isolation to prevent confusion and task interference
- The `task()` delegation tool and agent registry patterns
- Parallel execution capabilities for independent research streams

### `4_full_agent.ipynb` - Complete Research Agent
Combine all techniques into a production-ready research agent:
- Integration of TODOs, files, and sub-agents
- Real web search with intelligent context offloading
- Content summarization and strategic thinking tools
- Complete workflow for complex research tasks with LangGraph Studio integration


Each notebook builds on the previous concepts, culminating in a sophisticated agent architecture capable of handling real-world research and analysis tasks. 


