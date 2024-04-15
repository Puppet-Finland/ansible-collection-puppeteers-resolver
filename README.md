# Ansible Collection - puppeteers.resolver

Ansible roles for setting up system DNS resolver.

Only RHEL 9 and derivatives are supported currently.

# Roles

## resolvconf

Disables NetworkManager and configures /etc/resolv.conf directly. Parameters
should be self-explanatory:

* resolver_resolvconf_search (string)
* resolver_resolvconf_nameserver_1 (string)
* resolver_resolvconf_nameserver_2 (string)
