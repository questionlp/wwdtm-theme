# Contributing

If you would like to contribute to this projects, there are a few guidelines that you'll want to review below.

## Code of Conduct

A copy of this project's [Code of Conduct](CODE_OF_CONDUCT.md) is based on version 2.1 of the Contributor Covenant.

## Branching

The default branch for this repository and the branch used to deploy the application into production is `main`. Any bugs that are found in production should be made by creating a branch off of the latest version of `main` with a descriptive name.

All new feature development is handled off of the `develop` branch, which in turn would be merged into `main` after thorough unit and regression testing in a development and/or staging environment.

## Pull Requests

Once the new branch has been published to GitHub, the next step will be to create a new pull request to merge the new branch with the `main` branch for production bugfixes or the `develop` branch for new features.

After creating the pull request, it will go through a review and the request will either be accepted or declined based on needs, code quality, testing problems or any other reason that will be included in the commit message or request declined message.

Pull requests for new feature branches to merge directly with the `main` branch and have not gone through the `develop` branch pull request process (as well as the required testing) will be declined.

## License

This project is licensed under the under the terms of the [Apache License 2.0](./LICENSE), otherwise noted below.

Additional files that are derived from Bootstrap's `_variables.scss` and `_variables-dark.scss` located under `themes` as `_default.scss` and `_dark.scss` respectively, are licensed under the terms of the [MIT License](https://github.com/twbs/bootstrap/blob/main/LICENSE).
