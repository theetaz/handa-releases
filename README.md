# handa

Downloads for **handa**, on-device dictation for English and Sinhala on macOS. Speech is turned into text on your Mac; nothing you say leaves it.

This repository holds installers and update files only. The source code is private.

## Install

- **Requires** an Apple silicon Mac (M1 or later) on macOS 14 or later.
- Download `handa.dmg` from [Releases](https://github.com/theetaz/handa-releases/releases), open it, and drag **handa** into Applications.
- On first launch handa asks for the microphone and Accessibility, and downloads its speech and clean-up models (a few GB).

## Test builds

Test builds (pre-releases marked `-test`) aren't notarized by Apple yet, so macOS blocks them the first time:

1. Open handa. When macOS says it can't verify the developer, click **Done**.
2. Open System Settings → Privacy & Security, scroll to "handa was blocked…", click **Open Anyway** and enter your Mac's password.

Test builds don't update themselves; install the next one the same way.
