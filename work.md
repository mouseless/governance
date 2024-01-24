# Work

We manage our work using various backlogs and repositories.

## Backlog / Category

Each backlog is a prioritized list of work items to be done.

In GitHub, a backlog is represented by a single markdown file under `01-todo`
folder of the private `work` repository.

In Discord,

- Backlogs are represented by categories. Categories should have a related emoji
  before the name
- Categories does not have custom permission to be able to move the channels
  from one category to another without a concern

## Repository / Text Channel

We utilize git repositories to store;

- Source code
- Documentation
- Work items
- Scripts and automation
- Website Content
- Data

Most of the work we do has a corresponding repository unless it is related to
daily operations or routine tasks.

In Discord, each repository is represented by a text channel with a webhook
configured from GitHub to Discord.

Private repositories have private text channels, and are accesible only to
Members and above, whereas public repositories are accessible to anyone in the
collective.

Write permissions for a public repository / text channel and read / write
permissions for a private repository / text channel are given to the responsible
teams only.

## Work Item / Pull Requests / Threads

An active work item is placed under `02-in-progress` folder of the private
`work` repository as a separate markdown file. If this work is under a
repository, it has a corresponding pull request (PR) in GitHub and a
corresponding thread in Discord. These PRs and threads are temporary places to
discuss the active work and closed as soon as it is done.

We have an `Actively Working` category in Discord, to find active work threads
easily. A text channel with an active thread is temporarily moved under this
category by an Owner until the work is done.

## A Note on Project Management

Our project management methodology is not yet documented. Until it is done,
please take the latest works as an example and ask for help in a text channel
related to your work if you have any questions.
