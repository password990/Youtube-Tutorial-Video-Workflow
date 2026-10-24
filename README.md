# YouTube Tutorial Video Workflow (Veo 3)

A Veo-oriented adaptation of the host-led software tutorial workflow. It combines a real presenter and authentic screen recordings with short, generated Veo establishing or illustrative clips.

## Reference style

The supplied reference is a 10:13, 16:9 software tutorial. A seated host speaks to camera, alternating with readable full-screen desktop demonstrations. The host introduces the goal, explains decisions and returns for recap; the screen capture carries the exact steps. The edit uses occasional cursor emphasis, controlled crops/zooms, a title and a lower third. The style is practical and creator-led, not a cinematic fictional story.

## Veo production approach

Veo clips are short, so treat them as inserts rather than asking one generation to create the whole tutorial. For a software walkthrough, capture the actual product interface separately. Use Veo for a short opening atmosphere/result metaphor, workspace cutaways, or a consistent host shot if the chosen interface and model supports the needed controls. Record the real host and voice when possible. Do not let generated UI stand in for genuine steps.

## Files

- `SYSTEM_PROMPT.md` — reusable Veo-specific production instructions.
- `sample/README.md` — original sample concept and scene plan.
- `sample/SCRIPT.md` — original narration.
- `sample/VEO_PROMPTS.md` — shot-sized prompts for Veo 3.

## Start a production

1. Load `SYSTEM_PROMPT.md` into your production agent.
2. Supply topic, target viewer, ratio, runtime, Veo interface (Flow, Gemini, or Vertex AI), and whether you have host footage.
3. Verify the currently selected model, supported clip lengths, aspect ratios, reference/image features, sound options, and export behavior in the actual UI before batching generations.
4. Generate short Veo clips, capture the real screen walkthrough, record host/narration, and assemble them in a timeline editor.

## Model note

Veo product features and model names change. Google documentation currently distinguishes capabilities by model and interface. Classic Veo 3 on Vertex AI documents text-to-video, generated sound, 16:9/9:16, and 4/6/8-second clips; Flow exposes a changing set of Veo 3.1 variants and feature support. Check the live model settings and official docs linked from `SYSTEM_PROMPT.md` before production.

## Output status

The sample is a complete script, storyboard, and Veo prompt pack. No generated clips or finished tutorial video are included; rendering requires access to Veo and a timeline editor.

