# sf__legacy_vagrant
Task B6.5 (HW-03) B6.5.2. 

using Vagrant to run legacy PostgreSQL 8.4 code

# Install
1. Create a new virtmachine directory
2. Copy *.box file to virtmachine directory
3. vagrant init
4. Copy a private_key file to virtmachine/.vagrant/machines/default/virtualbox/private_key
5. sudo chown vagrant virtmachine/.vagrant/machines/default/virtualbox/private_key
6. vagrant up
