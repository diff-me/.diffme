# a suspended handle is not rendered; nothing it owns is touched

A suspension targets a handle, and keeps applying after the handle changes. diff.me stops rendering the handle's posts, replies and vouched work, which show as their addresses, and the direct messages it wrote, which no one it wrote to is shown while the suspension stands, and touches nothing in its repositories. Every suspension is published in the action log with this rule's version.

```diff-me-rule
{"stops_rendering":true,"touches_repository":false}
```
