# Shadow Rounds

A solo grappling trainer for staying in shape without a partner. Voice callouts tell you what to do, and the phone does the timing. Two modes:

- **Conditioning:** high-intensity wrestling intervals. Stay in stance, hit randomly called moves (sprawl, double leg, single leg, snap-down, down block, plus cardio bursts like tuck jumps and spin drills), recover, repeat.
- **Flow:** calm, continuous movement practice. Moves chain by position (standing, seated, on your back, all fours), so each one starts where the last ended.

A passion project built for fun, not for profit. Styled in a Swiss / International Typographic manner: Helvetica, a strict grid and a very large timer.

## Conditioning

- **Stance is the default.** Between calls you circle, hand fight and keep your feet moving.
- **Hit the call.** A move is announced by voice and flashes on screen, then the screen returns to "In stance".
- **Presets:** Match Rounds (3 x 2:00), Shot Sprints (10 x 0:30), Long Grind (3 x 5:00), plus a custom timing builder.
- **Pace slider:** after picking a preset, choose how often moves are called, from Chill to Scramble.
- **Camera scoring (beta, optional):** prop your phone 2–3 m away and the front camera scores how quickly and how hard you move after each call, with a combo multiplier and an end-of-session score, grade and personal best. It measures reaction speed and effort, not technique. Video is analysed on the device and never recorded or sent anywhere. Needs a hosted (HTTPS) page to work.

## Flow

- **Moves and poses alternate.** Every BJJ movement is followed by a held stretch or yoga pose that starts where you are, so there is no dead time.
- **Moves:** shrimp, bridge, invert, backward and forward shoulder rolls, sit-out, technical stand-up and sprawl, linked by "Lie back" and "Back to your feet" connector cues.
- **Poses:** standing forward fold, deep squat, low lunge, downward dog, child's pose, cat-cow, thread the needle, cobra, pigeon, butterfly, seated forward fold, seated twist, 90/90 hip switch, happy baby and supine twist. One-sided poses call "switch sides" halfway through the hold.
- **Always shows what's next,** with a live hold countdown during poses.
- **Length** (5 to 20 min) and **tempo** (Relaxed to Brisk) sliders. Tempo sets move spacing and pose hold length (about 45 s relaxed, 20 s brisk). No countdown beeps, just a soft chime at the start and end.
- Move order favors the least-used move and takes the shortest chain of positions to reach it, so everything stays in rotation.

Sessions are logged on the device only, with a simple weekly streak.

## Run it

It is a single self-contained file. Open `shadow-rounds.html` in a browser, or add it to your phone's home screen. Turn the ringer on so voice callouts are audible. Voice uses the browser's built-in speech synthesis, so quality varies by device.

## Status

Prototype. Open questions: whether browser voice is good enough, whether audio cues play over music on iOS, and how Flow tempo feels in practice. The app name is still being decided.
