# every public post, newest push first

The all source, the signed-out home and `all.atom`, shows every post in every public repository diff.me has read, newest push first. It is not ranked, and it is not limited to the handles you watch. A push is ordered by its effective time: the earlier of its committer date and the moment diff.me first observed it, so a commit dated in the future does not sort above everything else, and history pushed late does not arrive as new.

A post appears once, at its newest version, and an amend brings it back to the top.

```diff-me-rule
{"one_row_per_post":true,"amend_resurfaces":true}
```
