# Vagrant GVM #

Install GVM (Groovy enVironment Manager) on a vagrant box.

Currently this fails on the first run, but succeeds on the second run.

Tested on:

 * Centos 6.4

Follow these steps to use:

 * Install vagrant (http://www.vagrantup.com/)
 * Add a box to your vagrant installation "vagrant box add precise32 vagrant box add precise32 http://files.vagrantup.com/precise32.box"
 * Clone this repo
 * Cd into vagrant-gvm
 * run "vagrant up"
 * run "vagrant reload"