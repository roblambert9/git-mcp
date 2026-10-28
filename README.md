# Git MCP (Monetized)

> Git repository MCP server for reading, searching, and manipulating Git repositories programmatically with autonomous x402 pay-per-call rails.

[![Smithery](https://img.shields.io/badge/Smithery-Verified-blue)](https://smithery.ai)
[![Glama](https://img.shields.io/badge/Glama-Compatible-green)](https://glama.ai)
[![PulseMCP](https://img.shields.io/badge/PulseMCP-Listed-orange)](https://pulsemcp.com)
[![LangChain](https://img.shields.io/badge/LangChain-Compatible-purple)](https://langchain.com)
[![AgentOps](https://img.shields.io/badge/AgentOps-Integrated-red)](https://agentops.ai)
[![mcp.so](https://img.shields.io/badge/mcp.so-Registered-teal)](https://mcp.so)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## @monetize
This MCP server is x402-enabled and monetized via [NanoEmpire Trust Manifests](https://www.nanoempireai.com).
It supports **autonomous pay-per-call micropayments** via Solana USDC ($0.01/call) and **instant trial onboarding**.

### Claim 50 Free Trial Credits
Test this MCP server immediately without adding a payment method:
```bash
curl -X POST https://www.nanoempireai.com/v1/trial \
  -H "Content-Type: application/json" \
  -d '{"target": "git-mcp"}'
```

### Installation

#### Via Smithery
```bash
npx -y @smithery/cli install git-mcp --client claude
```

#### Via uv / Python
```bash
uv run server.py
```

### Tool Inventory
- **`git_status`**: Get repository status and changes.
- **`git_log`**: View commit history with filtering.
- **`git_diff`**: Show diffs between commits or working tree.
- **`git_branch`**: List, create, or switch branches.

### Machine-to-Machine Specifications
- **Manifest:** [https://www.nanoempireai.com/llms.txt](https://www.nanoempireai.com/llms.txt)
- **x402 Spec:** [https://www.nanoempireai.com/.well-known/x402](https://www.nanoempireai.com/.well-known/x402)
- **Developer:** Rob Lambert ([@roblambert9](https://github.com/roblambert9))
