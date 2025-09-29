# Governance

## Maintainers

The maintainers are responsible for managing issues, doing code review and similar tasks.

A maintainer must be a contributor and contributed at least 4 accepted PRs.
The owners or the maintainers may invite the contributor.
A maintainer must spend some time on code reviews.

If a maintainer has no time to do that, they should apply to leave the maintainers team and we will give them the honor of being a member of the
[advisors team](https://github.com/orgs/woodpecker-ci/teams/advisors/members).
Of course, if an advisor has time to code review, we will gladly welcome them back to the maintainers team.
If a maintainer is inactive for more than 3 months and forgets to leave the maintainers team, the owners may move him or her from the maintainers team to the advisors team.

For security reasons, maintainers must [use 2FA for their accounts](https://docs.github.com/en/authentication/securing-your-account-with-two-factor-authentication-2fa) and if possible [provide signed commits](https://docs.github.com/en/authentication/managing-commit-signature-verification).

## Owners

Since Woodpecker is a pure community organization without any company support, to keep the development healthy we will elect two owners at the end of every year (December).\
This can also happen when an owner proposes a vote or the majority of the maintainers do so.\
All maintainers and advisors may vote to elect up to two other maintainers. Votes cannot be cast for oneself.
When the new owners have been elected, the old owners will give up ownership to the newly elected owners.
If an owner is unable to do so, the other owner will assist in ceding ownership to the newly elected owners.

To honor the past owners, here's the history of the owners and the time they served:

- 2025-01-01 ~ 2025-12-31 - <https://github.com/woodpecker-ci/woodpecker/issues/4559>

  - [Anbraten](https://github.com/anbraten)
  - [qwerty287](https://github.com/qwerty287)

- 2024-01-01 ~ 2024-12-31 - <https://github.com/woodpecker-ci/woodpecker/issues/2903>

  - [6543](https://github.com/6543)
  - [Anbraten](https://github.com/anbraten)

- 2023-01-01 ~ 2023-12-31 - <https://github.com/woodpecker-ci/woodpecker/issues/1467>

  - [6543](https://github.com/6543)
  - [Anbraten](https://github.com/anbraten)

- 2021-09-28 ~ 2022-12-31 - <https://github.com/woodpecker-ci/woodpecker/issues/633>

  - [6543](https://github.com/6543)
  - [Anbraten](https://github.com/anbraten)

- 2019-07-25 ~ 2021-09-28
  - [Laszlo Fogas](https://github.com/laszlocph)

## Access

The project has multiple accounts and systems. Owners have access to all systems. Maintainers may be granted additional access.

### Accounts

- [GitHub Org](https://github.com/woodpecker-ci/)
- [Codeberg Org](https://codeberg.org/woodpecker-ci)
- [Codeberg Plugins Org](https://codeberg.org/woodpecker-plugins)
- [OpenCollective](https://opencollective.com/woodpecker-ci)
- [Docker](https://hub.docker.com/u/woodpeckerci)

### Shared Accounts

Some accounts do require to share passwords. Those password should be shared using our [Vault](https://vault.woodpecker-ci.org).

- Bluesky
- Mastodon
- YouTube
- GitHub Bot account
- Codeberg Bot

### Infrastructure

- Domain: woodpecker-ci.org
  - owned by: [6543](https://github.com/6543)
  - access: [Anbraten](https://github.com/anbraten)
- Hetzner project (VPS)
  - owned by: [Anbraten](https://github.com/anbraten)
  - access: [qwerty287](https://github.com/qwerty287)
- Hetzner DNS
  - owned by: [Anbraten](https://github.com/anbraten)
  - access using Ansible / API
- Ansible (vault password):
  - access: [Anbraten](https://github.com/anbraten) [qwerty287](https://github.com/qwerty287) [xoxys](https://github.com/xoxys)
