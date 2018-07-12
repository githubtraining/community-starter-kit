{% if private %}
Your project doesn't have a `README.md` file. Even though your project might be private, that doesn't mean the `README.md` file isn't useful. The `README.md` file can inform other contributors that you invite to your project how to work on the project, display badges from GitHub Integrations that display the health or status of the project, and more.
{% else %}
Your project doesn't have a `README.md` file. A `README.md` file is useful for telling other people why your project is useful, what they can do with your project, how they can use it, and more importantly, how they can contribute to your project.
{% endif %}

A `README` is often the first item a visitor will see when visiting your repository. `README` files typically include information on:

- What the project does
- Why the project is useful
- How users can get started with the project
- Where users can get help with your project
- Who maintains and contributes to the project

### :keyboard: Activity: Adding a README

{% if private %}
1. Access the [**Code**](https://github.com/{{ user.username }}/github-move/) tab of your project.
1. Below the list of files in your project is a notification reading: "Add a README with an overview of your project.", click the **Add a README** button found within that notification
1. Edit the new README file to describe your projects, using the bullet points listed above :point_up:
1. After editing the README file, scroll down and click the **Commit new file** button.

    > This is committing your README file directly to `master`. Normally, you would create a pull request when making changes to your projects, but README files are very important on GitHub.

{% else %}
1. Access the [Community profile pane](https://github.com/{{ user.username }}/github-move/community)
1. Click the **Add** button on the README row.
1. Edit the new README file to describe your projects, using the bullet points listed above :point_up:
1. After editing the README file, scroll down and click the **Commit new file** button.

    > This is committing your README file directly to `master`. Normally, you would create a pull request when making changes to your projects, but README files are very important on GitHub.

{% endif %}

<hr>
<h3 align="center">I won't respond to this issue, just close it when you are done!</h3>
