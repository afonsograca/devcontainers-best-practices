# Contributing guidelines

Thank you for considering contributing to devcontainers-best-practices. As the maintainers of this project, we want it to live and grow without depending on any single person. One of the simplest ways to do that is to encourage a larger set of shallow contributors, so the project can be updated even when original maintainers have less time.

### Development Process

We use a [trunk-based development](https://trunkbaseddevelopment.com/) approach, with a single protected branch:

- **`main`**: The primary branch. All development (features, fixes, updates) happens here. `main` should stay stable and releasable.

Create a new branch for each set of related changes, then open a pull request into `main` when ready. We follow the [Conventional Commits](https://www.conventionalcommits.org/) specification. Using [gitmoji](https://gitmoji.dev/) for commit types is encouraged but not required.

By contributing, you agree to abide by [our Code of Conduct](CODE_OF_CONDUCT.md).

### Release Process

Releases are manual. We decide when to cut a release and what it includes; discussion in issues or PRs is welcome.

This skill is distributed via **GitHub only**. [skills.sh](https://skills.sh/) installs skills from the repository (e.g. `npx skills add owner/devcontainers-best-practices`); there is no npm package to publish. Releases are made by:

1. Tagging a version using [Semantic Versioning](https://semver.org/) (e.g. `v1.0.0`).
2. Optionally creating a [GitHub Release](https://docs.github.com/en/repositories/releasing-projects-on-github) with notes from [CHANGELOG.md](CHANGELOG.md).

Once the tag is pushed, users who install the skill get that version when they run `npx skills add`.

### Ownership

If you get a merged pull request (whether it’s typos, code, or docs), you are eligible for push access to this repository.

That might sound risky, but in practice it brings fresh perspectives and gives dependents a stake in the project. If you use this skill, you likely have the skills to improve it. All code is peer-reviewed; we prefer that someone other than the author merges non-trivial PRs. No one can push directly to `main` without review.

As a contributor with push access you can:

- Create branches in the repo instead of forking for every change.
- Triage issues and review/merge pull requests.
- Help maintain the project if others step back.

You’re not obliged to do any of that.

When reviewing, focus on the motivation of a PR rather than minor style issues. We’ll work with you on tests and quality where it matters.

### Our expectations

To quote [@alloy](https://github.com/alloy) from [this issue](https://github.com/Moya/Moya/issues/135):

> Do not ever feel bad for not contributing to open source.

Contributing is optional. We want ideas and help, but we’re here to get things done in an enjoyable way.

### Contact

If you have something that shouldn’t be discussed in a public issue, contact the maintainers via the links on their GitHub profiles.

### Attribution

This contributing guide is adapted from [Moya’s contributors](https://github.com/moya/contributors).

### [:skateboard:](https://en.wikipedia.org/wiki/Van_Halen#Contract_riders)

If you read this whole file, you’re awesome. You can put the :skateboard: emoji at the top of your PR to show you’ve read it and are following it as best you can.
