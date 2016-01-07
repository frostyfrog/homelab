Directory Listing
=================

- 1.yml - Arch server base setup. TODO: Figure out what to do next.
- roles/yaegashi.blockinfile/ - [Ansible Plugin, not by me](https://github.com/yaegashi/ansible-role-blockinfile)

Ansible plugins can be installed via the `ansible-galaxy` command. In my case,
I used the following command since I didn't want to use sudo to install the
role and I wanted it to live alongside my current ansible configuration.

```
ansible-galaxy install yaegashi.blockinfile -p roles
```
