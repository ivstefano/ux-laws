---
name: ux-laws
description: Apply ~65 laws and principles of UX (Fitts, Hick, Jakob, Miller, Tesler, Postel, Peak-End, Von Restorff, Zeigarnik, all Gestalt laws, cognitive load, choice overload, Doherty threshold, progressive disclosure, information scent, affordances, behavioural biases like anchoring, framing, defaults and social proof), plus Nielsen's 10 heuristics and John Maeda's 10 Laws of Simplicity, to design or review an interface. Use this whenever the user asks to review, critique, audit or improve a screen, page, flow, form, component or screenshot; asks "why does this feel confusing/cluttered/slow"; wants to decide what goes where, how many options to show, what to emphasise, or how to order things; or mentions any UX law, heuristic or psychology principle by name — even if they don't say "laws of UX".
---

# Laws of UX

About 65 well-established findings from psychology, HCI and behavioural economics, plus two classic checklists (Nielsen's heuristics, Maeda's laws of simplicity), about how people perceive, decide and act. They are lenses, not rules: each one predicts a specific failure, so use them to find real problems and justify fixes with something firmer than taste.

## Two ways to use this

**Reviewing something that exists** (screenshot, URL, component, flow): run the audit below.
**Designing something new**: before drawing anything, answer the questions in "Design questions" and let the answers decide layout, count and order.

## Audit workflow

1. **Name the job.** In one sentence: who lands here and what must they do or understand? Every finding is judged against this. A law violation on something nobody needs is noise.
2. **Find the symptoms.** Look at the thing as a first-time user would — scan it for 5 seconds, then try the main task. Note where you hesitated, misread, had to hunt, or didn't know what happens next.
3. **Map symptoms to laws** with the table below, then open only the reference file(s) you need for the check and the fix.
4. **Report findings**, most damaging to the main job first. For each:
   - **What** — the concrete problem, pointing at the element (or `file:line`).
   - **Law** — which one predicts it, in a few words why.
   - **Fix** — specific change, not "improve hierarchy".
   - **Cost** — small / medium / large.
5. **Check fixes against each other** (see "When laws collide"). Removing options for Hick can break Tesler; enlarging targets for Fitts can break proximity.

Keep the report short. Five sharp findings beat thirty observations. If something is fine, don't list it.

## Symptom → law map

| You notice… | Look at | Reference |
|---|---|---|
| Can't tell what's important; everything shouts or nothing does | Von Restorff, Selective Attention, Aesthetic-Usability | perception.md |
| Related things look unrelated, or unrelated things look grouped | Proximity, Common Region, Similarity, Uniform Connectedness | perception.md |
| Busy, cluttered, hard to parse at a glance | Prägnanz, Cognitive Load, Occam's Razor | perception.md, cognition.md |
| Too many choices; user stalls or bounces | Hick's Law, Choice Overload, Pareto | decisions.md |
| User must remember something from a previous step | Working Memory, Miller's Law, Chunking | cognition.md |
| Long lists where the middle gets ignored | Serial Position Effect | cognition.md |
| Users abandon multi-step tasks halfway | Goal-Gradient, Zeigarnik | interaction.md, cognition.md |
| Works differently from sites people know | Jakob's Law, Mental Model | decisions.md, cognition.md |
| Users skip instructions / onboarding | Paradox of the Active User | decisions.md |
| Small or far-away tap targets, misclicks | Fitts's Law | interaction.md |
| Feels slow, users double-click or leave | Doherty Threshold | interaction.md |
| Form rejects reasonable input | Postel's Law | decisions.md |
| Complexity was pushed onto the user (manual steps, jargon) | Tesler's Law | decisions.md |
| Forms or tasks that drag on | Parkinson's Law | decisions.md |
| Ending feels flat, or one bad moment sours everything | Peak-End Rule | interaction.md |
| Users drift off task or lose focus | Flow | interaction.md |
| Users draw wrong conclusions from how data is framed | Cognitive Bias | cognition.md |
| Looks unpolished, so users distrust the content | Aesthetic-Usability | perception.md |
| Users don't see what's clickable, or click decoration | Affordances and Signifiers, Similarity | interaction.md, perception.md |
| Users don't know if their action worked | Feedback, Doherty Threshold | interaction.md |
| Users make avoidable mistakes | Constraints and Error Prevention, Postel's Law | interaction.md, decisions.md |
| Links don't lead where users expect; vague labels | Information Scent, Curse of Knowledge | cognition.md |
| Text over photos is hard to read; modals blend in | Figure-Ground | perception.md |
| Users miss key info on long pages | Scanning Patterns (F/Z), Visual Hierarchy, Banner Blindness | perception.md |
| Numbers lead readers to a biased conclusion | Anchoring, Framing, Cognitive Bias | cognition.md |
| Low sign-ups or follow-through | Reciprocity, Commitment and Consistency, IKEA Effect, Default Effect | decisions.md |
| Too much of everything, needs a simplification pass | Maeda's laws (Reduce → The One) | simplicity.md |
| Need a broad general checklist | Nielsen's 10 heuristics | heuristics.md |

## Design questions

Answer these before designing a screen; each answer comes from a law.

1. **What is the one thing?** One primary action or message per view gets the visual weight (Von Restorff). Everything else is visibly secondary.
2. **How many choices?** Show the few that cover most use (Pareto, Hick); put the rest behind "more", search or progressive disclosure.
3. **What does the user already expect?** Use the conventions of the sites they spend time on (Jakob) — logo top-left goes home, search looks like search, cart top-right.
4. **What must they hold in their head?** Nothing, ideally. Keep information visible where it's needed (Working Memory); chunk what's long (Chunking).
5. **What goes first and last?** The most important items at the start and end of lists and pages (Serial Position).
6. **What's grouped with what?** Space, boxes and shared style should mirror real relationships (Gestalt laws).
7. **Where's the complexity going?** Absorb it in the system — defaults, inference, autocomplete — instead of handing it to the user (Tesler).
8. **How fast must it respond?** Feedback within ~400 ms, or show progress (Doherty).
9. **How does it end?** Design the peak and the final moment deliberately — confirmation, summary, a reason to come back (Peak-End).

## When laws collide

- **Hick vs Tesler** — fewer visible options is good until the complexity reappears as extra steps. Hide rarely-used options, don't delete needed ones.
- **Jakob vs Von Restorff** — break convention only for the one thing you want noticed, never for navigation or controls.
- **Fitts vs Proximity** — bigger targets need more space; keep groups tight inside and separated outside.
- **Aesthetic-Usability vs testing** — a beautiful screen makes users forgive and *not report* problems. Watch behaviour, don't just ask opinions.
- **Miller as a limit** — "7±2" is about short-term memory, not a cap on menu items. Don't cite it to cut a nav to seven links; cite Hick or Choice Overload instead.

## Reference files

Open only what the symptoms point to.

- `references/perception.md` — Gestalt (all), emphasis, hierarchy, scanning, attention, aesthetics (17)
- `references/cognition.md` — memory, load, chunking, order, mental models, information scent, biases in reading data (16)
- `references/decisions.md` — choices, conventions, complexity, tolerance, time, persuasion and motivation (19)
- `references/interaction.md` — targets, speed, feedback, affordances, errors, flow, progress, endings, motion (12)
- `references/heuristics.md` — Nielsen's 10 usability heuristics, cross-linked to the laws
- `references/simplicity.md` — John Maeda's 10 Laws of Simplicity + 3 keys, mapped to the laws they overlap with, and a "Maeda pass" for simplification

Each law has: the idea, how to spot a violation, fixes, and pitfalls.

**Persuasion laws** (scarcity, social proof, decoy, loss aversion) work on users, not for them. In public-interest, civic, health or news products, use them only honestly: real counts, real deadlines, no manipulation.

## Source

The core 30 follow the selection on lawsofux.com by Jon Yablonski; the additions come from Gestalt psychology, Don Norman (*The Design of Everyday Things*), Jakob Nielsen's heuristics, behavioural economics (Kahneman, Cialdini) and John Maeda (*The Laws of Simplicity*). All descriptions are original summaries, not copies of those sources.
