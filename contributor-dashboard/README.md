<!-- Written by `npm run screenshots` in bb-plugins. Edit the stories there, not this file. -->

# Contributor Dashboard

A dashboard of how people contribute to one GitHub repository, from a local mirror of its pull requests, reviews and issues. The page opens with the flow of stages work passes through, from Triage and Assign ownership on issues to Implement change, Prepare pull request, Code review and Merge decision on pull requests, each with how many are in it now and the median, p75 and p90 of how long it takes, and clicking a stage lists what is in it. Its Review Velocity section charts for each person the reviews requested of them and the reviews they gave, week by week, and clicking a name opens that person's page.

Source: [`bb-plugin-contributor-dashboard`](https://github.com/danielbachhuber/bb-plugins/tree/main/bb-plugin-contributor-dashboard)

## Page

### Six weeks

Six weeks, the default: one small chart per person, alphabetical, all on one scale.

![Six weeks](page--six-weeks.png)

### Six weeks hovered

Hovering a week shows that week's requested and given counts.

![Six weeks hovered](page--six-weeks-hovered.png)

### One year

A year, drawn by month.

![One year](page--one-year.png)

### First sync

The first sync, still reaching back two years; the charts fill in as pages arrive.

![First sync](page--first-sync.png)

### No repository

Before a repository is set.

![No repository](page--no-repository.png)

### Sync failed

A sync that failed, such as gh not being signed in.

![Sync failed](page--sync-failed.png)

### Person page

One person's page, reached by clicking their name on the dashboard.

![Person page](page--person-page.png)

### Person page paged

A prolific author: their pull requests page 25 at a time.

![Person page paged](page--person-page-paged.png)

### Person page quiet

Nobody is waiting on them and they have opened nothing this period.

![Person page quiet](page--person-page-quiet.png)

### Stage page

One stage's page: how long it took, how long the queue has waited, what is in it, and each week.

![Stage page](page--stage-page.png)

### Stage page clear

A stage with nothing waiting: the queue chart is empty and the list says so.

![Stage page clear](page--stage-page-clear.png)
