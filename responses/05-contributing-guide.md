A contributing guide provides important information to those who may be interested in helping you with your project. Without a contributing guide, they might not know what you need help with, how they can get started, or how you like to communicate.

{% if private %}
Although a contributing guide is typically found in Open Source projects, it can be useful for private projects as well. The contributing guide provides a quick reference for project contributors to the expectations when make contributions to the project. Even a the most veteran contributor to your project might forget how you handle a specific action item if it doesn't get dealt with very often. Having processes documented in your contributing guide makes working on your project easier for everyone.
{% else %}
Providing the baseline expectations for a contribution to your project makes it much easier for a new user to contribute to the growth and development of your project. Identifying the processes that you expect to be followed when creating contributions to your project helps reduce the hesitation a new contributor might feel when adding a new contribution because what you are looking for in a contribution is well laid out. The contributing guide is helpful for veteran contributors as well, as it provides a reference point for their review if they are contribting to an area of the project they hadn't previously worked with.
{% endif %}

### :keyboard: Activity: Adding Contributing guidelines

{% if private %}
1. Access the [**Code**](https://github.com/{{ user.username }}/community-starter-kit/) tab of your project
1. Click the **Create new file** button
1. Name your new file `CONTRIBUTING.md`
1. Modify your new file with contributing guidelines for your project, for ideas on what should be included in a contributing guidelines file, read [this stellar documentation](https://help.github.com/articles/setting-guidelines-for-repository-contributors/)
1. After editing your file click the **Commit new file** to commit your `CONTRIBUTING.md` file directly to your `master` branch.
{% else %}
1. Access the [Community profile pane](https://github.com/{{ user.username }}/community-starter-kit/community)
1. Click the **Add** button on the Contributing row
1. Modify your new file with contributing guidelines for your project, for ideas on what should be included in a contributing guidelines file, read [this stellar documentation](https://help.github.com/articles/setting-guidelines-for-repository-contributors/)
1. After editing the `CONTRIBUTING.md` file, scroll down and click the **Commit new file** button.

    > This is committing your `CONTRIBUTING.md` file directly to `master`.

{% endif %}

<hr>
<h3 align="center">I won't respond to this issue, just close it when you are done!</h3>
