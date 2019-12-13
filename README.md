# Get-Branch-Name Github Action

This action outputs the current branch name and corresponding tag.

## Outputs
### `branch`
The current branch name.

### `tag`
The corresponding tag name. If `master` -> `latest`, `branch-name` for the others.

## Example usage
```
uses: ypicard/get-branch-name-github-action@v1
```