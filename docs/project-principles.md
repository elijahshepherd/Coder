# Project principles

These principles describe what should stay true across the Coder ecosystem, even as individual subprojects change.

## Local first

Coder is centered on work that happens close to the user's own computer and projects. A Coder tool should respect that local context and make it clear when work touches files, tools, commands, providers, or external services.

## User control

The user should remain in charge. Coder projects can help plan, explain, inspect, and act, but they should not hide important decisions from the person using them.

Good Coder experiences should make it easy to understand:

- What the user asked for.
- What the agent is trying to do.
- What information or tool access is involved.
- What changed.
- What still needs review.

## Provider and model flexibility

Coder should not be tied to one provider or one model. Different users and projects need different tradeoffs. The ecosystem should leave room for provider choice and future model options without making the central project depend on one provider's identity.

## Open and inspectable

Coder should be understandable. The source, documentation, and project map should help people inspect how the project is organized and where each part lives.

The central repository should favor clear language over hype. It should explain the project plainly so users can trust what they are reading.

## Complex project support

Coder is meant for real work, including tasks that need multiple steps, context, review, and correction. A useful agent workflow should help users move through complexity rather than pretending every task is a single prompt.

Coder projects should support careful work on codebases, documents, workflows, and computer tasks where planning and follow-through matter.

## Stable central docs

This repository should document the ideas that are meant to last. Version-specific details, current UI details, exact feature lists, downloads, and release notes should live in the subproject that owns them.

That separation keeps the central repository useful even when individual tools evolve.

## Clear subproject ownership

Every official Coder subproject should have a clear page in `subprojects/` that explains what it is for and links to its own repository. That page should be stable enough to survive normal product changes.
