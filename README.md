1. clone this repo: 
2. cd into the repo
3. run `/opt/puppetlabs/puppet/bin/r10k puppetfile install`
4. `vagrant up`
5. `vagrant ssh`
6. `curl -O https://apt.puppetlabs.com/puppet6-release-trusty.deb`
7. `apt-get update && apt-get install puppet-agent`
8. `sudo /opt/puppetlabs/bin/puppet apply --verbose --environmentpath=/ --environment=vagrant -e 'include profile::rundeck'`
