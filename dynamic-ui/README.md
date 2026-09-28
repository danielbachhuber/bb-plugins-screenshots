<!-- Written by `npm run screenshots` in bb-plugins. Edit the stories there, not this file. -->

# Dynamic UI

Lets a skill show its results as a list above the thread's composer, each item opening in the side panel with its details and buttons: send a reply to the thread, open a new thread, run a confirmed command, or open a link. A list view instead shows everything in the side panel as one list, with quick decisions such as Add and Skip on each row and the names to add editable. A visual review shows screenshots of a UI's original and its variations, for you to pick one and note on each. An item about a change shows it: a pull request's files in bb's diff view, a lockfile as the packages whose versions changed, or a section's new text beside the old with the changed words marked. Work that goes in rounds, such as sections of a document, shows a status the agent sets, a count of what is complete, each item's history and budget, supporting notes to add, a map of the pages the items fill, and a field for your push-back, and stays open until the agent marks it complete.

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

### Triage one done

One issue closed: it moves to the bottom, under the two still open.

![Triage one done](thread--triage-one-done.png)

### Triage after

After acting: one closed, one opened as a thread, one dismissed.

![Triage after](thread--triage-after.png)

### Triage failed

A command that failed: the row says so, and the panel shows the output.

![Triage failed](thread--triage-failed.png)

### Staples

A list view: one row above the composer previewing what is left and what is on the list, and the whole view in the side panel, each staple's name in a field to edit before Add.

![Staples](thread--staples.png)

### Staples after

After deciding: Oat milk added and moved into the list, Bananas skipped with Undo, and Brown rice failed with its error, ready to retry.

![Staples after](thread--staples-after.png)

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

### Grant

A piece of work in rounds: the header counts what the agent marked complete, and each row shows the status it set.

![Grant](thread--grant.png)

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

### List fresh

A list view: the staples to add on top as dashed rows, each name editable before Add, with Skip; the list as it stands below.

![List fresh](view--list-fresh.png)

### List working

Add running on one row.

![List working](view--list-working.png)

### List after

Added moves a row into the list as the name was sent, here edited to say how many, tagged with its button's done label; Skip strikes it through with Undo; a failure shows its error and keeps the buttons.

![List after](view--list-after.png)

### List confirm

A command that asks first shows it under its row, with Run and Cancel.

![List confirm](view--list-confirm.png)

### Text draft

A one-line field beside five product buttons: type a product of your own and press Use this, or Enter.

![Text draft](view--text-draft.png)

### Text draft question

A question card whose answer is the main button, with a product button in case one fits.

![Text draft question](view--text-draft-question.png)

### Text draft sent

After the answer is sent: the field shows it, greyed, and the banner repeats it.

![Text draft sent](view--text-draft-sent.png)

### Status rounds

A section worked in rounds: its status set by the agent beside its badges, and its history under the summary. Its buttons stay usable until the agent marks it complete.

![Status rounds](view--status-rounds.png)

### Status just revised

Revise pressed: the banner says it was sent, until the agent publishes the next round.

![Status just revised](view--status-just-revised.png)

### Changes files

A pull request's files: package.json's diff in bb's own diff view, and the lockfile as the packages whose versions changed, the zod downgrade package.json doesn't explain flagged.

![Changes files](view--changes-files.png)

### Changes raw lockfile

The lockfile's raw diff, one click from its packages, here split side by side.

![Changes raw lockfile](view--changes-raw-lockfile.png)

### Changes code review

A code review finding: the hunk it is about, above the comment to post.

![Changes code review](view--changes-code-review.png)

### Changes prose

A section's proposed text against the application: each line beside what it replaced, the changed words marked.

![Changes prose](view--changes-prose.png)

### Changes prose split

The same change split side by side: before on the left, after on the right.

![Changes prose split](view--changes-prose-split.png)

### Changes prose edit

Edit: the proposed text as source, in place of the diff. Accept and Revise send it as left here.

![Changes prose edit](view--changes-prose-edit.png)

### Map and related

Work that fills pages: the map at the top sizes each section by its word limit and fills it by its count, Approach red for running over; under the section, notes from the release history to add, one already used.

![Map and related](view--map-and-related.png)

### Related just added

Add pressed on a related note: it says so until the agent publishes again and marks the note used.

![Related just added](view--related-just-added.png)
