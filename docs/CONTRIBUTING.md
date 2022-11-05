# Contributing

When contributing to this repository, please first discuss the change you wish to make via issue, discussions, discord, or any other method with the owners of this repository before making a change.

Note we have a [code of conduct](CODE_OF_CONDUCT.md), please follow it in all your interactions with the project.

## Development environment setup

To set up a development environment, please follow these steps:

1. Clone the repo

   ```sh
   git clone https://github.com/divetool/divetool
   ```

2. Install dependencies

   ```sh
   npm i -g pnpm # If pnpm not installed
   pnpm install
   ```

3. You're done! Run an application in the repo. Eg:

   ```sh
   pnpm nx serve web
   ```

## Issues and feature requests

You've found a bug in the source code, a mistake in the documentation or maybe you'd like a new feature? Take a look at [GitHub Discussions](https://github.com/divetool/divetool/discussions) to see if it's already being discussed. You can help us by [submitting an issue on GitHub](https://github.com/divetool/divetool/issues). Before you create an issue, make sure to search the issue archive -- your issue may have already been addressed!

Please try to create bug reports that are:

- _Reproducible._ Include steps to reproduce the problem.
- _Specific._ Include as much detail as possible: which version, what environment, etc.
- _Unique._ Do not duplicate existing opened issues.
- _Scoped to a Single Bug._ One bug per report.

**Even better: Submit a pull request with a fix or new feature!**

### How to submit a Pull Request

1. Search our repository for open or closed
   [Pull Requests](https://github.com/divetool/divetool/pulls)
   that relate to your submission. You don't want to duplicate effort.
2. [Fork](https://github.com/divetool/divetool/fork) the project
3. Create your feature branch (`git checkout -b feat/scope/amazing-feature`) in you fork.
4. Commit your changes (`pnpm commit`). The cli wizard will guide you on writting commits using our [conventional commits](https://www.conventionalcommits.org) convention, please follow this specification in your commit messages.
5. Push to the branch (`git push origin feat/amazing_feature`)
6. [Open a Pull Request](https://github.com/divetool/divetool/compare?expand=1)