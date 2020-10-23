## Importance of documentation

Good documentation is key to the success of any project. Making documentation accessible enables people to learn about a project; making it easy to update ensures that documentation stays relevant.

- For contributors
- For users

Two common ways to document a project are *README files* and *wikis*:

- README files are a quick and simple way for other users to learn more about your work.
- Wikis on GitHub help you present in-depth information about your project in a useful way.

It’s a good idea to at least have a README on your project, because it’s the first thing many people will read when they first find your work.

source: guides.gtihub.com

## Issue Templates

 

You can customize the templates that are available for contributors to use when they open new issues in your repository.

You can create default issue templates and a default configuration file for issue templates for your organization or user account. For more information, see "[Creating a default community health file](https://docs.github.com/en/free-pro-team@latest/github/building-a-strong-community/creating-a-default-community-health-file)."

### **[Creating issue templates](https://docs.github.com/en/free-pro-team@latest/github/building-a-strong-community/configuring-issue-templates-for-your-repository#creating-issue-templates)**

1. On GitHub, navigate to the main page of the repository.
2. Under your repository name, click  **Settings**.

    ![https://docs.github.com/assets/images/help/repository/repo-actions-settings.png](https://docs.github.com/assets/images/help/repository/repo-actions-settings.png)

3. In the "Features" section, under "Issues," click **Set up templates**.

    ![https://docs.github.com/assets/images/help/repository/set-up-templates.png](https://docs.github.com/assets/images/help/repository/set-up-templates.png)

4. Use the Add template drop-down menu, and click on the type of template you'd like to create.

    ![https://docs.github.com/assets/images/help/repository/add-template-drop-down-menu.png](https://docs.github.com/assets/images/help/repository/add-template-drop-down-menu.png)

5. To preview or edit the template before committing it to the repository, click **Preview and edit**.

    ![https://docs.github.com/assets/images/help/repository/preview-and-edit-button.png](https://docs.github.com/assets/images/help/repository/preview-and-edit-button.png)

6. To edit the template, click , and type in the fields to edit their contents.

    ![https://docs.github.com/assets/images/help/repository/issue-template-edit-button.png](https://docs.github.com/assets/images/help/repository/issue-template-edit-button.png)

7. To automatically set a default issue title, assign the issue to people with read access to the repository, or apply labels to your issue template, enter these details under "Optional additional information." You can also add these details in the issue template with `title`, `labels`, or `assignees` in a YAML frontmatter format.

    ![https://docs.github.com/assets/images/help/repository/additional-issue-template-info.png](https://docs.github.com/assets/images/help/repository/additional-issue-template-info.png)

8. When you're finished editing and previewing your template, click **Propose changes** in the upper right corner of the page.

    ![https://docs.github.com/assets/images/help/repository/propose-changes-button.png](https://docs.github.com/assets/images/help/repository/propose-changes-button.png)

9. Enter a commit message describing your changes.

    ![https://docs.github.com/assets/images/help/repository/issue-template-commit-message-field.png](https://docs.github.com/assets/images/help/repository/issue-template-commit-message-field.png)

10. Below the commit message fields, decide whether to commit your template directly to the default branch, or to create a new branch and open a pull request. For more information about pull requests, see "[About pull requests](https://docs.github.com/en/free-pro-team@latest/articles/about-pull-requests)."

    ![https://docs.github.com/assets/images/help/repository/issue-template-commit-to-master-or-open-pull-request.png](https://docs.github.com/assets/images/help/repository/issue-template-commit-to-master-or-open-pull-request.png)

11. Click **Commit changes**. Once these changes are merged into the default branch, the template will be available for contributors to use when they open new issues in the repository.

Source: Github docs
