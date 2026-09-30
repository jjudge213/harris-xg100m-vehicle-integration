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
| `xg100m-speaker-integration-2025-03-30-01.png` | Low | Final visual check; fabrication/workbench image. |
| `xg100m-speaker-integration-2025-03-30-02.png` | Low | Final visual check; installed close-up. |
| `xg100m-speaker-integration-2025-03-30-03.png` | Low-Medium | Final visual check; wider vehicle interior view. |

## Public Rewrite Tasks

- Replace Instagram captions with original project prose.
- Add a sanitized block diagram of the intended vehicle communications layout.
- Add a short installation checklist covering mount, power, audio, routing, and verification.
- Keep all sensitive radio programming and COMSEC material out of the repository.
