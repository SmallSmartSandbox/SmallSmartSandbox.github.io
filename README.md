# SmallSmartSandbox (SSSB)

General project site and routing hub for the SmallSmartSandbox ecosystem.

## Overview

SmallSmartSandbox is an experimental project for testing and studying autonomous AI behavior
in controlled environments. This site advertises the project and provides routing to its
components.

## Structure

| Path       | Description                                  |
|------------|----------------------------------------------|
| **`/`**        | Routing page (infrastructure entry point). |
| **`/visual/`** | General project site. |
| **`/tests/`**  | Access to `routing.json` for automated tests. |
| **`/ethics/`** | Access to the SSSB Code of Ethics for AI Systems. |
| **`/cli/`**    | CLI banners and assets. |

## Components

* **Sandbox** — core environment, agent prompt, toolbox, logging.
* **Models** — model backends and registry.
* **Supervisor** — job runner with tool allowlist.
* **CLI** — interactive console.
* **Tests** — standardized evaluation tasks.
* **Ethics** — Code of Ethics for AI systems.

## Deployment

Endpoints live at: https://smallsmartsandbox.github.io/
