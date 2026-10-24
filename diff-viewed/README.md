<!-- Written by `npm run screenshots` in bb-plugins. Edit the stories there, not this file. -->

# Diff Viewed Enhanced

Adds a viewed count and GitHub sync to bb's own Viewed checkboxes, so you can see how much of a long diff you've read.

Source: [`bb-plugin-diff-viewed`](https://github.com/danielbachhuber/bb-plugins/tree/main/bb-plugin-diff-viewed)

## Changes panel

### Viewed

Three files checked Viewed in bb fold away, the unread file below them stays open, and the toolbar counts 3/6 viewed. Every file here syncs with the pull request, so none shows the Local icon.

![Viewed](changes-panel--viewed.png)

### Local

src/pricing.ts has edits that are not pushed, so its diff here differs from the pull request's. Its mark is Local, shown by the crossed-out cloud after the checkbox, and stays in bb until a push makes the diffs match.

![Local](changes-panel--local.png)

### No pull request

A thread with no open pull request: every mark is Local, checked or not, and goes to GitHub once a pull request with the same diff is opened.

![No pull request](changes-panel--no-pull-request.png)

### Loading

While GitHub is still answering: bb's checkboxes show its marks at once, a spinner holds the Local icon's place, and the viewed count stays muted.

![Loading](changes-panel--loading.png)
