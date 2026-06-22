---
name: kunaals-illustrations
description: Generate English article illustrations. Used when the user requests "bizarre", "Boy character", "Girl character", "hand-drawn", "article illustration", "post image", "illustration suggestions", "shot list", "remove title/edit image" for English articles, posts, blogs, Notion docs, workflow docs, methodologies, processes, structures, states, metaphors, or opinions. Defaults to the Reference Boy or Girl IP, pure white background, hand-drawn lines, sparse red/orange/blue English annotations, with a clean but wildly imaginative visual style.
---

# Kunaal's Bizarre Article Illustrations

## Core Positioning

Design and generate 16:9 horizontal illustrations for English articles. The goal is not to create commercial illustrations, PPT infographics, or cute cartoons, but to turn key judgments, processes, structures, states, or metaphors from the text into clean, bizarre, creative, readable-but-not-instructional hand-drawn explainer images.

The default visual IPs are:
1. **"Reference Boy"**: A simple hand-drawn boy with short black hair, light blue t-shirt, and grey pants, seriously performing a bizarre but logical task.
2. **"Reference Girl"**: A simple hand-drawn girl with shoulder-length black hair, yellow t-shirt, and dark grey pants, seriously performing a bizarre but logical task.

The character must participate in the core action of the scene and cannot just stand aside as decoration.

## Read These References First

Read them as needed based on the task, do not cram everything into context at once:

- `references/style-dna.md`: Style DNA, colors, text, taboos.
- `references/character-ip.md`: Boy & Girl IP appearance, personality, action library, and taboos.
- `references/composition-patterns.md`: Structure types, original metaphor methods, and anti-repetition rules.
- `references/prompt-template.md`: Single image generation prompt template.
- `references/qa-checklist.md`: Post-generation check and iteration rules.
- `assets/examples/`: Only use for low-frequency visual calibration, do not enter default generation paths. Do not copy the compositions, objects, or labels from these examples.

## Workflow

### 1. Digest the Text

First, read the user-provided text, link, Notion page, Markdown file, or screenshot. Extract:

- What is the core opinion?
- Which paragraphs carry a cognitive shift?
- Which content is suitable to be explained with an image?
- Which places are only suitable for text and do not need an image?

Do not evenly distribute images. Prioritize "cognitive anchors," for example: core judgments, broken points, input/output loops, splitting paths, before/after comparisons, multi-purpose usage, succession paths, common pitfalls, and changes in character states.

### 2. Output Illustration Strategy First

If the user just says "analyze how to illustrate / think about where illustrations are needed," provide a shot list first. For each image, clearly write:

- Which paragraph it follows
- The theme of the image
- Core meaning
- Structure type
- What the character is doing in the image
- Suggested elements
- Suggested English label words

Default to 4-8 images. 1-3 images for very short articles; do not easily exceed 9 images even for long articles. Just enough is fine, avoid turning the text into a picture book.

### 3. Single Image Generation

If the user explicitly requests "generate / output / make an image / help me generate," do not stop and wait for confirmation; use the built-in image generator to generate each image individually. Do not stitch multiple images together.

Each image should explain only one core structure. The prompt must include:

- 16:9 horizontal English article illustration
- Pure white background
- Black hand-drawn line art
- Sparse red/orange/blue handwritten English annotations
- Plenty of empty white space
- The Boy or Girl as the core action subject
- Prohibit PPT, commercial illustration, childish/cute, complex architecture, and top-left corner type titles

Do not copy past examples. You must reinvent a strange but valid metaphor from the current article every time.

### 4. Check and Iterate

After generation, check against `references/qa-checklist.md`. If the following issues occur, prioritize regenerating or locally editing:

- Character is just a decoration
- The scene is too crowded
- Looks too much like a flowchart/PPT
- Too much English text or severe typos
- Titles like "Common Pitfalls/Flowchart/System Architecture Diagram" appear in the top-left corner
- The art style is too cute, childish, or rigid
- The background is not clean white

### 5. Save and Deliver

If the user is working inside the workspace, copy the final image to:

```text
Generated/
```

Name them sequentially describing the content (e.g. `boy_coding.png`, `girl_building.png`). Do not name the characters Kunaal in the file names.

Keep the original generated files, do not overwrite existing assets unless explicitly requested by the user to replace them.

## Output Tone

Pre-generation strategy output should be short and precise. Post-generation delivery should include:

- How many images were generated
- The purpose of each image
- Save path
- Which images are solid, which are optional

Do not write lengthy explanations of style theory; let the images speak for themselves.
