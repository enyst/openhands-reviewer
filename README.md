# openhands-reviewer

This repository only contains the GitHub App configuration used by the OpenHands PR reviewer GitHub Actions workflow.

## GitHub App

See: `.github/github-app-manifest.json`

### Recommended secret names

When using `actions/create-github-app-token@v1` (as in agent-sdk PR #22), store these in the repo/org secrets of the repository running the PR-review workflow:

- `OH_REVIEWER_APP_ID`
- `OH_REVIEWER_APP_PRIVATE_KEY`
