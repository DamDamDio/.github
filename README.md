# .github

The DamDamDio organization's default community health files: today, only the issue forms (Task, Block, Decision,
Finding) and their `config.yml`, in `.github/ISSUE_TEMPLATE/`. GitHub serves them to every repository of the
organization that has no `.github/ISSUE_TEMPLATE/` of its own, private ones included; so no other repository keeps a
copy (admin-platform's ADR 0020, section 8).

This repository is public on purpose: GitHub serves default files only from a public `.github` repository. Never put a
secret in it, nor a host name, an address or anything else that is not meant for the internet.
