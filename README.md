This is the Git repository that contains the content for help.venuedriver.com.  The content is structured for a Ruby-based static HTML pre-processor called Jekyll.

To get the project:
===================

1. Clone this project from GitHub.
2. Optional: create an RVM gemset and .rvmrc for the project.  Suggested .rvmrc contents: "rvm 1.8.7@help-venuedriver-com"
3. Install the Bundler Ruby gem with "gem install bundler"
4. Install Jekyll with "bundle install"
5. Run the Jekyll pre-processor and server with "jekyll --server".  You can now see the web site at http://localhost:4000 in a web browser.

To edit the content:
====================

1. Edit, add, delete files, and check the results in the browser.  Don't edit files without checking the results in the browser!
2. AFTER you have checked your results in a web browser, commit your changes with Git.  ("git add .", "git commit -m 'I changed something.'")
3. Push your new commit back to GitHub with "git push".

To publish updates:
===================

1. Merge the master branch into the "gh-pages" branch, which is the branch that is published by GitHub Pages.
2. Push the update to the gh-pages branch to GitHub with "git push".
3. There is no step 3.  GitHub will automatically run Jekyll when you push your update to the "gh-pages" branch, and your static HTML results will be published at http://help.venuedriver.com