# Contributing

We welcome community contributions.

Before submitting a feature or enhancement, please propose the idea first so we can avoid duplicate work and ensure it aligns with the project’s goals.

Woodpecker CI is used by many organizations and individuals and is expected to remain stable at its core. As a result, we may reject changes that break existing functionality or address narrow use cases that are better implemented as plugins or extensions.

## Pull Requests

When opening pull requests, make sure that you link issues (using keywords like `closes`) that
are fixed by your change to automatically close them when the PR is merged.

## Code Review

Once code review starts on your PR, do not rebase nor squash your branch as it makes it
difficult to review the new changes. Only if there is a need, sync your branch by merging
the base branch into yours. Don't worry about merge commits messing up your tree as
the final merge process squashes all commits into one, with the commit message being the PR title.

Your PR must be approved by at least one maintainer.

Once your PR gets approved, don't worry about keeping it up-to-date or breaking
builds (unless there's a merge conflict or a request is made by a maintainer to make
modifications). It is the maintainer team's responsibility from this point to get it merged.

## Tests

For backend (golang) code, it is highly encouraged to write unit tests if you fix a bug to cover
that case.

For new functionality or features there should be at least basic testing.
