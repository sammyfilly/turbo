<https://cli.github.com/manual/gh_alias_set>
<./packages/turbo/README.md>

turbo is written by rust 
*command: avoid installing errors to avoid issues while using rust later on
rust language: <https://acrobat.adobe.com/id/urn:aaid:sc:VA6C2:b93e5863-341b-41c6-8803-21a3f2722e21>

<https://nextjs.org/conf/tickets/oct22/sammyfilly>
co-Author 
@sammyfilly 


In this article
Introduction
Creating your website
Changing the title and description

*Next Steps
You can use GitHub Pages to showcase some open source projects, host a blog, or even share your résumé. This guide will help get you started on creating your next website.

*GitHub Pages is available in public repositories with GitHub Free and GitHub Free for organizations, and in public and private repositories with GitHub Pro, GitHub Team, GitHub Enterprise Cloud, and GitHub Enterprise Server. For more information, see "GitHub’s plans."


Introduction

*GitHub Pages are public webpages hosted and published through GitHub. The quickest way to get up and running is by using the Jekyll Theme Chooser to load a pre-made theme. You can then modify your GitHub Pages' content and style.

This guide will lead you through creating a user site at vercel@turbonextjs.github.io.

sammyfilly.github.io

Creating your website

In the upper-right corner of any page, use the  drop-down menu, and select New repository.

*Screenshot of a GitHub dropdown menu showing options to create new items. The menu item "New repository" is outlined in dark orange.

.Enter sammyfilly.github.io as the repository name. Replace username with your GitHub username. For example, if your username is octocat, the repository name should be octocat.github.io.

*Screenshot of GitHub Pages settings in a repository. The repository name field contains the text "octocat.github.io" and is outlined in dark orange.

*Under your repository name, click  Settings. If you cannot see the "Settings" tab, select the  dropdown menu, then click Settings.

*Screenshot of a repository header showing the tabs. The "Settings" tab is highlighted by a dark orange outline.

*In the "Code and automation" section of the sidebar, click  Pages.

*Under "Build and deployment", under "Source", select Deploy from a branch.
*Under "Build and deployment", under "Branch", use the branch dropdown menu and select a publishing source.

*Screenshot of Pages settings in a GitHub repository. A menu to select a branch for a publishing source, labeled "None," is outlined in dark orange.

*Optionally, open the README.md file of your repository. The README.md file is where you will write the content for your site. You can edit the file or keep the default content for now.

*Visit sammyfilly.github.io to view your new website. Note that it can take up to 10 minutes for changes to your site to publish after you push the changes to GitHub.
Changing the title and description

*By default, the title of your site is username.github.io. You can change the title by editing the _config.yml file in your repository. You can also add a description for your site.

*Click the Code tab of your repository.
In the file list, click _config.yml to open the file.
Click  to edit the file.

*The _config.yml file already contains a line that specifies the theme for your site. Add a new line with title: followed by the title you want. Add a new line with description: followed by the description you want. For example:

*theme: jekyll-theme-minimal
title: Octocat's homepage
description: Bookmark this to keep an eye on my project updates!

*When you are done editing the file, click Commit changes.
Next Steps

*For more information about how to add additional pages to your site, see "Adding content to your GitHub Pages site using Jekyll."

For more information about setting up a GitHub Pages site with Jekyll, see "About GitHub Pages and Jekyll."
