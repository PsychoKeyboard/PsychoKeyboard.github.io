# README



1. **Title:** Assignment 2

2. **Purpose:** Explain how to host a resume on GitHub Pages.

3. **Prerequisites:** A resume formatted in Markdown. Check out 'More Resources' on how to use Markdown.

4. **Instructions:**

   - Using a Lightweight Markup language: 

     To begin, we need a resume that has been formatted in a GitHub Flavored Markdown using a Markdown Editor (eg. Atom, Typora). I crafted my resume in Typora. 

     

   - Avoid duplication:

     When creating a resume, avoid duplications. Use lists and headings to divide the resume into multiple *topics*, each dealing with a specific subject so that one talking point is not described again in another topic. 

     Also, include links to your projects so that you can avoid remaking your resume every time you update a project you have been working on.

     

   - Version Control:

     It is good practice to have different versions of your documents stored on an online cloud so you can view the changes made, revert back to old versions and keep the document updated. 

     Here, we will use GitHub Pages to upload our resumes.

     1. Create a GitHub Pages account

     2. Create a new public repository and name it: GH_Username/github.io  

        GH_Username refers to the username of your GitHub profile

     3. Click "add a new file" in your repository and upload your resume file with the name "index.md".

        To maintain version control, remember to add a comment whenever you change or update your files. This would make it easier to navigate between version files.

        

   - Static Website:

     Static websites provide portability and security to your resume and 

     We'll use a static site generator like Jekyll to create a website and give it a theme.

     1. In your repository, create a new file and name it "_config.yml"

     2. In the file, type, "theme: jekyll-theme-slate" to give it the theme Slate. 

        You could download other jekyll themes on your computer and use those themes with your resume or go into GitHub Pages Settings and choose one of the themes available on there.

        

   - More Resources:

     1. About Markdown: https://www.markdownguide.org/getting-started/

     2. How to use Markdown: https://www.youtube.com/watch?v=6A5EpqqDOdk

     3. Andrew Etter's Book: Modern Technical Writing: https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS

     4. Uploading to GitHub Pages: https://help.designmodo.com/article/startup-github-pages/#:~:text=On%20the%20upload%20page%2C%20you,select%20files%20from%20your%20computer.

        

5. **Authors and Acknowledgements:**

   Minimal Theme by: https://github.com/parkr

6. **FAQS:**

   1. How long until my website updates?

      The first time you generate your site it will take about 10 minutes for it to show up. Subsequent builds take only seconds from the time you push the changes to your GitHub repository.

      However, depending on how you have your domain configured, there may be extra time for the CDN cache to break.

   2. Why is Markdown better than the Word processor?

      Markdown is an easy-to-learn text editor and has a very simple syntax compared to Word's extensive list of formatting options. Markdown's limited features mean that most of the time, the output is more readable and better structured.
