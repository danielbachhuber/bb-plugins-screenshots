<!-- Written by `npm run screenshots` in bb-plugins. Edit the stories there, not this file. -->

# Issue Sweep

Open GitHub issues assigned to you, newest activity first. Needs gh-context.

Source: [`bb-plugin-issue-sweep`](https://github.com/danielbachhuber/bb-plugins/tree/main/bb-plugin-issue-sweep)

## Issue list

### Baseline

Four issues assigned to you, grouped under the Acme Board's columns in the board's own order. The one in progress already has a thread.

![Baseline](issue-list--baseline.png)

### Rows

Every section and row the panel can draw: board columns in order, a column the settings do not list, issues on no board, and blocked issues last. Rows show sub-issue and task counts, comments, a thread, and a disabled start button where no project is checked out. Then the same list across two repositories, a thread being started with a timer running, and the panel without Harvest.

![Rows](issue-list--rows.png)

### States

The panel before the first listing arrives, with nothing assigned, and with nothing visible because the only repository with issues has no project on this machine.

![States](issue-list--states.png)

### Warnings

What the panel shows when something is wrong: a failed sweep above the last good rows, gh-context missing so no row can start a thread, and no board configured so the status column cannot be changed.

![Warnings](issue-list--warnings.png)
