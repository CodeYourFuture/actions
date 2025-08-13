# validate-pr-metadata

This action validates that a PR's metadata is correct, e.g. that its title has the expected format.

It comments on the PR if there are problems.

To use this Action, you should add a step which looks like:

```yaml
- uses: CodeYourFuture/actions/validate-pr-metadata@main
  with:
    GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```
