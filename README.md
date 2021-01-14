Simple repo to try and learn Vagrant on [Vagrant getting started](https://learn.hashicorp.com/collections/vagrant/getting-started) page.

Install Vagrant:
- [Download package](https://www.vagrantup.com/downloads)
- Run `sudo dpkg -i vagrant*.deb` for debian based distribution


Useful command:
- `vagrant up` - Run Vagrantfile on current directory
- `vagrant ssh` - Connect through ssh on virtual machine
- `vagrant suspend` - Save VM state and suspend execution
- `vagrant halt` - Graceful shutdown of VM
- `vagrant destroy -f` - Destroy virtual machine
- `vagrant plugin install vagrant-share` - Install Vagrant Share plugin to enable environment sharing
- `vagrant share` - Share environment


