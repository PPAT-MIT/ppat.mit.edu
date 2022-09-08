# ppat.mit.edu

## creation Process  (just for prosterity)
This should not ever need to be done again, but I wanted to record my process in case anything goes wrong in the future.
* I used the following tutorial to create the originbal website
  * https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll .
    * I did need to install Ruby and Jekyll to begin the creation process.
    * needed to add a gem to fix jekyll issue 
    * https://github.com/jekyll/jekyll/issues/8523
  * Github Pages serves from /docs directory in repo
    * This was set in the github.com repo settings page
      * https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
* Custom subdomain of MIT
  * https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/about-custom-domains-and-github-pages
## Editing Process
* Required Tools
  * git or GitHub Desktop
    * 
  * Local copy of repo
    * Clone `ppat.mit.edu` repo from `PPAT-MIT` org on GitHub.com
  * Ruby with Jekyll
    * Install Ruby on local machine (default installation should be perfectly fine) 
    * Test Ruby installation
      * `> ruby -e "puts 'Hello, world!'"`
      * `> irb` to launch interactive ruby and run `> 2+2` 
    * Install Jekyll Gem 
      * `> gem install jekyll bundler`
* Editing Website (Use git branches and pull requests)
  * start from branch based on latest `main`
    * git fetch latest `main` branch
    * create git branch
    * Switch to your new branch
  * launch local site
    * test site locally
      * `> bundle exec jekyll serve --livereload`
      * http://localhost:4000/
    * edit local files until you are happy
  * when happy with local changes
    * git commit all changes to your branch
    * git push to your branch
    * create pull request to `main`
  * once pull request is accepted your changes will be live
    * https://ppat-mit.github.io/ppat.mit.edu/