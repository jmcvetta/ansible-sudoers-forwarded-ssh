Role Name
=========

Ansible role to ensure /etc/sudoers is configured for Git checkout with forwarded SSH agent


Installation
------------

```bash
ansible-galaxy install jmcvetta.sudoers-forwarded-ssh
```


Testing
-------

Assumes you have Ruby and Bundler already installed.


```bash
bundle install  # Only required once
bundle exec kitchen test
```


Requirements
------------

This role is tested and known to work on the platforms shown below.

```
platforms:
  - name: ubuntu-14.04
```


Role Variables
--------------

None


Dependencies
------------

None


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - jmcvetta.sudoers-forwarded-ssh

License
-------

GPLv3


Author Information
------------------

[Jason McVetta](mailto:jason.mcvetta@gmail.com)

Paid support and consulting services available from [Silicon
Heavy](http://siliconheavy.com)
