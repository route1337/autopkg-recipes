AutoPkg Recipes: Testing
========================
All Route 1337 LLC AutoPkg Recipes are tested against our production Jamf Pro server. This does mean that recipes we don't find useful
for deployment to our equipment will not be accepted into the repo as we will not be testing them In the future this may change if we setup
a second AutoPkg server for use with a development Jamf Pro environment.

Testing Requirements
--------------------
All recipes tested this way must follow these testing rules:

1. All recipes must be tested fully regarding their option sets.
2. Recipes should pass all pre-commit tests.

pre-commit
----------
This repo uses Yelp's [pre-commit](https://pre-commit.com/) to manage some pre-commit hooks automatically.  
In order to use the hooks, make sure you have `pre-commit` in your `$PATH`.  
Once in your path you should run `pre-commit install` in order to configure it. If you push commits that fail pre-commit, your PR will
not pass tests.

Return to [README](README.md)
