# release-train

## How to use

Copy setup considering yours branch names
-  .release-please-{branch_name}-config.json
-  manifest-{branch_name}.json

You can use the many branches as your project needs.


Copy github workflows
- create-release-pr.yml
- release-please.yml

Ajust your github token, for `PERSONAL_ACCESS_TOKEN`


1. Pull Requests

- Open the PR
- Edit the title using the conventional commits
    <feat/fix>: <JIRA_ID> short description
- Squash the merge


2. Release

- Merge the release created on `create-release-pr`