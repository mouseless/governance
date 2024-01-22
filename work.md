# Work

We manage our work using various backlogs and repositories.

## Backlog / Category

Each backlog is a prioritized list of work items to be done.

In GitHub, a backlog is represented by a single markdown file under `01-todo`
folder of the `work` repository.

In Discord, backlogs are represented by categories. Categories should have a
related emoji before the name.

## Repository / Text Channel

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

Repository and text channel write, and read for private repos, permissions are
given to the responsible teams only. For instance, a Marketer does not have
write access to a repository that requires work only from Coders.

## Work Item / Pull Requests / Threads

Each work item goes under `02-in-progress` folder of the `work` repository as a
separate markdown file.

A work item mostly have a corresponding pull request (PR) in GitHub and a
corresponding thread in Discord. These PRs and threads are temporary places to
discuss the work being done and closed as soon as the work is done.

We have an `Actively Working` category in Discord, to find active work threads
easily. A text channel with an active thread is temporarily moved under this
category by an Owner until the work is done.
