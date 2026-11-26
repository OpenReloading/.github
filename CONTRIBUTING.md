# Contributing

How to report a problem and propose a change in a RangeFoundry repository that has no `CONTRIBUTING.md` of its own. The repository's README names its setup and checks.

## Report a problem or ask for something

- Open an issue with the bug report, feature request or question form, and start with the plain-words field: what is wrong or wanted, for someone who does not know the code.
- Report a vulnerability privately, as the [security policy](https://github.com/OpenReloading/.github/blob/main/SECURITY.md) describes, never as an issue.

## Propose a change

1. For more than a small fix, open an issue first, so the approach is agreed before the work starts.
2. Branch from the default branch and open the pull request against it. Fill in every section of the pull request template.
3. Write the pull request title in [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) form, for example `fix(api): reject an empty name`. Pull requests are squash-merged, so the title becomes the commit message.
4. Sign your commits with an SSH or GPG key ([signing commits](https://docs.github.com/en/authentication/managing-commit-signature-verification/signing-commits)).
5. The repository's tests and checks pass before review. A change in behavior comes with a test that fails without it.

## License

A contribution is licensed under the license of the repository it goes into. There is no contributor license agreement (CLA).
