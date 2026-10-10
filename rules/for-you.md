# watched refs, ranked by forks and inbound Refs:, time-decayed

For You is the top of Following: the same posts, from the handles and paths you watch, ranked by what got taken up and built on. A post scores the repositories that reference it with `Refs:` and those that hold a live fork of it, counted as `rules/lineage.md` counts them, each weighed as below, plus the prior; the score halves every `half_life_hours` hours after the post was first published. Equal scores order newest first.

Only posts first published within the window are ranked; the rest of Following is still there, newest push first. Vouches do not rank For You: Explore is where they count.

```diff-me-rule
{"refs":1,"forks":1,"prior":0,"half_life_hours":24,"window":"week"}
```
