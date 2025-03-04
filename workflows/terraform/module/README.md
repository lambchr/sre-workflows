# Terraform Module

The workflows in this directory are used to automatically release Terraform
modules.

## `readme.yaml`

Automatically updates the `README.md` files of each module within a given
directory, this can be used on push or pull request events.

## `validate.yaml`

Run a series of Terraform commands on each module with changed files within a
pull request to ensure the module is syntacically correct.
