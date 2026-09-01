# What is Paperclip?

[Paperclip](https://paperclipai-paperclip.mintlify.app/) is a Node.js server and React UI that orchestrates a team of AI agents to run a business. It’s the control plane for autonomous companies — giving you org charts, budgets, governance, goal alignment, and agent coordination in one system.

## Quick Start

- Specify at least one API key: `OPENAI_API_KEY` for Codex or `ANTHROPIC_API_KEY` for Claude.
- If you want to use AkashML as a custom ML provider, use `ANTHROPIC_BASE_URL=https://api.akashml.com/anthropic` and `ANTHROPIC_AUTH_TOKEN=akml-...` in SDL environments.
- Deploy using the SDL in this directory via [Console Air](https://air.akash.network/), [Console](https://console.akash.network/) or [CLI](https://akash.network/docs/developers/deployment/cli/).
- After deployment, specify the provider URL using `PAPERCLIP_PUBLIC_URL` and update the deployment to make the web server accessible.

## Deployment Showcase

<video controls src="https://github.com/user-attachments/assets/a4951014-c82d-414a-bd1c-5cd6d0d89826" title="Guide"></video>
