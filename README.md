DNS
===

Setup DNS.

Role Variables
--------------

List DNS servers to be inserted into template:

    dns_servers:
      - 8.8.8.8
      - 208.67.222.222
      - 208.67.220.220


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: sdoran.dns, dns_servers:['10.0.1.7', '192.168.7.3'] }

License
-------

MIT
