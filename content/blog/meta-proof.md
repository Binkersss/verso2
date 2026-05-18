---
title: Meta-Proof
author: Nathaniel Chappelle
date: Thu, 14 May 2026 20:33:43 -0800
---

First: [proof](https://sashacarin.github.io/posts/proof.html)

Proof regresses infinitely unless you arbitrarily stop at an axiom. Complexity
is unmeasurable from inside a system. And the boundary between tractable and
intractable is a cliff you can't locate while standing on it.

The halting problem says you cannot, from inside a system, determine whether an
arbitrary computation will terminate or loop forever.

Compilers face this directly. A compiler analyzing some program with a recursion
cannot generally determine whether the program will finish, so it doesn't try.
The compiler itself halts not because it solved the problem but because it was
built with a hard exit.

Thus Languages inherit this. Every programming language is a formal system, and
every formal system is subject to Gödel: there are true statements it cannot
prove and questions it cannot answer from within its own rules.

Humans are the same structure with one difference. We also cannot determine from
inside our own reasoning whether a line of thought will converge. But unlike a
compiler we weren't built with a hard exit wired in from outside. We evolved one
from inside. This is exactly what makes it prior to the computation rather than
posterior to it. The halt is ours.

Natural language sits between formal languages and human reasoning, and inherits
problems from both.

A formal language is precise because it is closed — its syntax defines exactly
what can be expressed, and anything outside that syntax is not a statement in
the language at all. Natural language is open. New words, new metaphors, new
uses of old words — the boundary of what can be said is constantly being
renegotiated. This is its power and its problem.

Because natural language is open, it cannot be formally verified. You cannot
write a compiler for English. Ambiguity isn't a bug to be patched — it is
load-bearing. "The bank was steep" and "the bank was closed" use the same word,
and no syntax rule resolves which meaning is intended. Context does. But context
is itself a natural language problem, so the resolution is circular.

This means natural language reasoning carries an additional layer of
undecidability the proof paper didn't account for. Even if your logic is sound,
the terms you're reasoning with are not formally defined — they are
approximations agreed upon by convention, subject to drift, and impossible to
fully pin down. You are running a proof on variables whose values are fuzzy and
shifting.

The halting problem in natural language doesn't look like an infinite loop. It
looks like a conversation that keeps going because neither party is sure they're
talking about the same thing. The halt, when it comes, is social and emotional —
someone decides the terms are close enough, or gives up, or changes the subject.
Not because the problem resolved. Because the stopping mechanism fired.

## Emotion

If the halt cannot come from inside the reasoning — and the previous sections
establish that it cannot — then it must come from somewhere else. Damasio's
somatic marker hypothesis identifies where. The vmPFC integrates bodily states
with decision-making, tagging options with emotional valence before conscious
deliberation begins. The halt signal is not the conclusion of a logical process.
It is prior to one. The inversion case proves the independence. Patients with
vmPFC damage retain full reasoning capacity — they can analyze options,
construct arguments, follow chains of inference indefinitely. What they lose is
the ability to stop. Not cognition. Not logic. Just the exit. They deliberate
forever on trivial decisions, not because they are reasoning poorly but because
they are reasoning without a termination condition. The halt was never part of
the logic. Its absence reveals that. This reframes what emotions are. They are
not noise corrupting an otherwise clean reasoning process. They are not
irrational interruptions. They are the only available solution to a formally
undecidable problem — the mechanism that lets a system act despite having no
provable basis for stopping. Evolution didn't give us emotions because they feel
good. It gave us emotions because without them we would be the vmPFC patients,
reasoning perfectly and deciding nothing.

**IV. The AI Gap Follows From III**

- Directly derived — no restatement needed
- The gap isn't capability, it's the _location_ of the halt relative to the
  reasoning

**V. The Slippery Slope as Proof of Concept**

- Apply the framework to its own challenge from the proof paper
- Don't re-argue undecidability — use it. The classifier "fallacy" presupposes
  decidability that doesn't exist. That's the whole point, one paragraph.

**VI. This Document Is Also Subject to Its Own Argument**

- The meta-proof halted here. That choice was not logical.

> "Once you start doubting, there's no end to it" -- Ghost in the Shell

- Proof regress bottoms out at an axiom you choose to stop at
- Halting problem: you cannot, from inside a system, determine whether an
  arbitrary computation halts

We can't justify from inside the system.

> "You cannot, in general, determine the complexity of a system from inside it"

In reference to Kolmogorov complexity. Turing proved this 1936, applies not to
complexity but also to entire proof-regress argument.

Rices Theorem:

No non-trivial semantic property of a program is decidable => no non-trivial
question about whether reasing is _converging on something true_ is decidable
either. It's not just "will this computation halt?", it's "is this line of
inquiry going anywhere?". Undecidable in the general case

Stop without resolving:

Humans ability to ignore solving problem and transition out of turing states
into a third state. Lateral halt signal is not output of computation, it is
prior to it.

Damasio's somatic marker hypothesis; the neurological evidence that stopping
mechanism is emotional and not logical. Without it you reason perfectly and yet
become trapped in decision paralysis (they can't halt).

AI systems lack an embodied and arbitrary halt. Context windows and token limits
are hard cutoffs from outside, not an internal judgement. Losing interest vs. a
guillotine.

Slippery slope:

Before we can even think about the slope, we need to think about the label.
Fallacy is just a word that comforts us when we have a recursion we can't bound.
It's a hallucination of authority. In an undecidable system a slippery slope is
just a trajectory whose end is none of our business.

To prove, must prove that for any inference chain _P_ there exists a state _S_
where the chain must break. Since the 'slippiness' is a non-trivial semantic
property, there's no genereal decider.

I could keep going, but then we'd need a meta-meta-proof.
