# one slot a day: the newest post no path from your graph reaches

Explore holds one slot, and only one, from outside your graph: the newest post first published within the window that no path of at most `reach` references and forks from the posts you watch reaches, by an author you do not watch. It is chosen by that fact, never by a score, and a reader who watches nothing gets no slot. It never enters the feed.

```diff-me-rule
{"reach":2,"window":"day"}
```
