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

`npm run screenshots` commits here and does not push. It lists the images the
run added or changed.

1. Open each listed image and read all of it, including the story's label and
   hint beside the frame, and text that is cut off or small.
2. If every one is clean, push: `git push`.
3. If one is not, do not push. Drop the commit with `git reset --hard HEAD~1`,
   fix the fixture in bb-plugins, commit that there, and run
   `npm run screenshots` again.

A run that says "Captured with uncommitted changes" in its message took
pictures of work that is not committed in bb-plugins yet, possibly from
another thread. Screen those images the same way. They are no safer for
being unfinished.

## Nothing here is edited by hand

The script writes every image and removes the images of stories that no
longer exist. Fix a picture by fixing its story in bb-plugins, never by
editing, adding, or deleting files here.
