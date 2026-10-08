<!-- Written by `npm run screenshots` in bb-plugins. Edit the stories there, not this file. -->

# bb-plugins-screenshots

A picture of every story in [bb-plugins](https://github.com/danielbachhuber/bb-plugins),
taken after each commit there. The images live here so bb-plugins keeps a
small history while the visual history is still available.

## The plugins and shared packages

| Plugin | What it does | Screenshots |
| --- | --- | --- |
| [component-library](component-library/README.md) | UI that several plugins draw the same way, starting with the sync status in a page's title bar. | 5 stories |
| [Contributor Dashboard](contributor-dashboard/README.md) | A dashboard of how people contribute to one GitHub repository, from a local mirror of its pull requests, reviews and issues. | 14 stories |
| [Diff Comment](diff-comment/README.md) | Leave review comments inline on a thread's diff, then have the agent work through them one at a time. | 6 stories |
| [Dynamic UI](dynamic-ui/README.md) | Lets a skill show its results as a list above the thread's composer, each item opening in the side panel with its details and buttons: send a reply to the thread, open a new thread, run a confirmed command, or open a link. | 54 stories |
| [GitHub Context](gh-context/README.md) | A banner above the composer showing the thread's pull request and its reviewers, the GitHub issues it works on, its changes, and a Harvest timer, in place of bb's own. | 5 stories |
| [Issue Sweep](issue-sweep/README.md) | Open GitHub issues assigned to you, split into what needs you and everything else grouped by board status, with local notes, new comment counts, and the comments a click away. | 6 stories |
| [Now](now/README.md) | One list of what needs doing now, from Todoist and your Gmail inbox, with GitHub notifications gathered per pull request or issue, showing each pull request's reviewers, and Google Docs comments per document. | 12 stories |
| [Plugin Shelf](plugin-shelf/README.md) | Lists the plugins in your bb-plugins checkout as published and current, published with commits not yet released (with those commits), or personal, with each published plugin's install count, on a My plugins page in bb's Plugins screen, with a button on each to start a thread on it and one to publish an update where one is due. | 4 stories |
| [PR Sweep](pr-sweep/README.md) | Open pull requests you authored in one list, newest first with the overdue and in-progress ones pinned on top, with local notes, new comment counts, review comments a click away, a Dismiss for failing checks you cannot fix, and where a stacked pull request sits in its stack. | 5 stories |
| [Presentations](presentations/README.md) | Give a talk from a bb thread. | 6 stories |
| [Review Sweep](review-sweep/README.md) | Open pull requests waiting on a review from you in one list, ordered Now, Next, and Later by what needs you, oldest request first, with local notes, new comment counts, comments a click away, and where a stacked pull request sits in its stack, plus Batch to start reviews for several at once. | 6 stories |
| [Super Diff](super-diff/README.md) | Review a branch one concern at a time. | 18 stories |
| [sweep-ui](sweep-ui/README.md) | The list Issue Sweep, PR Sweep, and Review Sweep draw each tab with: summary squares, rows ordered Now, Next, and Later, and a stage track. | 3 stories |
| [Thread Overview](thread-overview/README.md) | A band under each thread's header saying what the thread is for, what has been done so far, and which step it is on, written by the agent as it works and edited by you in place. | 1 story |
| [Tokenomics](tokenomics/README.md) | Graphs how many tokens your threads used over the past day, three days, or week, shows where their turn time went, lists each thread's share, puts a sparkline of each thread's token use over time in its header that opens a summary of which of your messages used the most tokens and time, and shows a meter above a thread's composer once its context passes a size you set, with a button that compacts it. | 11 stories |
| [Weekly Review](weekly-review/README.md) | One page of what you actually did this week, gathered at 7am and 1pm on weekdays, sorted into workstreams by rules you refine, and set against the priorities in last week's entry, to write the journal entry from. | 8 stories |

Each directory is a plugin or a shared package, named for the first part of
its story titles. Its README describes it and shows each story, in the light
theme, under a heading for the part it draws. Each commit message starts with
the bb-plugins commit it was taken from and links to it.

To see how a story changed, look at the history of its file:

```sh
git log -p --follow review-sweep/review-list--baseline.png
```

Nothing here is edited by hand. `npm run screenshots` in bb-plugins writes
every image and README, and removes the images of stories that no longer
exist. A plugin's description comes from its `bb.description`, and a
story's caption from the doc comment above it. Its changes are committed only
after each changed file has been checked for private information, as
AGENTS.md describes.
