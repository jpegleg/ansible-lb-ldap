# ansible-lb-ldap
Ansible to set up 4 LDAP "mirror master" servers behind an ordered load balancer with HAProxy.

(If you use selinux, be sure to set the appropriate policies to allow binding to 389 etc.)


There are two approaches here, one is with ldifs only, the other is with slapd.conf.
