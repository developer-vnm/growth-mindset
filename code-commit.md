# Code Commit

## Purpose

To improve readability and traceability, commit messages should be:

- `Human-readable`: messages should clearly explain the purpose of the change.
- `Linked to work tickets`: commit messages should include associated ticket number to streamline tracking.

## Follow Convention

- `<type>(<scope>): [#ticket] <commit message>`
    - Commit message with scope and working ticket: feat(`<scope>`): [`#ticket`] create todo API
- `feat`: introduces a new feature.
- `test`: adds or corrects tests, including unit tests (UT), integration tests (IT)
- `fix`: fixes a bug
- `style`: code formatting, sonar code smell
- `docs`: document only changes
- `refactor`: code changes that neither fixes a bug nor adds a new feature
- `perf`: a code change that improve performance
- `chore`: update CI, configuration

## Example

- feat(voucher-promotion): [#123456] implement promotional voucher listing API
- test(standalone-insurance): [#123467] add insurance creating UT
- test(credit-card-cir17): [#123489] add fully KYC verification result IT
- style(voucher-promotion): [#123478] sonar code smell - remove unsued import
- docs(voucher-promotion): [#123512] promotional voucher listing communication diagram
- chore(ci): update azure pipelies to support Sonar
- chore(application): define environment variables


## Azure DevOps

- `<scope>`:  use the name of the primary feature linked to the user story.
    - Hierarchy: `Task (Backend, Frontend, QC)` -> `User Story (Sprint Delivery)` -> `Feature (Team Delivery)` -> `Epic (Project Delivery)`
- `<ticket>`: use working user story. 
    - Including `#` + user story in the commit will automatically link it to the PR and User Story.

## References

- [Conventional Commits V1.0.0](https://www.conventionalcommits.org/en/v1.0.0/)