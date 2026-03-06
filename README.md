# devcontainers-best-practices

[![GitHub release (latest SemVer)][version-badge]][releases]
[![GitHub contributors][contributors-badge]][contributors]
[![MIT License][license-badge]][license]
[![PRs Welcome][prs-welcome-badge]][prs-welcome]
[![Conventional Commits][commits-badge]][commits]
[![gitmoji][gitmoji-badge]][gitmoji]
[![Keep a Changelog][changelog-badge]][changelog]
[![Contributor Covenant][code-of-conduct-badge]][code-of-conduct]

A [skills.sh](https://skills.sh/) skill that teaches agents and developers **where and how** to look up the Development Container spec, `devcontainer.json` reference and schema, Features, Templates, and tools that support devcontainers.

## What this skill covers

- **Spec lookup** — When to use the [JSON reference](https://containers.dev/implementors/json_reference/), [JSON schema](https://containers.dev/implementors/json_schema/), and [spec](https://containers.dev/implementors/spec/). Lifecycle scripts, `features`, `forwardPorts`, `customizations`, merge logic.
- **References** — Canonical URLs (containers.dev, devcontainers.github.io) and repo layout (spec, features, templates, cli, ci).
- **Tools** — [Supporting tools](https://devcontainers.github.io/supporting): VS Code, JetBrains, GitHub Codespaces, Dev Container CLI, DevPod, CodeSandbox, and others. Tool-specific properties and limitations.
- **Features** — [devcontainers/features](https://github.com/devcontainers/features), OCI references (`ghcr.io/devcontainers/features/...`), versioning, options.
- **Templates** — [devcontainers/templates](https://github.com/devcontainers/templates), when to use a template vs a Feature vs a custom Dockerfile.
- **Best practices** — Use Features when possible, pin versions, non-root user, prefer official Features/templates for common stacks.

This skill is **reference and ecosystem oriented**. For implementation patterns (Dockerfiles, Docker-in-Docker, env management), see the complementary [DevContainer Workflow](https://github.com/ilude/claude-code-config) skill.

## Install

```bash
npx skills add <owner>/devcontainers-best-practices
```

Replace `<owner>` with the GitHub org or username that hosts this repo.

## Links

- [containers.dev](https://containers.dev/) — Dev container specification and docs
- [devcontainers/spec](https://github.com/devcontainers/spec) — Specification repo
- [devcontainers/features](https://github.com/devcontainers/features) — Official Features
- [devcontainers/templates](https://github.com/devcontainers/templates) — Official Templates
- [Supporting tools](https://devcontainers.github.io/supporting) — Tools that support devcontainers

## Contributing

Interested in contributing? See how you can help in our [contributing guide](CONTRIBUTING.md).

This project adheres to a Contributor Code of Conduct. By participating, you agree to abide by [its terms](CODE_OF_CONDUCT.md).

## License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

## Acknowledgments

This project owes its gratitude to:

- The [devcontainers](https://github.com/devcontainers) team and [containers.dev](https://containers.dev/) for the specification and ecosystem.
- The maintainers of [devcontainers/features](https://github.com/devcontainers/features) and [devcontainers/templates](https://github.com/devcontainers/templates).
- The [skills.sh](https://skills.sh/) / Vercel Labs skills ecosystem for the agent-skills platform.
- [DevContainer Workflow](https://github.com/ilude/claude-code-config) for complementary implementation-focused guidance.
- Everyone who contributes to or uses this skill.

<!-- badges -->

[version-badge]: https://img.shields.io/github/v/release/afonsograca/devcontainers-best-practices?sort=semver&style=flat-square
[releases]: https://github.com/afonsograca/devcontainers-best-practices/releases
[contributors-badge]: https://img.shields.io/github/contributors/afonsograca/devcontainers-best-practices?style=flat-square
[contributors]: https://github.com/afonsograca/devcontainers-best-practices/graphs/contributors
[license-badge]: https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square
[license]: LICENSE
[prs-welcome-badge]: https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square
[prs-welcome]: http://makeapullrequest.com
[commits-badge]: https://img.shields.io/badge/Conventional%20Commits-1.0.0-%23FE5196?logo=conventionalcommits&logoColor=white&style=flat-square
[commits]: https://conventionalcommits.org
[gitmoji-badge]: https://img.shields.io/badge/gitmoji-%20😜%20😍-FFDD67.svg?style=flat-square
[gitmoji]: https://gitmoji.dev/
[changelog-badge]: https://img.shields.io/badge/changelog-Keep%20a%20Changelog-orange?style=flat-square
[changelog]: CHANGELOG.md
[code-of-conduct-badge]: https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg?style=flat-square
[code-of-conduct]: CODE_OF_CONDUCT.md
