# Security Policy

This policy applies to ResilientMQ repositories that do not provide a more specific
`SECURITY.md`.

## Reporting a vulnerability

Do not open a public issue. Use **Security → Report a vulnerability** in the affected
repository to create a private GitHub advisory. If that option is unavailable, email
`security@didactika.org` with:

- the affected repository and version or commit;
- reproduction steps or a proof of concept;
- the expected impact;
- any suggested mitigation.

Please allow the maintainers time to confirm and fix the issue before publishing details.
We will coordinate disclosure and credit unless anonymity is requested.

## Supported versions

Until a repository publishes a dedicated support matrix, security fixes target its latest
published version and current default branch. Older releases may receive a backport when
the fix is safe and users cannot reasonably upgrade, but they are not implicitly supported.

Type-definition repositories follow the runtime package they describe. A declaration
release is supported only while it remains compatible with a supported runtime release.

