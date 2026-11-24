---
layout: page
title: Marketplace
permalink: /marketplace/
---

[Rafa's Marketplace](https://github.com/erdos2n/rafas-marketplace) is my collection of free Claude Code plugins and skills, organized by category. Everything is MIT licensed.

## What's in it

**`communication-style` plugin**

- **`adhd-communication`**: responses you can read at a glance. Answer first, structure over prose, no walls of text, questions you can't miss.
- **`ask-less`**: adds rules to your CLAUDE.md so Claude acts on stated assumptions instead of asking follow-up questions, while still asking before risky actions.

## Install

From your terminal:

```bash
claude plugin marketplace add erdos2n/rafas-marketplace
claude plugin install communication-style@rafas-marketplace
```

Or inside a Claude Code session:

```
/plugin marketplace add erdos2n/rafas-marketplace
/plugin install communication-style@rafas-marketplace
```

Then run `/reload-plugins` or start a new session.

## Use it

- `/adhd-communication` turns it on for the rest of the session
- `/adhd-communication once` applies it to the next reply only
- `/adhd-communication off` turns it off
- `/ask-less` adds the rules to this project's CLAUDE.md
- `/ask-less global` adds them to `~/.claude/CLAUDE.md` for every project

## Using the Claude app instead?

The Claude app doesn't install from marketplaces. Zip the skill's folder from the repo and upload it under Settings → Capabilities → Skills.

More skills coming. Full details, changelog, and source are in the [repo](https://github.com/erdos2n/rafas-marketplace).
