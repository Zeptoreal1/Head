# AltPulse

AltPulse is a new Geode mod for Geometry Dash 2.2081. It performs real alternating gameplay input from an in-level touch control or two configurable Geode keybinds. It is not a steering simulator.

## Features
- High-resolution steady-clock scheduler with separate press/release timing
- CPS, frequency, intensity, delay, duty cycle, buffer and catch-up controls
- Responsive in-level ALT control, live CPS/FPS HUD and wrap-around `5/7` preset selector
- Seven persistent preset slots
- Player 1 / Player 2 targeting and Practice-only safe mode
- Automatic release on death/pause and bounded frame-hitch catch-up
- Windows, macOS, Android 32/64 and iOS GitHub Actions builds

## Presets
Use the left/right HUD arrows to select slots 1-7. A slot loads automatically if it exists. Tap **SAVE** to overwrite the selected slot and **X** to clear it. All values persist through Geode saved data.

## Local build
1. Install Geode CLI and SDK.
2. Set `GEODE_SDK` to the SDK folder.
3. Run `geode build`.

## GitHub build
Push the extracted files to a new repository. `.github/workflows/build.yml` builds every supported target and combines the packages into one downloadable artifact.

## Important
Automatic input may be disallowed in competitive lists, events, or leaderboards. Use responsibly and disclose automated runs.
