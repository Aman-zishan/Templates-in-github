<img src="https://15daysofhack.github.io/images/tinkerhub.png" />


  <h1 align="center">Importance of documentation and templates in github:sparkles:</h1>


Good documentation is key to the success of any project. Making documentation accessible enables people to learn about a project; making it easy to update ensures that documentation stays relevant.

- For contributors
- For users

Two common ways to document a project are *README files* and *wikis*:

- README files are a quick and simple way for other users to learn more about your work.
- Wikis on GitHub help you present in-depth information about your project in a useful way.

It’s a good idea to at least have a README on your project, because it’s the first thing many people will read when they first find your work.

*source: guides.github.com*

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

*Source: Github docs*

## Pull Request Templates

When you add a pull request template to your repository, project contributors will automatically see the template's contents in the pull request body.

For more information, see "[About issue and pull request templates](https://docs.github.com/en/free-pro-team@latest/articles/about-issue-and-pull-request-templates)."

You can create a *PULL_REQUEST_TEMPLATE/* subdirectory in any of the supported folders to contain multiple pull request templates, and use the `template` query parameter to specify the template that will fill the pull request body. For more information, see "[About automation for issues and pull requests with query parameters](https://docs.github.com/en/free-pro-team@latest/articles/about-automation-for-issues-and-pull-requests-with-query-parameters)."

You can create default pull request templates for your organization or user account. For more information, see "[Creating a default community health file](https://docs.github.com/en/free-pro-team@latest/github/building-a-strong-community/creating-a-default-community-health-file)."

### **[Adding a pull request template](https://docs.github.com/en/free-pro-team@latest/github/building-a-strong-community/creating-a-pull-request-template-for-your-repository#adding-a-pull-request-template)**

1. On GitHub, navigate to the main page of the repository.
2. Above the list of files, using the **Add file** drop-down, click **Create new file**.

    ![https://docs.github.com/assets/images/help/repository/create_new_file.png](https://docs.github.com/assets/images/help/repository/create_new_file.png)

3. In the file name field:
    - To make your pull request template visible in the repository's root directory, name the pull request template `pull_request_template.md`.

        ![https://docs.github.com/assets/images/help/repository/pr-template-file-name.png](https://docs.github.com/assets/images/help/repository/pr-template-file-name.png)

    - To make your pull request template visible in the repository's `docs` directory, name the pull request template `docs/pull_request_template.md`.

        ![https://docs.github.com/assets/images/help/repository/pr-template-file-name-docs.png](https://docs.github.com/assets/images/help/repository/pr-template-file-name-docs.png)

    - To store your file in a hidden directory, name the pull request template `.github/pull_request_template.md`.

        ![https://docs.github.com/assets/images/help/repository/pr-template-hidden-directory.png](https://docs.github.com/assets/images/help/repository/pr-template-hidden-directory.png)

    - To create multiple pull request templates and use the `template` query parameter to specify a template to fill the pull request body, type *.github/PULL_REQUEST_TEMPLATE/*, then the name of your pull request template. For example, `.github/PULL_REQUEST_TEMPLATE/pull_request_template.md`. You can also store multiple pull request templates in a `PULL_REQUEST_TEMPLATE` subdirectory within the root or `docs/` directories. For more information, see "[About automation for issues and pull requests with query parameters](https://docs.github.com/en/free-pro-team@latest/articles/about-automation-for-issues-and-pull-requests-with-query-parameters)."

        ![https://docs.github.com/assets/images/help/repository/pr-template-multiple-hidden-directory.png](https://docs.github.com/assets/images/help/repository/pr-template-multiple-hidden-directory.png)

4. In the body of the new file, add your pull request template. This could include:
    - A [reference to a related issue](https://docs.github.com/en/free-pro-team@latest/articles/basic-writing-and-formatting-syntax/#referencing-issues-and-pull-requests) in your repository.
    - A description of the changes proposed in the pull request.
    - [@mentions](https://docs.github.com/en/free-pro-team@latest/articles/basic-writing-and-formatting-syntax/#mentioning-people-and-teams) of the person or team responsible for reviewing proposed changes.
5. At the bottom of the page, type a short, meaningful commit message that describes the change you made to the file. You can attribute the commit to more than one author in the commit message. For more information, see "[Creating a commit with multiple co-authors](https://docs.github.com/en/free-pro-team@latest/articles/creating-a-commit-with-multiple-authors)."

    ![https://docs.github.com/assets/images/help/repository/write-commit-message-quick-pull.png](https://docs.github.com/assets/images/help/repository/write-commit-message-quick-pull.png)

6. Below the commit message fields, decide whether to add your commit to the current branch or to a new branch. If your current branch is the default branch, you should choose to create a new branch for your commit and then create a pull request. For more information, see "[Creating a new pull request](https://docs.github.com/en/free-pro-team@latest/articles/creating-a-pull-request)."Templates are available to collaborators when they are merged into the repository's default branch.

    ![https://docs.github.com/assets/images/help/repository/choose-commit-branch.png](https://docs.github.com/assets/images/help/repository/choose-commit-branch.png)

7. Click **Propose new file.**

    ![https://docs.github.com/assets/images/help/repository/new-file-commit-button.png](https://docs.github.com/assets/images/help/repository/new-file-commit-button.png)
    
    
    
## Example of a PR template: 


<!--- Provide a general summary of your changes in the Title above -->

## Description
<!--- Describe your changes in detail -->


## Screenshots (if appropriate):

## Types of changes
<!--- What types of changes does your code introduce? Put an `x` in all the boxes that apply: -->
- [ ] Bug fix (non-breaking change which fixes an issue)
- [ ] New feature (non-breaking change which adds functionality)
- [ ] Breaking change (fix or feature that would cause existing functionality to change)
- [ ] Doc update

## Checklist:
<!--- Go over all the following points, and put an `x` in all the boxes that apply. -->
<!--- If you're unsure about any of these, don't hesitate to ask. We're here to help! -->
- [ ] My code follows the code style of this project.
- [ ] My change requires a change to the documentation.
- [ ] I have updated the documentation accordingly.
- [ ] I have read the **CONTRIBUTING** document.


# **Creating a template repository**

You can make an existing repository a template, so you and others can generate new repositories with the same directory structure, branches, and files.

Anyone with admin permissions to a repository can make the repository a template.

To create a template repository, you must create a repository, then make the repository a template. For more information about creating a repository, see "[Creating a new repository](https://docs.github.com/en/free-pro-team@latest/articles/creating-a-new-repository)."

After you make your repository a template, anyone with access to the repository can generate a new repository with the same directory structure and files as your default branch. They can also choose to include all the other branches in your repository. For more information, see "[Creating a repository from a template](https://docs.github.com/en/free-pro-team@latest/articles/creating-a-repository-from-a-template)."

1. On GitHub, navigate to the main page of the repository.
2. Under your repository name, click  **Settings**.

    ![https://docs.github.com/assets/images/help/repository/repo-actions-settings.png](https://docs.github.com/assets/images/help/repository/repo-actions-settings.png)

3. Select **Template repository**.

    ![https://docs.github.com/assets/images/help/repository/template-repository-checkbox.png](https://docs.github.com/assets/images/help/repository/template-repository-checkbox.png)
    
    
### **Generate new repositories with repository templates**

Sharing boilerplate code across codebases is a constant pattern in software development. Bootstrapping a new project with our favorite tools and directory structures helps programmers go from idea to “Hello world!” more efficiently and with less manual configuration.

Today, we’re excited to introduce repository templates to make boilerplate code management and distribution a first-class citizen on GitHub. To get started, all you need to do is mark a repository as a template, and you’ll immediately be able to use it to generate new repositories with all of the template repository’s files and folders.

![https://github.blog/wp-content/uploads/2019/06/repository-template.gif?w=1024&resize=1024%2C512](https://github.blog/wp-content/uploads/2019/06/repository-template.gif?w=1024&resize=1024%2C512)

Whenever you view a template repository, you’ll see a brand new “Use this template” button that enables you to get started with that codebase in seconds. Any templates you own, have access to through one of your organization memberships, or have used previously will be available from the [new repository page](http://github.com/new), too.

Every template repository gets a new URL endpoint called `/generate` that allows you to distribute your template more efficiently. Writing a tutorial? Building an app boilerplate for your enterprise? Distributing a project framework? Just link your users directly to the `/generate` endpoint. All they’ll need to do is name their project and clone their new repository to get started.

This is just the beginning for repository templates. We’re excited to bring more capabilities to all of our template types—repositories, issues, and pull requests—to help you spend less time repeating work so you can get back to building new things. In the meantime, [share your templates with the world](http://twitter.com/github) and [let us know](mailto:hello-product@github.com) how to make templates work better for you in the future!

Source: github blog
