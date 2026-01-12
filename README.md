# Bitcoin Script Failure Modes

This repository documents my study of Bitcoin Script execution,
with a focus on how and why scripts fail during transaction validation.

Understanding script failure behavior is essential for building
secure wallets, writing safe spending conditions, and reviewing
consensus-critical code.

## Focus Areas
- Script execution model and stack behavior
- Common script failure conditions
- OP code constraints and limits
- Script validation flags
- Historical script-related consensus bugs

## Security Perspective
Script failures must be deterministic and consensus-safe.
This repository highlights how malformed or adversarial scripts
are handled by Bitcoin Core.

## Methodology
- Read Bitcoin Core script interpreter code
- Review relevant BIPs and PR discussions
- Document failure scenarios and lessons learned

## Status
Living research notes. Updated as understanding deepens.
