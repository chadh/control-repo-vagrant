1. clone this repo: 
2. cd into the repo
4. `vagrant up`
5. `vagrant ssh`
6. `curl -O https://apt.puppetlabs.com/puppet6-release-trusty.deb`
7. `dpkg -i puppet6-release-trusty.deb`
8. `apt-get update && apt-get install puppet-agent`
9. `sudo /opt/puppetlabs/bin/puppet apply --verbose --modulepath /vagrant/modules -e 'include profile::rundeck'`
