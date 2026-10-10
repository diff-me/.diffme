# ranked by lineage and vouches — what your watched refs cite, then what those cite

Explore walks out from the posts you watch: what they reference or fork, then what those reference or fork, up to `hops` steps, the nearer first. Within a step, and for a reader who watches nothing, posts are ranked by lineage and by the vouches they received: the repositories that reference a post with `Refs:`, hold a live fork of it, or vouch for it, counted as `rules/lineage.md` counts them, each weighed as below, plus the prior; the score halves every `half_life_hours` hours after the post was first published. Equal scores order newest first.

Only posts first published within the window are ranked, and an unqueried Explore reads that window. No row says why it is there. This is the one ranking vouches enter.

```diff-me-rule
{"refs":1,"forks":1,"vouches":1,"prior":0,"half_life_hours":24,"window":"week","hops":2}
```
