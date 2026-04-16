# jasonhch Claude Code Plugin Marketplace

A curated collection of Claude Code plugins for code review, predictive agent workflows, and development harness tooling.

## Add this marketplace

```shell
/plugin marketplace add jason-hchsieh/marketplace
```

## Available plugins

### code-review-annotator

Inline code review with MCP integration — add comments in the browser via SSH port forward, let Claude Code read and fix them via MCP tools.

```shell
/plugin install code-review-annotator@jasonhch-plugins
```

### predictive-mind

FEP/World-Models scaffolding for stable LLM coding agents: predict-before-act, inspectable belief state, and surprise-triggered reflection.

```shell
/plugin install predictive-mind@jasonhch-plugins
```

### harness-toolkit

Developer toolkit for auditing harness maturity (L0-L4), setting up AGENTS.md, configuring linters, hooks, CI, and skill creation workflows.

```shell
/plugin install harness-toolkit@jasonhch-plugins
```

## Install all plugins at once

```shell
/plugin marketplace add jason-hchsieh/marketplace
/plugin install code-review-annotator@jasonhch-plugins
/plugin install predictive-mind@jasonhch-plugins
/plugin install harness-toolkit@jasonhch-plugins
```
