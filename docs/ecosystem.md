# Ecosystem and project map

Coder is the central project. Subprojects are the tools, apps, interfaces, or libraries that implement part of the Coder idea.

This repository should make it easy to understand the whole ecosystem without forcing every subproject to repeat the same background explanation.

## Repository roles

### Central Coder repository

The central repository owns:

- The high-level explanation of Coder.
- The stable project principles.
- The official subproject list.
- Shared language about what Coder is and why it exists.
- Links to the repositories where active work happens.

It should avoid details that change often, such as exact releases, current feature lists, active downloads, provider-specific setup, or implementation-specific commands.

### Subproject repositories

A subproject repository owns:

- Its own source code.
- Its own installation and development instructions.
- Its own release notes.
- Its own implementation documentation.
- Its own current feature explanations.
- Its own issues and project-specific discussions.

A subproject should be listed here when it is an official part of the Coder ecosystem.

## Current official subprojects

| Subproject | Repository | Stable purpose |
| --- | --- | --- |
| [Coder Desktop](../subprojects/coder-desktop.md) | [elijahshepherd/Coder-Desktop](https://github.com/elijahshepherd/Coder-Desktop) | A desktop-focused Coder subproject for local agent work on computer and coding tasks. |

## How to add a future subproject

When a new official Coder subproject exists:

1. Add it to [subprojects/README.md](../subprojects/README.md).
2. Add a stable subproject page in `subprojects/`.
3. Link to the subproject repository.
4. Explain the long-term purpose without listing release-specific details.
5. Keep changing install steps and feature lists in the subproject repository.

## Why the map matters

Coder is meant to grow without becoming confusing. A central map keeps the ecosystem understandable. People should be able to arrive here and quickly learn what Coder means, what has been made, and where to go next.
