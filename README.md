# Github CI trigger by PR comment

This repo is a minimum example that:

1. triggers a Github CI job via a PR comment ('/bot tests')
1. updates the PR with the CI job success or failure

See [PR2](https://github.com/luccabb/git-ci-pr-comment-automation/pull/2), you can comment `/bot tests` on the PR and see an example of tests being triggered!

[You can check the relevant CI Job here.](https://github.com/luccabb/git-ci-pr-comment-automation/blob/main/.github/workflows/pr_comment.yml)
