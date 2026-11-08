# Acorn — Adaptive Broadcast Layout System v0.1

**Status:** Written design analysis translating **approved Q58 A–H and middle-left webcam** into comparable interface briefs. UI dimensions, placements beyond webcam anchor, effects and aesthetics below are **PROPOSALS** until the user chooses them.  
**Source:** [Q58 approved decision](../decisions/Q58_ALL_STREAM_LAYOUT_MODES_AND_MIDDLE_LEFT_WEBCAM_APPROVED.md) · [Q57 game and reaction comparison](ACORN_Q57_CONTENT_LAYOUT_COMPARISON_PACKET_v0.1.md) · [Q56 eight-view blueprint](ACORN_Q56_EIGHT_VIEW_COMPARISON_BLUEPRINT_v0.1.md).  
**Restrictions:** **Documentation only.** No imagery, mockup screenshot, game prototype, character art, software implementation, coding, scenes or streaming.

## 1. Single guiding arrangement: Acorn webcam at MIDDLE-LEFT

The user's exact Q58 custom instruction, **“webcam on middle left”**, is binding as the **normal** on-screen placement where the stream uses a webcam window. Think of the viewport as broad zones—not chosen pixel measurements:

- **Left-middle:** Acorn's webcam panel, when a discrete webcam is used; smaller in **gameplay-first**, larger in **reaction-first**.
- **Main activity area:** the game, media/reaction content or Acorn's full camera, according to selected layout mode.
- **Chat/TTS/alerts:** remain legible, but their **exact position is OPEN**, not automatically “right side.”
- **Guest positions:** flexible as an approved mode capability; no specific grid or number of live cameras chosen.
- **Full-screen modes:** in Just Chatting and outdoor activities, the primary camera can naturally replace the small panel, without violating the middle-left default **for modes with a distinct webcam panel**.

**Not approved:** A permanently fixed-size webcam, automatically moving the webcam around during gameplay, exact middle-left coordinates, precise percentages/ratios, a top-right/bottom-left default, or automatic scene switches.

**Illustrative nonbinding area description:** "For a gaming screen, treat the central game image as dominant. Acorn's identifiable webcam occupies the left-middle margin/overlay without covering critical HUD; chat must have a readable placement yet to be chosen." This is *not* a rendered composition or finalized layout.

## 2. Eight approved layouts and their design tests

| Q58 mode | Explicit user approval | Proposed text-only composition comparison | Main acceptance question |
|---|---|---|---|
| **A Game-first** | Real game dominant; smaller Acorn webcam; unobtrusive chat | Contrast a fast Fortnite fight against an inventory-heavy Minecraft/Hypixel SkyBlock screen, using the **middle-left** camera anchor | Does webcam overlap Fortnite HUD/controls or Minecraft inventory elements? |
| **B Reaction-first** | Larger Acorn webcam next to videos, fanfiction, internet commentary or other approved material | Keep Acorn prominent left-middle with a clearly distinguishable adjacent media/text area and readable chat | Can he react without the clip/text being hidden or implying adult comprehension? |
| **C Just Chatting** | Acorn/surroundings primary; legible chat and TTS indicators | Acorn camera expands to primary frame with chat legible; inset webcam unnecessary | Is Acorn clearly the subject and is chat/TTS readable? |
| **D Family/friends split** | Flexible guest cameras | Suggest a main Acorn camera plus one or more smaller independent guest panels only when guests selected | Is each participant visually distinct? Are non-approved family character designs left provisional? |
| **E Outdoor/activity** | Cleaner, mostly full-screen camera | One prominent cub-level camera and minimal unobtrusive overlay | Does the full physical bear remain recognizable without imagined estate locations? |
| **F Resizable webcam/chat** | Size/placement can adapt; Acorn retains control | Compare the same example with compact webcam vs larger webcam as two written hypotheticals | Does the resizing preserve middle-left as ordinary anchor, while allowing approved exceptions? |
| **G Interactive challenge overlay** | Opt-in chat votes/challenges and temporary audience mechanics | An optional brief vote/challenge display that can disappear when challenge ends | Can Acorn refuse/stop; is participation optional; does an overlay cover game controls? |
| **H Minimal polish** | Restrained alerts; real typography; low clutter | Audit the number of overlay components per mode, remove meaningless elements | Is the main content legible, with believable interface labels and no AI-gibberish? |

**Scope distinction:** These are descriptions of what to *evaluate* someday, not scheduled scenes, mandated stream frequency or a new app/software specification.

## 3. Camera and webcam sizing behavior — candidate implementation principles (NOT approved mechanics)

**Current canon:** default anchor middle-left; smaller gameplay window; larger reaction window; full-screen/main camera where appropriate; resizability; Acorn ordinary control.

**Ideas needing approval:** whether the window has a draggable handle, follows preset layouts, resizes manually or automatically; whether chat auto-collapses; padding, safe zones, opacity, rounded borders, camera zoom, reactions framing and transition animations.

A potential QA approach is to use **content-critical zones** rather than hard-coded placement: protect Fortnite action/health HUD, Minecraft inventory slots, Pokémon move-selection UI, Zelda menus and game dialogue subtitles. Middle-left must remain an actual recognizable intention; if a game overlays vital content there, **document the conflict** rather than silently relocating Acorn to a random standard corner. A later user preference can resolve exact exceptions.

## 4. Q57 selected game and non-game content category fit

### Games (all ten Q57 selection groups; Fortnite canon game)
- **Fortnite:** active action plus viewer chat, compact left-middle webcam, no player HUD obstruction.
- **Minecraft/Hypixel SkyBlock:** inventory/progression overlays may conflict with left-middle webcam; preserve readable inventory text.
- **Cyberpunk 2077:** dialogue/subtitles/HUD have higher information density; webcam must not obscure them.
- **GTA V:** driving/minimap/world visibility; no assumption mature-rated content is seen by Acorn.
- **Pokémon Violet:** battle menus and readable moves; warm expression camera next to main capture.
- **ARK: Survival Ascended:** survival/crafting and dinosaur combat need screen space.
- **Elden Ring:** action telegraphs, health/boss bar; reaction cam shouldn't cover key movement.
- **Animal Crossing: New Horizons:** text dialogues and item grids; chatting can be more visible when no game-action urgency.
- **Zelda BOTW/TOTK:** open-world HUD and puzzle framing; avoid generic fantasy game substitutes.
- **Stardew Valley:** tile world and menus; maintain legible crops and inventory.

Each is **only a proposed screen-comparison subject** except Fortnite, which is already Acorn-played canon. All Q57 selections have equal inclusion status; no relative ranking was specified.

### Reaction and non-game references
- **Fanfiction:** reading/commentary could use reaction-first or Just Chatting, depending on yet-unapproved fandom and text; do not reproduce unprovided creative works.
- **Funny/edgy internet material:** reaction-first or chatting; exact references and content maturity are open.
- **Orange-and-black-logo website:** unresolved brand/site identity; **never silently choose a specific real site or depict explicit sexual content involving the toddler-equivalent cub**.
- **Rapper music videos:** conceptually compatible with reaction-first; no particular musician/video/music rights or copyrighted clip reproduction authorized.
- **Toys, family and outdoor broadcasts:** Q47 previously approved as possible spontaneous content; available Q58 modes make them visually accommodatable.

## 5. Invariant character and world continuity

Acorn is a **six-month male brown bear** with realistic largely quadrupedal anatomy, exceptionally plump face/body, giant bear paws (larger than Millie's), very large somewhat drooping ears, very wide short bear tail, thick fur, **hazel eyes**, dark brown dominant back/body, nearly all-white belly, cinnamon highlights in guard hairs/cheeks or muzzle/tail, **ONE deep red-cinnamon RIGHT ear**, and **ONE lighter FRONT-LEFT paw sock**. Do not introduce human hands, an adult voice or normal-sized paws to fit a gaming desk, or mirror his markings because of a webcam preview.

Acorn uses fast-chat **TTS**, but UI design does not grant a new full adult reading/comprehension level. Q47 gives him personal agency over stream content/challenges; Q58 modes cannot revoke it. Family size-comparison design H from Q56 must not assume Millie's exact coat and eye colors or adult relative's precise appearance.

The setting's bear-only technology/internet exists in prior canon; a specific fictional platform handle/logo/channel layout or legal/sexual-content rules are **not** selected here.

## 6. Future QA checks (design acceptance plan; none executed)

| Check | Pass concept | Failure concept |
|---|---|---|
| Q58-01 All eight modes | A–H represented in written specification as optional capabilities | Treating any selected mode as unavailable |
| Q58-02 Webcam placement | A distinct webcam is **normally middle-left** | Auto-default to bottom-right/upper-left without decision |
| Q58-03 Resizing | Game-first smaller; reaction-first larger; activity scenes can become mostly full-screen | A rigid permanent webcam window negates F |
| Q58-04 Overlap awareness | Game UI warnings documented when left-middle intersects inventory/controls | Moving webcam without approval while claiming approved location unchanged |
| Q58-05 Q47 autonomy | Challenges opt-in; format not fixed | Audience forcibly controls Acorn or mandatory schedule |
| Q58-06 Split screen | Independent approved guests may join | Every screenshot automatically includes all family members |
| Q58-07 Character fidelity | RIGHT cinnamon ear and FRONT LEFT light sock remain anatomically fixed | Mirrored markings or changed fur/eyes |
| Q58-08 Real references | Selected games and Q57 reaction categories appropriately acknowledged | Random fake games, fabricated copyrighted music/videoclips |
| Q58-09 Minimal polish | Legible chat/TTS/alerts with low clutter | Nonsense text or ad-like UI filling space |
| Q58-10 Non-explicit boundaries | Website reference remains unidentified and not explicit on screen | Sexual content depicted with Acorn |
| Q58-11 Documentation phase | Proposals clearly marked; no actual media/software reported | Claiming created renders, playable broadcasts or tested UI |

**Assessment state: all **NOT TESTED against actual screenshots**, as none were authorized or created. Only textual consistency can be checked now.**

## 7. Proposed Q59 next design decision

**Q59:** Choose **broadcast branding and overlay elements** that can work with the approved middle-left webcam and eight modes. Possible independent options: minimalist esports aesthetics; bear-world-themed but restrained overlay; dark-red accents (Acorn's favorite color, not automatically adopted as UI color); visible chat/TTS; selective alerts; vote widgets; stream-status strip; or combined modular UI. Include **Other/custom**.

Caution: If the user chooses all module capabilities, that doesn't mean all overlays appear simultaneously or crowd the screen; H requires minimal, polished presentation. Don't assign a platform name, a final font or real Twitch branding without approval.

**No image generation, gameplay, scenes or coding.**
