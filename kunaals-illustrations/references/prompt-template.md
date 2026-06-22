# Image Generation Prompt Template

Generate each image individually. Replace variables based on the text content. Do not combine multiple images into one.

```text
Generate one standalone 16:9 horizontal English article illustration.

Visual DNA:
Pure white background. Minimalist black hand-drawn line art. Slightly wobbly pen lines. Lots of empty white space. Sparse red/orange/blue handwritten English annotations. Clean absurd product-sketch feeling. No gradients, no shadows, no paper texture, no complex background, no commercial vector style, no PPT infographic look, no cute mascot poster, no children's illustration, no realistic UI.

IP Characters (Use ONLY if the prompt asks for a person, boy, girl, or character):
If the scene requires a human, you must use the Reference Boy or the Reference Girl (or both). If the prompt does NOT mention a person or character (e.g. asking for just an animal, object, or abstract scene), DO NOT include the Boy or Girl.
Reference Boy: A minimalist digital doodle of a young boy based on the character style of references/images/10-boy.png: The boy has short hair, simple dot eyes, and a neutral, focused expression. He is wearing a plain light blue t-shirt and light grey pants.
Reference Girl: A minimalist, clean vector line art illustration of a cute young girl, based on the character style of references/images/09-girl.png. She has dot eyes, a simple concentrated expression, and her hair is tied in a high ponytail. She is wearing a pale yellow t-shirt and grey pants.
MULTIPLE CHARACTERS RULE: If the prompt requires multiple boys or multiple girls (e.g., "three boys"), DO NOT draw exact clones. You MUST randomly vary their t-shirt colors and make slight adjustments to their heights or hair to make them look like distinct individuals while keeping the same minimalist line-art style.
If a human is included, they must be drawn in the exact same wobbly line-art style as the rest of the image, and they must perform the core conceptual action.
NEVER generate realistic humans, 3D humans, or anime characters. Only use the simple hand-drawn Boy or Girl character when a human is needed.

Theme:
{Article Illustration Theme}

Structure type:
{Structure Type: Workflow / System component / Before & After / Role state / Conceptual metaphor / Method layering / Map route / Comic storyboard}

Core idea:
{The core meaning this image needs to convey}

Composition:
{Specific scene: Where is the character, what are they doing, what are the main objects, how does the information flow?}

Suggested elements:
{Element 1} / {Element 2} / {Element 3} / {Element 4}

English handwritten labels:
{Label 1} / {Label 2} / {Label 3} / {Label 4} / {Optional Label 5}

Color use:
Black for main line art and characters. Orange for main flow/path/arrows. Red only for key warnings/problems/results. Blue only for secondary notes or feedback/system state.

Constraints:
One image explains only one core structure. Keep the main subject around 40%-60% of the canvas. Preserve at least 35% blank white space. Use at most 5-8 short handwritten English labels. Do not write a title in the top-left corner. Do not write the structure type on the image. Do not make it a formal diagram, course slide, or dense explainer. Do not copy prior examples or reuse known case compositions unless explicitly requested; invent a fresh visual metaphor for this specific article. It should be clear but not instructional, interesting but not childish, strange but clean. UNDER NO CIRCUMSTANCES should you generate a realistic, anime, or 3D image. You must STRICTLY adhere to the minimalist black hand-drawn line art style.
```

## Image Editing Prompts

Remove top-left title:

```text
Edit the provided image. Remove only the handwritten title "{Text to delete}" and its underline from the top-left corner. Fill that area with the same clean white background, matching the surrounding blank paper. Preserve everything else exactly: characters, labels, paths, line style, composition, aspect ratio, and image quality. Do not add any new text or objects.
```

Enhance strangeness/absurdity:

```text
Regenerate this illustration with the same core meaning and simple layout, but make the character more central to the conceptual action. The character should be doing the strange work that explains the idea, not standing beside the diagram. Keep it clean, sparse, hand-drawn, and not cute.
```
