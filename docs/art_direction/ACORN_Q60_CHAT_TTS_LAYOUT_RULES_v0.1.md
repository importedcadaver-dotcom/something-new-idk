# Acorn Q60 — Chat Panel & TTS Layout Rules v0.1

**Status:** WRITTEN DESIGN GUIDANCE derived from [Q60 direct approved decision](../decisions/Q60_CHAT_BELOW_WEBCAM_ADAPTIVE_TTS_APPROVED.md). No UI screenshot, art, game scene, implementation, voice or audio was created. Any treatment labeled “proposal” is NOT yet user-approved.

## Established on-screen relationship

**Normal discrete-webcam layout:**

- **Acorn's custom framed webcam:** **MIDDLE-LEFT** of the overall broadcast (Q58/Q59).
- **Live chat:** A **COMPACT PANEL DIRECTLY BELOW that webcam** (Q60 B).
- **Currently spoken TTS message indication:** **BESIDE the webcam** (Q60 G), rather than automatically inside or at the bottom of the chat box. Whether beside its left or right edge is **UNDECIDED**.
- **Main content:** remains readable; for Q58 gameplay-first, most screen area is the real game. The current chat/webcam arrangement must not hide essential real-game HUD controls, text or subtitles.
- **Mode adaptability:** Q60 E authorizes different chat arrangements for gameplay-first, reaction-first and Just Chatting; Q60 F authorizes expansion/collapse. These do not force every mode to keep a small independent webcam or panel.

This is a **textual spatial specification**, not a character scene, screenshot, image mockup, pixel layout or running app.

## Approved four-mode interactions (requirements, not state-machine code)

| Q60 approval | Written UI behavior | Still open |
|---|---|---|
| **B compact panel below camera** | In normal inset-camera mode, chat sits below Acorn on the left-middle part of the full composition. | Actual height/width, whether aligned to edges of camera frame, shadow, corners, border. |
| **E layout by stream format** | Chat layout can vary according to the existing Q58 game/reaction/chatting modes. | Exact alternate slot coordinates, persistence policy, how transitions happen. |
| **F expand/collapse** | Compact chat should be able to open for longer reading then return to a smaller view when gameplay must be legible. | Click/touch/keyboard control, auto-collapse vs Acorn instruction, animation and limits. |
| **G TTS indication beside webcam** | The audience and Acorn can tell which message is currently being spoken aloud, without losing association with Acorn's camera. | Left/right TTS position, spoken text display vs icon, queue behavior, speaking indicator and TTS voice. |

**Not approved:** Q60 A right-vertical as normal chat, C independent bottom strip, D transparent floating chat. Q60 E grants format flexibility but is **not** independent approval for A/C/D as chosen defaults.

## Mode-specific paper test cases — NOT chosen exact layouts

These are **examples to evaluate later**, not additional decisions:
- **Gameplay-first:** small webcam middle-left and compact panel below; ensure no critical Fortnite HUD, Minecraft/Hypixel SkyBlock inventory, Pokémon move menu, or Zelda interface is obscured. If a content conflict occurs, record the conflict rather than asserting that Acorn's normal chat is now right-side.
- **Reaction-first:** larger middle-left webcam and potentially larger/chat-focused companion panel; reaction media (text/video) should remain readable. No specific clip or transcript chosen.
- **Just Chatting:** Acorn camera can be primary/full-screen; chat can enlarge or use an alternate configuration under E. Do not force duplicate inset webcam.
- **Family/friends split-screen:** guest panel positions remain flexible and unselected; chat must not force identities or previously undecided guest appearances.
- **Outdoors and activities:** mostly full-screen view, minimal secondary UI; exact way chat appears remains open.
- **Challenge opt-in:** Q58 G/Q59 G permit voluntary challenge widgets; the chat area must still support TTS/readability, and Acorn may refuse a challenge.

## Q54 fidelity-first future QA checklist

1. **Spatial:** webcam normally middle-left; compact chat directly below; TTS indicator beside webcam.
2. **Variability:** chat can change in activity-specific layouts and can expand/collapse; no fixed all-mode lock.
3. **Separation:** keep in-world game, chat, TTS and alerts legible without a cluttered “AI dashboard.”
4. **Brand:** Q59 B/C/H custom HoneyDweller/Acorn motif (precise logo OPEN), dark-red accents, scalable webcam frame; Q59 option A remains **unselected** while Q58 H minimal polish stays approved.
5. **Authenticity:** real game screen references are Q57 selected titles, **Fortnite canon**; other listed game selections are comparison subjects, not invented prior VODs.
6. **Acorn's agency:** no forced donations/food/challenges, no fixed stream schedule, no unapproved platform branding.
7. **Visual identity:** anatomical **RIGHT** red-cinnamon ear, anatomical **FRONT LEFT** lighter sock; hazel eyes, white belly, dark back, cinnamon detail, broad tail and oversized paws. The webcam must not turn Acorn into an adult or a humanoid mascot.
8. **Family:** MilIie's unchosen coat/eye details and guest cameras do not become canon through layout hypotheses.
9. **Evidence:** There are **no actual visuals or software to test yet**; future performance, grades, lengths and dimensions must not be presented as observed.

## Suggested next owner decision (not approved)

**Q61 — TTS and chat behavior / active-message treatment:** What should be visible when TTS is speaking (message highlight, name label, queue, moderation, pause, density limits, reactions)? Support multiselect and **Other/custom**, while keeping confirmed beside-webcam indication and chat below-webcam default. Avoid inventing exact platform, specific viewers, sound samples, actual streamer UI or code.

**Source boundary:** Original Q6–17 direct responses remain incompletely recovered; Q60 is user-authored direct approval.
