## [![DebOps project](http://debops.org/images/debops-small.png)](http://debops.org) apparmor

<!-- This file was generated by Ansigenome. Do not edit this file directly but
     instead have a look at the files in the ./meta/ directory. -->

[![Travis CI](http://img.shields.io/travis/debops-contrib/ansible-apparmor.svg?style=flat)](http://travis-ci.org/debops-contrib/ansible-apparmor)
[![test-suite](http://img.shields.io/badge/test--suite-ansible--apparmor-blue.svg?style=flat)](https://github.com/ypid/test-suite/tree/master/ansible-apparmor/)
[![Ansible Galaxy](http://img.shields.io/badge/galaxy-debops--contrib.apparmor-660198.svg?style=flat)](https://galaxy.ansible.com/debops-contrib/apparmor)


AppArmor is able to restrict what programs can do and access based on policies for those programs.

See [AppArmor in the Debian Wiki](https://wiki.debian.org/AppArmor/HowToUse).

By default (e.g. no [auditd] installed) log messages from AppArmor are
logged via syslog to the kernel facility which usually ends up under
`/var/log/kern.log`.

[auditd]: https://packages.debian.org/search?keywords=auditd

### Installation

This role requires at least Ansible `v2.1.3`. To install it, run:

```Shell
ansible-galaxy install debops-contrib.apparmor
```

### Documentation

More information about `debops-contrib.apparmor` can be found in the
[official debops-contrib.apparmor documentation](http://docs.debops.org/en/latest/ansible/roles/ansible-apparmor/docs/).



### Are you using this as a standalone role without DebOps?

You may need to include missing roles from the [DebOps common
playbook](https://github.com/debops/debops-playbooks/blob/master/playbooks/common.yml)
into your playbook.

[Try DebOps now](https://github.com/debops/debops) for a complete solution to run your Debian-based infrastructure.





### Authors and license

`apparmor` role was written by:

- [Robin Schneider](https://github.com/ypid) | [e-mail](mailto:ypid@riseup.net)

License: [GPLv3](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

***

This role is part of the [DebOps](http://debops.org/) project. README generated by [ansigenome](https://github.com/nickjj/ansigenome/).
