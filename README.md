# github-actions-workflows
Examples of GitHub Actions Workflows for various use cases

## Workflows

### Trigger Workflow for Comment on Pull Request
Workflow: [deploy-on-comment.yml](.github/workflows/deploy-on-comment.yml)

Event: `issue_comment`

Run the workflow when a specific comment is made on a pull request. The workflow will only run if the comment contains the string `/deploy`.

See this [PR](https://github.com/zirkelc/github-actions-workflows/pull/2) for an example.