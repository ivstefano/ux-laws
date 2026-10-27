# Perception: grouping, emphasis, attention

## Law of Proximity
**Idea.** Things placed close together are read as belonging together. Distance is the strongest grouping signal, stronger than colour.
**Spot it.** A label equidistant from two fields; a button floating between two cards; equal gaps everywhere so nothing groups.
**Fix.** Tight spacing inside a group, clearly larger spacing between groups (roughly 2× or more). Put labels nearer their own field than the next one.
**Pitfall.** Uniform spacing scales (everything `gap-4`) erase grouping.

## Law of Common Region
**Idea.** Elements inside a shared boundary (card, panel, background tint) are seen as a group, even when they're spaced apart.
**Spot it.** Related controls scattered with no container; or cards inside cards inside cards, so boundaries stop meaning anything.
**Fix.** One level of container per real group. Use a background tint or a border, not both plus a shadow.
**Pitfall.** Boxing everything; containers then add load instead of structure.

## Law of Similarity
**Idea.** Things that look alike (colour, shape, size, style) are assumed to work alike.
**Spot it.** Links and plain text in the same colour; a clickable chip styled like a static tag; two button styles for the same kind of action.
**Fix.** One look per role: all primary actions match, all links match, static labels never look tappable.
**Pitfall.** Using brand colour for decoration and for interaction — users click the decoration.

## Law of Uniform Connectedness
**Idea.** Elements joined visually (a line, arrow, shared bar) read as more related than proximity or similarity alone would suggest.
**Spot it.** Steps of a process shown as loose items; a timeline without a connecting line.
**Fix.** Connect sequences and relationships explicitly: steppers, lines, brackets, a shared background strip.

## Law of Prägnanz (simplicity)
**Idea.** People resolve complex visuals into the simplest form they can; ambiguous or busy shapes take effort and get misread.
**Spot it.** Icons that need a caption to be understood; charts with decoration that competes with data; irregular layouts.
**Fix.** Simple shapes, aligned grids, fewer distinct sizes and colours. Remove anything that doesn't carry meaning.

## Von Restorff Effect (isolation)
**Idea.** Among similar items, the one that differs is noticed and remembered.
**Spot it.** The primary action looks like the secondary ones; or five things are highlighted, so none stands out.
**Fix.** Make exactly one thing per view distinct — colour, size, weight or space. Don't rely on colour alone (colour-blind users, greyscale screens).
**Pitfall.** Highlight inflation: badges, banners and bold everywhere. Distinctiveness is a budget.

## Selective Attention
**Idea.** People filter out most of what's on screen and focus on what serves their current goal. Things that look like ads or decoration get ignored ("banner blindness").
**Spot it.** Important notices styled like promos; key info in a sidebar or header band; animation competing with the task.
**Fix.** Put critical information in the path of the task, styled as content, not as a banner. Reduce motion and noise near the main action.

## Aesthetic-Usability Effect
**Idea.** Attractive designs are perceived as easier to use and more trustworthy; users forgive minor problems in them.
**Spot it.** Rough visuals undermine trust in good content (critical for civic, finance and health products). Conversely, polish hides usability bugs in testing.
**Fix.** Basic craft matters: consistent spacing, type scale, alignment, real images. In tests, watch what people *do*, since they will say it's fine.

## Law of Closure
**Idea.** People complete incomplete shapes in their mind; a partial outline still reads as a whole.
**Spot it.** Overly heavy borders where whitespace and alignment would already define the shape.
**Fix.** Let alignment and partial cues imply edges (cut-off carousel cards signal "scroll for more"). Remove redundant outlines.

## Law of Continuity
**Idea.** The eye follows smooth lines and curves; elements arranged on a line or curve read as related and ordered.
**Spot it.** Zig-zag layouts that break reading direction; misaligned columns.
**Fix.** Align related items on a single axis; use straight rows for sequences; let a horizontal row that runs off-screen invite scrolling.

## Figure-Ground
**Idea.** People separate a scene into a foreground object and its background. When contrast is weak, they can't tell which is which.
**Spot it.** Text over busy photos; modals without a dimmed backdrop; low-contrast cards on similar backgrounds.
**Fix.** Clear contrast between content and background, overlays or scrims behind text on images, a dimmed backdrop for modals.

## Common Fate
**Idea.** Elements that move or change together are seen as a group.
**Spot it.** Related items animating independently; unrelated items sliding in together and seeming linked.
**Fix.** Animate groups as one; use shared motion to show what belongs to the item being dragged, expanded or removed.

## Law of Symmetry
**Idea.** Symmetrical elements are perceived as a stable, coherent whole and feel orderly.
**Fix.** Use symmetry for calm, balanced layouts (landing heroes, cards); break it deliberately only to draw attention.

## Focal Point
**Idea.** Whatever stands out most visually is looked at first. Each view has one entry point, chosen or accidental.
**Spot it.** A decorative image or a secondary badge grabs attention before the heading or primary action.
**Fix.** Decide the first thing to be seen and give it the strongest contrast, size or position; tone everything else down.

## Visual Hierarchy
**Idea.** Size, weight, colour, contrast, position and spacing tell people the order of importance. Hierarchy is how a page answers "where do I look first, second, third".
**Spot it.** Several elements at the same size and weight; headings barely larger than body text; a hierarchy that contradicts what matters.
**Fix.** A clear type scale (3–4 sizes), one primary colour for actions, generous space around the most important element; check by squinting or blurring the screenshot.

## Scanning Patterns (F and Z)
**Idea.** On text-heavy pages people scan in an F shape (top lines, then down the left edge); on sparse pages, a Z (top-left → top-right → diagonal → bottom).
**Spot it.** Key info placed on the right of long text, or in the middle of paragraphs; headings that start with filler words.
**Fix.** Front-load headings and list items with the meaningful word; put key actions and facts on the scanning path; use subheadings and bullets so the F has anchors.

## Banner Blindness
**Idea.** Users ignore anything that looks like an advertisement — boxed, brightly coloured, in typical ad positions — even when it's real content.
**Fix.** Don't style essential content like a promo; integrate it into the content flow. (See Selective Attention.)
