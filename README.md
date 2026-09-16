# PubSpaceNap

Public, short-lived control mailbox for the Gesang / Guthrie / G2 automation.

## Rules

- `jobs/<job-id>.json` files are temporary machine-readable launch instructions for the private `ug-steel-bridge` service.
- Never put passwords, API keys, tokens, cookies, private URLs, personal data, or unreleased musical content in this repository.
- Jobs use a strict schema, high-entropy IDs, and expire within 30 minutes.
- The bridge accepts only the whitelisted `ug_batch` job type; this repository is not a remote shell.
- Completed/failed job files should be deleted after their result has been collected. Git history remains public, so anything committed here must be safe to disclose permanently.

The application source, secrets, detailed scrape data, and durable project records remain in their existing private systems.
