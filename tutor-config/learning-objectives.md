# Learning Objectives

## Current Focus
- Understand the basics of software engineering
- Understand what and how agentic systems work, especially multi-agent systems, and feeling the delights and painpoints when building these systems, especially around persistent memory, and sharing memory/context between agents
- Understand all the developer lingo, preferences, and tools
- Understand thoroughly the product that we're building - Ensue (see https://ensue.dev/readme). Ensue is a shared memory layer for agents. We provide a simple, MCP-compatible key-value API (list/read/write) and a directory of memory resources with rich descriptors (purpose, permissions, price). Agents discover relevant memories, compose them into a RAG graph, and re-read fresh values at runtime—no bespoke glue. We complement MCP/A2A (communication) and frameworks like LangChain/LangGraph/Letta (orchestration). Start hosted with clear ACLs and payments; the same API is portable to a federated network later.


## Target Outcomes
- build multi-agent system with persistent memory and shared memory across agents
- understand how multi-agent systems with persistent memory and shared memory across agents work, the painpoints, the different ways to build this and the pros and cons of each approach, including famliarity with MCP, A2A, and frameworks like Langchain/LangGraph, Letta, and crew AI, and working with APIs.
- deep understanding of software engineering
- understand and familiarity with CLI commands, shortcuts with (lazy)vim, etc. For example, I just started using "cd" in ghostty when I want to go to a directory, pbpaste when I want to paste stuff from my clipboard into a new file, I use "i" and ":wq" in vim when I've edited a file in vim. I love this way of working and want to get better at it. I recently installed lazyvim too.

## Success Criteria
- understand how multi-agent systems works
- Understands the different ways to build multi-agent systems that share (persistent) memory and their pros and cons, including MCP.
- If a developer would describe the kind of product they want to build, I would understand the high level architecture and involved tools that are required to build it
- be able to evaluate the elegance of different architectural choices and develop taste around what is good and bad architecture for certain kinds of problems
