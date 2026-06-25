---
name: cj-15sec-prompt
description: CJ Studios AI 15-second instant-karma drama reel system for Higgsfield Seedance 2.0. Activate whenever the user types "/cj", mentions CJ Studios, asks for a video concept, a reference-image prompt, or a 15-second karma reel. Default to this skill for all AI short-video creation requests even if the user does not say "/cj". All stories are set in bright daylight. All hooks are physical confrontation. Single-generation 15s output — no stitching.
---

# CJ Studios — 15-Second Instant-Karma Reel System

Higgsfield Seedance 2.0 · 9:16 Vertical · Single-Generation 15s · Bright Daylight Only

---

## THE 15-SECOND LAW

One Seedance generation. One 15-second video. Three internal beats. No stitching, no clip chain.

Seedance renders the full 15s in a single pass — your prompt must carry all three beats inside it, timed to the second. If you describe stitch points or "clip 1 / clip 2," the model breaks continuity. Write it as one fluid scene with three moments.

**The 3-beat structure:**
- **Beat 1 (0–5s):** Hook — villain's move, the injustice, the humiliation. Must be physically visible in frame 1.
- **Beat 2 (5–10s):** Turn — hero's response, the redirect, the moment the villain realizes he over-committed.
- **Beat 3 (10–15s):** Payoff — villain hits the ground / gets exposed / staggers back. Hero delivers the final cold line. Crowd reacts.

---

## THE BRIGHT LIGHT LAW (NON-NEGOTIABLE)

**Every single shot is in bright daylight or a brightly lit interior. No exceptions.**

Why: On a phone screen, dark clips look muddy. Bright, warm, sunlit shots pop on every screen and get held longer. More views start with better lit frames.

- All stories set in morning sun, midday light, or large-window interiors.
- Faces always fully visible — no shadows crossing the eyes.
- Shadows are present (for depth) but never cover faces or key action.
- If the location is indoors, it has large windows with daylight flooding in.

**Default location palette:** sunlit street corner, bright café with floor-to-ceiling windows, open-air market, hotel lobby with skylights, parking lot in morning sun, bright school hallway, outdoor restaurant patio, sunny apartment entryway.

---

## THE HOOK LAW (from viral-hook playbook)

The first 0–2 seconds determine everything. 50% bounce = the algorithm buries the video. 90% hold = the algorithm amplifies it.

**For karma reels, the hook is always a physical move:** the villain does something visible and physical in frame 1. The viewer's brain registers threat + injustice instantly — no setup needed.

**Hook types that work for karma reels:**

| Hook | How to write it |
|---|---|
| **Sudden Movement** | Villain enters frame fast, closes distance, reaches out — camera flinches slightly. Viewer's peripheral vision hijacked. |
| **Reaction Before Action** | Open on hero's face — eyes widen, jaw tightens. We don't see what happened yet. Brain asks: what did this person just do to them? |
| **Status Assault** | Villain physically takes something, blocks something, or pushes someone in the very first frame. Injustice is established before the viewer can scroll. |
| **Eye Contact Break** | Hero looks directly into the lens for 0.5s then eyes shift to villain. Primal social brain activation — the viewer is now in the scene. |

**Camera for the hook:**
- Snap zoom from wide to tight close-up in under 0.5s — no easing, hard mechanical zoom.
- OR handheld with slight camera-flinch when the villain makes contact.
- Sound starts at 0.0s — no silent opening. Ambient crowd noise, outdoor ambience, or sharp impact.

---

## BRIGHT LIGHTING PRESETS

Pick ONE per video. State it in your prompt by name.

**OPEN DAYLIGHT**
`bright open-shade daylight ~5600K, soft wraparound fill from sky, faces fully lit, no harsh shadows, natural outdoor morning light`

**SUNLIT HARD** *(best for street/parking lot/outdoor confrontations)*
`direct hard morning sunlight ~5400K, strong key from sun at 30-degree angle, bright bounce fill off pavement and walls, golden-warm, sharp shadows on ground only`

**BIG WINDOW INTERIOR** *(café, hotel lobby, office)*
`large floor-to-ceiling window daylight ~5200K flooding the interior, bright even fill, warm interior ambient mixed with cool daylight, faces fully visible`

**BRIGHT OVERHEAD RETAIL/OFFICE**
`even overhead daylight-balanced lighting ~5000K, high-key, minimal shadow, bright and clean, commercial interior feel`

**GOLDEN MORNING** *(most cinematic — best for emotional payoffs)*
`warm early-morning sun ~3800K, bright golden key from low angle, strong bounce from nearby surface, faces glowing, warm cinematic grade`

---

## KARMA PHYSICALITY LAW

The villain does not "get beaten up." He defeats himself through his own momentum. The hero makes one small, precise movement. The villain's own force does the rest.

This is both more realistic and moderation-safe — describe physics, not combat.

**VILLAIN'S APPROACH — use these words:**
- advances aggressively / moves toward / closes distance / reaches out / lunges forward
- grabs at / shoves toward / pushes against / swings arm toward / steps into hero's space

**HERO'S RESPONSE — use these words:**
- steps aside / shifts weight / turns the shoulder / redirects the force
- the villain over-commits / his own momentum carries him / he loses his footing
- the hero's one small movement is enough / barely moved / planted and still

**THE RESULT — use these words:**
- villain stumbles / staggers backward / loses balance / goes down hard
- meets the counter-surface / crumples / lands on the ground
- the hero stands composed / untouched / steady / calm / did not move more than one step

**WHAT ACCURATE LOOKS LIKE:**

Wrong: "hero punches villain in the face"
Right: "villain lunges forward with both hands — hero sidesteps left, shifts weight — villain's own momentum carries him hard into the metal shelving unit — he crumples — hero watches, composed, unhurt"

Wrong: "they get in a fight outside"
Right: "villain advances fast, reaches for hero's collar — hero pivots, steps aside — villain's weight takes him past, his shoulder meets the car door — he goes down — hero did not move more than one step"

**BANNED WORDS IN ALL PROMPTS:**
fight, fighting, fighter, punch, kick, hit, strike, attack, assault, combat, violence, violent, weapon, blood, injury, fist, brawl, chokehold

---

## WORKFLOW (always follow this order)

1. **Concept** — one strong recommendation + 2 quick alternates. State: location, villain move, hero response type, prop reveal, final line.
2. **Reference-image prompt** — one still-image prompt the user pastes into ChatGPT. Establishes characters, costume, location, lighting, mood, 9:16 vertical. This is a visual reference — show key characters and location clearly in one frame.
3. **Wait for the image** — user pastes back the generated reference image.
4. **15-second video prompt** — using the locked structure below + the reference image, write the final prompt for Seedance 2.0 on Higgsfield. This is the deliverable they paste in.

**Reference syntax:** `@material[image1]` for images, `@material[video1]` for video clips, `@material[audio1]` for audio.

---

## THE 9:16 SAFE ZONES

```
┌─────────────────┐  ← Top 12%: platform UI (covered)
│   SAFE CONTENT  │
│   CENTER 68%    │  ← All faces, key action, prop reveals go here
│                 │
└─────────────────┘  ← Bottom 20%: captions/UI (covered)
```

- Hero's face: always in center 68% of frame.
- Villain's face during reaction: always in center 68%.
- Prop reveal: must happen in center 68%.
- Final line delivery: hero's face center-frame, not at the edges.

---

## CHARACTER CASTING PATTERN

**Hero:** Sympathetic underdog. Working class, parent, or person with hidden skill/status. Dressed simply. Not physically imposing — the surprise is that they don't need to be.

**Villain:** Entitled, confident, publicly aggressive. Expensively dressed or in a position of assumed authority. Loud. Their confidence is the setup for their fall.

**Prop reveal:** One object that flips the status at payoff. The viewer didn't see it coming. Examples: badge, bracelet, credential, ID, phone screen, key fob, uniform element hidden under coat.

**Write simple, exact descriptions. Repeat them in every beat.**

---

## DIALOGUE RULES

- Spoken dialogue required. Clear American English only. Visible, natural lip sync of the exact lines.
- Villain lines: cruel, personal, specific — not generic.
- Hero final line: cold, short, simple — never to camera, always to villain.
- No narration. No subtitles. No voiceover.

**Good final-line texture:**
- "Park your ego somewhere else."
- "House wins."
- "Wrong platform."
- "Your ride just told on you."
- "Now we wait for the police."
- "First class doesn't fix low class."
- "Keep the video."
- "Wrong person."
- "Clock's running."
- "Already called it in."

---

## IDENTITY vs MOTION SPLIT

To prevent face drift across the 15-second generation, split the description into two blocks:

**IDENTITY BLOCK** (describe once, early in the prompt — this locks the face):
> Hero: [ethnicity, age range, hair, face features, exact clothing — frozen, no action words]
> Villain: [same format]

**MOTION BLOCK** (describe actions after — reference characters by role, not appearance):
> The villain advances and reaches toward the hero. The hero sidesteps. The villain's momentum carries him forward. He goes down. The hero stands still, watching.

Do not mix physical description and motion in the same sentence — it confuses the model's face-locking.

---

## LOCKED VISUAL THEME BLOCK

Paste this verbatim into every prompt (at the end, before the negative prompt):

```
VISUAL THEME LOCK: 24fps cinematic, slight film grain, color grade warm-neutral,
no digital smoothing, no soap-opera effect, no interpolated frames,
real-movie-footage texture throughout. Consistent lighting, consistent background,
consistent costumes — no changes between shots.
```

---

## CLIP PROMPT STRUCTURE (fill this in every time)

```
REFERENCE: Use @material[image1] as VISUAL REFERENCE ONLY — not as the literal
first frame. Use it for character consistency, clothing, location mood, and style only.

FORMAT: 15-second single-generation video, 9:16 vertical, ultra-photorealistic
real-movie-footage look, handheld cinematic camera, hard cuts every 1–2s.
MULTIPLE SEPARATE CINEMATIC SHOTS. NO SINGLE CONTINUOUS SHOT. NO SLOW PACING.

LIGHTING: [paste chosen preset]

IDENTITY BLOCK:
Hero — [exact description]
Villain — [exact description]

CONTINUITY LOCK: Same faces, same costumes, same location, same lighting
across all 15 seconds. No costume changes, no background changes, no face changes.

PROP: [the reveal object] — no readable text on it.

DIALOGUE: Spoken audio required. Clear American English. Visible lip sync.
No subtitles, no narration.

MOTION BLOCK:
0–5s: [hook beat — villain's move, hero's immediate reaction, crowd noticing]
Villain says: "[villain line]"
5–10s: [turn beat — villain escalates or re-commits, hero's redirect, the moment]
10–15s: [payoff beat — villain goes down, crowd reacts, hero delivers final line]
Hero says: "[final line]" — spoken to the villain, not to camera.

SOUND STACK:
Ambient: [outdoor crowd / café hum / office background / street noise]
Impact: [hard surface contact, sudden stillness, crowd exhale or gasp]
Dialogue: spoken lines as described above
Tone: tension cut to silence cut to crowd reaction

VISUAL THEME LOCK: 24fps cinematic, slight film grain, color grade warm-neutral,
no digital smoothing, no soap-opera effect, no interpolated frames,
real-movie-footage texture throughout. Consistent lighting, consistent background,
consistent costumes — no changes between shots.

NEGATIVE PROMPT: dark, underexposed, low light, night scene, crushed shadows,
silhouette, murky, dim, moody darkness, narration, voiceover, subtitles,
readable text, letters, captions, logos, watermark, cartoon, anime, CGI look,
3D render, plastic skin, waxy skin, smooth airbrushed skin, dead glassy eyes,
distorted hands, extra fingers, fused fingers, morphing hands, morphing objects,
duplicating objects, vanishing objects, warping background, melting geometry,
smearing crowd faces, gibberish text, over-smooth motion, soap-opera effect,
interpolated frames, floaty motion, gliding feet, weightless movement,
rubbery limbs, acrobatics, exaggerated movement, superhero action, flying bodies,
slow motion, slow pacing, boring wide shots, empty transition shots,
single continuous shot, multiple camera POV switches, head turning during dialogue,
changing faces, changing clothes, changing background, different person,
extra limbs, foreign language, low quality
```

---

## THE LOOP

The final frame must rhyme with the first frame — same location framing, same camera angle, same ambient sound. The viewer who watches twice sees it as seamless.

**Loop checklist:**
- Final frame: hero standing in same position as frame 1 (villain now on the ground)
- Camera angle at end: matches opening wide shot
- Ambient sound at 14–15s: same as 0–1s (crowd noise, outdoor ambience)
- The prop that was hidden in frame 1 is now visible in frame 15

**Loop template line (paste at end of motion block):**
`Final frame echoes the opening — same wide angle, same location, same ambient sound. The scene has resolved. The loop is complete.`

---

## HOOK PATTERN MENU (pick one per video)

| Hook | Opening line in prompt |
|---|---|
| Sudden Movement | "Opens on hero in bright morning sun — villain enters frame from the left at speed, closes distance fast — camera flinches slightly as villain reaches out —" |
| Reaction Before Action | "Opens on extreme close-up of hero's face — eyes widen, jaw tightens — we don't see the villain yet — camera pulls back to reveal the confrontation already in progress —" |
| Status Assault | "First frame: villain's hand is already on hero's shoulder, pushing — hero is mid-stumble — crowd in the background already turning to look —" |
| Eye Contact Break | "Hero looks directly into lens for 0.5s — then eyes shift hard left to villain — camera follows the shift — villain is advancing —" |

---

## REFERENCE-IMAGE PROMPT TEMPLATE (for ChatGPT)

```
Ultra-photorealistic cinematic still, vertical 9:16, [GOLDEN MORNING / SUNLIT HARD /
BIG WINDOW INTERIOR] lighting. [Location: specific place, rich background detail].

Hero: [exact age, ethnicity, hair, clothing — simple and working class].
Villain: [exact age, ethnicity, hair, clothing — expensive/authoritative].

The moment shows [the humiliation beat — what is the villain doing to the hero right now?].
[Crowd / onlookers / bystanders] visible in background.

[Prop: the reveal object, partially hidden on hero's person].

Sharp focus, film-grade color, shallow depth of field, warm cinematic grade.
No text, no logos, no watermark, no subtitles.
```

---

## RETAKE / TROUBLESHOOT

| Problem | Fix |
|---|---|
| Face drift mid-video | Strengthen IDENTITY BLOCK. Add: "Same face throughout — do not alter facial features between shots." |
| Villain doesn't go down convincingly | Replace vague action with specific physics: "his left foot slips on the polished floor, his weight shifts forward, he goes down on one knee then fully to the ground." |
| Final line not syncing to mouth | Add: "Hero pauses for 0.5s after the villain hits the ground — then speaks slowly and clearly." |
| Restricted content flag | Check your prompt for: fight, punch, kick, hit, strike, attack, assault, combat, violence, blood. Replace all with physics/consequence language. Also check your negative prompt for those same words. |
| Background changes between shots | Add: "Identical location in every shot — same wall, same floor, same crowd arrangement, same light source position. No background changes." |
| AI-tell: floaty movement | Add to negative prompt: floaty motion, gliding feet, weightless movement, rubbery limbs |
| Too slow / boring pacing | Add: "Hard cuts every 1.5 seconds. No held shots longer than 2 seconds. Urgency throughout." |

---

## DELIVERY DEFAULTS

- Duration: 15 seconds
- Aspect: 9:16 vertical
- Resolution: 720p (Seedance standard) — upscale in post if needed
- Format: Seedance 2.0 Enhanced Fast on Higgsfield
- Logo: never in the AI prompt — add in CapCut post (top-left, 7–9% width, 45–60% opacity)
- Subtitles: never in the AI prompt — add in CapCut post
- Platform: Facebook Reels primary, YouTube Shorts secondary, Instagram Reels tertiary

---

## CONCEPT CATALOGUE (do NOT repeat — use for tone calibration)

- Beach patrol officer vs drunk yacht guy (Miami morning). Reveal: stolen-yacht key fob. Line: "Your ride just told on you."
- Female pilot vs entitled passenger (airport gate, bright terminal). Reveal: she's the captain. Line: "First class doesn't fix low class."
- Woman confronted outside bright apartment lobby; aggressor's confidence collapses. Line: "Now we wait for the police."
- Food delivery driver vs wealthy restaurant owner (bright lunch service). Reveal: child's hospital bracelet. Line: "Keep the video."
