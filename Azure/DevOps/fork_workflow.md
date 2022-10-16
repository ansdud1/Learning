# Create the Fork
  NOTE:Create Repository permission required.
+ Branches to include :
  + Only the default branch(main)
  + All branches

# Clone your fork locally
+ after cloning, add the upstream repository (where you forked from) as a remote named upstream.  
  + git remote add upstream {upstream_url}  


# Make and push changes
## Create and complete a PR
## Sync your fork to the latest
    git fetch upstream main   : fork reflects the latest state of the repo.
    git rebase upstream/main  : recommend rebasing on upstream's main branch (assuming main is the main development branch).
    git push origin
