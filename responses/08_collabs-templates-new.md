When you add an issue template and pull request template to your repository, project contributors will automatically see the template's contents in the issue or pull request body. Templates customize and standardize the information you'd like included when contributors open issues. This information can guide contributors to include the information that allows enhancement or bug reports to be reviewed quickly and identify the information that a reviewer would need to succintly review a new pull request.

{% if private %}
Even if you aren't expecting to Open Source your project, Issue and Pull Request templates provide a starting point for other project contributors to use when creating new issues and pull requests. This makes it easier for everyone working on the project to review a new feature or gauge the severity of a bug quickly.
{% else %}
In Open Source projects, these templates make it very easy for a new contributor to your project to create a bug report, suggest a new enhancement, or potentially contribute a change. By identifying what information the new contributor should provide when creating a new issue or pull request, veteran contributors to the project can easily review and move forward with reported bugs, new enhancements, or contributed pull requests.
{% endif %}

### :keyboard: Activity: Adding Issue and Pull Request template files

{% if private %}
Issue and Pull Request templates use the following naming conventions:

     - Issue templates are named: `ISSUE_TEMPLATE.md`
     - Pull Request templates are named: `PULL_REQUEST_TEMPLATE.md`

1. Access the [**Code**](https://github.com/{{ user.username }}/community-starter-kit/) tab of your project.
1. Click the **Create new file** button
1. Name your new file based on the template you are trying to create
1. Modify your template file to include the information you want to automatically populate when a user creates an issue or a pull request, for examples of what to include read [this](https://help.github.com/articles/creating-an-issue-template-for-your-repository/)
1. After editing your file click the **Commit new file** to commit your `CONTRIBUTING.md` file directly to your `master` branch.

    > This is committing your template file directly to `master`.

{% else %}
1. Access the [Community profile pane](https://github.com/{{ user.username }}/community-starter-kit/community)
1. On the Issue or pull request template row, select the **Add** drop down and select **Issue template** or **Pull request template**
1. Edit the new template file to identify how you want issues or pull requests submitted to your project, for suggestions on what should be included in a template file, read [this](https://help.github.com/articles/creating-an-issue-template-for-your-repository/)
1. Afer editing the template file, scroll down and click the **Commit new file** button

    > This is committing your template file directly to `master`.

<details>
  <summary>Add another template file</summary>
  <hr>

  ### Add another template file

  After using the [Community profile pane](https://github.com/{{ user.username }}/community-starter-kit/community) to create a template file, the option to create the other template file isn't displayed. To create the other template file, perform the following steps:

     - Issue templates are named: `ISSUE_TEMPLATE.md`
     - Pull Request templates are named: `PULL_REQUEST_TEMPLATE.md`

  1. On the [Code](https://github.com/{{ user.username }}/community-starter-kit) tab of your project, click the **Create new file** button
  1. Enter the name of the template file your project is missing
  1. Modify your template file to include the information you want to automatically populate when a user creates an issue or a pull request, for examples of what to include read [this](https://help.github.com/articles/creating-an-issue-template-for-your-repository/)
  1. Once you have modified your file, click the **Commit new file** button

    > This is committing your template file directly to `master`.

  <hr>
</details>

{% endif %}

<hr>
<h3 align="center">I won't respond to this issue, just close it when you are done!</h3>
