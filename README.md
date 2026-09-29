<p align="center">
  <a href="https://www.agentlist.io"><img src="media/banner.png" width="800" alt="Awesome Agent Sandboxes — Execution sandboxes, browser environments, and isolation runtimes for AI agents."></a>
</p>

# Awesome Agent Sandboxes

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![Contributions welcome](https://img.shields.io/badge/contributions-welcome-f04424.svg)](CONTRIBUTING.md) [![CC0](https://img.shields.io/badge/license-CC0_1.0-6b6a64.svg)](LICENSE)

> Execution sandboxes, browser environments, and isolation runtimes for AI agents.

12 projects · Upstream documentation checked 2026-09-29. Curated by [agentlist.io](https://www.agentlist.io).

Environments for running agent tools or untrusted code, plus the isolation runtimes used to build them. Browser automation libraries alone are excluded. A listing is not a security certification.

## Contents

- [How to choose](#how-to-choose)
- [Agent execution platforms](#agent-execution-platforms)
- [Local and self-managed environments](#local-and-self-managed-environments)
- [Isolation building blocks](#isolation-building-blocks)
- [Related awesome lists](#related-awesome-lists)
- [More from Agentlist](#more-from-agentlist)
- [Contributing](#contributing)

## How to choose

- What isolation boundary is used: process restrictions, containers, an application kernel, or a VM?
- How are network access, credentials, filesystem access, and resource limits controlled?
- Does state persist, and can you inspect, stop, snapshot, or destroy an environment?

## Agent execution platforms

- [Cloudflare Sandbox SDK](https://github.com/cloudflare/sandbox-sdk) - SDK for executing commands and managing files in isolated containers from Workers applications. **Cloud platform SDK.**
- [Daytona](https://github.com/daytonaio/daytona) - Sandbox infrastructure with SDK and API access to code execution, files, and processes. **Sandbox platform.**
- [E2B](https://github.com/e2b-dev/E2B) - Cloud sandbox infrastructure with Python and JavaScript SDKs for running agent-generated code. **Cloud sandbox.**
- [OpenSandbox](https://github.com/opensandbox-group/OpenSandbox) - Sandbox platform with lifecycle and execution APIs for Docker and Kubernetes environments. **Deployable platform.**
- [Vercel Sandbox](https://github.com/vercel/sandbox) - SDK and tooling for ephemeral compute environments that run user-generated code. **Cloud sandbox.**

## Local and self-managed environments

- [Agent Infra Sandbox](https://github.com/agent-infra/sandbox) - Docker environment combining browser, shell, files, MCP, and a VS Code server. **Container environment.**
- [Anthropic Sandbox Runtime](https://github.com/anthropics/sandbox-runtime) - Process-level tool for applying filesystem and network restrictions without a container. **Process restrictions.**
- [Browserless](https://github.com/browserless/browserless) - Browser service deployable in Docker, with a hosted service also available. **Browser environment.**
- [Microsandbox](https://github.com/superradcompany/microsandbox) - Programmable local microVM runtime for agent tools and other untrusted workloads. **Local VM runtime.**

## Isolation building blocks

- [Firecracker](https://github.com/firecracker-microvm/firecracker) - Virtual machine monitor for building lightweight KVM microVM environments. **VM building block.**
- [gVisor](https://github.com/google/gvisor) - Application kernel that interposes between containerized workloads and the host kernel. **Container isolation.**
- [Kata Containers](https://github.com/kata-containers/kata-containers) - Container runtime that runs workloads inside lightweight virtual machines. **VM-backed containers.**

## Related awesome lists

Independent collections for deeper discovery. These are references, not affiliations or endorsements.

- [arjan/awesome-agent-sandboxes](https://github.com/arjan/awesome-agent-sandboxes) - Code-execution sandboxing options for agents.
- [fishman/awesome-agent-sandbox](https://github.com/fishman/awesome-agent-sandbox) - Portable sandboxes and local isolation tools.
- [msyvr/awesome-agent-sandboxes](https://github.com/msyvr/awesome-agent-sandboxes) - Sandbox landscape and isolation guidance.
- [backblaze-labs/awesome-agent-infrastructure](https://github.com/backblaze-labs/awesome-agent-infrastructure) - The surrounding storage, memory, and execution stack.

## More from Agentlist

- [Awesome Agent List](https://github.com/AgentListIO/awesome-agent-list)
- [Awesome Personal Assistants](https://github.com/AgentListIO/awesome-personal-assistants)
- [Awesome Agent Clients](https://github.com/AgentListIO/awesome-agent-clients)
- [Awesome Agent Memory](https://github.com/AgentListIO/awesome-agent-memory)
- [Awesome Agent Orchestration](https://github.com/AgentListIO/awesome-agent-orchestration)
- [Awesome Agent Observability](https://github.com/AgentListIO/awesome-agent-observability)

**[Browse agents](https://www.agentlist.io/list-of-ai-agents) · [Compare agents](https://www.agentlist.io/compare) · [GitHub organization](https://github.com/AgentListIO)**

## Contributing

Missing something useful? Read the [contribution guide](CONTRIBUTING.md) and open an issue or pull request with an official source.

The machine-readable [list.json](list.json) includes a primary-source link and a documentation-check date for every entry. Descriptions are editorial summaries of upstream documentation; inclusion does not imply hands-on testing, a security audit, or endorsement. Hosted services and source code may have different terms.

To update the list, edit `list.json`, run `bun run build`, then `bun run check`. The README is generated; avoid editing it directly.

[CC0](LICENSE) applies to this list’s text and data. Linked projects retain their own licenses.
