# GitHub Actions SSH Playground

This repository provides an easy way to set up a GitHub Actions workflow with an SSH connection.

A bunch of runtimes are installed so it's easy to run different scripts and play around with the GHA environment.

## Usage

1. Run the "playground" workflow
2. Look at the logs, you'll see something like `SSH: ssh 56KDSUP8bWE3Ddz2tDkZLcBTh@nyc1.tmate.io` appear
3. Run that ssh command in your terminal
4. Most likely run something like `export PS1='> '` to make your life easier


## Tips

* `sudo -s` to run all commands as sudo
