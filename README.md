# An experiment using husky and lint-staged at different levels

- app is not a package controlled by lerna and has no eslint or tsc failures, and we want husky to prevent new ones being added

- package1 has no eslint and tsc failures and we want husky to prevent new ones being added

- package2 has eslint and tsc failures and we don't care about husky finding them

- all packages should be formatted by prettier on pre-commit and pre-push
