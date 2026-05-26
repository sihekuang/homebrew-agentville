# homebrew-agentville

Homebrew tap for [AgentVille](https://github.com/sihekuang/agentville) — real-time visualization dashboard for AI coding agents.

## Install

```bash
brew install sihekuang/agentville/agentville
```

## Usage

```bash
# Start on default port (4200)
agentville

# Start on a custom port
AGENTVILLE_PORT=8080 agentville
```

## Run as a background service

```bash
brew services start agentville
```

## Update

```bash
brew update && brew upgrade agentville
```
