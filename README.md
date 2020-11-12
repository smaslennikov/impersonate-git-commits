# Faking Gabriel Fok

This repository is just a POC of impersonating someone else on GitHub.

## Process

1. Find Gabriel Fok's name and email used in git by looking at `git log`s of his existing repositories
1. Edit `.git/config` within the repository to use the name and email found in step 1 - as in [the checked-in example](gitconfig)
1. `git commit` away!
