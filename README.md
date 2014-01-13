# Readme
git-test
========
Using --recurse-submodules can only fetch 
new commits in already checked out submodules right now. 
When e.g. upstream added a new submodule in the just fetched commits of 
the superproject the submodule itself can not be fetched, 
making it impossible to check out that submodule later without having to do a 
fetch again. This is expected to be fixed in a future Git version.

Some update

