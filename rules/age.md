# 16 or older to sign up; only the yes is kept

Signing up asks whether you are at least `minimum_years` old, the age GDPR Article 8(1) sets for a person's own consent to an online service. The page you sign up on compares the date you give with it, and the date goes no further: diff.me keeps the yes and this rule's version, never the date.

```diff-me-rule
{"minimum_years":16}
```
