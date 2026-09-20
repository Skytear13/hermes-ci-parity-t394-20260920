# Hermes T394 CI parity orchestration

This temporary public repository contains only CI orchestration. It clones the
public Hermes Agent repository at the exact frozen commit required by T394,
installs the frozen test dependencies, and runs the complete canonical test
runner without credentials or model calls.

Frozen source:
- tag: `v2026.9.14`
- commit: `345cd2b057a452236de401d3534b8502a7465e8d`
- tree: `6e14b9791cdc5a47068685e9429dd5d6bdc5ef5f`

The repository contains no Hermes migration evidence, user configuration,
secrets, `.env`, `auth.json`, or provider credentials.
