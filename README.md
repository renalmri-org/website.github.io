
# How to edit the website

## On the GitHub page
1. Find the file that you want to edit and click on it to open it.
2. On the next page, you will see the contents of the file displayed in the browser. To make changes to the file, click on the pencil icon in the top-right corner of the file viewer. This will open the file in edit mode.
3. Make the changes that you want to the file in the editor. You can use the editor's features to format the text and add comments as needed.
4. When you are finished making your changes, scroll to the bottom of the page and enter a commit message that describes the changes that you made. This will help other users understand what you did to the file.
5. Finally, click the "Commit changes" button to save your changes to the file. Your changes will now be part of the repository, and other users will be able to see them and use them.

**Important for major changes please create a new branch first, modify it and create a pullrequest afterwards.**
- To create a new branch on GitHub, follow these steps:

  - Navigate to the repository on GitHub that you want to create a branch in.
  - On the main page of the repository, click on the "Branch: master" dropdown menu in the top-left corner of the page. This will show a list of all the existing branches in the repository.
  - In the "Find or create a branch" field, enter the name of the new branch that you want to create.
  - Click the "Create branch" button to create the new branch. This will create a new branch with the specified name and switch you to that branch.
  - You can now make changes to the files in the new branch. Your changes will be isolated from the main branch of the repository, allowing you to experiment and work on new features without affecting the main branch.
  - When you are ready, you can create a pull request to propose your changes to the other members of the repository. If they agree with your changes, they can accept the pull request and merge your changes into the main branch.

## local with own branch 

The [renalmri.org](https://www.renalmri.org) using generator website [Jekyll](https://jekyllrb.com/).

The text files that the site is built from live in the 'main' branch of a [GitHub repository](https://github.com/renalMRIAlexandra/renalMRIAlexandra.github.io/tree/main). Whenever the files in this repository are changed, GitHub rebuilds the website automatically.

To maintain and update the renalmri website, you will need to set up two software packages on your computer:
- **Jekyll** to test changes locally before committing them to the GitHub repository where the website text files live. Follow the [Jekyll installation guide](https://jekyllrb.com/docs/installation/) to set up Jekyll.
- **Git** (and optionally the GitHub Desktop software) to track and commit changes you make in your local copy to the website repository.

## website maintenance workflow

1. Clone the develop branch into a folder of your choice on your computer. 
  - 1.1. install jekyll https://jekyllrb.com/docs/installation/ and change your gemfile (Example at the bottom)
  - 1.2. then `gem install bundler:2.3.7`
  - 1.3. `bundle install`
  - 1.4. `bundle exec jekyll serve` use this for start site on your local machine
  - 1.5. go to http://127.0.0.1:4000/ and test site
  - 1.6. press `ctrl + c` in console to stop

2. Make changes to files as you see fit. The website is built around the widely used and well-supported [Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/).

3. To test the changes you made locally, open a terminal or prompt, navigate to the folder you just created (so you can see the file `_config.yml`).

4. Type the command `jekyll serve` or `jekyll install` and hit Enter. If you see `jekyll` producing errors at this stage, try using the command `bundle exec jekyll serve` instead. If that does not resolve the problem, re-installe and upgrade Jekyll (follow the [Jekyll installation guide](https://jekyllrb.com/docs/installation/) again).

5. After a while, you should see a line `Server address: http://127.0.0.1:4000/`. Enter this address into your web browser.

6. If you're happy with the local rendering of the site, commit the changes back to the 'develop' branch of the repository.

7. Submit a pull request from the 'develop' branch to the 'master' branch of the repository. The site will then automatically be rebuilt by the Netlify host service. You can check the status of the rebuild by logging into Netlify with the MRSHub GitHub account credentials. Once the build is successful, the  is live without further ado.

# gemfile 

```source "https://rubygems.org"

gem "jekyll", "~> 4.3.1"

gem "minima", "~> 2.5"
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
gem "minimal-mistakes-jekyll"```

