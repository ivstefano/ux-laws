# Decisions: choices, conventions, complexity

## Hick's Law
**Idea.** The time to decide grows with the number and complexity of choices. Decision time grows roughly logarithmically, but complex or unfamiliar choices cost far more than the count suggests.
**Spot it.** Mega-menus, many equal-weight buttons, homepages that offer every section at once, settings pages with everything visible.
**Fix.** Show the common choices, hide the rest behind "more" or search, break big decisions into steps, recommend a default.
**Pitfall.** Over-applying it can create extra steps that cost more than the choice did (see Tesler).

## Choice Overload
**Idea.** Beyond a point, more options lower satisfaction and make people more likely to choose nothing.
**Spot it.** Long lists of comparable items with no filtering, sorting or recommendation; pricing pages with many near-identical tiers.
**Fix.** Curate (top picks), let users filter and compare, show a clear recommendation. Fewer, more distinct options.

## Jakob's Law
**Idea.** Users spend most of their time on other sites, so they expect yours to work the same way.
**Spot it.** Unusual navigation placement, custom-styled controls that hide what they are, novel gestures without hints, a logo that doesn't go home.
**Fix.** Follow common conventions for navigation, forms, search, checkout and icons. Innovate in content and value, not in basic controls. When redesigning, change gradually or let people keep the old way for a while.

## Occam's Razor
**Idea.** Among solutions that work, prefer the one with the fewest elements and assumptions.
**Spot it.** Features nobody uses, duplicate paths to the same page, explanations of things that could be made self-explanatory.
**Fix.** Remove an element and see if anything is lost. Keep removing until something is.

## Pareto Principle
**Idea.** Roughly 80% of effects come from 20% of causes — most use concentrates on a few features, pages or content items.
**Spot it.** Equal prominence for everything; effort spent polishing rare paths while the main path has friction.
**Fix.** Use analytics to find the vital few (pages, actions, items) and give them prominence and polish. Put the long tail behind search or "more".

## Tesler's Law (conservation of complexity)
**Idea.** Every system has some complexity that can't be removed — only moved. The question is whether the system or the user carries it.
**Spot it.** Users format inputs manually, choose things the system could infer (country from IP, city from postcode), learn internal jargon, or repeat data entry.
**Fix.** Absorb complexity in code: smart defaults, autocomplete, inference, sensible formatting. Accept a more complex implementation for a simpler experience.
**Pitfall.** Over-simplifying until power users lose needed control. Hide, don't remove.

## Postel's Law (robustness)
**Idea.** Be liberal in what you accept from users, conservative in what you output.
**Spot it.** Forms that reject spaces in phone numbers, dashes in card numbers, Cyrillic vs Latin lookalikes, different date formats or trailing whitespace.
**Fix.** Normalise input silently (strip spaces, accept common formats), validate meaning not form, give specific error messages, produce clean, consistent output.

## Paradox of the Active User
**Idea.** People don't read manuals or onboarding; they start using the product immediately and learn by doing, even if reading would save time.
**Spot it.** Long onboarding tours, instruction blocks above forms, features only explained in a help page.
**Fix.** Put guidance inside the task: inline hints, good empty states, contextual tooltips at the moment of need, safe undo so exploring is cheap.

## Parkinson's Law
**Idea.** A task expands to fill the time available. Applied to UX: make tasks take less time than users expect, and they'll feel effortless.
**Spot it.** Forms asking for information that isn't needed yet; multi-page flows that could be one screen; no autofill.
**Fix.** Ask only what's needed now, autofill what you can (browser autofill, saved data), show realistic time estimates ("2 min") and beat them.

## Default Effect
**Idea.** Most people keep whatever is pre-selected. Defaults are decisions you make for users.
**Fix.** Set the default to what most people would choose and what serves them; never pre-tick consent or paid extras.

## Social Proof
**Idea.** People look to what others do when unsure ("2,300 people follow this district").
**Fix.** Show real counts and testimonials where they help a decision; never fabricate them; small numbers can backfire, so hide counts until they're meaningful.

## Scarcity and Urgency
**Idea.** Things perceived as limited or time-bound feel more valuable and prompt action.
**Fix.** Use only when true (a real deadline for public comments). Fake timers and "only 2 left" destroy trust.

## Reciprocity
**Idea.** People feel inclined to return a favour. Giving value first (useful content, a free tool) makes them more open to a later ask.
**Fix.** Show value before asking for sign-up or email; ask after the user got something useful.

## Commitment and Consistency
**Idea.** After a small commitment, people tend to stay consistent with it and accept larger ones.
**Fix.** Start with a small, low-effort step (pick your district) before asking for more (email, account).

## IKEA Effect
**Idea.** People value what they helped build or personalise more.
**Fix.** Let users customise (follow topics, pick a district); that investment increases attachment and return visits.

## Endowment Effect
**Idea.** People value what they already own more than the same thing they don't own.
**Fix.** Let users try or "own" something early (a saved watchlist before sign-up), then ask them to keep it.

## Decoy Effect
**Idea.** Adding a clearly inferior third option makes one of the other two look better.
**Fix.** Know it to avoid accidental decoys in comparisons; don't use it to manipulate in neutral or public-interest products.

## Kano Model
**Idea.** Features fall into basics (expected; absence angers), performance (more is better) and delighters (unexpected; presence pleases). Basics bring no praise but must be there.
**Fix.** Secure basics first (fast, correct, search works), then improve performance features, and add one or two delighters.

## Satisficing
**Idea.** Users don't look for the best option; they pick the first one that seems good enough.
**Fix.** Put the right choice where it's seen first and make labels unambiguous, because users won't read all options before clicking.
