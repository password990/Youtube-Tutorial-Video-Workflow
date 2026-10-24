# YouTube Tutorial Video Workflow

A reusable VideoExpress workflow for polished, creator-led software tutorials modeled on the supplied *How to Use Hermes AI Agent* reference. The style alternates a personable on-camera host with crisp desktop screen recordings and short host returns.

## Reference style, observed

The attached reference is a 10:13, 16:9 tutorial (1280×720, 29.97 fps) with one continuous stereo audio track. It uses direct-to-camera presenter footage intercut with screen recordings of web pages, setup screens, terminals, and app interfaces. Screen sections carry the practical instruction; the presenter frames the chapter, explains why a step matters, and returns for transitions and summary. The visual treatment is clean, dark-interface-friendly, with occasional title text, a brief lower-third URL, cursor emphasis, and subtle zooms/crops on important controls. There are no animated characters, historical scenes, or lip-synced fictional avatars.

The intended adaptation is a presenter-led tutorial with the presenter speaking naturally on camera (lip sync to the recorded speech), plus screen-capture demonstrations under continuous narration. Never infer a voice model or imitate the reference presenter. Use a newly recorded or user-selected voice and identity.

## Contents

- `SYSTEM_PROMPT.md` — reusable production instructions for a browser-capable VideoExpress agent.
- `sample/README.md` — original sample concept and storyboard.
- `sample/SCRIPT.md` — original narration for a short demonstration video.

## Use

Load `SYSTEM_PROMPT.md` as the agent's instructions and provide a software topic, target audience, preferred presenter, aspect ratio, and runtime. The prompt asks for all missing choices together, researches the current interface before writing click paths, and plans a scene-by-scene mix of presenter and screen footage.

This is a browser-automation workflow, not a direct API integration. It requires access to VideoExpress and a way to record or generate presenter speech and screen footage. The sample script is a production-ready blueprint; it has not been rendered into a playable video in this repository.

## Local setup for a production

1. Confirm the current UI and workflow from the software's official documentation or live app.
2. Record the presenter segments with the chosen voice and camera setup; capture the software steps at readable resolution.
3. Assemble in the editor in the order laid out by the system prompt, retaining the full spoken track.
4. Review the exported result for factual accuracy, legible UI, audio continuity, and privacy before publishing.

## License and attribution

The workflow text and sample story are original. They describe high-level production characteristics of the user-supplied reference and do not include copied frames, transcript, audio, or presenter likeness.

