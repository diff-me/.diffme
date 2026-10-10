# a repository unreachable for a day becomes an inbox event

The feed states a watched repository's failed fetches at once, where its posts would be. When fetching it has failed for `after_hours` hours without a success, the failure also reaches the inbox, once.

```diff-me-rule
{"after_hours":24}
```
