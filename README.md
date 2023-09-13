A Bash script for generating a pretty list of commits to use as a description for a pull request.

## Install (for Mac)

Copy the file to /usr/local/bin and ensure it's in your path. You should then be able to run `pr-describe` while in a git repo and see the commits on the current branch.

## Usage

- `pr-describe` gives you a list of commit messages.
- Including `-c` like `pr-describe -c` includes the commit hashes in the list.
- On Mac, you can pipe the result into `pbcopy` like `pr-describe | pbcopy` to quickly get a branch summary to include in a pull request.
