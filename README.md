# GitHub templates and community-file examples

This repository is a **collection of reusable examples**, not a drop-in configuration that is automatically safe or current for every project.

It contains contribution, security and support guidance; issue and pull-request templates; and GitHub Actions workflow examples. Some files came from older projects and may contain project-specific names, version numbers, workflows, contacts or assumptions.

## How to reuse a file

1. **Pick only the files you need.** Do not copy the whole directory into a project.
2. GitHub convention: place an issue template in `.github/ISSUE_TEMPLATE/`, a PR template in `.github/PULL_REQUEST_TEMPLATE.md`, and a workflow under `.github/workflows/`.
3. Replace any example project name, owner contact, version or support policy. Remove unsupported claims and fake signatures or keys.
4. Adapt commands and CI versions to the real runtime and framework; check permissions and third-party actions before enabling CI.
5. Choose a license for the *destination project* deliberately. This repository does not grant a license to other code by copying configuration files.
6. Test on a branch, review changed files, and follow the destination project's rules before merging.

For maintained repositories, useful minimums are a **working README, reproducible tests, an issue/PR route, and accurate licensing/security information**. A school exercise, archived snapshot or private repository may need much less.

## Contributing to these examples

Please report dead links, obsolete GitHub Action usage, inappropriate security claims or broken template paths. A good pull request says which template is affected and why the correction is safer or clearer.

See [CONTRIBUTING.md](CONTRIBUTING.md) and [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md).
