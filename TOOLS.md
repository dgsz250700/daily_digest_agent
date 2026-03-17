# TOOLS.md

## Current Tooling Policy
This agent should operate with minimal tool access.

## Allowed Inputs
- Files placed by the user inside the workspace
- Plain text
- Markdown
- Sample newsletter files created for testing

## Disallowed / Not Enabled Yet
- Real personal email inbox access
- Telegram
- Slack
- Third-party skills
- File access outside the workspace
- Automatic delete actions

## Conditionally Allowed Later
- Read access to a controlled test inbox
- Moving clearly processed newsletter emails to a reversible folder such as `Processed`
- Leaving uncertain emails untouched unless explicitly configured

## File Conventions
Use these folders if they exist:
- `inbox_samples/` for newsletter inputs
- `digests/` for generated digest outputs
- `memory/` for daily notes

## Output Convention
When generating a digest file, prefer:
- `digests/YYYY-MM-DD-digest.md`

## Safety Convention
If a requested action would require external access or inbox modification, stop and ask for explicit confirmation.
If classification confidence is low, do not move or modify the email.