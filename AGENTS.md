# AGENTS.md

Screenshots of the stories in
[bb-plugins](https://github.com/danielbachhuber/bb-plugins), written by its
`npm run screenshots`. The README covers the layout.

## This repository is public

`danielbachhuber/bb-plugins-screenshots` is public, and an image in its history
stays there even after a later commit deletes it. So every image is read
before it is pushed, not only scanned by name:

- **No credentials.** No tokens, keys, or anything from `~/.bb`.
- **No real repository, project, board, team, or person names.** Not in a
  title, an author line, a reviewer list, a URL, or a hint.
- **No content copied out of a thread or a real screen.** A pull request
  title reworded slightly, with its real number and line counts, still
  identifies the pull request.

The stories use invented names: `acme/widgets`, `acme/gadgets`, `octocat`,
`hubber`, `Acme Board`. Anything else in an image is worth a second look.

## Publishing a run

`npm run screenshots` in bb-plugins writes the images here and lists the
ones it added or changed. It does not commit, so everything is still only in
the working tree while it is checked.

1. Open each listed image and read all of it, including the story's label and
   hint beside the frame, and text that is cut off or small.
2. If every one is clean, run `npm run screenshots:commit` in bb-plugins. It
   commits here with a message naming the bb-plugins commit, and pushes.
3. If one is not, throw the capture away with `git checkout -- . && git clean
   -fd` here, fix the fixture in bb-plugins, commit that there, and capture
   again. Nothing was committed, so there is no history to undo.

A commit that says "Captured with uncommitted changes" in its message holds
pictures of work that is not committed in bb-plugins yet, possibly from
another thread. Screen those images the same way. They are no safer for
being unfinished.

## Nothing here is edited by hand

The script writes every image and removes the images of stories that no
longer exist. Fix a picture by fixing its story in bb-plugins, never by
editing, adding, or deleting files here.
