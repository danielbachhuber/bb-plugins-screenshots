<!-- Written by `npm run screenshots` in bb-plugins. Edit the stories there, not this file. -->

# Super Diff

Group the Diff tab by concern, with an explanation for each group and notes on the trickier code, written by the thread's agent.

Source: [`bb-plugin-super-diff`](https://github.com/danielbachhuber/bb-plugins/tree/main/bb-plugin-super-diff)

## Super diff

### Not generated

Before anything is generated: bb's own diff, with Generate Super Diff on the left of the row.

![Not generated](super-diff--not-generated.png)

### Generating

While the thread's agent reads the diff and writes the Super Diff.

![Generating](super-diff--generating.png)

### Showing super diff

A Super Diff is showing: the toggle switches back to bb's own list, and the line counts what the agent wrote.

![Showing super diff](super-diff--showing-super-diff.png)

### Out of date

Two files have joined the diff since the Super Diff was written, so the row turns amber and offers Regenerate.

![Out of date](super-diff--out-of-date.png)

### Annotation list

The list at the top of a Super Diff: each annotation's number, title, and line, which jumps to its card. One note's line has left the diff.

![Annotation list](super-diff--annotation-list.png)

### Annotation card

A note card as it sits under the line it explains, inside the diff.

![Annotation card](super-diff--annotation-card.png)
