# Project contribution guide

## Documentation

Keep related project documentation aligned with changes and link it to the feature.

## Review

Ask a project maintainer to review changes before merging.

Client-specific rule: payment-related changes require a payments maintainer review.
Client-specific rule: do not modify production configuration during documentation work.

## Local conventions

Document the adopting team's local conventions in a dedicated section before merging updates.

## Agentic routing

For payment-related tasks, start with the payments maintainer and the client API.
For incident analysis, consult docs/run/ before changing application code.
Keep our client-specific routing rules; do not replace them with generic defaults.
