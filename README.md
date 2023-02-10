# Secrets manager
Update secrets across multiple github repositories.

To **update** a secret value, update it in this repository's secrets and trigger the workflow manually.

To **add** a new secret, add it in this repository's secrets then update the `secret_name`
list of the `update_secrets` job in `.github/workflows/update-secrets.yaml`.

To **delete** a secret, update the `secret_name` list of the `delete_secrets` job in
`.github/workflows/update-secrets.yaml`.

To add a new repository, update the `repo` lists of both jobs in `.github/workflows/update-secrets.yaml`.

## Setup pre-commit
```shell
pipx install pre-commit
pre-commit install
```
