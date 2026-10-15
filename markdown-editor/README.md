<!-- Written by `npm run screenshots` in bb-plugins. Edit the stories there, not this file. -->

# Markdown Editor

Edit markdown files in the tab bb opens them in, preview the result, and save with Cmd+S without overwriting an agent's edits.

Source: [`bb-plugin-markdown-editor`](https://github.com/danielbachhuber/bb-plugins/tree/main/bb-plugin-markdown-editor)

## Tab

### Without the plugin

Without the plugin: bb opens a markdown file read-only, with a Preview and Raw toggle and no way to change the text.

![Without the plugin](tab--without-the-plugin.png)

### Raw with unsaved changes

The same file in Raw, edited in place: two lines changed, Unsaved changes in the header, and Save ready.

![Raw with unsaved changes](tab--raw-with-unsaved-changes.png)

### Preview with unsaved changes

Preview renders the unsaved text before it reaches disk.

![Preview with unsaved changes](tab--preview-with-unsaved-changes.png)

### Saved

Saved, in Preview.

![Saved](tab--saved.png)

### Add to chat

A paragraph selected in Preview, with Add to chat under it to quote it into the composer.

![Add to chat](tab--add-to-chat.png)

### Discard armed

Discard pressed once: it asks before throwing the edits away.

![Discard armed](tab--discard-armed.png)

### Conflict

An agent changed the file on disk while it had unsaved edits. Save stopped, and the banner asks which copy to keep.

![Conflict](tab--conflict.png)
