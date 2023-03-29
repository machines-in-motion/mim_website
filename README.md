# mim_website

This is our laboratory website.

The `main` branch contains the source code and the `gh-pages` contains the publishable site used by github pages


## Local install
To compile the site you will need to use [Jekyll](https://jekyllrb.com/docs/installation/)
Make sure to install bundle `gem install bundler`

1. Go in the root directory (after cloning)
2. Make sure you are in the `main` branch
3. Install the dependencies `bundle install`
4. Compile and run the site `bundle exec jekyll serve`

## Publish the modifications
Commit and push your changes in the `main` branch
Run the script `./bin/publish` it will push into the `gh-pages` branch a cleaned and compiled version of the site 
(actually it merely copies the files from _site into the root directory and removes the rest - cf. https://www.drewsilcock.co.uk/custom-jekyll-plugins)
We don't use the github pages capabilities for auto-publish because it handles a minimum number of plugins.
