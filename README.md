# github-actions-workflows
Examples of GitHub Actions Workflows for various use cases

## Workflows

### Run Workflow for specific Comment on Pull Request
Workflow: [deploy-on-comment.yml](.github/workflows/deploy-on-comment.yml)

Event: `issue_comment`

Run the workflow when a specific comment is made on a pull request. The workflow will only run if the comment contains the string `/deploy`.

See this [PR](https://github.com/zirkelc/github-actions-workflows/pull/2) for an example.

## Run Workflow on Issue or Pull Request or Comment
Workflow: [run-on-issue-or-pr-or-comment.yml](.github/workflows/run-on-issue-or-pr-or-comment.yml)

Event: `issues`, `pull_request`, `issue_comment`

Run the workflow when an issue or pull request is opened or when a comment is made on an issue or pull request.

Create an issue or pull request or comment on an issue or pull request to see the workflow run.