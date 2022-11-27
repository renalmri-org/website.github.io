## How to edit the  website

The [renalmri.org](https://www.renalmri.org) using generator website [Jekyll](https://jekyllrb.com/).

The text files that the site is built from live in the 'main' branch of a [GitHub repository](https://github.com/renalMRIAlexandra/renalMRIAlexandra.github.io/tree/main). Whenever the files in this repository are changed, GitHub rebuilds the website automatically.

To maintain and update the renalmri website, you will need to set up two software packages on your computer:
- **Jekyll** to test changes locally before committing them to the GitHub repository where the website text files live. Follow the [Jekyll installation guide](https://jekyllrb.com/docs/installation/) to set up Jekyll.
- **Git** (and optionally the GitHub Desktop software) to track and commit changes you make in your local copy to the website repository.

## website maintenance workflow

1. Clone the develop branch into a folder of your choice on your computer.

2. Make changes to files as you see fit. The website is built around the widely used and well-supported [Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/).

3. To test the changes you made locally, open a terminal or prompt, navigate to the folder you just created (so you can see the file `_config.yml`).

4. Type the command `jekyll serve` or `jekyll install` and hit Enter. If you see `jekyll` producing errors at this stage, try using the command `bundle exec jekyll serve` instead. If that does not resolve the problem, re-installe and upgrade Jekyll (follow the [Jekyll installation guide](https://jekyllrb.com/docs/installation/) again).

5. After a while, you should see a line `Server address: http://127.0.0.1:4000/`. Enter this address into your web browser.

6. If you're happy with the local rendering of the site, commit the changes back to the 'develop' branch of the repository.

7. Submit a pull request from the 'develop' branch to the 'master' branch of the repository. The site will then automatically be rebuilt by the Netlify host service. You can check the status of the rebuild by logging into Netlify with the MRSHub GitHub account credentials. Once the build is successful, the  is live without further ado.

