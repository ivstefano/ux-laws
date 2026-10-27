# John Maeda's 10 Laws of Simplicity (summarised)

From *The Laws of Simplicity* (2006). These are design *attitudes* more than measurable effects; most restate in broader terms what the psychology laws in the other files predict. Use them to frame a simplification pass, then justify each change with the specific law.

| # | Maeda law | The idea | Overlaps with |
|---|---|---|---|
| 1 | **Reduce** | The simplest way to simplify is thoughtful removal. Maeda's SHE: **S**hrink (make it feel smaller and lighter), **H**ide (tuck complexity away), **E**mbody (make what remains feel valuable). | Occam's Razor, Hick's Law, Progressive Disclosure, Tesler (hide, don't delete) |
| 2 | **Organize** | Organization makes many things feel like fewer. Sort, label, integrate, prioritize. | Gestalt grouping (Proximity, Common Region, Similarity), Chunking, Miller |
| 3 | **Time** | Saving time feels like simplicity. Make waits shorter, or make them feel shorter. | Doherty Threshold, Parkinson's Law, Labor Illusion, Feedback |
| 4 | **Learn** | Knowledge makes everything simpler. Relate the new to what people already know, and reward learning. | Jakob's Law, Mental Model, Paradox of the Active User, Recognition over Recall |
| 5 | **Differences** | Simplicity and complexity need each other; simplicity is noticed by contrast with complexity. | Von Restorff, Visual Hierarchy, Focal Point |
| 6 | **Context** | What lies at the periphery isn't peripheral. Empty space and surroundings shape meaning. | Figure-Ground, Selective Attention, Proximity (whitespace as structure) |
| 7 | **Emotion** | More emotion is better than less. Sometimes adding warmth, personality or ornament beats stripping everything bare. | Aesthetic-Usability, Peak-End Rule |
| 8 | **Trust** | In simplicity we trust. The more a system knows and does for you, the less you have to think, but you must be able to undo. | Default Effect, Tesler's Law, Constraints and Error Prevention, user control (Nielsen 3) |
| 9 | **Failure** | Some things can never be made simple. Recognise it and move on. | Tesler's Law (irreducible complexity), Kano basics |
| 10 | **The One** | Simplicity is subtracting the obvious and adding the meaningful. | Occam's Razor, Pareto, Focal Point |

## Maeda's three keys
- **Away** — more appears like less by moving it far away (to the cloud, to another screen, to settings). ~ Progressive Disclosure.
- **Open** — openness simplifies complexity (open data, transparency, standards). ~ Trust, Jakob's Law.
- **Power** — use less, gain more: fewer resources and less user effort. ~ Tesler, Parkinson.

## Where Maeda adds something the psychology laws don't
- **Emotion (7)** pushes back on pure minimalism: if stripping everything makes a product cold, add meaning back. The cognitive laws alone tend to over-reduce.
- **Failure (9)** gives permission to stop simplifying. Some domains (budgets, legal decisions) carry real complexity; explain it well instead of hiding it.
- **SHE (1)** is a practical order of operations: shrink first, then hide, then make what remains feel valuable.

## How to use in an audit
Run a quick "Maeda pass" after the specific findings:
1. Can anything be removed (Reduce, The One)?
2. Can what remains be grouped into fewer apparent things (Organize)?
3. Does any step waste the user's time (Time)?
4. Does it build on what users know (Learn)?
5. Is there one clear contrast, the thing that matters (Differences)?
6. Is the empty space working for you (Context)?
7. Is there warmth, or just sterility (Emotion)?
8. Does the system do the work, with undo (Trust)?
9. Is the remaining complexity real? Then explain it rather than hide it (Failure).
