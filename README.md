# bb-plugins-screenshots

A picture of every story in [bb-plugins](https://github.com/danielbachhuber/bb-plugins),
taken after each commit there. The images live here so bb-plugins keeps a
small history while the visual history is still available.

Each directory is a plugin, named for the first part of its story titles, and
each file is one story in the light theme. Each commit message starts with the
bb-plugins commit it was taken from and links to it.

To see how a story changed, look at the history of its file:

```sh
git log -p --follow review-sweep/review-list--baseline.png
```

Nothing here is edited by hand. `npm run screenshots` in bb-plugins writes
every file and removes the images of stories that no longer exist. Its
changes are committed only after each changed image has been checked for
private information, as AGENTS.md describes.
