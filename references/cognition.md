# Cognition: memory, load, order, expectations

## Cognitive Load
**Idea.** Understanding a screen costs mental effort. *Intrinsic* load comes from the task itself; *extraneous* load comes from the design (clutter, jargon, inconsistency). Cut the extraneous so attention goes to the task.
**Spot it.** Jargon, unexplained abbreviations, several ways to do the same thing, decoration around data, dense paragraphs where a number would do.
**Fix.** Plain words, one way per action, progressive disclosure for detail, defaults for decisions most people don't care about.

## Working Memory
**Idea.** People can hold only a few items in mind for a short time. Anything they must remember between steps or screens is likely to be lost.
**Spot it.** "Note this code and enter it on the next page"; comparison tables split across pages; a summary step that doesn't show earlier choices.
**Fix.** Keep needed information visible where it's used: carry selections forward, show recently viewed items, allow side-by-side comparison. Recognition over recall.

## Miller's Law
**Idea.** Short-term memory holds roughly 7±2 items (later research says closer to 4 chunks). This is about *memory*, not about how many things can appear on screen.
**Spot it.** Misuse: cutting menus to seven "because of Miller". Real issue: asking users to remember long sequences (codes, steps, options).
**Fix.** Don't make users memorise; when they must, chunk it.

## Chunking
**Idea.** Grouping individual items into meaningful units makes them easier to scan and remember.
**Spot it.** Phone numbers, IBANs or codes shown as one long string; long forms as one undivided list; walls of text.
**Fix.** Format long strings in groups (`0888 123 456`), split forms into labelled sections, break text with headings and short paragraphs.

## Serial Position Effect
**Idea.** People remember the first items in a series (primacy) and the last (recency) best; the middle blurs.
**Spot it.** The most important nav item or option buried in the middle; key info mid-page with nothing at the end.
**Fix.** Put the most important items first and last — in navigation, lists, page sections. Put less important items in the middle.

## Zeigarnik Effect
**Idea.** Unfinished tasks stick in memory more than finished ones; visible incompleteness motivates people to come back and finish.
**Spot it.** Long processes without any progress indicator; saved drafts with no reminder; profiles with no sense of "almost done".
**Fix.** Show progress and what's left ("2 of 4"), keep drafts, gently remind about unfinished tasks. Don't abuse it with fake incompleteness.

## Mental Model
**Idea.** Users act on their internal picture of how a system works, built from previous experience. When the design matches that picture, it feels intuitive; when it doesn't, they make "errors" that are really design mismatches.
**Spot it.** Users look for things in the wrong place; vocabulary differs from how users talk about the domain; behaviour surprises (a "save" that also publishes).
**Fix.** Learn users' words and expectations (interviews, search logs) and use them for labels and structure. Make system state visible.

## Cognitive Bias
**Idea.** Systematic shortcuts in thinking — anchoring, framing, confirmation bias, default effect, social proof — shape how people read information and decide.
**Spot it.** The first number shown anchors judgement; "90% passed" vs "10% failed" leads to different conclusions; defaults quietly decide for users.
**Fix.** For neutral or informative products (news, civic data, health), present data symmetrically, show baselines and context, avoid manipulative defaults. Know which bias your framing triggers.

## Recognition over Recall
**Idea.** Recognising something seen before is far easier than recalling it from memory.
**Spot it.** Empty search boxes with no suggestions; command lines; forms that require typing codes the user saw elsewhere.
**Fix.** Show options, recent items, suggestions and autocomplete; keep menus visible; label icons.

## Progressive Disclosure
**Idea.** Show only what's needed now; reveal advanced or rare options when users ask for them. Reduces load without removing power.
**Spot it.** Every option and detail on the first screen; or important features hidden so deep nobody finds them.
**Fix.** Primary content and actions first; "show more", accordions, advanced settings, detail pages. Make the disclosure control obvious.

## Spatial Memory
**Idea.** People remember *where* things are. Moving elements around breaks learned habits and slows everyone down.
**Fix.** Keep navigation and key controls in stable positions; avoid reordering menus automatically by usage; announce big layout changes.

## Information Scent
**Idea.** Users follow links whose labels promise what they're looking for, like animals following a scent. Weak or vague labels make them give up or go back.
**Spot it.** "Click here", "Learn more", clever names for sections, links whose destination doesn't match the label.
**Fix.** Descriptive link text that names the destination; previews or counts ("Решения (391)"); the landing page's heading should match the link that led there.

## Anchoring
**Idea.** The first number or reference people see shapes how they judge the numbers that follow.
**Fix.** Choose deliberately what you show first. In informative products, give a neutral reference (last year, average, per resident) rather than an extreme figure.

## Framing Effect
**Idea.** The same fact presented differently (gain vs loss, percentage vs count) leads to different judgements.
**Fix.** For neutral information, show both framings or the absolute count with the percentage ("12 of 391 (3%)"); avoid wording that pre-judges.

## Loss Aversion
**Idea.** Losses feel about twice as strong as equivalent gains; people work harder to avoid losing something than to gain the same.
**Fix.** Explain what users stand to lose by not acting (missed decisions about their street) — honestly, without fake urgency.

## Curse of Knowledge
**Idea.** Once you know something, it's hard to imagine not knowing it. Teams write labels and explanations that only insiders understand.
**Spot it.** Internal terms, abbreviations, legal or technical language in UI copy; steps skipped because "everyone knows".
**Fix.** Test copy with people outside the team; write as you'd explain to a neighbour; define terms where they first appear.
