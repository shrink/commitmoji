# `$ git commitmoji` [:clipboard:][emojis]

> Gitmoji is an initiative to standardize and explain **the use of emojis on
GitHub commit messages**.

commitmoji takes the [gitmoji][gitmoji] concept and introduces strict rules that
simplify the standard so that it can be used as part of a mature git workflow.
[How to Write a Git Commit Message][write-a-commit-message] describes a set of
seven rules for writing commit messages, commitmoji provides a standard that
works alongside these rules.

> If applied, this commit will... :memo: Include last activity timestamp in user metadata \
If applied, this commit will... :wrench: Load hostname from environment \
If applied, this commit will... :bug: Generate cache key with user identifier \
If applied, this commit will... :family: List `@example` as a Gold sponsor

## Principles

A commit message should describe the change that is to be applied to the
project: an emoji is used to identify the _area_ of change, leaving the
remainder of the subject free to describe the specifics. Each type should apply
consistently across all types of project whether it's the source code for a
mobile application, a developer's environment configuration files or
[law][dc-law-html].

**Less is more**. A simple consistent set of emojis enable quick recognition and
recall across all projects. Any change to the substance of the standard is
considered breaking and requires a new major release.

## Emojis

:construction: commitmoji is currently in pre-release, please review the
proposed types below.

### Proposed Emojis

| Type | Emoji | Pull Request |
| ---- | ----- | ------------ |
| Feature | :sparkles: `:sparkles:` | [#5 &rarr;](https://github.com/shrink/commitmoji/pull/5) |
| Development Environment | :construction_worker: `:construction_worker:` | [#6 &rarr;](https://github.com/shrink/commitmoji/pull/6) |

## License

commitmoji is licensed under the [MIT License][license].

[gitmoji]: https://github.com/carloscuesta/gitmoji
[write-a-commit-message]: https://chris.beams.io/posts/git-commit/
[emojis]: #emojis "List of Emojis"
[LICENSE]: LICENSE
[dc-law-html]: https://github.com/DCCouncil/dc-law-html
[commitmoji-pull-requests]: https://github.com/shrink/commitmoji/pulls
