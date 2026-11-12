# 🌌 void-cyber-infiltration

🕳️ **VOID CYBER INFILTRATION**

A cyber-themed twist on the Google Chrome Dino game. 🦖⚡

🌑 Enter the VOID. 🖥️

VOID // Cyber Infiltration
NEURAL BREACH PROTOCOL · Endless Runner

VOID is a standalone cyberpunk endless-runner game. Evade firewall
barriers and sentry drones, collect data shards, deploy three tactical
abilities, and fight the Archon Core as the security waves intensify.
Play
1. Download VOID-Cyber-Infiltration.html.
2. Open the HTML file in a modern desktop or mobile browser.
3. Select Initiate Run.
4. Audio begins after the first user interaction, in keeping with
   browser autoplay restrictions.
The game runs locally in the browser. It does not require a server,
installation, external scripts, external stylesheets, or downloaded
assets.
Controls
  Action                   Keyboard               Mobile
  Jump                     Space, ↑, or W   JUMP
Slide                    Hold ↓ or S        Hold SLIDE
Fire pulse at the boss   Hold X or J        Hold PULSE
EMP Blast                1                    EMP
Phase Shift              2                    PHASE
Data Magnet              3                    MAGNET
Pause / resume           P or Esc           Pause button

The on-screen Controls panel also displays the input map. On mobile,
use the touch-control buttons below the game canvas.
Gameplay
- Run and evade: jump over firewall barriers and slide beneath
  sentry drones.
- Collect data: data shards add to your run's shard count and
  score.
- Survive: the run ends when your integrity is depleted.
- Progress: the wave advances over time. The game increases
  movement speed and obstacle pressure as the run continues.
- Fight the boss: an Archon Core appears every fifth wave. Hold
  the pulse-fire control to launch shots and reduce its health.
  Defeating it awards bonus score and data shards.
- Build a record: your best score is saved locally in the browser.
Bonus abilities
  Ability               Effect                                    Cooldown
  EMP Blast         Clears nearby                           10 seconds
firewall obstacles
and awards score for
obstacles removed.    

  Phase Shift       Grants temporary                        13 seconds
collision immunity.   
Data Magnet       Attracts nearby data                    12 seconds
shards toward the
player.
Abilities can be activated with their keyboard shortcuts, the sidebar
buttons, or the mobile touch controls. The HUD displays each ability's
cooldown.
Adaptive generative soundtrack
The soundtrack is synthesized in real time with the browser's Web
Audio API. It uses no audio files or third-party audio libraries.
Four harmonic acts
  Act   Harmonic palette      Scale pitches (MIDI note numbers)
  I     A minor               57, 59, 60, 62, 64, 65, 67
II    D Phrygian            50, 51, 53, 55, 57, 58, 60
III   E minor with flat 2   52, 53, 55, 57, 59, 60, 62
IV    B Locrian             47, 48, 50, 52, 53, 55, 57

The progression changes as waves advance. Chord voicings use minor,
major, and diminished triads appropriate to the supplied harmonic
design.
Five adaptive mix layers
- Ambient --- sustained harmonic atmosphere and low foundation.
- Tension --- unsettled tones that build anticipation around
  nearby threats.
- Combat --- rhythmic pulses and bass energy during close danger.
- Critical --- sharper, urgent tones when integrity is low or the
  player is in a critical state.
- Boss --- heavier low tones and upper-register motifs during
  Archon Core encounters.
The game adjusts the independent layer levels in response to
exploration, nearby obstacles, critical health, boss encounters, and
victory or defeat. The sidebar's Adaptive Mix / Live meters show the
current target mix.
Audio controls and compatibility
- Audio is initialized following a user gesture, rather than
  automatically on page load.
- Use Sound On / Sound Off to mute or unmute the master output.
- Pause suspends the music scheduler and audio context where
  supported.
- Audio nodes and scheduled music activity are cleaned up when the
  page is closed or navigated away from.
- If Web Audio API is unavailable or blocked by the browser, gameplay
  remains playable without sound.
Score and saved data
The HUD shows the current score, high score, wave, integrity, and
collected data shards. The high score is stored using browser
localStorage under the key:
voidCyberInfiltration.highScore.v2
This means the record is associated with the current browser profile and
local origin. Clearing browser site data or using private browsing may
remove or prevent persistence. The game does not upload scores to a
server.
Technical details
- Single self-contained HTML document.
- Inline CSS for the responsive interface.
- Inline JavaScript for gameplay, rendering, input, and audio.
- HTML Canvas rendering.
- Web Audio API synthesis and adaptive mixing.
- requestAnimationFrame game loop.
- localStorage high-score persistence.
- Keyboard, pointer/touch, pause, mute, and page-lifecycle handling.
- No external runtime dependencies.
Browser support
Use a recent version of a browser with HTML Canvas, JavaScript, and Web
Audio API support. Chromium-based browsers, Firefox, and Safari
generally provide these APIs. Browser audio policies require a user
interaction before sound can start.

For mobile play, use a current mobile browser and the on-screen touch
controls. Screen size and browser audio policies may affect the
experience.
Project files
The game is distributed as a single file:
VOID-Cyber-Infiltration.html
Keep this README alongside the HTML file when sharing the project.
Credits and project notes
VOID // Cyber Infiltration
NEURAL BREACH PROTOCOL · ENDLESS RUNNER

The adaptive soundtrack is procedural and generated during play. No
pre-recorded music tracks are bundled with the game.

**🌑 Enter the VOID. 🖥️**
