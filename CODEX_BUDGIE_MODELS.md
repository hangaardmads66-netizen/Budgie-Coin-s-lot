# Codex task: Replace the placeholder Budgie bird characters

## Goal
Upgrade the existing mobile game's two budgerigar characters, using the user's own birds as visual inspiration and four new concept-art sheets prepared in ChatGPT. Do not assume the concept sheets are actual 3D models or production-ready sprites.

## Characters
1. **Green budgie (Kawa):** yellow head and face; yellow/black barred neck and wings; vivid turquoise-green chest; dark throat spots and blue cheek patches; long teal/blue tail. Energetic, curious, confident.
2. **Blue budgie:** white forehead and face; pale sky-blue chest; black/gray striped wings and head; blue/violet cheek patches and black throat spots; long blue tail. Gentle, curious, expressive.

## Art direction
- Premium stylized 3D-looking casual-game aesthetics, smooth rounded-but-believable anatomy, individually legible layered feathers, lively glossy eyes.
- Two possible presentations from the concept art: **polished natural/soft lighting** or **cinematic neon accents**. Choose a single coherent in-game style; don't overdo glow, and keep both birds visually consistent.
- Make models readable at small Android-screen sizes. Preserve the distinct colors and patterning from the real birds.
- The images are design references only: create actual usable runtime assets appropriate to the game's engine, which must first be identified.

## Animation goals
- Gentle breathing, subtle body movement, blinking and head tilts while idle
- Hops/perching, expressive wing flaps, tail movements, small chirp motions
- Light feather particles at slot-machine spin stop, as previously requested
- Random but controlled bird fly-bys if performant
- Consistent animations without clipping/disappearing body parts

## Implementation roadmap
- [ ] Locate the actual game source and determine engine/rendering approach. If this GitHub repo remains empty, stop and ask for the project code or its correct repo rather than pretending the models are implemented.
- [ ] Import/view the concept images attached separately by the user to the Codex conversation (the four sheets are not embedded here).
- [ ] Build new bird visual assets for both characters, with reusable materials, texture atlases and LOD/sprite sizes as appropriate.
- [ ] Rig and animate, or set up equivalent sprite/mesh animation, matching the current engine.
- [ ] Replace placeholder visuals while preserving gameplay and behavior.
- [ ] Optimize Android performance and fit different aspect ratios; check foldables, tall screens, smaller devices.
- [ ] Produce screenshots/video previews and request approval before publishing or replacing production assets.

## Important
- This is a single-player mobile game intended for Google Play.
- Do not copy Coin Master's artwork, animations, trademark or proprietary UI.
- The user's real photographs are private. Do not publish original photos to this public GitHub repository without express permission.
- Do not modify company logo/branding as part of this character task.
