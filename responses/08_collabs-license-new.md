{% if private %}
Although your repository is currently private, you might want to review the different licenses available, especially if you are thinking about open sourcing your project. Licenses aren't normally used in private or closed source applications, but they are very important for public or open source project, because they set the rules for how others are allowed to use, change, and contribute to your project.
{% else %}
Your repository is public but there's no License. Licenses are vital in public repositories, because they set the rules for how others are allowed to use, change, and contribute to your project.
{% endif %}

### :keyboard: Activity: Adding a License

{% if private %}
1. Read [this documentation](https://help.github.com/articles/adding-a-license-to-a-repository/) about having a License
1. Add a License to this project using the GitHub Flow
{% else %}
1. Access the [Community profile pane](https://github.com/{{ user.username }}/community-starter-kit/community)
1. Click the **Add** button on the License row.
1. Select a license from the left side of the screen and review the license you selected.
1. Add information to the displayed fields and click the **Review and submit** button.
1. With your file displayed, scroll down and click the **Propose new file** button.

    > This is adding your new file to a new branch that GitHub created for you.

1. With the Open a pull request screen displayed, click the **Create pull request** button.
1. If you are ready to merge (or apply) your file to the project click the **Merge pull request** button. If you want to share this change to your repository with someone, share the URL for this pull request or @ mention them in the comment section.
1. After clicking **Merge pull request**, click **Confirm merge**.
1. Once the merge is complete (it should happen really quickly) delete your branch by clicking **Delete branch**.
{% endif %}

<hr>
<h3 align="center">I won't respond to this issue, just close it when you are done!</h3>
