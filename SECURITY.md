# Security Policy

## Supported Security Posture

This repository contains public WordPress plugin package files and release metadata for RavenHawk Services Showcase.

## Secrets Policy

Do not commit:

- API keys
- OAuth credentials
- WordPress credentials
- `.env` files
- SQL/database exports
- `wp-config.php`
- private keys
- debug logs
- production backups

The gitignore patterns help reduce accidental commits but are not a substitute for reviewing changes before pushing.

## WordPress Update Security

Recommended update chain:

```text
versioned package
→ release ZIP
→ GitHub Release asset
→ update manifest
→ WordPress Admin update
```

## Reporting Issues

Report security issues privately to the repository owner rather than opening public issues containing secrets or exploit details.
