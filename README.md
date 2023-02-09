# Secrets manager
Update secrets across multiple github repositories.

To update a secret value, update it in this repository's secrets.

To add a new secret, add it in this repository's secrets then update the `secret_name` list in `.github/workflows/update-secrets.yaml`. 

To add a new repository, update the `repo` list in `.github/workflows/update-secrets.yaml`.
