# Interaction: targets, speed, flow, progress, endings

## Fitts's Law
**Idea.** The time to reach a target depends on its distance and size: big, close targets are fast; small, far ones are slow and error-prone.
**Spot it.** Tap targets under ~44×44 px (iOS) / 48×48 dp (Android); icon-only buttons with a tiny hit area; destructive and primary actions next to each other; the main action far from where the thumb or cursor already is.
**Fix.** Enlarge hit areas (padding counts, not just the visible icon), keep primary actions close to the related content and within thumb reach on mobile, separate destructive actions. Screen edges and corners are effectively infinite targets on desktop.

## Doherty Threshold
**Idea.** Productivity and engagement rise sharply when the system responds within about 400 ms; slower feedback breaks the user's flow and invites double clicks or abandonment.
**Spot it.** Buttons with no pressed or loading state; blank screens while data loads; layout jumps when content arrives.
**Fix.** Instant visual feedback on every action (pressed state, optimistic UI), skeletons sized like the final content, progress for anything over ~1 s, perceived-speed tricks (prefetch, animation that covers latency). Avoid layout shift.

## Flow
**Idea.** People reach a state of focused, effortless engagement when the challenge matches their skill and nothing interrupts them.
**Spot it.** Interruptions mid-task (pop-ups, cookie walls, newsletter modals), unclear next step, tasks that are tediously easy or confusingly hard.
**Fix.** Clear goal and immediate feedback at each step, remove interruptions from core paths, let experts skip what beginners need.

## Goal-Gradient Effect
**Idea.** Motivation increases as people get closer to a goal; showing progress — even artificial head starts — speeds completion.
**Spot it.** Multi-step processes with no indication of how far along the user is; progress bars that start at zero after work was already done.
**Fix.** Show steps and progress, count completed actions, give credit for steps already done ("1 of 3 complete" after sign-up).

## Peak-End Rule
**Idea.** People judge an experience mostly by its most intense moment and its end, not by the average of every moment.
**Spot it.** A flow that ends abruptly (generic "Success" page) or with an error; a painful step at the climax (payment failure, a confusing final form).
**Fix.** Design the peak deliberately (the moment of value — the result, the insight, the delivery) and end well: a clear confirmation, a useful summary, a next step. Fix the worst moment before polishing average ones.

## Feedback
**Idea.** Every action needs a visible response showing it was received and what happened.
**Spot it.** Buttons with no state change; silent saves; errors shown far from the cause.
**Fix.** Pressed, loading, success and error states for every action; inline validation next to the field; toasts for background results.

## Affordances and Signifiers
**Idea.** An affordance is what an element lets you do; a signifier is the visual cue that tells you so. Flat design often removes signifiers, so users can't tell what is clickable.
**Spot it.** Clickable cards with no hover or arrow; text links in body colour; swipeable areas with no hint.
**Fix.** Make interactive things look interactive: underline or colour links, button shapes, hover and focus states, partial-overflow hints for scroll.

## Mapping
**Idea.** Controls should relate obviously to what they affect: spatially, by direction, or by convention.
**Spot it.** A filter that changes content somewhere unexpected; arrows that move content the opposite way; settings far from what they change.
**Fix.** Place controls next to their effect and make their direction match the movement.

## Constraints and Error Prevention
**Idea.** It's better to make errors impossible than to explain them afterwards.
**Spot it.** Free-text dates; destructive actions without confirmation or undo; submitting forms with missing required data.
**Fix.** Pickers and masks, disabled invalid options, confirmations for irreversible actions, undo instead of "are you sure?" where possible.

## Labor Illusion
**Idea.** People value results more when they see the work being done ("checking 391 decisions…"), even if it takes a little longer.
**Fix.** For searches, AI answers or analyses, show meaningful progress steps rather than a bare spinner. Don't add fake delays.

## Aesthetic Motion (purposeful animation)
**Idea.** Motion should explain changes (where something came from or went) rather than decorate. Gratuitous animation adds load and delay.
**Fix.** Short (150–300 ms) transitions that show cause and effect; respect `prefers-reduced-motion`; never block input behind animation.

## Hawthorne Effect (for testing)
**Idea.** People behave differently when they know they're being observed: more careful, more patient, more positive.
**Fix.** Treat lab-test success as an upper bound; back it with real-usage analytics and session recordings.
