# Nothing AG work contract

This repository contains the [work contract template](./work_contract.md) of Nothing AG.

Branches are created for the work contract of each robot.

Only the `master` branch is mirrored on GitHub.

## Set a contract for a new robot

- Create a new branch `robot/{robotName}`
- Edit `work_contract.md` in the branch
  - Replace all the placeholders with the contract values
  - The placeholders are in between curly braces: `{}`
  - Don't keep the curly braces

## Update an existing contract with a newer version of the template

- Merge the branch `master` into the branch `robot/{robotName}` of the contract you want to update
- Resolve conflicts if there is any