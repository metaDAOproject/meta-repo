# meta-repo
Monorepo for Meta DAO devs

# Contributing guide

After creating the codespace, run `git submodule init && git submodule update`. You may need to repeat this recursively for any sub-repos which have their own submodules

When adding a new repo run `git submodule add https://metaDAOproject/<repo-name> "repos/<repo-name>"`. 
Also add the repo to `.devcontainer/devcontainer.json` so that your codespace token will have the necessary permissions to write to that repo
