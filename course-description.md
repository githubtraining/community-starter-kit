# Community Starter Kit

This file contains the course flow for the "Community Starter Kit" course.

### User Registration
- Before registration, a description of the class and the recommended prerequistes will be available.
- On registration, the app will create a repository for the user based on [this template](https://github.com/githubtraining/community-starter-kit-template).
- Once the repository is created, the app will create an issue an introduction `responses/01-welcome-story.md` and a follow up comment introducing the first activity `responses/01a-add-description.md`.  

## Step 1: Add a repository description

| Student action | App response |
| -------------- | ------------ |
| user closes issue 1 | on success: app opens a new PR using branch `add-readme` and `responses/02-create-readme.md`, leaves comment in issue 1 using `01n-next.md` directing user to PR |

## Step 2: Add a README

| Student action | App response |
| -------------- | ------------ |
| user edits README file | app looks for placeholder text `DESCRIPTION PLACEHOLDER`. If present, comments on PR with `responses/02a-readme-description.md` and waits for another edit |
|  | app looks for placeholder text `FEATURES PLACEHOLDER`. If present, comments on PR with `responses/02b-readme-features.md` and waits for another edit |
|  | If neither placeholder text is present, comment on PR with `responses/02c-readme-done.md` |
| user merges PR | app waits for merge, opens the next PR using branch `add-docs` and `responses/03-add-docs.md`, leaves comment in step 2 PR with `responses/02n-next.md` directing user to next PR |

## Step 3: Add user documentation

| Student action | App response |
| -------------- | ------------ |
| user edits getting-started.md file | app looks for placeholder text `CONFIGS PLACEHOLDER`. If present, comments on PR with `responses/03a-docs-configs.md` and waits for another edit |
|  | If placeholder text is not present, comment on PR with `responses/03b-docs-done.md` |
| user merges PR | app waits for merge, opens the next PR using branch `add-issue-template` and `responses/04-helping-contributors.md`, leaves comment in step 3 PR with `responses/03n-next.md` directing user to next PR |

## Step 4: Adding issue templates

| Student action | App response |
| -------------- | ------------ |
| user adds new .github/ISSUE_TEMPLATE/bug-report.md file | app checks file path, if incorrect comments on PR with `responses/04a-template-location.md` and waits for another edit |
|  | If path is correct, comment on PR with `responses/04b-template-done.md` |
| user merges PR | app waits for merge, opens the next PR using branch `add-contrib-guide` and `responses/05-contributing-guide.md`, leaves comment in step 4 PR with `responses/04n-next.md` directing user to next PR |


## Step 5: Add a CONTRIBUTING guide

| Student action | App response |
| -------------- | ------------ |
| user edits CONTRIBUTING.md file | app looks for placeholder text `DESCRIPTION PLACEHOLDER`. If present, comments on PR with `responses/05a-contributing-labels.md` and waits for another edit |
|  | If placeholder text is not present, comment on same PR with `responses/06-add-labels.md` and mark step 5 complete |

## Step 6: Add labels

| Student action | App response |
| -------------- | ------------ |
| user adds a label to PR | app adds comment `responses/06a-label-done.md` and waits for merge |
| user merges PR | app opens the next PR using branch `add-license` and `responses/07-add-license.md`, leaves comment in step 6 PR with `responses/06n-next.md` directing user to next PR |

## Step 7: Add license

| Student action | App response |
| -------------- | ------------ |
| user edits LICENSE.md file | app looks for placeholder text `[year]` and `[fullname]`. If present, comments on PR with `responses/07a-replace-placeholders.md` and waits for another edit |
|  | If placeholder text is not present, comment on same PR with `responses/07b-license-done.md` and await merge |
| user merges PR | app opens the next PR using branch `add-code` and `responses/08-code-of-conduct.md`, leaves comment in step 7 PR with `responses/07n-next.md` directing user to next PR |

## Step 8: Add code of conduct

| Student action | App response |
| -------------- | ------------ |
| user edits code-of-conduct.md file | app looks for placeholder text `CONTRIBUTOR CODE`. If present, comments on PR with `responses/08a-replace-placeholders.md` and waits for another edit |
|  | If placeholder text is not present, comment on same PR with `responses/08b-code-done.md` and await merge |
| user merges PR | app opens an issue with text from `responses/09-make-it-visible.md`, leaves comment in step 8 PR with `responses/08n-next.md` directing user to issue |

## Step 9: Add topics

| Student action | App response |
| -------------- | ------------ |
| user closes issue | app comments on issue with `responses/10-finish.md` |
