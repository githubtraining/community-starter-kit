# Community Starter Kit

This file contains the course flow for the "Protected Branches and CODEOWNERS" course.

### User Registration
- Before registration, a description of the class and the recommended prerequistes will be available.
- On registration, the app will create a repository for the user based on [this template](https://github.com/githubtraining/community-starter-kit).
- Once the repository is created, the app will [create an issue with the first set of instructions](responses/01_add_topics.md).  

## Activity 1: Add topics to repository

| Student action | App response |
| -------------- | ------------ |
| nothing | App creates issue using [this](responses/01_add_topics.md) |
| student adds at least one label to the repository | on success: app uses [this](responses/01r_add_topics.md); on fail: app uses [this](responses/01e_add_topics.md) |


## Activity 2: Add labels to repository

| Student action | App response |
| -------------- | ------------ |
| successfully completed activity 1 | app creates new issue using [this](02_targeted_labels.md) |
| following instructions from [this](02_targeted_labels.md), student adds labels to the repository  | on fail app uses [this](responses/02e_targeted_labels.md)  ; on success app uses [this](responses/02e_targeted_labels.md) |

## Activity 3: Add repository description

| Student action | App response |
| -------------- | ------------ |
| successfully completed activity 2 | app creates issue using [this](responses/04_repository_description.md) if no repo description exists, if a repo description exists use [this](responses/08-description-update.md) |
| student modifies the repository description | on fail app uses [this](responses/04e_repository_description.md) ; on success app uses [this](responses/04r_repository_description.md) |

## Activity 4: Open Ended Adventure

| Student action | App response |
| -------------- | ------------ |
| success on activity 3 | app opens issue with [this](responses/05_other_repository_files.md)  |
| student closes the issue | app opens issues with the following content (if the file doen't exist, use the 'new', if the file does exist use the 'update'): [code of conduct](responses/08-collabs-code-new.md), [contributing guide](responses/08-collabs-contributing-new.md), [license](responses/08-license-new.md), [readme](responses/08-collabs-readme-new.md), and [templates](responses/08-collabs-templates-new.md), app also opens [closing](responses/09_advertising_your_repo.md) |