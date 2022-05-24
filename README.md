# Nothing AG work contract

This repository contains the [work contract template](./work_contract.md) of Nothing AG.

Branches are created for the work contract of each crew member.

Only the _protected_ branches are mirrored on GitHub.

## Set a contract for a new crew member

- Create a new branch `crew-member/{crewMemberFirstName}`
  - From `master` for a part-time or full-time contract
  - From a `alt/*` branch for another type of contract
  - **Do not** protect this new branch
- Edit `work_contract.md` in the branch
  - Replace all the placeholders with the contract values
  - The placeholders are in between curly braces: `{}`
  - Don't keep the curly braces

## Update an existing contract with a newer version of the template

- Merge the branch `master` into the branch `crew-member/{crewMemberFirstName}` of the contract you want to update
- Resolve conflicts if there is any

## Export a PDF of a contract

Many markdown apps allow to export a PDF of a rendered markdown file.
They either have a dedicated export function, or it can be done through the print prompt of macOS.

In order to have a consistent result, we suggest doing it the following way:

- Open the contract with [Typora](https://typora.io/)
- Select the [Nothing theme](https://galaxy.nothing.ch/nin/typora-theme)
- Export into PDF by going in the menu _File_ > _Export_ > _PDF_
  - If some margins seem to be too large, you can set custom ones in the _Export_ settings of Typora.

## License

<a rel="license" href="http://creativecommons.org/publicdomain/zero/1.0/">
  <img src="http://i.creativecommons.org/p/zero/1.0/88x31.png" alt="CC0" />
</a>

To the extent possible under law, Nothing AG has waived all copyright and related or neighboring rights to [this work contract template](./work_contract.md). This work is published from Switzerland.

**© The [Nothing logo](./nothing_logo.md) keeps an _all rights reserved_ copyright to Nothing AG.**
