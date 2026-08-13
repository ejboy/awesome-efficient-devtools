# Awesome Efficient Devtools

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

An opinionated collection of developer tools that reduce compute, context, operational, or workflow overhead.

Efficiency can mean reducing:

* compute or memory usage
* AI context or token usage
* terminal or build noise
* setup and operational complexity
* unnecessary infrastructure
* repetitive developer work
* workflow friction

Open-source, local-first, small, composable, and single-purpose tools are preferred, but these are preferences rather than strict requirements. This is a curated list, not an exhaustive directory.

## AI & Context Efficiency

- [AI Badger](https://github.com/PVRLabs/aibadger) - A local-first tool for extracting focused repository context for ChatGPT, Claude, Gemini, Grok, and other AI assistants without requiring provider API integration.

## Build & Test Efficiency

- [mvn-lite](https://github.com/ejboy/agent-scripts) - Reduces noisy Maven output to compact success or failure output while preserving useful diagnostics.
- [npm-lite](https://github.com/ejboy/agent-scripts) - A lightweight npm-output wrapper that reduces unnecessary command output for human and agent workflows.
- [cargo-nextest](https://github.com/nextest-rs/nextest) - Runs Rust tests efficiently with fast execution and clear, useful results.

## Fast CLI Tools

- [ripgrep](https://github.com/BurntSushi/ripgrep) - Searches files quickly while respecting common ignore rules, making repository navigation less wasteful.
- [fd](https://github.com/sharkdp/fd) - Finds files with a fast, simple interface and sensible defaults that reduce command-line friction.
- [fzf](https://github.com/junegunn/fzf) - Adds fast fuzzy selection to shell workflows, reducing repetitive typing and lookup work.
- [jq](https://github.com/jqlang/jq) - Filters and transforms JSON from the command line without requiring a larger scripting workflow.
- [hyperfine](https://github.com/sharkdp/hyperfine) - Benchmarks commands consistently so performance comparisons require little setup.

## Lightweight Observability

- [StatLite](https://github.com/PVRLabs/statlite) - Lightweight, self-hosted monitoring for Spring Boot and other applications, providing useful visibility without a large observability stack.
- [Beszel](https://github.com/henrygd/beszel) - Lightweight server monitoring with a small operational footprint.

## Data & Automation

- [Scriptella ETL](https://github.com/scriptella/scriptella-etl) - A lightweight Java-based ETL and script execution tool for moving and transforming data without requiring a full integration platform.
- [H2 Database](https://www.h2database.com/html/main.html) - An embeddable Java SQL database for development, testing, and lightweight applications without requiring a separate database server.

## Developer Environment

- [jenv](https://github.com/jenv/jenv) - Switches between Java versions per project, reducing manual environment setup and configuration drift.
- [mise](https://github.com/jdx/mise) - Manages development tools and environment variables in one place, reducing setup work across projects.
- [direnv](https://github.com/direnv/direnv) - Loads project-specific environment variables automatically, reducing repeated shell configuration.
- [just](https://github.com/casey/just) - Provides a small, readable command runner that turns repeated project tasks into easy-to-discover recipes.
- [watchexec](https://github.com/watchexec/watchexec) - Runs commands in response to file changes, shortening feedback loops for development tasks.
- [uv](https://github.com/astral-sh/uv) - Handles Python environments and packages quickly with less setup and fewer separate tools.

## Containers & Local Infrastructure

- [Colima](https://github.com/abiosoft/colima) - A lightweight container runtime for macOS and Linux that supports Docker and Kubernetes-style workflows without requiring a full desktop container platform.

## System & Desktop Utilities

- [Amphetamine](https://apps.apple.com/us/app/amphetamine/id937984704) - A macOS utility for preventing sleep during builds, downloads, demos, and other long-running development tasks.
- [GrandPerspective](https://grandperspectiv.sourceforge.net/) - An open-source macOS disk-usage analyzer that uses treemap visualization to make large files easy to find.

## Maintainer note

The maintainer builds some of the listed tools through PVR Labs. Those tools are included under the same editorial criteria as every other project here.
