<!-- Written by `npm run screenshots` in bb-plugins. Edit the stories there, not this file. -->

# bb-plugins-screenshots

A picture of every story in [bb-plugins](https://github.com/danielbachhuber/bb-plugins),
taken after each commit there. The images live here so bb-plugins keeps a
small history while the visual history is still available.

## The plugins

| Plugin | What it does | Screenshots |
| --- | --- | --- |
| [Dynamic UI](dynamic-ui/README.md) | Lets a skill show its results as a list above the thread's composer, each item opening in the side panel with its details and buttons: send a reply to the thread, open a new thread, run a confirmed command, or open a link. | 25 stories |
| [GitHub Context](gh-context/README.md) | A banner above the composer showing the thread's pull request and its reviewers, the GitHub issues it works on, its changes, and a Harvest timer, in place of bb's own. | 5 stories |
| [Now](now/README.md) | One list of what needs doing now, from Todoist and your Gmail inbox, with GitHub notifications gathered per pull request or issue, showing each pull request's reviewers, and Google Docs comments per document. | 5 stories |
| [Review Sweep](review-sweep/README.md) | Open pull requests waiting on a review from you, oldest request first. | 3 stories |
| [Thread Overview](thread-overview/README.md) | A band under each thread's header saying what the thread is for, what has been done so far, and which step it is on, written by the agent as it works and edited by you in place. | 1 story |
| [Tokenomics](tokenomics/README.md) | Graphs how many tokens your threads used over the past day, three days, or week, lists each thread's share, and puts a sparkline of each thread's token use over time in its header that opens a summary of which of your messages used the most. | 10 stories |

Each directory is a plugin, named for the first part of its story titles.
Its README describes the plugin and shows each story, in the light theme,
under a heading for the part of the plugin it draws. Each commit message
starts with the bb-plugins commit it was taken from and links to it.

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
