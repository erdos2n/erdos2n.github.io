---
layout: post
title:  "A skill for replies I can actually follow"
date:   2026-11-24 13:00:00 -0600
---

Install in Claude Code:

```bash
claude plugin marketplace add erdos2n/rafas-marketplace
claude plugin install communication-style@rafas-marketplace
```

I've noticed that as I've used AI, it tends to generate walls of text. That may be great for some people. For me, it's difficult to follow. I can get lost trying to find what I need.

So I designed a skill around it.

## What it does

`adhd-communication` changes how Claude replies:

- The answer comes first
- Structure over long paragraphs
- Questions are easy to spot

## How I use it

I mostly use it at work in Claude Code. I type `/adhd-communication` and it stays on for the session. `/adhd-communication once` applies it to one reply, and `/adhd-communication off` turns it off.

## What I find helpful

- I can find what I need without digging for it
- I can act on a reply right away
- When Claude needs something from me, I don't miss the question

It's free in [my skills marketplace]({{ "/marketplace/" | relative_url }}).
