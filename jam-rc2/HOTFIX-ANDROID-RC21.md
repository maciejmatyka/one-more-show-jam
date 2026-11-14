# Android startup update — v0.21.1 RC2.1

14 November 2026. Windows remains the unchanged v0.21.0 RC2 build.

The author reported that the WeLoveIndies startup film played brief audio without visible video on the phone. Android now selects a complete 1280×720 H.264 constrained baseline level 3.1 rendition instead of the 3840×2160 Main level 5.1 film. All 188 frames, 7.52 seconds of picture and the original audio are retained. Decoded audio hashes match exactly. The original movie, previous APK and previous release evidence remain archived.

The Vulkan emulator visibly shows the heart animation, full provider logo, fade-out and opening letter. All 43 packaged show-flow checks pass. APK signing and 16 KB alignment pass; the existing signing identity and package name are retained for an update without uninstalling. Game C++, physics, scoring and the project-local movie plugin are unchanged.

Limitations: the original 4K film also played on the emulator, so this is a codec compatibility correction, not a phone-log-confirmed root cause. The new APK still needs the author's physical Redmi 13 check. The attempted OpenGL test could not reach playback because this emulator exposes ES 3.1 while the engine requires ES 3.2. No OpenGL playback pass or new subjective audio review is claimed.

Current Android download: **TheLastShow-v0.21.1-Android-RC2.1.apk**, versionCode **2101**, **186,576,654 bytes**.

SHA-256: `43bbdaa2a5b7102d25d425f4a117aa1fe327d5104eafcfed2392ee9c2d6bf7d1`

[Download the current game](https://maq.itch.io/the-last-show). The previous Android file is hidden from the public download list and preserved privately. Final jam submission remains a human action.
