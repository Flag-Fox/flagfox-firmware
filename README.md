# FlagFox firmware releases

Signed firmware for FlagFox base stations and sensors, and `manifest.json`
describing the current release. The FlagFox iOS app reads this repo (no login)
to offer firmware updates. Devices only install images signed with the FlagFox
key, so these files are safe to publish.

| File | Device |
|---|---|
| `manifest.json` | current versions, build IDs, sizes, SHA-256 |
| `flagwatch_base_devkit.bin` | base (ESP32-S3) |
| `flagwatch_rev1.bin` | Rev1 sensor (ESP32-C3) |

Raw URL: `https://raw.githubusercontent.com/Flag-Fox/flagfox-firmware/main/<file>`
