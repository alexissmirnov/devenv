# devenv
Vagrant-based multi-language development environment

This project contains the definition of a Vagrant dev environment box.

The idea of factoring this in a separate project is to be able to include the dev environments into various projects (by reference) without having to recreate it’s definition.

Read Vagrantfile to see how the box is configured.

### How to use this?
- Install [vagrant](vargantup.com)
- Install [vagrant plugin](http://docs.vagrantup.com/v2/cli/plugin.html) for virtualbox: vagrant plugin install virtualbox
- Create your new project in git
- Link devenv into the project under “devenv” top-level directory. The name is not important, but the directory must be top-level relative to your project.
