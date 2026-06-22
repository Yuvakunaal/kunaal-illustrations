# QA Checklist

## Must Pass

- It is 16:9 horizontal.
- The background is clean white.
- If the prompt requires a human, the designated character (Boy or Girl) is present.
- If a character is present, they must undertake the core action and not just be decoration.
- Did not copy old case compositions; instead, a new metaphor was generated for the current article.
- The image is bizarre, creative, and interesting.
- Simple and clean, the main subject does not exceed approximately 60% of the image.
- One image expresses only one core structure.
- English annotations are few, short, and readable.
- Orange is only used for main paths or arrows.
- Red is only used for key points, problems, reminders, or results.
- Blue is only used for supplementary explanations, feedback, or system states.

## Failure Signals

If the following occur, regenerate or locally edit:

- There are titles like "Common Pitfalls / Workflow / System Architecture Diagram / Roadmap" in the top-left corner.
- The character looks like a mascot, emoji, or cute cartoon.
- The image looks like a PPT, course slide, or formal flowchart.
- Too many elements, too many arrows, too many nodes.
- Text has become long explanatory paragraphs.
- The background has paper textures, shadows, gradients, beige color, or noise.
- Realistic UI screenshots or sci-fi/tech interfaces.
- Severe English typos or unreadable annotations.
- The image is too rigid, lacking an absurd metaphor.
- The composition is too similar to the old cases in `assets/examples/`.

## Iteration Methods

- **Too ordinary:** Make the character the subject of the action, add a strange but valid metaphor.
- **Too complex:** Delete nodes, keep only one action and 3-5 short annotations.
- **Too cute:** Emphasize "deadpan," "blank serious expression," "not cute," "not mascot."
- **Too PPT-like:** Remove titles, borders, neat grids, and excessive arrows; change to a hand-drawn scene.
- **Too similar to old cases:** Keep the core meaning, swap out the main object and character action.
- **Typos:** Prioritize local editing; if there are too many errors, regenerate and reduce the number of annotations.

## Delivery Judgment

A high-quality image should make the reader first feel "this is a bit strange," and then understand the structure within 1 second.

If at first glance it looks like a tutorial page rather than a bizarre product sketch on white paper, it fails.
