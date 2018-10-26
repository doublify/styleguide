# Contributing Guidelines

## Table of Contents

- [Pull Request Checklist](#pull-request-checklist)
- [Coding Style](#coding-style)
- [Contribution Guidelines and Standards](#contribution-guidelines-and-standards)

### Pull Request Checklist

Before sending your pull requests, make sure you followed this list.

- Read [contributing guidelines](/CONTRIBUTING.md).
- Read [Code of Conduct](/CODE_OF_CONDUCT.md).
- Ensure you have signed the [Contributor License Agreement (CLA)](https://doublify.org/en-US/about/governance/policies/commit/).
- Check if my changes are consistent with the [guidelines](#contribution-guidelines-and-standards).
- Changes are consistent with the [Coding Style](#coding-style).
- Run Unit Tests.

### How to become a contributor and submit your own code

#### Contributor License Agreements

For any code changes to be accepted,
the [Contributor License Agreement (CLA)](https://doublify.org/en-US/about/governance/policies/commit/)
must be signed.

### Coding Style

To keep a consistent code style, we use [Google's Coding Style Guide](https://github.com/google/styleguide).

### Contribution Guidelines and Standards

Before sending your pull request for review,
make sure your changes are consistent with the guidelines and
follow the [Google coding style](https://github.com/google/styleguide).

We adhere to the principles of [Google's TensorFlow philosophy for contribution](https://github.com/tensorflow/tensorflow/blob/master/CONTRIBUTING.md#general-guidelines-and-philosophy-for-contribution).

#### License

Include a license at the top of new files.

- [Go license example](/examples/code-licensing/go/main.go#L1)
- [Rust license example](/examples/code-licensing/rust/license-example/src/main.rs#L1)
- [Python license example](/examples/code-licensing/python/main.py#L1)

To ensures, source code files have copyright license headers
you can use [Google's addlicense](https://github.com/google/addlicense).

#### Git

#### Commit Message Guidelines

We prefer [Angular's Commit Message Guidelines](https://github.com/angular/angular/blob/master/CONTRIBUTING.md#-commit-message-guidelines)
rules over how our git commit messages can be formatted.

#### Git ignore

The local `.gitignore` file contains rules for ignoring project-specific files,
while others should go into a global `.gitignore` file.

##### Pre-commit hooks

For managing and maintaining pre-commit hooks we use [Yelp's pre-commit](https://pre-commit.com).
