<!-- Written by `npm run screenshots` in bb-plugins. Edit the stories there, not this file. -->

# PR Sweep

Open pull requests you authored in one list, ordered Now, Next, and Later by what needs you, with local notes, new comment counts, and where a stacked pull request sits in its stack. Needs gh-context.

Source: [`bb-plugin-pr-sweep`](https://github.com/danielbachhuber/bb-plugins/tree/main/bb-plugin-pr-sweep)

## Pr list

### Baseline

A typical day. The pull requests that need you, the one ready to merge, and the one with a thread at the top, each with a red banner naming what stops it or a green one when it can merge; then the draft and the one awaiting review. The one with a thread is stacked on the one ready to merge, so each has a chip: "1 of 2 · base" and "2 of 2 · on #512".

![Baseline](pr-list--baseline.png)

### Rows

Every run the list can draw: needs you, ready to merge, and working in Now; drafts in Next; waiting in Later, including one stale after six days with its reviewer. Then every flag in the banner, the list across two repositories, a thread being started with a timer running, and the panel without Harvest.

![Rows](pr-list--rows.png)

### States

Loading, empty, and the notices the panel shows above and below its rows.

![States](pr-list--states.png)

### Long list

A long list: the Now and Next rows at the top, then the first five Later rows, with the rest folded into "N more".

![Long list](pr-list--long-list.png)
