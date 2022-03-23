# How to format and host your resume on GitHub Pages



## Purpose

To produce and host a resume on a GitHub Pages public repository using the tools described in Andrew Etter's book Modern Technical Writing. These tools include Markdown, a Markdown editor, a static generator site like Jekyll and GitHub Pages.



## Prerequisites

- A Markdown Editor(eg. Typora, Atom)
- A Resume formatted in Markdown
- An account on GitHub

 

## Instructions

Here is how you can upload a resume to GitHub Pages based on principles from the popular book Modern Technical Writing by Andrew Etter:

### Create a New Repository

In the book *Modern Technical Writing*, Etter recommends using a distributed version control system like Git and Mercurial since they allow for better performance, offline work and are superior for concurrent work on the same file. 

A GitHub repository contains all of your project's files and each file's revision history. To create a new public repository:

1. Go to `github.com` and log into your GitHub account
2. On the left side, next to Recent Repositories click `New`
3. On the new page, enter `<YourGitHubUsername>.github.io`. \<YourGitHubUsername>  is the username used to create your account.
4. Select `Public` so that others can view it.
5. We recommend adding a README to your repository.
6. Finally, click `Create Repository`



### Upload your Resume to the Repository

Erret discusses how Light Weight Markup languages like Markdown are superior to the Word processor and are a better choice for creating documents in general. For this tutorial, your resume should be written and formatted in Markdown(Check out this link on how to use markdown https://www.markdownguide.org/getting-started/).

1. In your repository, click `Add File`.
2. In the drop-down menu, click `Create new file`.
3. Name your file `index.md`.
4. Copy over your resume to this `index.md` file
5. Click `Commit new file` at the bottom of the page.

GitHub Pages will host your project pages from your GitHub repository and your resume should now be available at `https://<YourGitHubUsername.github.io>/`



### Themes with a Static Site Generator

Etter focuses on the importance of customizing a theme for your documents to improve navigation and approachability. A static site generator is a tool that generates a full static HTML website based on raw data and a set of templates. We will use Jekyll in this tutorial.

To add a theme to your resume:

1. Create a new file in your repository with the name `_config.yml`
2. In the content of this new file, type `theme: jekyll-theme-slate`.
3. Commit this file.

Your resume should now have the theme 'slate'. To add a different theme to your resume you could also:

1. Go to the `Settings` in your repository
2. Scroll to `Github Pages` and click the link `Check it out here!`. This will take you to GitHub Pages.
3. Under `Theme Chooser` click `Change theme`
4. Select any of the given theme templates to view them. Once you have selected a theme, click on the `Select Theme` button. This will automatically edit your `_config.yml` file to use the theme you have selected.



If you have followed all these steps correctly, you should end up with a resume like this:



![alt-text](https://github.com/PsychoKeyboard/PsychoKeyboard.github.io/blob/main/gif.gif)







If you encounter any errors, check out the FAQ or the other Resources listed below which might help you with any problems you may face.



### More Resources:

1. About Markdown: https://www.markdownguide.org/getting-started/

2. How to use Markdown: https://www.youtube.com/watch?v=6A5EpqqDOdk

3. Andrew Etter's Book: Modern Technical Writing: https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS

4. Uploading to GitHub Pages: https://help.designmodo.com/article/startup-github-pages/#:~:text=On%20the%20upload%20page%2C%20you,select%20files%20from%20your%20computer.

   

### Authors and Acknowledgements

Minimal Theme by: https://github.com/parkr

Thank you to my group members Chris Rogers, Xian Mardiros, Christian Bera and Brett Downey for the excellent feedback.



### FAQs

1. **How long until my website updates?**

   The first time you generate your site it will take about 10 minutes for it to show up. Subsequent builds take only seconds from the time you push the changes to your GitHub repository.

   However, depending on how you have your domain configured, there may be extra time for the CDN cache to break.

2. **Why is Markdown better than the Word processor?**

   Markdown is an easy-to-learn text editor and has a very simple syntax compared to Word's extensive list of formatting options. Markdown's limited features mean that most of the time, the output is more readable and better structured.

