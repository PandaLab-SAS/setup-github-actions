# Setup GitHub Actions

This action set-ups actions from a private repository in the current workspace.

## Usage

### Inputs

**Required**

- `token` (`string`): the token that will be used to checkout the private repository

**Optional**

- `repository` (`string`): the repository that will be checked out
- `ref` (`string`): the reference that will be checked out
- `path` (`string`): the path where the repository will be checked out
