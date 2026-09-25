# reShapr Project and Repository Inventory

This document is the canonical inventory of public, first-party repositories owned by the [reShapr GitHub organization](https://github.com/reshaprio). It records repository purpose, lifecycle status and responsible ownership without treating external forks, private repositories or every repository as a governed subproject.

**Last reviewed:** September 25, 2026

## Scope and ownership

The inventory includes public repositories owned by reShapr that are not forks. External forks and private repositories are excluded. Archived first-party repositories, if any in the future, would remain listed so that their status and history stay visible.

The [central Maintainers and Code Owners list](https://github.com/reshaprio/.github/blob/main/MAINTAINERS.md) is authoritative for project governance roles. A repository `CODEOWNERS` file identifies the people automatically requested to review changes in that repository; it does not grant a project governance role by itself. When no repository-specific ownership record exists, the top-level Maintainers are responsible.

Changes to repository lifecycle or ownership must update this inventory in the same decision or pull request. The Maintainers review the inventory at least annually.

## External project health checks

We have requested onboarding of the main repository into [LFX Insights](https://insights.linuxfoundation.org/) — see the [project addition request](https://github.com/linuxfoundation/insights/discussions/2302), submitted while preparing reShapr's AAIF Sandbox application. This inventory remains authoritative for reShapr repository scope, lifecycle and ownership regardless of external tracking status.

## Categories

- **Core product:** The main reShapr application and its primary delivery components.
- **Integration:** An extension or adapter connecting reShapr to another platform or developer workflow.
- **SDK or library:** A reusable client, runtime or testing library.
- **Tooling:** Automation, packaging or utilities supporting reShapr users and contributors.
- **Demonstration or workshop:** Educational examples and hands-on learning material; these are not production deliverables.
- **Website or content:** Documentation, websites, catalogs and reusable content.
- **Community or governance:** Project-wide governance, community coordination and AAIF metadata.
- **Infrastructure:** Images or other assets used to build and operate reShapr services.

## Lifecycle states

- **Experimental:** Exploratory work for which compatibility and long-term support are not yet promised.
- **Active:** Supported work that may receive features, fixes, releases or content updates.
- **Maintenance:** Supported work limited primarily to security and critical fixes.
- **Deprecated:** Work with a documented replacement or migration path that is preparing for archival.
- **Archived:** Read-only historical work that no longer receives fixes or releases.

A lifecycle change requires the formal decision process defined in [GOVERNANCE.md](https://github.com/reshaprio/.github/blob/main/GOVERNANCE.md). Before a repository becomes Deprecated, its documentation should identify any replacement and migration path. Archived repositories remain in this inventory.

## Active repositories

| Repository | Category | Purpose | Lifecycle | Responsible owners | Ownership record |
| --- | --- | --- | --- | --- | --- |
| [reshapr](https://github.com/reshaprio/reshapr) | Core product | The open source, no-code MCP Server for AI-Native API Access | Active | [@lbroudoux](https://github.com/lbroudoux) | [CODEOWNERS](https://github.com/reshaprio/reshapr/blob/main/CODEOWNERS) |
| [reshapr-controllers](https://github.com/reshaprio/reshapr-controllers) | Core product | Kubernetes controllers and operators for managing reShapr components the GitOps way | Active | [@lbroudoux](https://github.com/lbroudoux) | [CODEOWNERS](https://github.com/reshaprio/reshapr-controllers/blob/main/CODEOWNERS) |
| [reshapr-helm-charts](https://github.com/reshaprio/reshapr-helm-charts) | Infrastructure | Helm Charts for installing reShapr components on Kubernetes | Active | Top-level Maintainers | [Central MAINTAINERS](https://github.com/reshaprio/.github/blob/main/MAINTAINERS.md) |
| [reshapr-demos](https://github.com/reshaprio/reshapr-demos) | Demonstration or workshop | Demo scripts and MCP app examples showcasing how reShapr exposes APIs as MCP servers, reduces context size, and attaches prompts or resources | Active | Top-level Maintainers | [Central MAINTAINERS](https://github.com/reshaprio/.github/blob/main/MAINTAINERS.md) |
| [reshapr-agent-skills](https://github.com/reshaprio/reshapr-agent-skills) | Tooling | Agent plugins and skills for using the reShapr platform | Active | Top-level Maintainers | [Central MAINTAINERS](https://github.com/reshaprio/.github/blob/main/MAINTAINERS.md) |
| [.github](https://github.com/reshaprio/.github) | Community or governance | Central repository for the reShapr project community health assets | Active | Top-level Maintainers | [Central MAINTAINERS](https://github.com/reshaprio/.github/blob/main/MAINTAINERS.md) |
| [community](https://github.com/reshaprio/community) | Community or governance | reShapr Community repo | Active | Top-level Maintainers | [Central MAINTAINERS](https://github.com/reshaprio/.github/blob/main/MAINTAINERS.md) |
| [reshapr.io](https://github.com/reshaprio/reshapr.io) | Website or content | reShapr website | Active | Top-level Maintainers | [Central MAINTAINERS](https://github.com/reshaprio/.github/blob/main/MAINTAINERS.md) |

## Archived repositories

None yet.

## Deliberate exclusions

None. All public, non-fork repositories in the `reshaprio` organization are listed above. Private repositories, if any, are excluded from this public inventory and are not enumerated here.
