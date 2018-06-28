Role Name
=========

Install and run Hashicorp Vault as Docker container.

Requirements
------------


Role Variables
--------------

```
vault_args: []
vault_cluster_name: "vault.example.com"
vault_enabled: true
vault_image: vault:0.10.1
vault_path: "/opt/vault"
vault_service: "vault"
```

Dependencies
------------

lmickh.docker

Example Playbook
----------------

    - name: servers
      roles:
        - {{ lmickh.vault }}

License
-------

MIT
