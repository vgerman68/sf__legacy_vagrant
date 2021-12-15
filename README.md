# sf__legacy_vagrant
Task B6.5 (HW-03) B6.5.2. 

using Vagrant to run legacy PostgreSQL 8.4 code

# Install
1. Create a new virtmachine directory
2. Copy *.box and Vagrantfile files to virtmachine directory
3. Run command: vagrant init
4. Copy a private_key file to virtmachine/.vagrant/machines/default/virtualbox/private_key distanation
5. Run command: sudo chown vagrant virtmachine/.vagrant/machines/default/virtualbox/private_key
6. Run command: vagrant up
