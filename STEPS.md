# Distant Empires — Production Workflow
AI cinematic YouTube channel. HBO historical drama tone. 2–3 min episodes.

**Tool Stack**
- Script: Claude / ChatGPT
- Image generation: Higgsfield
- Video/clip generation: Higgsfield / Kling
- Voiceover: ElevenLabs
- Music: Suno
- Editing: CapCut
- Publishing: YouTube (channel already created)

**Status:** Episode 1 complete. Prompts to be captured live during Episode 2.

---

## Step 1 — Topic & Angle

Choose a historical event or civilization with strong visual potential.

- Target era: ancient civilizations, empire collapse, war, natural disaster
- Angle: cinematic, dramatic, first-person or narrator POV
- Runtime target: 2–3 minutes
- Episode 1 topic: **Pompeii — the eruption of Vesuvius 79 AD**

**What to capture during Episode 2:**
- [ ] Topic chosen
- [ ] Angle / POV decided (narrator vs. first-person)
- [ ] Why this topic has visual potential (notes for future episodes)

---

## Step 2 — Script

Write a narration script. Tight, cinematic, no filler.

- Length: ~300–400 words for 2–3 min at natural narration pace
- Tone: HBO documentary — gravitas, precision, imagery
- Structure: hook → build → climax → reflection
- Each paragraph should map to a visual scene

**Episode 1 script:** `episodes/ep01-pompeii/script.md` — 12 clips, full narration + image + movie prompts captured.

**Prompt used to generate script:**
[PROMPT PLACEHOLDER — collect from Claude/ChatGPT session]

**What to capture during Episode 2:**
- [ ] Full script text
- [ ] Prompt used to generate it
- [ ] Any manual edits made and why

---

## Step 3 — Scene Breakdown

Split script into scenes. Each scene = one or more clips.

- One scene per paragraph (roughly)
- Note the visual action for each: what is shown, camera movement, mood
- This becomes the input for image and video generation

**Episode 1 scene breakdown:**
12 clips — see `episodes/ep01-pompeii/script.md` for full scene list with image and movie prompts per clip.

**What to capture during Episode 2:**
- [ ] Scene list with visual description for each
- [ ] Number of clips per scene

---

## Step 4 — Image Generation (Higgsfield)

Generate key frame images for each scene. Used as references or direct clips.

- Style: photorealistic, cinematic lighting, dramatic
- Aspect ratio: 16:9 (YouTube)

**Episode 1 prompts:**
Captured in `episodes/ep01-pompeii/script.md` — image prompt per clip.

**Settings used:**
- Model: [PLACEHOLDER]
- Style preset: [PLACEHOLDER]
- Any negative prompts: [PLACEHOLDER]

**What to capture during Episode 2:**
- [ ] Every prompt used, copied verbatim
- [ ] Model and settings for each generation
- [ ] Which images were kept vs. rejected and why

---

## Step 5 — Video Clip Generation (Higgsfield / Kling)

Animate the key frames into short clips. 3–6 seconds each.

- Motion: slow, cinematic — no fast cuts or jarring movement
- Prompt should describe camera motion as well as scene action

**Episode 1 prompts:**
Captured in `episodes/ep01-pompeii/script.md` — movie prompt per clip.

**Settings used:**
- Tool: [Higgsfield / Kling — which was used per clip]
- Duration per clip: [PLACEHOLDER]
- Motion intensity: [PLACEHOLDER]

**What to capture during Episode 2:**
- [ ] Every video prompt, verbatim
- [ ] Tool used per clip (Higgsfield vs. Kling)
- [ ] Clip duration and motion settings
- [ ] Clips kept vs. rejected

---

## Step 6 — Voiceover (ElevenLabs)

Generate narration audio from the script.

- Voice: [PLACEHOLDER — voice name/ID used for Episode 1]
- Stability: [PLACEHOLDER]
- Similarity boost: [PLACEHOLDER]
- Style: [PLACEHOLDER]

**Process:**
1. Paste full script into ElevenLabs
2. Generate full narration in one pass (or by paragraph if needed)
3. Export as MP3/WAV
4. Listen through — re-generate any lines that sound off

**Episode 1 voice settings:**
- Voice: Harrison (ElevenLabs)
- Stability: [PLACEHOLDER — note after generation]
- Similarity boost: [PLACEHOLDER]
- Style: [PLACEHOLDER]

**What to capture during Episode 2:**
- [ ] Voice name and ID
- [ ] All settings (stability, similarity, style)
- [ ] Any sections re-generated and why

---

## Step 7 — Music (Suno)

Generate background score. Cinematic, instrumental, period-appropriate.

- Mood: dramatic, orchestral, building tension
- Must not overpower the voiceover

**Episode 1 prompt:**
Cinematic orchestral score, ancient Rome, warm Mediterranean opening, building tension toward catastrophe, mournful reflective ending, no vocals, documentary style, 60 seconds

**Settings:**
- Style tags: cinematic, orchestral, documentary, no vocals
- Duration: 60 seconds
- Download format: MP3
- Track selected: [PLACEHOLDER — note which variation was used]

**What to capture during Episode 2:**
- [ ] Suno prompt verbatim
- [ ] Style tags used
- [ ] Which generated track was selected and why

---

## Step 8 — Edit (CapCut)

Assemble everything into the final video.

**Assembly order:**
1. Import all clips into timeline
2. Arrange clips to match scene breakdown order
3. Import voiceover — lay on audio track
4. Sync clips to narration (clip transitions should follow narration beats)
5. Import music — lay under voiceover, set volume to 40 (CapCut iOS 1–100 scale)
6. Add titles:
   - Opening title card: episode name + "Distant Empires"
   - Optional: location/date overlays per scene
   - End card: channel name + subscribe prompt
7. Color grade if needed — cinematic look, slightly desaturated
8. Export: 1080p minimum, 4K if clips support it

**Episode 1 edit notes:**
[PLACEHOLDER — any decisions made during edit: pacing, transitions, title style]

**What to capture during Episode 2:**
- [ ] Title card text and font used
- [ ] Music volume level relative to voiceover
- [ ] Any color grade settings applied
- [ ] Export settings

---

## Step 9 — Publish (YouTube)

**Channel:** [PLACEHOLDER — channel name/URL]

**Upload checklist:**
- [ ] Title: descriptive, curiosity-driven — e.g., "The Last Day of Pompeii | Distant Empires"
- [ ] Description: 2–3 sentences + timestamps if applicable
- [ ] Tags: historical, cinematic, AI, documentary, [topic-specific]
- [ ] Thumbnail: pull best frame from video, add title text overlay in CapCut/Canva
- [ ] Visibility: Public
- [ ] Category: Education or Entertainment
- [ ] End screen configured

**Episode 1 metadata:**
[PLACEHOLDER — title, description, tags used]

---

## Prompt Capture Checklist (Episode 2)

Use this during production — don't rely on memory after the fact.

| Step | Item to capture | Captured? |
|---|---|---|
| Script | Generation prompt | [ ] |
| Script | Manual edits made | [ ] |
| Scene breakdown | Visual description per scene | [ ] |
| Images | Higgsfield prompt per image | [ ] |
| Images | Model + settings | [ ] |
| Clips | Higgsfield/Kling prompt per clip | [ ] |
| Clips | Tool used + duration + motion settings | [ ] |
| Voiceover | ElevenLabs voice name + ID + settings | [ ] |
| Music | Suno prompt + style tags + track selected | [ ] |
| Edit | Title card text + font | [ ] |
| Edit | Music volume level | 40 (CapCut iOS 1–100 scale) |
| Edit | Export settings | [ ] |
| Publish | Title, description, tags | [ ] |

---

## Episodes

| Episode | Topic | Status | Notes |
|---|---|---|---|
| 1 | Pompeii — eruption of Vesuvius 79 AD | PUBLISHED | https://www.youtube.com/shorts/BSS7R9G0Qos |
| 2 | Antonine Plague — the disease that began the fall of Rome | TODO | Full prompt capture during production |
| 3 | [TBD] | TODO | Pipeline run (automated) |
