# Sanitization Checklist

Use before moving any evidence from candidate status into a public repository.

## Radio / COMSEC

- No encryption keys, key-fill files, key IDs, or keyloader screenshots.
- No proprietary codeplugs or programming files.
- No operational frequencies unless they are recreated/sanitized examples.
- No restricted military manuals or non-public COMSEC procedures.
- Crop or blur radio displays if they expose sensitive channel/frequency/system data.
- Use public/user-generated connector references only.

## Location / Network / TAK

- Remove coordinates, MGRS, home/work locations, callsigns tied to locations.
- Remove TAK package URLs, cert paths, server hostnames, internal IPs, ZeroTier IDs.
- Replace real endpoints with `example.net`, `10.0.0.0/24`, or documentation ranges.
- Recreate screenshots where redaction would leave too much sensitive context.

## Infrastructure / Software

- No tokens, passwords, API keys, SSH keys, private certs, cookies, or session files.
- No raw production config backups.
- No personal chat IDs, Telegram IDs, or live-location data.
- Run secret scanning before public commits.

## Images / Personal Data

- Review faces, addresses, plates, serial numbers, unit identifiers, and private comments.
- Prefer cropped close-ups of the technical artifact.
- Do not publish family/minor photos as portfolio evidence.
- Preserve only what supports the technical claim.

## Employer / Proprietary Work

- No employer drawings, programs, fixtures, customer data, or proprietary process sheets.
- Use personal projects, recreated examples, or sanitized retrospective writeups.

