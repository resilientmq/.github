# Contributing to ResilientMQ

Thanks for helping make RabbitMQ event processing more predictable. This guide is the
default for every repository in the ResilientMQ organization. A repository-specific
guide takes precedence when it exists.

By contributing, you agree that your work is licensed under the license of the target
repository and that participation follows our [Code of Conduct](CODE_OF_CONDUCT.md).

## Before starting

- Open a pull request directly for a typo, broken link or small, isolated fix.
- Open an issue first for a feature, behavioral change or substantial refactor.
- Never report a vulnerability in a public issue; follow [SECURITY.md](SECURITY.md).

## Making a change

1. Fork the repository and branch from its default branch.
2. Name the branch `type/short-description`, such as `fix/redelivery-state`.
3. Follow the existing TypeScript style and keep public APIs backwards compatible unless
   the issue explicitly agrees otherwise.
4. Add unit, integration or type tests for behavior that changes.
5. Run the repository's build and test commands locally.
6. Use [Conventional Commits](https://www.conventionalcommits.org), with body lines that
   explain why the change is needed.
7. Open a focused pull request and link the issue it resolves.

## Repository policy

Repository settings, security features, metadata, environments and default-branch rules
are reconciled from a private Octoform configuration. A difference between repositories
of the same type may be policy drift rather than an intentional exception; report it
instead of changing settings manually.

Pull requests are required on package default branches. Approval counts and required
checks are deliberately limited to what the current contributor and CI setup can satisfy;
they may become stricter as the maintainer and workflow model evolves.

