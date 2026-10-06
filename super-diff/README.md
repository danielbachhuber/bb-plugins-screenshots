<!-- Written by `npm run screenshots` in bb-plugins. Edit the stories there, not this file. -->

# Super Diff

Review a branch one concern at a time. A panel beside the thread groups every hunk on the branch into concerns, each with a summary written by the thread's agent, checks that every hunk appears exactly once, lets you mark files viewed, shows test changes as Gherkin scenarios with what they leave out, and shows exactly what changed when the branch moves on.

Source: [`bb-plugin-super-diff`](https://github.com/danielbachhuber/bb-plugins/tree/main/bb-plugin-super-diff)

## Review panel

### Grouped

Grouped and current: the first concern open, the lockfile set aside.

![Grouped](review-panel--grouped.png)

### Stale

After a commit: the banner, with exactly what changed since the grouping.

![Stale](review-panel--stale.png)

### Not grouped yet

Before any grouping: everything under Not yet grouped, with Generate.

![Not grouped yet](review-panel--not-grouped-yet.png)

### Generating

After Generate, while the agent works.

![Generating](review-panel--generating.png)

### Unavailable

An environment without a git checkout.

![Unavailable](review-panel--unavailable.png)

### No changes

A branch with nothing on it yet.

![No changes](review-panel--no-changes.png)

### Code and tests

A concern that changes code and tests: the code first, then its tests as scenarios under Tests, whose Scenarios and Diff toggle swaps only the test files. The rail counts its scenarios.

![Code and tests](review-panel--code-and-tests.png)

### Test concern

A concern that is only tests: its scenarios listed, the chosen one as Gherkin with recorded values folded until Show values, then what the tests leave out. Diff, beside the title, shows the raw files. The rail tags it "tests".

![Test concern](review-panel--test-concern.png)

### Some viewed

Some files marked viewed: they fold and dim, and the bar and the outline count them.

![Some viewed](review-panel--some-viewed.png)
