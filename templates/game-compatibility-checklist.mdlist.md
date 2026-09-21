# Game / Compatibility QA Checklist

## Build and environment
- Record build/version.
- Record OS/device and relevant hardware.
- Record controller/input method.
- Record graphics/performance settings.
- Confirm whether this is a clean install or an update.

## Smoke test
- Launch / boot.
- Main menu.
- Start new game / load save.
- Basic movement and input.
- Pause/resume.
- Save/load.
- Exit/relaunch.

## Exploratory areas
- Rapid/repeated input.
- Invalid or unexpected input.
- Menu transitions.
- Suspend/resume where supported.
- Save/reload during different states.
- Low/high graphics or performance settings.
- Controller disconnect/reconnect where supported.
- Different aspect ratios/resolutions where applicable.

## Compatibility comparison
- Compare emulator vs physical hardware when relevant.
- Compare Firefox vs Chrome for browser extensions.
- Record differences, not just failures.

## Reporting
- Clear title.
- Exact environment/build.
- Reproduction steps.
- Expected result.
- Actual result.
- Reproduction rate.
- Severity and impact.
- Screenshot/video/log when available.
- Retest the exact fix.
- Regression-check nearby features.
