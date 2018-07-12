# Protected Branches and CODEOWNERS

This README contains the course flow for the "Protected Branches and CODEOWNERS" course.

### User Registration
- Before registration, a description of the class and the recommended prerequistes will be available.
- On registration, the app will create a repository for the user based on [this template](https://github.com/githubtraining/protected-branches-codeowners.git).
- Once the repository is created, the app will [create an issue with the first set of instructions](/responses/01_introduction-issue.md).  
- Repository needs to have `@githubstudent` as a collaborator

Changes to make to outline

1. App sets up repo, opens a PR with a CODEOWNERS file requesting the user’s review
2. App asks user to turn on branch protections
3. User turns on branch protections, sees their effect on the PR
4. User submits a review approval
5. App merges
6. App opens an issue asking the user to modify the CODEOWNERS by adding @github-learning-lab
7. User modifies CODEOWNERS, opens PR
8. App merges the PR.
9. User modifies README.
10. GitHub requests a review from @github-learning-lab
11. App submits approval on behalf of @github-learning-lab
12. User merges PR.

## Activity 1: Enable Protected Branches

| Student action | App response |
| -------------- | ------------ |
| background step | App sets up repo, opens a PR with a [CODEOWNERS file](assets/CODEOWNERS) requesting the user's review. App responds on PR with directions for enabling protected [branches](/responses/02_enable_protection.md) |
| User enables protected branches based on instructions | Enable protected branches: App responds with text from [this](/responses/03_enabled_protection.md) |
| User approves PR | App merges PR, app creates new issue based on [this](/responses/04_reviews_by_codeowners.md)


## Activity 2: Adding CODEOWNERS

| Student action | App response |
| -------------- | ------------ |
| User creates a branch, modifies a file that will kick off a review request using the CODEOWNERS file, creates PR | App responds with this [review](/responses/05_peer_review.md)
| background step | App approves the PR | 
| User merges PR | App responds with [ending](/responses/06_graceful_exit.md) 

## Activity 3: Using CODEOWNERS

| Student action | App response |
| -------------- | ------------ |
| User creates a branch, modifies a file that will kick off a review request using the CODEOWNERS file, creates PR | insert |
| background step | insert | 
| User merges PR | insert |

