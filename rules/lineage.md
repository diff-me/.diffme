# forks and inbound Refs:, linked sources counted once

A post's lineage is what took it up: the repositories whose posts reference it with `Refs:`, those that hold a live fork of it, and, where Explore reads them, those that vouch for it. A repository never counts for its own posts, nor while it is suspended, and a `Refs:` naming a page outside diff.me is recorded but is never an edge.

Two tests keep volume from buying rank. The component test: repositories joined to one another by references, forks or vouches count once between them. Push-time evidence: a repository counts only when diff.me observed its first push at least `fresh_hours` hours before its first reference, fork or vouch of the post.

The lineage order, which search reads after exact strings, weighs the counts as below over the whole corpus, without decay and without vouches.

```diff-me-rule
{"refs":1,"forks":1,"fresh_hours":1}
```
