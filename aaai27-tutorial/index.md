---
layout: default
title: "AI and Theorem Proving: A Two-Way Lane"
description: Tutorial at AAAI-27
---

# AI and Theorem Proving: A Two-Way Lane

*Tutorial at AAAI-27*

**Presenters:** [Mohammad Abdulaziz](https://mabdula.github.io) and [Maximilian Schäffeler](https://schaeffm.github.io/), King's College London

## Overview

AI and interactive theorem proving (ITP) are in a mutually beneficial relationship.
AI is being applied to theorem proving, making interactive theorem provers far easier to use.
Conversely, theorem provers are being applied to AI, both to verify AI algorithms and to check proofs or programs developed by agents.
Both directions are currently active, and the two communities rarely see them presented together.
In this tutorial, we introduce AI researchers to ITP, and formal methods researchers to the challenges of formalising the foundations of AI.

Part I covers AI for theorem proving and mathematics.
We introduce what ITPs are, from their underlying logical foundations to practical challenges such as proof automation.
We then survey automated theorem proving from its beginnings in the 1950s to hammers, which bring automated provers into ITPs.
Finally, we turn to LLM-based ITP workflows and discuss which recipes and interaction models currently work in practice.

Part II covers theorem provers applied to AI.
We show what it takes to verify AI algorithms, with case studies ranging from heuristic search and SAT-based planning to Markov decision processes (MDPs).
We explain how combining verification with certification, formally verifying a checker for an algorithm's output rather than the algorithm itself, often leads to verified systems that are also efficient.
Finally, we turn to the semantics of planning languages, and show how our ITP formalisations uncovered ambiguities in pen-and-paper semantics and problems in widely used AI planning tools.

The tutorial ends with a hands-on session.
Starting from a template, attendees use a coding agent to verify an executable A\* search in the Isabelle/HOL proof assistant, with the agent doing most of the proof work.
They see where the agent succeeds on its own and where it needs a human hint, and learn how to interact with ITPs.
The message throughout is that mechanising the proofs behind an algorithm is becoming practical enough to accompany research papers, and that the remaining difficulty lies in getting specifications right.

Much of Part II is based on [FormPlan](/), our library of formally verified tools for planning and model checking.

## Schedule

Coming soon.

## Prerequisites and Setup

Coming soon.

## Materials

Coming soon.
