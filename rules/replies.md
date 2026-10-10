# replies render under their post, unless push-time evidence declines them

A reply lives in its author's repository and renders under the post it references. diff.me declines to render one there only on push-time evidence: when it observed the replying repository's first push less than `fresh_hours` hours before the reply, and the forge created that repository in an hour in which it created at least `cluster_at_least` bound public repositories, that one included.

Every such judgement is published in the action log of the post's author and of the replier, with the shape that produced it. The notice under the post states the count and links each declined reply, which stays at its own address.

```diff-me-rule
{"fresh_hours":1,"cluster_at_least":9}
```
