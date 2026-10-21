<!-- Written by `npm run screenshots` in bb-plugins. Edit the stories there, not this file. -->

# Dev Bar

A status bar along the bottom of a thread that shows which of the checkout's dev services are running, and starts, stops, or restarts them.

Source: [`bb-plugin-dev-bar`](https://github.com/danielbachhuber/bb-plugins/tree/main/bb-plugin-dev-bar)

## Strip

### Running

Four of six services up, one still starting, with the repository's own buttons at the end.

![Running](strip--running.png)

### All stopped

Every service stopped, as in a fresh worktree.

![All stopped](strip--all-stopped.png)

### Busy

Start all is running, so its button shows a spinner.

![Busy](strip--busy.png)

### Action failed

A start that exited with an error shows the last lines it printed.

![Action failed](strip--action-failed.png)

### Status failed

The status command failed, so there are no services to show.

![Status failed](strip--status-failed.png)

### Loading

Before the first status arrives.

![Loading](strip--loading.png)
