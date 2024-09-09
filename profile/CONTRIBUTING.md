## Table of Contents

- [Contributing to Pluto](#contributing-to-pluto)
- [Code of Conduct](#code-of-conduct)
- [Ways to contribute](#ways-to-contribute)
- [Bounties](#bounties)
- [Submitting a bug report](#submitting-a-bug-report)
- [Submitting a feature request](#submitting-a-feature-request)
- [Resolving an issue](#resolving-an-issue)
  - [Adding tests](#adding-tests)
  - [Commits](#commits)
  - [Discuss and update](#discuss-and-update)
  - [Be aware of the person behind the code](#be-aware-of-the-person-behind-the-code)
  - [Abandoned or stale pull requests](#abandoned-or-stale-pull-requests)
  - [Contributions related to spelling and grammar](#contributions-related-to-spelling-and-grammar)



## Contributing to Pluto

Thank you for your interest in improving Pluto.

There are multiple opportunities to contribute to Pluto, at any level. It doesn't matter if you are just getting started with applied cryptography or if you are an expert; we can use your help. No contribution is too small and we value all contributions.

This document will help you get started. It should be considered as a guide to help you navigate the contribution process. The [Pluto telegram](https://t.me/pluto_xyz/1) is available to help you with any questions concerns that you may have that are not covered in this guide.

If you contribute to this project, your contributions will be made to the project under the Apache 2.0 license.

## Code of Conduct

The Pluto project adheres to the [Rust Code of Conduct](https://github.com/rust-lang/rust/blob/master/CODE_OF_CONDUCT.md). This code of conduct describes the minimum behavior expected from all contributors.

Instances of violations of the Code of Conduct can be reported by contacting the team at [eng@pluto.xyz](mailto:eng@pluto.xyz).

## Ways to contribute

Individuals can contribute to Pluto's open-source repositories a few different ways:

1. **Open an issue:** For example, if you find a bug or want to request a new feature, you can create a new issue in the issue tracker.
2. **Add context to an existing issue:** Providing additional context to existing issues, such as screenshots and code snippets, can help others resolve issues.
3. **Resolve an issue:** Open a pull request that fixes the underlying problem in a reviewable manner, or demonstrate that the issue is not a problem after all.

**Anybody can participate in any of these ways**. We urge you to participate in the discussion around bugs and participate in reviewing PRs.

## Bounties

We will gladly support high-quality contributions to the Pluto repositories with a cash bounty. 

For any issue labelled as a bounty, completion of a bounty (per the requirements listed in the issue) is sufficient to receive a $250 minimum bounty. Issues that go above and beyond the minimum requirements (large test suite, additional features, well-commented code, etc.) may receive larger cash bounties, subject to the discretion of the reviewing team. Issues that are not labelled as bounties may still receive cash bounties if the quality of work is high, subject to the discretion of the reviewing team.

## Submitting a bug report

When filing a new bug report in the issue tracker, you will be presented with a basic form to fill out.

If you believe that you have uncovered a bug, please fill out the form to the best of your ability. Do not worry if you
cannot answer every detail, just fill in what you can. Contributors will ask follow-up questions if something is
unclear.

The most important pieces of information we need in a bug report are:

- The version of the software that you are on (and that it is up to date)
- The platform you are on (Windows, macOS/m1 Mac, Linux)
- Code snippets if this is happening in relation to testing or building code
- Concrete steps to reproduce the bug

In order to rule out the possibility of the bug being in your project, the code snippets should be as minimal as
possible. It is better if you can reproduce the bug with a small snippet as opposed to an entire project!

## Submitting a feature request

When adding a feature request in the issue tracker, you will be presented with a basic form to fill out.

Please include as detailed of an explanation as possible of the feature you would like, adding additional context if
necessary.

If you have examples of other tools that have the feature you are requesting, please include them as well.

## Resolving an issue

Pull requests are the way concrete changes are made to the code, documentation, and dependencies of Pluto's projects.

Even tiny pull requests are greatly appreciated. Before making a large change, it is usually a good idea to first open an issue describing the change to solicit feedback and guidance. This will increase the likelihood of the PR getting merged.

If you are working on a larger feature, we encourage you to open up a draft pull request, to make sure that other contributors are not duplicating work.

### Adding tests

If the change being proposed alters code, it is either adding new functionality or fixing existing, broken functionality.
In both of these cases, the pull request should include one or more tests to ensure that Reth does not regress in the future.

Types of tests include:

- **Unit tests**: Functions which have very specific tasks should be unit tested.
- **Integration tests**: For general purpose, far reaching functionality, integration tests should be added. The best way to add a new integration test is to look at existing ones and follow the style.

### Commits

It is a recommended best practice to keep your changes as logically grouped as possible within individual commits. There is no limit to the number of commits any single pull request may have, and many contributors find it easier to review changes that are split across multiple commits.

That said, if you have a number of commits that are "checkpoints" and don't represent a single logical change, please squash those together.

### Discuss and update

You will probably get feedback or requests for changes to your pull request. This is a big part of the submission process, so don't be discouraged! Some contributors may sign off on the pull request right away, others may have more detailed comments or feedback. This is a necessary part of the process in order to evaluate whether the changes are correct and necessary.

### Be aware of the person behind the code

Be aware that _how_ you communicate requests and reviews in your feedback can have a significant impact on the success
of the pull request. Yes, we may merge a particular change that makes Pluto better, but the individual might just not
want to have anything to do with Pluto ever again. The goal is not just about having good code, but creating an ecosystem where others want to contribute as well. 

### Abandoned or stale pull requests

If a pull request appears to be abandoned or stalled, it is polite to first check with the contributor to see if they
intend to continue the work before checking if they would mind if you took it over (especially if it just has nits
left). When doing so, it is courteous to give the original contributor credit for the work they started, either by
preserving their name and e-mail address in the commit log, or by using the `Author: ` or `Co-authored-by: ` metadata
tag in the commits.


### Contributions related to spelling and grammar

At this time, we will not be accepting contributions that only fix spelling or grammatical errors in documentation, code or elsewhere.

