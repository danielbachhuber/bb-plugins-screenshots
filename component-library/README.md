<!-- Written by `npm run screenshots` in bb-plugins. Edit the stories there, not this file. -->

# component-library

UI that several plugins draw the same way, starting with the sync status in a page's title bar.

Source: [`component-library`](https://github.com/danielbachhuber/bb-plugins/tree/main/component-library)

## Segmented

### States

Segmented picks one of a few choices, such as a period; one is always on. SegmentedToggle filters a list, and pressing the chosen option again turns the filter off.

![States](segmented--states.png)

## Sidebar count

### States

The counts beside a page's name in the sidebar: the rows that need you most in a red circle, those due today in an amber one when the page counts them, then every row.

![States](sidebar-count--states.png)

### Aligned

Rows with and without a circle, one above the other: the totals line up because each keeps a box at least 20px wide.

![Aligned](sidebar-count--aligned.png)

### Levels

Counts of rows past a warning, in amber, and past an error, in red, for a page with no total to show.

![Levels](sidebar-count--levels.png)

## Sync status

### States

Every label the control can show, from no sync yet to days old, and the button while a refresh runs.

![States](sync-status--states.png)

### In a title bar

Where the control goes: the right end of a page's title bar, across from its name.

![In a title bar](sync-status--in-a-title-bar.png)
