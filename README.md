## [![DebOps project](http://debops.org/images/debops-small.png)](http://debops.org) nginx

[![Travis CI](http://img.shields.io/travis/debops/ansible-nginx.svg?style=flat)](http://travis-ci.org/debops/ansible-nginx) [![test-suite](http://img.shields.io/badge/test--suite-ansible--nginx-blue.svg?style=flat)](https://github.com/debops/test-suite/tree/master/ansible-nginx/)  [![Ansible Galaxy](http://img.shields.io/badge/galaxy-debops.nginx-660198.svg?style=flat)](https://galaxy.ansible.com/list#/roles/1580)

[nginx](http://nginx.org/) is a fast and light webserver with extensible
configuration.

`debops.nginx` role can be used to install and manage `nginx` configuration
for multiple websites at the same time. Server is configured using
inventory variables, role can also be used as a dependency of another role
to configure a webserver for that role using dependency variables.

### Installation

This role requires at least Ansible `v1.7.0`. To install it, run:

    ansible-galaxy install debops.nginx

### Documentation

More information about `debops.nginx` can be found in the
[official debops.nginx documentation](http://docs.debops.org/en/latest/ansible/roles/debops.nginx.html).


### Role dependencies

- `debops.secret`
- `debops.pki`
- `debops.ferm`
- `debops.apt_preferences`

### Are you using this as a standalone role without DebOps?

You may need to include missing roles from the [DebOps common
playbook](https://github.com/debops/debops-playbooks/blob/master/playbooks/common.yml)
into your playbook.

[Try DebOps now](https://github.com/debops/debops) for a complete solution to run your Debian-based infrastructure.





### Authors and license

`nginx` role was written by:
- Maciej Delmanowski | [e-mail](mailto:drybjed@gmail.com) | [Twitter](https://twitter.com/drybjed) | [GitHub](https://github.com/drybjed)

License: [GPLv3](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

***

This role is part of the [DebOps](http://debops.org/) project. README generated by [ansigenome](https://github.com/nickjj/ansigenome/).
