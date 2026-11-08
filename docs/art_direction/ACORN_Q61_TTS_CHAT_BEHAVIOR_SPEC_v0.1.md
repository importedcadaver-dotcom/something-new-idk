# Acorn Q61 — TTS and Chat Behavior Specification v0.1

**Status:** Text-only design synthesis of [Q61 approved choices A/B/D/E/F/G/H](../decisions/Q61_CHAT_TTS_A_B_D_E_F_G_H_APPROVED.md). **C (visible queue) not approved.**  
**No actual screenshots, images, scenes, gameplay, sound, software or code created.**

## Locked spatial layout from Q58–61

- Acorn's framed webcam normally **MIDDLE-LEFT** (Q58 and Q59), its **compact chat panel DIRECTLY BELOW** (Q60 B).
- The **TTS speaking-status indicator BESIDE his webcam** (Q60 G). Q61 B adds a **small speaker-name label BESIDE the webcam**; it may be visually associated with the status indicator, but the precise grouping and side are OPEN.
- Chat may rearrange for modes (Q60 E) and expand/collapse (Q60 F). Q61 G additionally specifies **fewer visible messages compact; more conversation history expanded**.
- Q59 branding remains distinctive Acorn/HoneyDweller with dark-red **accent**, readable user/message hierarchy and restrained contextual overlays; no exact theme, font, name, border or exact pixel location selected.

## Seven selected behaviors — requirements with uncertainties

| Q61 | Required written behavior | OPEN choices / negative constraints |
|---|---|---|
| **A active spoken-message highlight** | While TTS reads a message, its chat row is visually distinguished | Style, color, fade and treatment when panel is collapsed |
| **B speaker label** | Show whose message is being spoken **beside webcam** | Side of camera, username formatting, whether same as TTS indicator |
| **D Acorn TTS control** | Acorn can **pause, skip one message, resume** | Hardware/input, buffering details, what happens to skipped message text |
| **E spam and content moderation** | Mods can filter spam, repeats and inappropriate content | Exact filters, named mods, escalation, whether blocked messages are deleted or held |
| **F approved-sender priority** | Mods, family and selected senders may receive **special treatment** | Whether earlier readout or different visuals/audio, ranking/cost, priority override policy |
| **G chat density** | Compact fewer visible messages; expanded more history | Counts, scrolling, history retention and visibility to viewers vs Acorn |
| **H idle display restraint** | When nobody is being read, TTS status becomes unobtrusive | Dimmed/hidden/idle icon, lingering speaker label |

**Q61 C specifically unselected:** No **VISIBLE TTS queue** selected. **Do not display a queued-message counter/list** as if Q61 approved it; unread messages may exist in some future design, but that is not current on-screen canon.

## Interaction scenarios for future paper QA — NOT fictional scenes

1. **Normal single message:** one row highlighted, sender label beside Acorn's webcam, TTS state active; no visible queue.
2. **Idle:** no active highlight and idle indicator reduced; if a label persists, its details need later approval.
3. **Acorn pauses:** speech stops or pauses according to future implementation semantics; he retains control and can resume.
4. **Acorn skips:** current selected readout is skipped; whether chat history retains its row remains OPEN.
5. **Moderator filters spam:** only a class of messages can be hidden/held; whether filter occurs pre-read is a proposed safety preference, not a chosen exact software mechanic.
6. **Priority sender:** special treatment allowed, but cannot overrule Acorn's explicit pause/skip/refusal. No paid priority requirement.
7. **Compact vs expanded:** text density changes without hiding the main game, Acorn webcam or essential game UI.
8. **Guest or outdoor mode:** Q60 alternative chat arrangement and Q58 primary/full-screen camera can coexist; the default inset positions are not mandatory in every mode.
9. **Mirrored webcam:** Acorn's **RIGHT** deep reddish-cinnamon ear and **FRONT LEFT** lighter sock remain his anatomical marks, regardless of flipped preview.

## Evidence-based external inspiration — no copied systems

- DougDoug's official FAQ describes a custom **donation-message TTS program**. His separately published **ChatGodApp** shows that chat participants can be represented with distinctive synthesized voices and selectable speech styles. These are **research examples**, not specifications of Acorn's own fictional platform, audio tool or paid message policies.
- Twitch first-stream/moderation guidelines recommend rules, filtering and pre-stream safety checks. Applied only as **proposals**; Acorn's bear-only internet is not automatically Twitch.
- Details and primary-source links: [DougDoug research memo](../research/DOUGDOUG_TTS_AND_FIRST_STREAM_MODERATION_Q61.md).

## Design phase decision

The owner asked whether to start drafting first chats/incidents now or first develop Acorn's emotions, private backstory, room and gaming computer. Recommended **shift to foundational character/room development first**. See [proposed pre-stream roadmap](../ROADMAP_PRE_STREAM_FOUNDATIONS_Q61_PROPOSED.md). This recommendation itself is not an approved new story event or mandatory phase change.

## Upcoming Q62 (proposed, not approved)

Interview on Acorn's **off-camera emotional regulation and character-driven behavior**, maintaining Q45's selected trait spectrum and Q44's six-month developmental limit. Provide multiple consequential options and **Other/custom**. Do not invent specific memories, backstory events or scene dialogue. The exact first chatters and original moderation incidents remain intentionally unassigned.
