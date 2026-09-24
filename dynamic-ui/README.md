<!-- Written by `npm run screenshots` in bb-plugins. Edit the stories there, not this file. -->

# Dynamic UI

Lets a skill show its results as a list above the thread's composer, each item opening in the side panel with its details and buttons: send a reply to the thread, open a new thread, run a confirmed command, or open a link. A visual review shows screenshots of a UI's original and its variations, for you to pick one and note on each.

Source: [`bb-plugin-dynamic-ui`](https://github.com/danielbachhuber/bb-plugins/tree/main/bb-plugin-dynamic-ui)

## Thread

### Triage

The view above the composer, before anything is opened.

![Triage](thread--triage.png)

### Triage item open

A row clicked: the side panel shows that issue with its details and every button.

![Triage item open](thread--triage-item-open.png)

### Triage confirm command

"Close only" is a command, so clicking it opens the item asking first.

![Triage confirm command](thread--triage-confirm-command.png)

### Triage after

After acting: one closed, one opened as a thread, one dismissed.

![Triage after](thread--triage-after.png)

### Triage failed

A command that failed: the row says so, and the panel shows the output.

![Triage failed](thread--triage-failed.png)

### Self improve

Five findings above the composer.

![Self improve](thread--self-improve.png)

### Self improve item open

A finding opened: the evidence and the task in the side panel.

![Self improve item open](thread--self-improve-item-open.png)

### Self improve collapsed

Collapsed to one line once two threads are open.

![Self improve collapsed](thread--self-improve-collapsed.png)

### Dependabot

One pull request above the composer, with its main button.

![Dependabot](thread--dependabot.png)

### Dependabot item open

The pull request opened: the evidence, the assessment to edit, and every button.

![Dependabot item open](thread--dependabot-item-open.png)

### Dependabot conflict

A conflicted bump: the rebase is the main button, and it asks before running.

![Dependabot conflict](thread--dependabot-conflict.png)

### Dependabot after

After "Post, approve, and merge": with nothing left open, the list above the composer collapses to its header, and the checkmark there hides it. The panel shows the draft as posted.

![Dependabot after](thread--dependabot-after.png)

### Visual review

A fresh review: the original on top, two directions under it.

![Visual review](thread--visual-review.png)

### Visual review filled in

One picked, with notes, ready to send.

![Visual review filled in](thread--visual-review-filled-in.png)

### Visual review sent

After sending: the pick and notes stay as what was sent, and the row says which was picked.

![Visual review sent](thread--visual-review-sent.png)

## View

### Nothing picked

Nothing picked yet: the panel starts on the first open entry.

![Nothing picked](view--nothing-picked.png)

### All handled

Every entry handled and none picked: the panel asks for one from the list above the composer.

![All handled](view--all-handled.png)

### Picked

An entry picked: its summary, details, the draft to edit, and every button.

![Picked](view--picked.png)

### Editing draft

The draft as source, after Raw is picked or its preview double-clicked.

![Editing draft](view--editing-draft.png)

### Confirm command

A command button asks before it runs, showing the command.

![Confirm command](view--confirm-command.png)

### After command

After a command ran: its output on the entry, and the draft as a preview only.

![After command](view--after-command.png)

### After thread

After opening a thread: the button becomes Go to thread.

![After thread](view--after-thread.png)

### Command failed

A command that failed leaves the entry open with the output on it.

![Command failed](view--command-failed.png)

### Working

An action in flight.

![Working](view--working.png)
