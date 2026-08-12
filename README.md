# ResilientMQ organization files

This is the special public `.github` repository for the
[ResilientMQ organization](https://github.com/resilientmq), an open source
initiative that is part of [Didactika](https://github.com/didactika).

It owns organization-level content rather than application code:

- `profile/data/content.json` is the editable source for the bilingual profile.
- `profile/README*.md`, `profile/projects/` and `profile/assets/` are generated.
- `.github/workflows/update-profile.yml` refreshes the profile from live GitHub data.
- `CONTRIBUTING.md`, `SECURITY.md` and `CODE_OF_CONDUCT.md` are the default community
  health files for ResilientMQ repositories that do not provide their own.

## Updating the profile

Change [`profile/data/content.json`](profile/data/content.json). Section visibility,
organization relationships, project groups, copy and founder roles all live there. Do
not edit generated Markdown or SVG files directly.

The workflow renders that data with
[`resilientmq/profile-generator`](https://github.com/resilientmq/profile-generator), an
unmodified fork of Didactika's shared generator. Keeping the fork free of organization
specific code means both profiles have the same capabilities and differ only in data.

