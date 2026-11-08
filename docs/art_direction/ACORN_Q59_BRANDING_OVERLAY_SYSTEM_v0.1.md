# Acorn Q59 — Branded Stream Overlay System v0.1 (Written Design)

> **Q61 subsequent approval (2026-11-08):** The current [Q61 TTS behavior spec](ACORN_Q61_TTS_CHAT_BEHAVIOR_SPEC_v0.1.md) adds active-message highlighting, speaker names beside webcam, Acorn skip/pause/resume, moderation, eligible priority senders, variable density and quiet idle display (A+B+D+E+F+G+H). No visible queue C. Q59 and Q60 remain binding; this document's earlier open TTS behavior notes are superseded only in those directly approved areas.

> **Q60 subsequent direct approval (2026-11-08):** Compact **chat directly BELOW Acorn's normally middle-left webcam**, **mode-dependent chat arrangement**, **expandable/collapsible chat**, and **TTS speaking indicators BESIDE the webcam**: options **B+E+F+G**. See [Q60 decision log](../decisions/Q60_CHAT_BELOW_WEBCAM_ADAPTIVE_TTS_APPROVED.md) and [Q60 design rules](ACORN_Q60_CHAT_TTS_LAYOUT_RULES_v0.1.md). Statements below describing chat position as OPEN apply only to this Q59 document's earlier historical stage and are superseded for normal chat placement.

**Status:** DESIGN COMPARISON ONLY — Q59 selected B–H, did NOT select A.  
**Authority:** [Q59 Approval](../decisions/Q59_BRANDING_AND_OVERLAY_B_TO_H_APPROVED.md); [Q58 approved layout options](../decisions/Q58_ALL_STREAM_LAYOUT_MODES_AND_MIDDLE_LEFT_WEBCAM_APPROVED.md); [Q54 fidelity-first rubric](ACORN_STYLE_EVALUATION_RUBRIC_Q54_v0.1.md).  
**No images, screenshots, implemented UI, gameplay, scenes, music, source code, or live stream are authorized.**

## 1. Design objectives and what is actually approved

**Identity:** A distinct **Acorn/HoneyDweller branded** interface that does not resemble a children's cartoon; use **dark red as an accent**, not necessarily as its entire palette. The user's checked Q59 B/C authorize a *design objective*, not a particular logo, exact colors, icon set, font or template.

**Functional overlay features:** Readable chat (D), visible TTS/chat-reading status (E), transient contextual donations/alerts (F), opt-in challenge/vote widgets (G), a custom resizable webcam frame (H).

**Independent option A unselected:** Q59's generic “clean professional gaming overlay” was NOT chosen. However, Q58 H approved a minimal, polished broadcast interface; therefore branded elements should be intentional and restrained. Do not falsely promote the omitted A checkbox to a Q59 approval.

## 2. Anchor / zones

The user's **MIDDLE-LEFT Acorn webcam** placement from Q58 is already canon. The custom webcam *frame* from Q59 H should be anchored around that panel in ordinary game/reaction broadcasts.

**Resizability:** Q58 F allows the camera and chat to grow/shrink/reposition with the activity; reaction-first usually calls for a bigger webcam, gameplay-first a smaller webcam. Just Chatting or outdoor streams may use a primary/full-screen camera without a second webcam inset. “Middle-left” is the default panel anchor, **not an absolute always-visible box**.

**Q60 RESOLVED normal chat position:** A compact panel **directly BELOW** Acorn's **MIDDLE-LEFT** webcam. Mode-specific rearrangements and expansion/collapse are approved; TTS speaking status is **BESIDE** the webcam. The previous right-vertical, bottom-strip and transparent-floating Q60 options were **not selected**. Exact variations and TTS left/right side remain OPEN.

**Other open layout details:** relative panel percentages, webcam aspect ratio, clipping mask, safe zones for real-game HUD, layering of donation alerts, vote widget position, TTS queue position, chat badge policy, whether stream chat is a platform widget or an overlay at all.

## 3. Textual visual/design variants — PROPOSALS only

The variants deliberately preserve Q59's checked B/C/H and Q58 minimal polish, without pretending to have graphic examples.

| Proposed direction | Visual identity hypothesis | Potential advantage | QA risk |
|---|---|---|---|
| **Branded restraint** | Tiny Acorn/HoneyDweller identity cues on webcam edge and a sparing dark-red accent; neutral base colors | Feels like a real streamer, readable | Could look too generic if branding weak |
| **Premium bear-world identity** | Deliberate den/paw/wood texture cues used very selectively; dark-red signals for interactivity | More distinct world-building | Becomes toy-like or childish if heavy |
| **Broadcast esports-inspired** | Practical gaming HUD integration plus one distinctive branded webcam treatment | Good for Fortnite, Minecraft and Elden Ring | Might imply Q59 A chosen if treated as the permanent branding objective |
| **Reactive personality layer** | Minimal branding most of the time, with optional dark-red TTS/vote/alert states | Reflects Acorn's spontaneous channel authority | Clutter/cuteness clichés; too many moving overlays |

No variant is selected, and no exact “bear paw” or honey-themed icon is approved. Candidate motifs are **illustrative ideas**, not permanent world logos.

## 4. Individually approved Q59 modules — written behavior tests

### B — Bear-world / HoneyDweller brand
- **Must:** Recognizable family/character identity, not a preschool cartoon or generic off-the-shelf streamer theme.
- **Proposals:** subtle wordmark, motif near webcam, little branded status panel, limited use of themed icons.
- **Open:** channel handle, logo geometry, actual names displayed, secondary palette, font, whether the entire fictional platform permits custom branding.

### C — Dark-red accent
- **Must:** dark red used as an **accent** and conceptually linked to Acorn's already established favorite color. Do not convert his fur, eye color or the display into a red monochrome.
- **Proposals:** a selection state, a webcam-frame notch, current challenge progress or highlighted category labels.
- **Open:** hex code, contrast targets, use on donor alerts, light/dark UI surface, accessibility contrast implementation.

### D — Readable live chat and moderation
- **Must:** plausible username/message distinction, moderation signals and clear hierarchy. Chat panels may grow/shrink under Q58 F.
- **Proposals:** readable scrolling columns, small badges, text spacing, clipped message rows rather than walls of text.
- **Open:** chat-panel position, names/avatars, actual platform message system, whether Acorn sees an internal dashboard not shown to viewers.

### E — TTS / reading status
- **Must:** clear indication of when a message is being read aloud to help Acorn follow live conversation.
- **Proposals:** lightweight speaker glyph / active-message highlight, queue count, speaking bar.
- **Open:** queue behavior, duration, audio voice, player controls, source filters, whether per-user TTS is enabled.

### F — Donations / contextual alerts
- **Must:** do not occupy prime screen space constantly; appear only when relevant.
- **Proposals:** fade-in compact alert anchored outside game-HUD critical zones, optional small alert queue.
- **Open:** currency, amount, legal/fictional mechanics, alert priority/rate, sound, retention time.

### G — Interactive challenges
- **Must:** polls, vote status, optional challenge progress and audience choice clearly distinct from compulsory instructions; **Acorn can refuse/cancel** even if viewers paid or voted.
- **Proposals:** temporary compact poll strip, progress chip, clear canceled state.
- **Open:** actual challenges, on-screen voting format, duration, chat interaction data, channel moderation.

### H — Webcam frame
- **Must:** a recognizable and scalable border around Acorn's **middle-left webcam** where the webcam is a distinct inset.
- **Proposals:** thin dark-red trim, branded corner element, flexible aspect crop.
- **Open:** corner radius, thickness, shadows, animations, shape, logo or framing material.

## 5. Integration with approved Q58 modes

| Q58 mode | Intended use of Q59 modules | Conflict to check |
|---|---|---|
| **A Gameplay-first** | Smaller middle-left branded webcam, compact chat/TTS, optional transient alerts | Real-game HUD or inventory obscured by window |
| **B Reaction-first** | Larger Acorn camera, readable media panel, secondary chat/TTS | Reaction media too small or age-inappropriate |
| **C Just Chatting** | Main Acorn camera, legible chat and TTS | Duplicating full-screen and inset cameras |
| **D Family/friends** | Multiple variable guest panels, one primary Acorn branded camera | Accidentally assigning guest designs or identical branding |
| **E Outdoors** | Mostly full-screen camera, reduced overlays | Chat/votes competing with Acorn's physical activity |
| **F Resizing** | Same brand elements retain proportions across camera scale changes | Frame looks distorted or shifts away from middle-left without reason |
| **G Opt-in challenges** | Vote/widget visible while authorized, then disappears | Audience control overriding Acorn |
| **H Minimal UI** | Suppress inactive panels and decorations | “More branding” leading to impossible visual noise |

Each mode is an optional visual capability, not a scheduled segment. The title list for games remains the Q57 candidate comparison pool, with Fortnite canonically played.

## 6. Character model and reference continuity (cross-cutting)

- Acorn is a **six-month male brown bear**, plump/fluffy with enormous paws, wide tail, big slightly drooping ears and rounded cheeks.
- Back and main body dark brown; belly nearly white; cinnamon guard hairs and muzzle/cheek/tail accents; **hazel eyes**.
- **His anatomical RIGHT ear** alone deep reddish-cinnamon; **front-left paw** alone has a lighter sock.
- A webcam frame cannot hide the face entirely or silently mirror anatomical markings. A straight-on **unmirrored** image shows marked ear on viewer-left and marked forepaw on viewer-right.
- Acorn's voice is baby-high-pitched by default; chat TTS is a UI accessibility/reading aid, not a new adult voice.
- Gaming controls must be designed for a quadrupedal cub (exact hardware undecided).

## 7. Paper acceptance checklist — no actual visual tested

- **Q59-A-UNSELECTED:** Do not claim option A specifically approved.
- **Q59-B/C:** Acorn-branded identity and dark-red accent, no childish/cartoon overload.
- **Q59-D/E:** Readable user/chat hierarchy and TTS status, not invented technical backend.
- **Q59-F:** Alerts contextual, with relevant appearance and disappearance.
- **Q59-G:** Challenge widgets opt-in; Acorn can reject/cancel.
- **Q59-H:** Custom frame scales; ordinary middle-left anchor maintained.
- **Q58:** All eight modes remain compatible; no fixed show format or always-on noisy UI.
- **Q54:** Character anatomy/fidelity gate highest priority.
- **Q57:** Game and non-game reference categories remain design subjects; not fake past broadcasts or permission to show explicit adult sexual content to a toddler-equivalent cub.
- **Production phase:** Absolutely no graphics/screenshots/music/video/game code have been generated for this decision.

## 8. Q60 completed; next owner decision — Q61 proposal only

**Q60 COMPLETED:** B+E+F+G approved. The normal compact chat panel is **directly beneath the middle-left webcam**, expandable/collapsible and adaptable by stream format; currently spoken TTS status is **beside** Acorn's camera. See the Q60 direct decision. **Q61 proposed:** select visible TTS/current-message treatment, queue and chat density/moderation presentation, with **Other/custom**. Exact webcam frame style, palette shades and platform remain open; do not assign a final branded UI without signoff.
