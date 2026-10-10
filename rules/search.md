# exact strings first, then lineage

Search puts first the posts that hold the exact string you typed, then orders by the lineage order of `rules/lineage.md`, newest first among equals. The pickaxe, `-S` and `-G`, selects posts; it does not rank them.

```diff-me-rule
{"tiers":["exact","lineage"]}
```
