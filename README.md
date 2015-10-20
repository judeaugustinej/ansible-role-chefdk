# ansible-role-chefdk
[![Build Status](https://travis-ci.org/judeaugustinej/ansible-role-chefdk.svg?branch=masterr)](https://travis-ci.org/judeaugustinej/ansible-role-chefdk/)
Install the Chef Development Kit. 

## Requirements

None.

## Role Variables

* ``chefdk_version``: Chef Development Kit version to install (default: ``0.9.0``)
* ``chefdk_tmp``: Downloaded file is placed. (default: ``/opt/chef_downloads/``)
* `` chefdk_tmp_dir ``: 
#### Ubuntu Variables

* ``chefdk_deb``: chef Development kit package  (default: ``https://downloads.chef.io/chef-dk/ubuntu/``)
* ``chefdk_url_deb``: Complete url to download the package chef Development kit(0.9.0) (default: ``https://opscode-omnibus-packages.s3.amazonaws.com/ubuntu/12.04/x86_64/chefdk_0.9.0-1_amd64.deb``)

#### Debian Variables

* ``chefdk_deb``: chef Development kit package  (default: ``https://downloads.chef.io/chef-dk/debian/``)
* ``chefdk_url_deb``: Complete url to download the package chef Development kit(0.9.0) (default: ``https://opscode-omnibus-packages.s3.amazonaws.com/debian/6/x86_64/chefdk_0.9.0-1_amd64.deb``)

## Example playbook

    - hosts: localhost
      roles:
        - { role: ansible-role-chefdk }



## License

 MIT

## Author information

Jude Augustine Job judeaugustinej@gmail.com

