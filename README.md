Google auth
=========

> Ansible role to setup google authentication for [stackdriver] tools.

Requirements
------------

You should have an [GCP] account

Role Variables
--------------

```yaml
# JSON provided by google
google_auth_credentials: |
  {
    …
  }
```


Dependencies
------------

There is no dependencies

Example Playbook
----------------

```yaml
- roles:
   - SimpliField.google-auth
```

License
-------

BSD

[stackdriver]: https://cloud.google.com/stackdriver/
[GCP]: https://cloud.google.com/
