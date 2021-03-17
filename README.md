# How to use this project

## Installation

- Add the DefinitelyTyped remote as upstream via `git remote add upstream https://github.com/DefinitelyTyped/DefinitelyTyped.git`

## Updating Scrivito Types

- Checkout `definitely-typed`
- Fetch upstream
- Rebase current onto upstream via `get rebase upstream/master`
- Change whatever you need
- Add your name to the contributors in `types/scrivito/index.d.ts`
- Install dtslint, lint your changes and fix
- Create a PR in DefinitelyTyped and reference this branch
- Follow DefinitelyTyped procedures
