# MeowKit-S3 documentation agent instructions

This public repository is a personal documentation mirror based on vendor
materials. It is not an official vendor release. Keep the upstream GitHub
repository as `origin` and use the personal public mirror `mcc1/meowkit-s3-docs`
as the `github` remote when it is configured locally.

## Personal modifications

- Keep vendor facts, personal observations, and experimental workflows
  distinguishable in the text.
- Local firmware build instructions belong in the firmware repository README;
  local installer and artifact instructions belong in the installer repository
  README.
- If a document conflicts with source code or a tested device, record the
  discrepancy and its verification status instead of silently rewriting the
  specification.

## Change and verification rules

- Check this repository's Git status before editing and preserve unrelated
  changes.
- Do not present unverified pinouts, capacities, serial settings, firmware
  behavior, or flashing workflows as confirmed facts.
- Run the relevant Markdown/Mintlify checks when available and run
  `git diff --check` before committing.
- Keep public documentation free of credentials, Wi-Fi passwords, tokens, and
  private device data.
