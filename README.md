# Vagrant-based multi-language development environment

This project contains the definition of a Vagrant dev environment box.

The idea of factoring this in a separate project is to be able to include the dev environments into various projects (by reference) without having to recreate it’s definition.

Read Vagrantfile to see how the box is configured.

### How to use this?
- Install [vagrant](vargantup.com)
- Install [vagrant plugin](http://docs.vagrantup.com/v2/cli/plugin.html) for virtualbox: `vagrant plugin install virtualbox`
- Create your new project in git
- Link devenv into the project under “devenv” top-level directory. Like this: `git submodule add https://github.com/alexissmirnov/devenv devenv` The name is not important, but the directory must be top-level relative to your project. Here's [how to set up a git project to use an external repo submodule](http://stackoverflow.com/questions/2140985/how-to-set-up-a-git-project-to-use-an-external-repo-submodule)
