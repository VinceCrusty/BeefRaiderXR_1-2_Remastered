# BeefRaiderXR 1 + 2 Remastered: Features and Installation

This Windows PCVR build supports Tomb Raider I and II, with optional Remaster graphics and motion-controlled VR interactions.

This is a test build, so some graphics issues and gameplay bugs are still possible. HD features require the corresponding Remaster assets; the EXE does not include the game files.

## Installation

1. Open your BeefRaiderXR installation folder
2. Copy the new `BeefRaiderXR.exe` into that same folder, alongside the `DATA` folder and the other game-content folders. Do not put it inside `DATA`, `ITEM` or `TEX`
3. If you have separate TR1 and TR2 installations, replace the EXE in both. The same executable supports both games; the surrounding game files determine which game starts
4. Start the new EXE using your existing PCVR/OpenXR setup

Keep your existing content folders and runtime files. For HD graphics, retain the complete Remaster content, including `ITEM`, `TEX`, `PIX`, `FMV`, `TRACKS` and `SFX`. Some TR2 assets are shared with TR1: if your installation uses neighbouring `1` and `2` folders, keep that layout intact.

Existing settings and saves are preserved. The bundled defaults apply when no valid settings file is present. This EXE update is not a complete first-time installation package.

## Graphics and presentation

- **Visual Style: Classic / HD / HD + Remaster Look:** Original graphics, HD textures on classic level geometry, or HD textures with supported Remaster level geometry
- **Remaster Object Models: Original / Remaster:** Switch supported enemies, objects, pickups, weapons and inventory/menu models to their HD versions
- **HD Lara: Off / On:** Use Lara's supported Remaster outfits, hair, hands and weapon geometry with the existing animation and VR system
- **Remaster Lighting: Off / On:** Use imported Remaster lighting data for supported scenes
- **Atmosphere: Off / Low / Medium / High:** Adjust the atmospheric fog effect
- **Godrays: Off / Low / Medium / High:** Enable and adjust light shafts in supported TR1/TR2 locations
- **Snow: Off / On:** Enable snowfall in supported Remaster weather areas
- **Image Contrast: Normal / Mild / Strong:** Adjust the image's contrast treatment
- **Water: Low / Medium / HD / HD + Foam:** Select water rendering quality, with enhanced surface effects and optional foam
- **Reflective puddles:** Supported Remaster floor materials receive masked reflections; not every floor is reflective
- **HD effects:** Supported flame, waterfall and other effects use their imported assets. Breakable HD windows also use HD fragments
- **Shadows: Low / Medium / High:** Adjust shadow quality
- **Draw Detailed Sky: Off / On:** Toggle detailed sky rendering
- **Draw Distance: Classic to Maximum:** Adjust how far the level is rendered
- **Anti-Aliasing: Off / 2x / 4x MSAA:** Reduce jagged edges; higher values cost performance
- **World Texture Smoothing: Normal / Mild / Strong:** Reduce distant texture shimmer, with some loss of sharpness
- **Title Screen: Original / BeefRaiderXR:** Choose the original title artwork or the embedded custom artwork
- **Loading Screens: Off / On:** Toggle loading-screen presentation
- **HD movies with audio:** Play supported OGV movies from `FMV/HD`, including available language audio
- **Mesh-overlap repairs:** Reduce duplicate classic/HD geometry and texture flicker. This is not a guarantee that every remaining overlap is fixed

Graphics settings take effect automatically. Some changes may take a few seconds.

## Immersive VR mechanics

Use first-person VR with weapons put away for hand interactions. Enable **Immersive VR Interactions**; wall climbing and block pull-ups also have their own settings.

- **Tracked aiming:** Aim weapons with your controllers, including independent aiming for dual weapons when auto-aim is disabled
- **Physical levers:** Reach for a supported lever, hold the grip button and move your hand to operate it
- **Physical buttons:** Reach forward and push supported wall buttons with your hand
- **Physical keys:** Approach a compatible keyhole with the correct key in your inventory. The key appears in your dominant hand; insert it and turn your wrist. Puzzle sockets still use their existing interaction system
- **Gesture pickups:** Point at a nearby supported item, hold the trigger and move your hand to pull it into your hand and collect it. Works in supported standing and underwater situations
- **Physical swimming:** Hold both triggers and make swimming strokes to move forward; both grips select backward movement. A single trigger or grip selects movement toward that hand's side. Stick swimming remains available
- **Low-block pull-ups:** Place either hand on a reachable ledge, then lower it by approximately 15 cm to initiate the short climb
- **High-ledge catches and pull-ups:** Place your hands on the ledge while jumping or falling. Your hands anchor to the edge; downward arm movement raises Lara and completes the climb. Withdrawing your hands releases the hold
- **Assisted high-ledge jump:** Face a reachable high ledge and press forward plus a trigger to jump toward it, then place your hands on the edge and pull yourself up
- **Short-tap jump:** In immersive block-climbing mode, briefly tap Jump for roughly 75% of normal jump height; hold it for the full jump
- **Immersive wall climbing:** Hold triggers to grip a supported TR2 climbing surface and use hand movement to climb vertically or sideways. Release and re-grip to reposition your hands
- **TR2 wall jump:** Press Jump while attached to a climbable wall to jump away, including during immersive climbing
- **Contact feedback:** Supported interactions use hand anchoring, highlights and controller vibration to indicate contact or activation

Hand interactions respect collision checks. You cannot climb every surface or move through walls. Classic movement, jumping, climbing, shimmying, block pushing/pulling and supported vehicle gameplay remain available.

## View and comfort options

- **Camera Mode: Modern / Classic-ish:** Choose VR-adapted movement or classic-style tank controls
- **POV Mode:** Restrict play to first person, allow first/third-person switching, or use third-person views
- **Toy Mode:** Add the miniature, diorama-style view to the available perspectives
- **Auto 3rd Person:** Automatically switch perspective for supported interactions and cutscenes
- **Action Cameras:** Allow or suppress supported scripted camera changes
- **Fixed Camera Mode:** Enable the fixed-camera presentation mode
- **Turn Mode:** Choose snap turning, snap in first person with smooth turning in third person, or slow/fast smooth turning
- **Handedness:** Select the dominant hand
- **Swim Inverted Stick:** Reverse the swimming stick's vertical control
- **1st Person IK Body:** Show or hide the controller-driven first-person body
- **Lara's Braid:** Toggle the braid rendering
- **VR Climbing: Classic / Immersive:** Choose button-driven or hand-driven wall climbing
- **VR Block Pull-up: Classic / Immersive:** Choose the existing block-climbing controls or physical ledge catches and pull-ups

## Gameplay, audio and utility options

- **Difficulty: Easy / Normal / Hard:** Adjust combat difficulty
- **Auto-Aim: Off / On:** Choose manual VR aiming or assisted aiming
- **Music / Sound:** Adjust their volumes separately
- **Reverberation:** Toggle the room reverb effect
- **Subtitles / Language:** Select subtitles and the available language content; audio availability depends on your files
- **Controls help:** Open the built-in text help or controller diagram, where available
- **Invulnerable:** Enable the damage-protection option
- **Noclip / Fly: Off / Normal / Fast:** Explore freely using the sticks, with room-visibility restrictions relaxed. Press the right trigger to request moving Lara to a valid position at the inspection camera, then disable Fly to resume normal play. Fly always starts disabled; viewing levels from outside can expose normally hidden geometry
- **Cheat: All Weapons and Items:** Add supported weapons/ammunition, health packs, keys and puzzle items for testing. Not available in the title, cutscene or home levels
- **Cheat: Unlock All Levels:** Unlock level selection for the current game and immediately save the unlock. Fresh installations do not start with every level unlocked
- **Saving:** Use the Passport for saving/loading, including the quick/crystal-save entry and ten manual slots per game
- **Enemy navigation fixes:** Ground enemies in TR2 handle narrow passages and corners more reliably

## Settings and saves

Files are stored in `%APPDATA%\BeefRaiderXR\`:

- `settings_vr`: Settings shared by both games
- `savegame.dat`: Shared save container with separate TR1/TR2 save slots and unlock state

Replacing the EXE keeps these files intact. The hand/arm calibration menu is gone, but your existing calibration remains.
