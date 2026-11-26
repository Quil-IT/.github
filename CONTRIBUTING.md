# Contributing

Thanks for contributing to a Quil-IT project. Each repository may have its own `CONTRIBUTING.md` with project-specific setup; that file takes priority over this one.

## Workflow

1. Work from an issue. If there is none, open one first and agree the scope.
2. Branch from an up-to-date `main`: `feat/<issue>-short-name`, `fix/<issue>-short-name` or `chore/<short-name>`.
3. Keep commits small and use [Conventional Commits](https://www.conventionalcommits.org/): `feat:`, `fix:`, `docs:`, `chore:`, `refactor:`, `test:`.
4. Open a pull request using the template, link the issue (`Closes #123`) and make sure CI is green.
5. A maintainer reviews and merges. Nobody pushes directly to `main`.

## Standards

- TypeScript with `strict` mode for all new source code.
- Never commit secrets, keys or real customer data. Use `.env.local`, which is git-ignored.
- Public pages must meet accessibility and SEO basics before merge.
- Write commit messages, comments and docs clearly and plainly.

## Security

Found a vulnerability? Follow [SECURITY.md](SECURITY.md) instead of opening an issue.
