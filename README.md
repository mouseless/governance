# Governance

Here, you will find information about how we govern our collective.

## Roles

Everyone has one or more roles to contribute to the software we're delivering.

### Legal

- **Owner**: Makes the final decisions and handles responsibilities not covered
  by current roles
- **Member**: People with legal binding so that they get paid for what they do
- **Contributor**: People with no legal binding but known personally within our
  network who voluntarily contribute to public repositories
- **Follower**: This is the base role to for the rest of the people in our
  Discord server

Rules;

- Each role covers those below it; for instance, a Member can do what a
  Contributor can, etc
- A person can have only one legal role
- People with Member or Owner roles are added to GitHub organization

### Functional

- **Coders**: People who professionally write code
- **Governors**: Make contributions to the governance model
- **Lawyers**: Provide legal advice, create, and review legal contracts
- **Marketers**: Take initiative in marketing the collective and its projects

Rules;

- These roles serve as team names on GitHub and can be mentioned on Discord
- A person can have multiple functional roles

### Other

- `Booster` is an automatic role from Discord, and doesn't have any additional
  permissions
- Bot roles starts with `Bot ` and share the same color
- Bot roles are assigned manually to the related channel(s)

## Work

We manage our work using various backlogs and repositories.

### Backlog / Category

Each backlog is a prioritized list of work items to be done.

In GitHub, a backlog is represented by a single markdown file under `01-todo`
folder of the `work` repository.

In Discord, backlogs are represented by categories.

### Repository / Text Channel

We utilize git repositories to store;

- Source code
- Documentation
- Work items
- Scripts and automation
- Content
- Data

Most of the work we do has a corresponding repository unless it is purely
operational.

In Discord, each repository is represented by a text channel with a webhook
configured from GitHub to Discord.

Private repositories have private text channels, and are accesible only to
Members and above, whereas public repositories are accessible to anyone in the
collective.

Repository and text channel write permissions are given to the responsible teams
only. For instance, a Marketer does not have write access to a repository that
requires work only from Coders.

### Work Item / Pull Requests / Threads

Each work item goes under `02-in-progress` folder of the `work` repository as a
separate markdown file.

A work item mostly have a corresponding pull request (PR) in GitHub and a
corresponding thread in Discord. These PRs and threads are temporary places to
discuss the work being done and closed as soon as the work is done.

We have an `Actively Working` category in Discord, to find active work threads
easily. A text channel with an active thread is temporarily moved under this
category by an Owner until the work is done.

## Communication

It is allowed to have text and voice channels for communication purposes as well
as work tracking.
