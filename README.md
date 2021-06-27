# Building a local development environment

I'm using Windows. Doing this on Linux is probably simpler.  This process describes how to install everything necessary to build and serve your github_pages project locally so you don't have to commit and push to test every little change.  This is documented on [github](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll) too.

* [Install Ruby](https://rubyinstaller.org/downloads): I installed the latest release of Ruby+devkit.  Devkit is probably not required but I'm a professional software developer by trade so...why not.
* [Install Bundler](https://bundler.io/)
* [Create a Gemfile](https://bundler.io/gemfile.html)  Your repo needs a Gemfile in the root.  This repo has a Gemfile, so if you start with this repo, you can skip this.
* Open a shell to the root of the repo and run `bundle install`. This will install all the necessary gems.
* [Create Personal Access Token](https://docs.github.com/en/github/authenticating-to-github/keeping-your-account-and-data-secure/creating-a-personal-access-token): This is required to fix the 


# Build and server the site locally

Open a git bash shell at the repo root (or wherever your publishing root is set).

* `bundle exec jekyll serve`
* Open [your site](localhost:4000) in your browser

