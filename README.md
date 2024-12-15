# GitHub Actions

Examples of GitHub Actions and Workflows for typical use cases.

Feel free to submit a PR to add your own examples.

## Actions

- [tj-actions/changed-files](https://github.com/tj-actions/changed-files): Get the list of changed files in a pull request

- [wearerequired/lint-action](https://github.com/wearerequired/lint-action): Run linters like ESLint and TypeScript.

## Events

### `issue_comment`

#### Comment on Pull Request
Workflow: [comment-on-pull-request.yml](.github/workflows/comment-on-pull-request.yml)

Run the workflow when a specific comment is made on a pull request. The workflow will only run if the comment contains the string `/deploy`.

See this [PR](https://github.com/zirkelc/github-actions-workflows/pull/2) for an example.


## Workflows

### Linting

- [ESLint](.github/workflows/lint-eslint.yml)
- [Biome](.github/workflows/lint-biome.yml)

