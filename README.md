# github-actions-workflows
Examples of GitHub Actions Workflows and Actions for various use cases

## Workflows

### Run Workflow for specific Comment on Pull Request
Workflow: [deploy-on-comment.yml](.github/workflows/deploy-on-comment.yml)

Event: `issue_comment`

Run the workflow when a specific comment is made on a pull request. The workflow will only run if the comment contains the string `/deploy`.

See this [PR](https://github.com/zirkelc/github-actions-workflows/pull/2) for an example.

### Run Workflow on Issue or Pull Request or Comment
Workflow: [issue-pr-comment.yml](.github/workflows/issue-pr-comment.yml)

Event: `issues`, `pull_request`, `issue_comment`

Run the workflow when an issue or pull request is opened or when a comment is made on an issue or pull request.

Create an issue or pull request, or comment on an issue or pull request to see the workflow run.
Then, go to the [Actions](https://github.com/zirkelc/github-actions-workflows/actions/workflows/issue-pr-comment.yml) tab to see the workflow run.

## Actions

### Write GitHub Event to Workflow Summary
Action: [event-summary](.github/actions/event-summary.yml)

Write the GitHub event to the workflow summary. See the following links for more information:
- [Adding a Job Summary](https://docs.github.com/en/actions/using-workflows/workflow-commands-for-github-actions#adding-a-job-summary)
- [Supercharging GitHub Actions with Job Summaries](https://github.blog/2022-05-09-supercharging-github-actions-with-job-summaries/)