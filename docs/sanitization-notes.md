# Sanitization Notes

Private draft. This repository currently contains images and notes for internal review only.

## Before Public Release

Review every image for:

- operational frequencies or channel names
- radio IDs, serials, unit IDs, or codeplug details
- encryption/key-fill references or key IDs
- private locations, addresses, license plates, or vehicle identifiers
- personal information in comments, captions, or screen reflections
- terminal output, hostnames, usernames, paths, or package sources
- proprietary Harris documentation or non-public pinout information

## Current Asset Review

| Asset | Risk | Required Action |
|---|---|---|
| `xg100m-progress-2025-04-28.png` | Medium | Inspect radio display and visible labels; crop/redact if needed. |
| `xg100m-speaker-integration-2025-03-30.png` | Low | Final visual check; likely lead image. |
| `custom-truck-tablet-radio-mount-cad-2024-08-05.png` | Medium | Inspect CAD UI for filenames, project names, or private comments. |
| `vehicle-radio-atc-monitoring-2020-12-03.png` | Medium | Redact/crop any readable frequency or channel detail. |
| `android-car-radio-ubuntu-vm-2023-08-30.png` | Medium | Inspect terminal output before public use. |
| `vehicle-tool-field-loadout-2021-04-10.png` | Low-Medium | Check for personal/private items. |
| `vehicle-troubleshooting-2020-12-05.png` | Low-Medium | Check for private vehicle identifiers and unrelated personal items. |

## Public Rewrite Tasks

- Replace Instagram captions with original project prose.
- Add a sanitized block diagram of the intended vehicle communications layout.
- Add a short installation checklist covering mount, power, audio, routing, and verification.
- Keep all sensitive radio programming and COMSEC material out of the repository.
