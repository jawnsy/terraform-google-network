# terraform-google-network

This is [@jawnsy](https://github.com/jawnsy)'s fork of https://github.com/terraform-google-modules/terraform-google-network.git.

I wanted to avoid maintaining the `main` branch in my fork because:

1. It is traditionally a pristine copy of the upstream repository, which
   can cause confusion 
1. I would have to synchronize it with the upstream repository periodically
   time to time (`git fetch upstream`, `git merge --ff-only upstream/main`)
   since it would traditionally be a pristine copy

In order to avoid maintaining the `main` branch in my fork, I configured
my local repository to track the upstream's default branch.
