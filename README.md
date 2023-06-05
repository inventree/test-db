# test-db

Repository containing active test databases used for codebase CI testing

- The sqlite database is kept up to date with the latest migrations from the InvenTree project.
- On a PR to the InvenTree project, this repo is pulled down, and any new (or updated) migrations are applied
- This checks to ensure that that the new migrations will not break a production database
- When the PR is merged, the applied database changes are pushed back to this repository
