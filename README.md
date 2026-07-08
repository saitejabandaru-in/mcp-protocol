# MCP Protocol

**Model Context Protocol — build tools that any AI can use. Connect AI to your files, databases, APIs, and services.**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

---

## What Is MCP?

MCP (Model Context Protocol) is an open standard for giving AI models access to tools:

AI Client (Claude, Cursor) <-> MCP Protocol <-> MCP Server (your tools)

You build an MCP server that exposes tools, and any MCP-compatible AI can use them.

## MCP Primitives

### Tools (Actions AI can take)
- query_database — Execute SQL and return results
- search_web — Search and return top results
- read_file — Read from filesystem
- call_api — Make external API calls

### Resources (Context AI can read)
- file://path — File contents
- db://tables — Database schema
- api://endpoint — Live data

### Prompts (Templates AI can use)
- Reusable prompt templates with parameters
- Standardize common AI tasks in your org

## 4 MCP Servers to Build

1. **File System MCP** — read/write access to files
2. **Database MCP** — natural language to SQL
3. **GitHub MCP** — read repos, create issues, list PRs
4. **Web Search MCP** — real-time web search

## Languages

Build MCP servers in Python or TypeScript.
Both have official SDKs from Anthropic.

---

Part of the [Real-World AI Skills Ecosystem](https://github.com/saitejabandaru-in)
