---
layout: post
title:  "Agents need to know what mastery looks like"
date:   2026-11-24 12:00:00 -0600
---

Before I worked in data and AI, I taught middle school math and science.

The first thing teacher prep drills into you is backward design: decide what mastery looks like before you plan a single lesson. Write the assessment first. Then teach toward it.

The second thing: show students the rubric up front. A kid who doesn't know what "good" looks like isn't failing to learn. They're guessing.

I think about this constantly when I build with agents.

We hand an agent a vague task, get back something mediocre, and blame the model. But most of the time we never told it what mastery looks like. No success criteria. No examples of strong work. No definition of done.

## The parallels are almost one-to-one

- **Learning objective** = the agent's goal, stated plainly
- **Rubric** = your eval criteria, shared with the agent, not hidden until grading
- **Exemplars** = examples of good output
- **Formative feedback** = eval results fed back into the next iteration
- **Mastery** = passing the evals consistently, not once

## Output is a signal

In a classroom, student work is a signal about instruction. With agents, output is a signal about the context you gave it.

## Start with what mastery looks like

Good evals are backward design. Teachers have been doing it for decades.

If your agent keeps missing the mark, ask the question every good teacher asks: did I ever show it what success looks like?
